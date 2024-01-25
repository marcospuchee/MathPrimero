### Proposición

$\mathbb N \times \mathbb N$ es numerable.

---
### Demostración

Vamos a utilizar [[Teorema de Schröeder-Bernstein]]. 

Tengo que probar que $f$ sea inyectiva. Sea $f: \mathbb N \rightarrow \mathbb N \times \mathbb N$ con $n \rightarrow (n,1)$. $(n,1) = f(n) = f(m) = (m,1) \implies n = m$. Esto implica que $|\mathbb N| \le |\mathbb N \times \mathbb N|$ ([[Aplicaciones inyectivas en numerabilidad]])

Sea $g : \mathbb N \times \mathbb N \rightarrow \mathbb N$ con $(a,b) \rightarrow 2^a 3^b$. ¿$g$ inyectiva?
$2^a 3^b = g((a,b)) = g((a', b')) = 2^{a'} 3^{b'}$. Por la unicidad del [[Teorema fundamental de la aritmética]], concluimos que $a = a'$ y $b = b'$. Por tanto, $|\mathbb N \times \mathbb N | \le | \mathbb N|$.

Así, por el [[Teorema de Schröeder-Bernstein]], $|\mathbb N| = |\mathbb N \times \mathbb N|$.

---
### Referencias

[[Numerabilidad]]

---
### Anki

START
Básico
Anverso: Demostración de que $\mathbb N \times \mathbb N$ es numerable
Reverso: Vamos a utilizar [[Teorema de Schröeder-Bernstein]]. 

Tengo que probar que $f$ sea inyectiva. Sea $f: \mathbb N \rightarrow \mathbb N \times \mathbb N$ con $n \rightarrow (n,1)$. $(n,1) = f(n) = f(m) = (m,1) \implies n = m$. Esto implica que $|\mathbb N| \le |\mathbb N \times \mathbb N|$ ([[Aplicaciones inyectivas en numerabilidad]])

Sea $g : \mathbb N \times \mathbb N \rightarrow \mathbb N$ con $(a,b) \rightarrow 2^a 3^b$. ¿$g$ inyectiva?
$2^a 3^b = g((a,b)) = g((a', b')) = 2^{a'} 3^{b'}$. Por la unicidad del [[Teorema fundamental de la aritmética]], concluimos que $a = a'$ y $b = b'$. Por tanto, $|\mathbb N \times \mathbb N | \le | \mathbb N|$.

Así, por el [[Teorema de Schröeder-Bernstein]], $|\mathbb N| = |\mathbb N \times \mathbb N|$.
Tags: demostración
<!--ID: 1705822944853-->
END