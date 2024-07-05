### Enunciado Teorema

Sea $f : A \subseteq \mathbb R \rightarrow \mathbb R$ y sea $x_0 \in ac(A)$, entonces: 
$\exists lim_{x \to x_0} f(x) \iff \forall (x_n)_{n=1}^{+\infty} \subseteq A$ con $x_n \not = x_0, \forall n \in \mathbb N$ y tal que $\exists lim_{n \to \infty} x_n = x_0$ entonces $\exists lim_{n \to \infty} f(x_n)$

En este caso, si $\lim_{x \to x_0} f(x) = l \in \mathbb R \cup \{- \infty, + \infty, \infty\}$ entonces $\lim_{n \to +\infty} f(x_n) = l$ para toda sucesión en las condiciones anteriores.

---
### Demostración

### Caso 1. $l \in \mathbb R$
$\rightarrow$. Sea $(x_n)_{n=1}^{+\infty} \subset A$ con $x_n \not = x_0, \forall n \in \mathbb N$ y tal que $\lim_{n \to + \infty} x_n = x_0$. Veamos que $\exists lim_{n \to +\infty} f(x_n) = l$. Como $lim_{x \to x_0} f(x) = l$, dado $\epsilon > 0, \exists \delta > 0$ tal que si $x \in A, 0 < |x-x_0| < \delta$ entonces $|f(x) - l| < \epsilon$. Como $lim_{n \to +\infty} x_n = x_0, \exists n_0 \in \mathbb N$ tal que si $n \ge n_0, |x_n - x_0| < \delta$. Como $x_n \not = x_0, \forall n \in \mathbb N$, $|f(x_n) - l| < \epsilon$. Esto es, $\exists lim_{n \to +\infty} f(x_n) = l$.

$\leftarrow$. Veamos que si $(x_n)_{n=1}^{+\infty}$ e $(y_n)_{n=1}^{+\infty}$ en $A$ con $x_n \not = x_0 \not = y_n, \forall n \in \mathbb N$, $\lim_{n \to +\infty} x_n = x_0 = \lim_{n \to +\infty} y_n$, entonces $\lim_{n \to +\infty} f(x_n) = \lim_{n \to +\infty} f(y_n)$. En efecto, llamamos $l_1 := \lim_{n \to +\infty} f(x_n), l_2:=\lim_{n \to +\infty} f(y_n)$. La sucesión $(z_n)^{+\infty}_{n=1} := (x_1, y_1, x_2, y_2, x_3, y_3, \dots)$ tiende a $x_0$. Por hipótesis, $\exists \lim_{n \to +\infty} f(z_n) = l_3$, luego $l_1 = l_2 = l_3$, dado que [[Una subsucesión de una sucesión convergente converge al mismo límite]].
Llamamos $l := \lim_{n \to +\infty} f(x_n)$, donde $(x_n)_{n=1}^{+\infty}$ es cualquier sucesión en $A$ con $x_n \not = x_0, \forall n \in \mathbb N$ y $x_n$ tiende a $x_0$. Veamos que $\exists \lim_{x \to x_0} f(x) = l$.
Supongamos por reducción al absurdo que $f(x)$ no tiene límite en $x_0$. Por tanto, que no exista el límite implica que $\exists \epsilon > 0$ tal que $\forall \delta > 0, \exists x \in A$ tal que $0 < |x-x_0| < \delta$ tal que $|f(x) - l| \ge \epsilon$ (inversa de [[Límite funcional]]). Por tanto, $\exists \epsilon > 0$ tal que $\forall n \in \mathbb N$ (tomando $\delta := 1/n$), $\exists x_n \in A, 0 < |x_n - x_0| < 1/n$ tal que $|f(x_n) - l| \ge \epsilon$. Luego la sucesión $(x_n)_{n=1}^{+\infty} \subset A$, con $x_n \not = x_0, \forall n \in \mathbb N$ con $\lim_{x \to +\infty} x_n = x_0$ tal que $|f(x_n) - l| \ge \epsilon, \forall n \in \mathbb N$. Esto contradice la hipótesis: $\exists \lim_{n \to +\infty} f(x_n) = l$.

### Caso 2. $l = +\infty$
$\rightarrow$. Sea $(x_n)_{n=1}^{+\infty} \subset A$ con $x_n \not = x_0, \forall n \in \mathbb N$ y con $\lim_{n \to +\infty} x_n = x_0$. Veamos que $\exists \lim_{n \to +\infty} f(x_n) = +\infty$. Sea $k \in \mathbb R$, como $\lim_{x \to x_0} f(x) = +\infty, \exists \delta > 0$ tal que si $x \in A, 0 < |x-x_0| < \delta$ entonces $f(x) > k$.
Como $\lim_{n \to +\infty} x_n = x_0, \exists n_0 \in \mathbb N$ tal que si $n \ge n_0, |x_n - x_0| < \delta$. Como $f(x) > k$, entonces $f(x_n) > k$. Es decir, $\exists \lim_{n \to +\infty} f(x_n) = +\infty$.
$\leftarrow$. Supongamos por RA que $f(x)$ no tiende a $+\infty$ cuando $x$ tiende a $x_0$. La negación del límite es: $\exists k \in \mathbb R$ de tal forma que $\forall \delta > 0, \exists x = x(\delta)$ (que depende de $\delta$) $\in A$ con $0 < |x-x_0| < \delta$ tal que $f(x) \le k$.
Luego $\exists k \in \mathbb R$ tal que $\forall n \in \mathbb N$ (tomando $\delta := 1/n$), $\exists x_n \in A, 0 < |x_n - x_0| < 1/n$ tal que $f(x_n) \le k$. La sucesión $(x_n)_{n=1}^{+\infty} \subset A$ con $x_n \not = x_0, \forall n \in \mathbb N$ y con $\lim_{n \to +\infty} x_n = x_0$ cumple que $f(x_n) \le k$, lo que contradice que $\lim_{n \to +\infty} f(x_n) = +\infty$.

### Caso 3. $l = -\infty$
### Caso 4. $l = \infty$
Ejercicios análogos.


---
### Referencias

[[Función]]
[[Sucesión]]