### Enunciado Teorema

La serie $\sum^{+\infty}_{n=1} a_n$ converge $\iff \forall \epsilon > 0, \exists n_0 \in \mathbb{N}$ tal que $|\sum^{n+p}_{m=n+1} a_n| < \epsilon, \forall n \ge n_0, \forall p \in \mathbb{N}$.

---
### Demostración

Por definición, $\sum^{+\infty}_{n=1}$ converge $\iff (\sum^{N}_{m=1}a_m)^{+\infty}_{m=1}$ converge, lo que quiere decir que si y solo si $(\sum^{N}_{m=1})^{+\infty}_{n=1}$ es de Cauchy. Es decir, si y sólo si, $\forall \epsilon > 0, \exists n_0 \in \mathbb{N}$ tal que $|\sum^{n}_{m=1} a_m - \sum^{n'}_{m=1} a_m| < \epsilon$, con $n, n' \ge n_0$.

Sean $n,n' \ge n_0$, supongamos $n < n' \implies n' = n+p$ con $p \in \mathbb{N}$. Entonces, $|\sum^{n}_{m=1} a_m - \sum^{n+p}_{m=1} a_m| = |\sum^{n+p}_{m=n+1} a_m| < \epsilon$.

---
### Referencias

[[Serie numérica]]
[[Convergencia de una serie numérica]]