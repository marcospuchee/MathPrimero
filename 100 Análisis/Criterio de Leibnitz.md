### Proposición

Sea $\sum_{n=1}^{+\infty} a_n$ una [[Serie alternada]] tal que, $|a_n| \ge |a_{n+1}| , \forall n \in \mathbb{N}$ y $|a_n| \to_n 0$, entonces $\sum_{n=1}^{+\infty} a_n$ converge.

---
### Demostración

Veamos que $(S_n)^{+\infty}_{n=1}$, donde $S_n = \sum_{j=1}^n (-1)^j a_j$, converge.
$S_1 = -a_1$ 
$S_2 = -a_1 + a_2$ 
$S_3 = -a_1 + a_2 - a_3 = S_1 + a_2 - a_3$
$S_4 = -a_1 + a_2 -a_3 + a_4 = S_2 - a_3 + a_4$
$S_5 = -a_1 + a_2 - a_3 + a_4 - a_5 = S_3 + a_4 - a_5 \ge S_3$.
$S_6 = -a_1 + a_2 - a_3 + a_4 - a_5 + a_6 = S_4 -a_5 + a_6 \le S_4$.

Como podemos comprobar, se repite un patrón:
$S_{2k+1} = S_{2k-1} + a_{2k} - a_{2k+1} \ge S_{2k-1}$
$S_{2k+2} = S_{2k} - a_{2k+1} + a_{2k+2} \le S_{2k}$

Por tanto, tenemos que $(S_{2k+1})_{k=1}^{+\infty}$ es monótona creciente y $(S_{2k})_{k=1}^{+\infty}$ es monótona decreciente. Como $S_{2k+1} = S_{2k} - a_{2k+1} \le S_{2k}, \forall k \in \mathbb{N}$, entonces concluimos que $S_2 \ge S_{2k} \ge S_{2k+1} \ge S_1$. Por tanto, $(S_{2k+1})_{k=1}^{+\infty}$ y $(S_{2k})_{n=1}^{+\infty}$ convergen. Como $S_{2k} - S_{2k+1} = a_{2k+1}$, y $a_{2k+1} \to 0$ (hipótesis), entonces $lim_{k \to +\infty} S_{2k} = lim_{k \to +\infty} S_{2k+1}$.

---
### Referencias

[[Serie numérica]]
[[Convergencia de una serie numérica]]