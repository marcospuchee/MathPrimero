### Corolario

Si $\sum_{n=1}^{+\infty} a_n$ converge, entonces $lim_{n \to +\infty} a_n = 0$.

---
### Demostración

Como $\sum_{n=1}^{+\infty} a_n$ converge, dado $\epsilon > 0, \exists n_0 \in \mathbb{N}$ tal que: $|\sum_{m=n+1}^{n+p} a_m| < \epsilon, \forall n \ge n_0, \forall p \in \mathbb{N}$.
Tomo $p=1 \implies |\sum_{m=n+1}^{n=1} a_m| = |a_{n+1}| < \epsilon, \forall n \ge n_0$. Luego $\exists lim_{n \to +\infty} a_{n+1} = lim_{n \to +\infty} a_n = 0$.

El recíproco no es cierto en general.

---
### Referencias
[[Serie numérica]]
[[Convergencia de una serie numérica]]