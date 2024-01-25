### Proposición

Sean $\sum_{n=1}^{+\infty} a_n$ y $\sum_{n=1}^{+\infty} b_n$ stp ([[Serie de términos positivos]]) cumpliendo que $\exists n_0 \in \mathbb{N}$ tal que $a_n \le b_n, \forall n \ge n_0$. Entonces:
1) Si $\sum_{n=1}^{+\infty} b_n$ converge, entonces $\sum_{n=1}^{+\infty} a_n$ también converge.
2) Si $\sum_{n=1}^{+\infty} a_n$ diverge, entonces $\sum_{n=1}^{+\infty} b_n$ también diverge.

---
### Demostración

1) Sea $m>n$, $\sum_{n=n_0}^{m} a_n \le \sum_{n=n_0}^{m} b_n$ (hipótesis). Como $\sum_{n=1}^{+\infty} b_n$ converge, entonces $\sum_{n=n_0}^{+\infty} b_n$ converge ([[Proposición convergencia de una serie numérica]]). Por tanto, $(\sum_{n=n_0}^{m} b_n)^{+\infty}_{m = n_0}$ está acotada. Por la hipótesis, $(\sum_{n=n_0}^{m} a_n)_{m = n_0}^{+\infty}$ está acotada superiormente. Como $a_n > 0, \forall n \in \mathbb{N}$, $(\sum_{n=n_0}^{m} a_n)_{m = n_0}^{+\infty}$ es creciente. Luego $(\sum_{n=n_0}^{m} a_n)^{+\infty}_{m = n_0}$ converge ([[Toda sucesión creciente y acotada superiormente es convergente]]), esto es $\sum_{n=n_0}^{+\infty} a_n$ converge, luego $\sum_{n=1}^{+\infty} a_n$ converge.
2) Claro por 1).

---
### Referencias

[[Serie numérica]]

24-10-23. Análisis.