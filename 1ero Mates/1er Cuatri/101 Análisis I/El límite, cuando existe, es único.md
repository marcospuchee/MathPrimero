### Proposición

El límite, cuando existe, es único.

---
### Demostración

Supongamos que $l, l'$ son límites de una sucesión $(a_n)^\infty_{n=1}$ cuando esta tiende a $\infty$.
Sea $\epsilon > 0, \exists n_0 \in \mathbb{N}$ tal que $|a_n - l| < \epsilon, \forall n \ge n_0$.
Sea $\epsilon > 0, \exists n_1 \in \mathbb{N}$ tal que $|a_n - l'| < \epsilon, \forall n \ge n_1$.
Sea $n_2 \ge max(n_0, n_1)$ :
$0 \le |l-l'| = |l-a_{n_2} + a_{n_2} - l'| = |(l-a_{n_2}) + (a_{n_2} - l')| = |l-a_{n_2}| + |a_{n_2} - l'| < \epsilon + \epsilon = 2\epsilon$.

Como $\epsilon > 0$ es arbitrario, concluimos que $|l-l'| = 0, l = l'$.

---
### Referencias
[[Límite de una sucesión]]