### Proposición

Sea $\sum_{n=1}^{+\infty} a_n$ stp ([[Serie de términos positivos]]) tal que $\exists lim_{n \to +\infty} \frac{a_{n+1}}{a_n} = L$. Entonces:
1. $L < 1 \implies \sum_{n=1}^{+\infty} a_n$ converge.
2. $L > 1 \implies \sum_{n=1}^{+\infty} a_n$ diverge.

Si $L=1$, el Criterio no es concluyente.

---
### Demostración

1. Supongamos que $L<1$. Sea $L < \gamma < 1, \exists n_0 \in \mathbb{N} : \frac{a_{n+1}}{a_n} < \gamma = \frac{\gamma^{n+1}}{\gamma^n}, \forall n \ge n_0$. Así, $a_{n+1} \gamma^n < \gamma^{n+1} a_n, \forall n \ge n_0$. Esto implica que $\frac{a_{n+1}}{\gamma^{n+1}} < \frac{a_n}{\gamma^n}, \forall n \ge n_0$. Esto demuestra que $(\frac{a_n}{\gamma^n})^{+\infty}_{n = n_0}$ es estrictamente decreciente, por  lo que $\frac{a_n}{\gamma^n} < \frac{a_{n_0}}{\gamma^{n_0}} = M, \forall n \ge n_0 \iff a_n < M \gamma^n, \forall n \ge n_0$. Como $\sum_{n=1}^{+\infty} \gamma^n$ converge por ser $0 < \gamma < 1$, por el [[Criterio de Mayoración de Weierstrass]], $\sum_{n=1}^{+\infty} a_n$ converge.
2. Como $lim_{n \to +\infty} \frac{a_{n+1}}{a_n} > 1$, $\exists n_0 \in \mathbb{N}$ tal que $\frac{a_{n+1}}{a_n} > 1, \forall n \ge n_0$. Así, tenemos que $a_{n+1} > a_n, \forall n \ge n_0$, luego $0 < a_{n_0} < a_n, \forall n \ge n_0$. Por lo tanto, $a_n \not \to_{n \to +\infty} 0$, luego $\sum_{n=1}^{+\infty} a_n$ diverge.

---
### Referencias

[[Serie numérica]]

24-10-23