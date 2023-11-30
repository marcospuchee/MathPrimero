### Enunciado Teorema

Sea $f : A \subseteq \mathbb R \rightarrow \mathbb R$ y sea $x \in ac(A)$, entonces: 
$\exists lim_{x \to x_0} f(x) \iff \forall (x_n)_{n=1}^{+\infty} \subseteq A$ con $x_n \not = x_0, \forall n \in \mathbb N$ y tal que $\exists lim_{n \to \infty} x_n = x_0$ entonces $\exists lim_{n \to \infty} f(x_n)$
En este caso, si $\lim_{x \to x_0} f(x) = l \in \mathbb R \cup \{- \infty, + \infty, \infty\}$ entonces $lim_{n \to +\infty} f(x_n) = l$ para toda sucesión en las condiciones anteriores.

---
### Demostración

#### Caso 1. $l \in \mathbb R$
$\rightarrow$. Sea $(x_n)_{n=1}^{+\infty} \subset A$ con $x_n \not = x_0, \forall n \in \mathbb N$ tal que $\lim_{n \to + \infty} x_n = x_0$. Veamos que $\exists lim_{n \to +\infty} f(x_n) = l$. Como $lim_{x \to x_0} f(x) = l$, dado $\epsilon > 0, \exists \delta > 0$ tal que si $x \in A, 0 < |x-x_0| < \delta$. Esto implica que $|f(x) - l| < \epsilon$
Como $lim_{n \to +\infty} x_n = x_0, \exists n_0 \in \mathbb N$ tal que si $n \ge n_0, |x_n - x_0| < \delta$. Como $x_n \not = x_0, \forall n \in \mathbb N$, $|f(x_n) - l| < \epsilon$. Esto es, $\exists lim_{n \to +\infty} f(x_n) = l$.

---
### Referencias

[[Función]]