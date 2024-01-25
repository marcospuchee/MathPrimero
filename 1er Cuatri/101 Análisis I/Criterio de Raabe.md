### Proposición

Sea $\sum_{n=1}^{+\infty} a_n$ stp ([[Serie de términos positivos]]) tal que $\exists lim_{n \to +\infty} n(\frac{a_n}{a_{n+1}}-1) = l \in \mathbb{R} \cup \{-\infty, +\infty\}$.

1. $l>1 \implies$ la serie converge.
2. $l < 1 \implies$ la serie diverge.

Si $l =1$, no podemos concluir nada.

---
### Demostración

### 1.
$l > 1$, sea $k \in \mathbb{R}$ tal que $1<k<l$. Como $lim_{n \to +\infty} n(\frac{a_n}{a_{n+1}} - 1) = l, \exists n_0 \in \mathbb{N}$ tal que $n(\frac{a_n}{a_{n+1}}-1) >k, \forall n \ge n_0$. Por tanto, $\frac{a_n}{a_{n+1}} > \frac{k}{n} + 1 = \frac{k+n}{n}, \forall n \ge n_0 \iff na_n > ka_{n+1} + na_{n+1}, \forall n \ge n_0$. Ahora nos damos cuenta de que:
2. $ka_{n_0+1} < n_0 a_{n_0} - (n_0 + 1) a_{n_0 +1} + a_{n_0+1}$
3. $ka_{n_0+2} < (n_0+1) a_{n_0+1} - (n_0 + 2) a_{n_0 +2} + a_{n_0+2}$
4. $ka_{n_0+3} < (n_0+2) a_{n_0+2} - (n_0 + 3) a_{n_0 +3} + a_{n_0+3}$
Hasta que para $n$ y $n+1$:
5. $ka_n < (n-1) a_{n-1} - n  a_{n} + a_n \iff k_{a_{n+1}} < na_n - (n+1)a_{n+1} + a_{n+1}$.

Todo esto es igual a: $k(S_{n+1} - S_{n_0}) < n_0 a_{n_0} - (n+1)a_{n+1} + (S_{n+1} - S_{n_0})$ dado que todo lo demás se cancela.
$(k-1)(S_{n+1}-S_{n_0}) < n_0a_{n_0} - (n+1)a_{n+1} < n_0 a_{n_0}$. Como sabemos que $k > 1$, $S_{n+1} - S_{n_0} < \frac{n_0 a_{n_0}}{k-1}$ $\iff S_{n+1} < \frac{k_0 a_{n_0}}{k-1} + S_{n_0}$. Así, tenemos que $(S_{n+1})_{n=n_0}^{+\infty}$ está acotada superiormente por una constante. Como $a_n > 0, \forall n \in \mathbb{N}, (S_{n+1})_{n=n_0}^{+\infty}$ es estrictamente creciente. [[Toda sucesión creciente y acotada superiormente es convergente]].

### 2.
$l < 1, \exists n_00 \in \mathbb{N}$ tal que $n(\frac{a_n}{a_{n+1}} - 1) < 1, \forall n \ge n_0$. De aquí tenemos que $\frac{a_n}{a_{n+1}} < \frac{1}{n} + 1 = \frac{1+n}{n}, \forall n \ge n_0$. Esto nos lleva a que $na_n < (n+1)a_{n+1}, \forall n \ge n_0 \iff n_0 a_{n_0} < na_n, \forall n>n_0 \iff \frac{n_0 a_{n_0}}{n} < a_n, \forall n>n_0$. Como la serie armónica $\sum_{n=1}^{+\infty} \frac{1}{n}$ diverge, por el [[Criterio de Mayoración de Weierstrass]], $\sum_{n=1}^{+\infty} a_n$ diverge.


---
### Referencias

[[Serie numérica]]

30-10-23. Análisis.