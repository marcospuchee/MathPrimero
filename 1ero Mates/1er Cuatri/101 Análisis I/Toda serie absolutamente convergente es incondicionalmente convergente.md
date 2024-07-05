### Proposición

Toda [[Serie absolutamente convergente]] es [[Serie incondicionalmente convergente]].

---
### Demostración

Supongamos en primer lugar que $\sum_{n=1}^{+\infty} a_n$ es una [[Serie de términos positivos]] convergente, sea $S = \sum_{n=1}^{+\infty} a_n$. Sea $\sum_{n=1}^{+\infty} b_n$ una reordenación ([[Teorema de reordenación de Riemann]]) de $\sum_{n=1}^{+\infty} a_n$, dado $\epsilon > 0$, $\exists n_0 \in \mathbb{N}$ tal que: $|\sum_{k=1}^n a_k - S| < \epsilon, \forall n \ge n_0$.

Sea $n_1 \in \mathbb{N}$ tal que $a_k \in \{b_1, \dots, b_{n_1}\}, \forall k \in \{1, \dots, n_0\}$. 
Si $n > n_1$, $|\sum_{k=1}^n b_k - S| = S - (b_1 + b_2 + \dots + b_n) \le S - (a_1 + a_2 + \dots + a_{n+1}) < \epsilon$.
En el caso general, si $\sum_{n=1}^{+\infty} a_n$ es absolutamente convergente, entonces $\sum_{n=1}^{+\infty} |a_n|$ es convergente. Si $\sum_{n=1}^{+\infty} b_n$ es una reordenación de $\sum_{n=1}^{+\infty} a_n, \sum_{n=1}^{+\infty} |b_n|$ es una reordenación. Luego $\sum_{n=1}^{+\infty} |b_n|$ converge, y por tanto $\sum_{n=1}^{+\infty} b_n$ converge ([[Toda serie absolutamente convergente converge]]). Faltaría probar que tiene la misma suma.

---
### Referencias

[[Serie numérica]]

08-10-23. Análisis.