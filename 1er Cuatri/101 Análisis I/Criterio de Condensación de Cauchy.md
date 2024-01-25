### Proposición

Sea $(a_n)_{n=1}^{+ \infty}$ una sucesión tal que: $a_n \ge 0, \forall n \in \mathbb{N}$ y $a_n \ge a_{n+1}, \forall n \in \mathbb{N}$. La serie $\sum_{n=1}^{+\infty} a_n$ converge $\iff \sum_{n=1}^{+\infty} 2^n a_{2^n}$ converge.

---
### Demostración

Veamos que $\sum_{k=1}^n a_k \le \sum_{k=0}^n 2^k a_{2^k} \le 2 \sum_{k=1}^{2^n} a_k$.

##### Primera desigualdad.
Sea $\sum_{k=1}^n a_k$, vamos a agrupar por $2^n \rightarrow$ $a_1, a_2, a_3, a_4, a_5, a_6, a_7, a_8, a_9, \dots, a_{15}, a_{16}, \dots$
$a_2 a_3 < a_2 a_2 \rightarrow a_4 a_5 a_6 a_7 < a_4 a_4 a_4 a_4 \rightarrow a_8 a_9 \dots a_{15} < a_8 a_8 \dots a_8$, y así con todos. Por lo tanto, tenemos que
$\sum_{k=1}^n a_k \le \sum_{k=1}^{2^{n+1}-1} a_k \le \sum_{j=0}^n \sum_{k=2^j}^{2^{j+1}-1} a_k \le \sum_{j=0}^n \sum_{k=2^j}^{2^{j+1}-1} a_{2^j} = \sum_{j=0}^n (2^{j+1} - 2^j)a_{2^j} = \sum_{j=0}^n 2^j a_{2^j}$.

##### Segunda desigualdad.
$\sum_{j=0}^n 2^j a_{2^j} = a_1 + \sum_{j=1}^{n} 2^j a_{2^j}$. Tomamos $k = j-1$, $a_1 + \sum_{k=0}^{n-1} 2^{k+1} a_{2^{k +1}} = a_1 + 2 \sum_{k=0}^{n-1} 2^k a_{2^{k+1}}$. De aquí sabemos que $2^k = 2^{k+1} -2^k$, $a_1 + 2\sum_{k=0}^{n-1}(2^{k+1} - 2^k) a_{2^{k+1}} = a_1 + 2\sum_{k=0}^{n-1} \sum_{j=2^k +1}^{2^{k+1}} a_{2^{k+1}} \le a_1 + 2 \sum_{k=0}^{n-1} \sum_{j=2^k +1}^{2^{k+1}} a_j$. Esto es lo mismo que $a_1 +2 \sum_{k=2}^{2^n} a_k < 2a_1 + 2\sum_{k=2}^{2^n} a_k = 2 \sum_{k=1}^{2^n} a_k$.

Así, si $\sum_{n=1}^{+\infty} 2^n a_{2^n}$ converge, entonces $(\sum_{j=1}^n 2^j a_{2^j})_{n=1}^{+\infty}$ está acotada. Por la primera desigualdad, $(\sum_{j=1}^n a_j)_{j=1}^{+\infty}$ está acotada superiormente, y por ser creciente (pues $a_n \ge 0, \forall n \in \mathbb{N}$), converge ([[Toda sucesión creciente y acotada superiormente es convergente]]). Análogamente, usando la segunda desigualdad se tiene la otra implicación.

---
### Referencias

[[Serie numérica]]

30-10-23. Análisis