### Proposición

Toda [[Serie absolutamente convergente]] converge.

---
### Demostración

Sea $\sum_{n=1}^{+\infty} a_n$ una serie absolutamente convergente. Por el [[Teorema criterio general de convergencia de Cauchy]], dado $\epsilon > 0$, $\exists n_0 \in \mathbb{N}$ tal que $|\sum_{m = n+1}^{n+p} |a_m||  < \epsilon, \forall n \ge n_0, \forall p \in \mathbb{N}$. Si $n \ge n_0, p \in \mathbb{N}$, $|\sum_{m=n+1}^{n+p} a_m| \le \sum_{m=n+1}^{n+p} |a_m| = |\sum_{m=n+1}^{n+1} |a_m|| < \epsilon$. Por lo que $\sum_{n=1}^{+\infty} a_n$ converge.

Sin embargo, el recíproco no es cierto. Hay series convergente que no son absolutamente convergentes: [[Serie condicionalmente convergente]]

---
### Referencias

[[Serie numérica]]

08-11-23. Análisis.