### Proposición

Sean $\sum_{n=1}^{+\infty} a_n$ y $\sum_{n=1}^{+\infty} b_n$ stp ([[Serie de términos positivos]]) tales que $\exists lim_{n \to +\infty} \frac{a_n}{b_n} = L \in \mathbb{R} \cup \{+\infty\}$. Entonces:
1. $L \in \mathbb{R} - \{0\}\implies \sum_{n=1}^{+\infty} a_n$ y $\sum_{n=1}^{+\infty} b_n$ tienen el mismo carácter.
2. $L = 0 \implies (\sum_{n=1}^{+\infty} b_n$ converge $\implies \sum_{n=1}^{+\infty} a_n$ converge$)$.
3. $L = +\infty \implies (\sum_{n=1}^{+\infty} b_n$ diverge $\implies \sum_{n=1}^{+\infty} a_n$ diverge$)$.

---
### Demostración

1. $L \in \mathbb{R} - \{0\} \implies L > 0$ (dado que $a_n$ y $b_n$ son stp). Tomamos $\epsilon = \frac{L}{2}$, $\exists n_0 \in \mathbb{N}$ tal que $|\frac{a_n}{b_n} - L| < \frac{L}{2}$. $-\frac{L}{2} < \frac{a_n}{b_n} - L < \frac{L}{2} \iff \frac{L}{2} < \frac{a_n}{b_n} < \frac{3}{2} L \iff \frac{L}{2} b_n < a_n < \frac{3L}{2}b_n, \forall n \ge n_0$. Por el [[Criterio de Mayoración de Weierstrass]], se sigue 1).
2. Tomo $\epsilon = 1, \exists n_0 \in \mathbb{N}$ tal que $|\frac{a_n}{b_n} - L| < 1, \forall n \ge n_0$. $\frac{a_n}{b_n} < L +1, \forall n \ge n_0$. $a_n < (L+1)b_n, \forall n\ge n_0$. $(L+1)b_n$ converge, entonces por el [[Criterio de Mayoración de Weierstrass]], $a_n$ también converge.
3. Supongamos ahora que $L = +\infty$. Sea $M > 0, \exists n_0$ tal que $\frac{a_n}{b_n} > M, \forall n \ge n_0$. $a_n > Mb_n, \forall n \ge n_0$. Como $\sum_{n=1}^{+\infty} Mb_n$ diverge, por el [[Criterio de Mayoración de Weierstrass]], $\sum_{n=1}^{+\infty} a_n$ diverge.
---
### Referencias

[[Serie numérica]]

24-10-23. Análisis.