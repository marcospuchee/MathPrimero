### Proposición

Si $(a_n)^\infty_{n=1}$ es una sucesión de Cauchy que contiene una subsucesión convergente, entonces $(a_n)^\infty_{n=1}$ converge.

---
### Demostración

Sea $(a_{n_k})^\infty_{k=1}$ una subsucesión de $(a_n)^\infty_{n=1}$ convergente, digamos a $l \in \mathbb{R}$. Sea $\epsilon > 0$, como $lim_{k \to +\infty} a_{n_k} = l, \exists k_0 \in \mathbb{N} : |a_{n_k} - l| < \frac{\epsilon}{2}, \forall k \ge k_0$. Como $(a_n)^\infty_{n=1}$ es de Cauchy, $\exists n_1 \in \mathbb{N}$ tal que $|a_n - a_m| < \frac{\epsilon}{2}, \forall n,m \ge n_1$. 

Tomamos $n_0 := max\{n_1, k_0\}$. Si $k\ge n_0, n_k \ge k \ge n_0$:
$|a_k - l| = |(a_k - a_{n_k}) + (a_{n_k} - l)| \le |a_k - a_{n_k}| + |a_{n_k} - l| < \frac{\epsilon}{2} + \frac{\epsilon}{2} = \epsilon$.
$|a_k - l| < \epsilon$.

---
### Referencias
[[Sucesión]]
[[Sucesión de Cauchy]]
