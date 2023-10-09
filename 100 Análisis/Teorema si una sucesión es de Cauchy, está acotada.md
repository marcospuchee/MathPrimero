### Enunciado Teorema

Si una sucesión es de Cauchy, entonces está acotada.

---
### Demostración

Sea $(a_n)^\infty_{n=1}$ una sucesión de Cauchy. Vamos a tomar $\epsilon = 1$, ya que se cumple que $\epsilon > 0$. $\exists n_0 \in \mathbb{N}: |a_n - a_m| < \epsilon, \forall n,m \ge n_0$. En particular, $|a_n - a_{n_0}| < \epsilon, \forall n \ge n_0$. $(n_0 = m)$.
Si $n \ge n_0, |a_n| = |(a_n - a_{n_0}) + a_{n_0}| \le |a_n - a_{n_0}| + |a_{n_0}| < 1 + |a_{n_0}|$. Por tanto $|a_n| < 1+ |a_{n_0}|$, la sucesión a partir de la cual $|a_n - a_m| < 1$ está acotada por $1 + |a_{n_0}|$.

En cambio, si $n < n_0$, es decir, toda la parte de la sucesión en que no se cumple que $|a_n - a_m| < 1$, está acotada por $M := max(\{|a_1|, |a_2|, \dots , |a_{n_0 - 1}|\})$.

Así, ambas partes de la sucesión queda acotada.

---
### Referencias
[[Sucesión de Cauchy]]
[[Sucesión]]
[[Sucesiones acotadas]]