### Proposición

$\mathbb Z$ es numerable ([[Conjunto numerable]]).

---
### Demostración

Para ello vamos a construir una aplicación biyectiva ([[Aplicaciones inyectivas, sobreyectivas y biyectivas]]).

Sea $f: \mathbb N \rightarrow \mathbb Z$ con $n \rightarrow \frac{n}{2}$ si $n$ es par y $n \rightarrow \frac{-n+1}{2}$ si $n$ es impar. Veamos que esta aplicación es biyectiva:
- Inyectiva: tenemos que probar que si $f(n) = f(m)$, entonces $n=m$. Distinguimos dos casos:
	- $f(n) = f(m) > 0$, en este caso necesariamente tenemos que $\frac{n}{2} = f(n) = f(m) = \frac{m}{2} \rightarrow n = m$.
	- $f(n) = f(m) \le 0$, en este caso: $\frac{-n+1}{2} = f(n) = f(m)= \frac{-m+1}{2} \rightarrow n = m$.
- Sobreyectiva: tenemos que probar que $\forall z \in \mathbb Z, \exists n \in \mathbb N$ tal que $f(n) = z$. Sea $z \in \mathbb Z$. De nuevo, distinguimos dos casos:
	- $z \le 0$. En este caso, definimos $n = 2z \in \mathbb N$, y tenemos que $f(n) = z$.
	- $z \le 0$. En este caso definimos $n = -(2z - 1) \in \mathbb N$, y tenemos que $f(n) = \frac{2z -1 + 1}{2} = z$.

---
### Referencias

[[Numerabilidad]]

---
### Anki


START
Básico
Anverso: Demostración de que $\mathbb Z$ es numerable
Reverso: Para ello vamos a construir una aplicación biyectiva ([[Aplicaciones inyectivas, sobreyectivas y biyectivas]]).

Sea $f: \mathbb N \rightarrow \mathbb Z$ con $n \rightarrow \frac{n}{2}$ si $n$ es par y $n \rightarrow \frac{-n+1}{2}$ si $n$ es impar. Veamos que esta aplicación es biyectiva:
- Inyectiva: tenemos que probar que si $f(n) = f(m)$, entonces $n=m$. Distinguimos dos casos:
	- $f(n) = f(m) > 0$, en este caso necesariamente tenemos que $\frac{n}{2} = f(n) = f(m) = \frac{m}{2} \rightarrow n = m$.
	- $f(n) = f(m) \le 0$, en este caso: $\frac{-n+1}{2} = f(n) = f(m)= \frac{-m+1}{2} \rightarrow n = m$.
- Sobreyectiva: tenemos que probar que $\forall z \in \mathbb Z, \exists n \in \mathbb N$ tal que $f(n) = z$. Sea $z \in \mathbb Z$. De nuevo, distinguimos dos casos:
	- $z \le 0$. En este caso, definimos $n = 2z \in \mathbb N$, y tenemos que $f(n) = z$.
	- $z \le 0$. En este caso definimos $n = -(2z - 1) \in \mathbb N$, y tenemos que $f(n) = \frac{2z -1 + 1}{2} = z$.
Tags: demostración
<!--ID: 1705822944814-->
END