### Proposición

Sea $\sum_{n=1}^{+\infty} a_n$ stp ([[Serie de términos positivos]]) tal que $\exists lim_{n \to +\infty} \sqrt[n]{a_n} = L$. Entonces,
1. Si $L < 1, \sum_{n=1}^{+\infty} a_n$ converge.
2. Si $L > 1, \sum_{n=1}^{+\infty} a_n$ diverge.

Si $L = 1$, el criterio no nos da información.

---
### Demostración

1. Supongamos que $L < 1$. Tomamos $L < \gamma < 1, \exists n_0 \in \mathbb{N} : \sqrt[n]{a_n} < \gamma, \forall n \ge n_0 \iff a_n < \gamma^n, \forall n \ge n_0$. Como $\sum_{n=1}^{+\infty} \gamma^n$ converge (por ser [[Series geométricas]] con razón $\gamma < 1$), entonces por el [[Criterio de Mayoración de Weierstrass]], $\sum_{n=1}^{+\infty} a_n$ converge.
2. Si $L>1, \exists n_0 \in \mathbb{N}$ tal que $\sqrt[n]{a_n} > 1, \forall n \ge n_0$. Entonces, $a_n > 1^n = 1, \forall n \ge n_0$. Luego $a_n$ no converge a $0$, diverge. Por tanto, $\sum_{n=1}^{+\infty} a_n$ diverge.

---
### Referencias

[[Serie numérica]]