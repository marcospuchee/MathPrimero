### Proposición

Sea $p \in \mathbb{N}, \sum_{n=1}^{+\infty} a_n$ converge $\iff \sum_{n=p}^{+\infty} a_n$ converge.

$\sum_{n=1}^{+\infty} a_n = a_1 + a_2 + \dots + a_{p-1} + \sum_{n=p}^{+\infty} a_n$.

---
### Demostración

Sea $S_N = \sum_{n=1}^{N} a_n$ con $N>p$ y sea $S'_N = \sum_{n=p}^{N} a_n$, entonces $S_N = a_1 + a_2 + \dots + a_{p-1} + S'_N$.
Luego $\exists lim_{N \to +\infty} S_N \iff \exists lim_{N \to +\infty} S'_N$ y en este caso, $lim_{N \to +\infty} S_N = a_1 + \dots + a_{p-1} + lim_{N \to +\infty} S'_N$, de aquí, sabemos que $lim_{N \to +\infty} S_N = \sum_{n=1}^{+\infty} a_n$, y $lim_{N \to +\infty} S'_N = \sum_{n=p}^{+\infty} a_n$.

---
### Referencias
[[Serie numérica]]