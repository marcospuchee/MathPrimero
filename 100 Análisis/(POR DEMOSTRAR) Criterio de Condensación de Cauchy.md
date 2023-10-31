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
POR DEMOSTRAR.

---
### Referencias

[[Serie numérica]]

30-10-23. Análisis