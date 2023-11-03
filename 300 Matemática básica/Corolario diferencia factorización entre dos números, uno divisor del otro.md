### Corolario

Sea $n = p_1^{a_1} \dots p_k^{a_k}$. Si $1 < m | n$, entonces, $m = p_1^{b_1} \dots p_k^{b_k}$ con $0 \le b_i \le a_i$.

---
### Demostración

Si $m = n$, está claro. Si $n > m$, entonces sea $1 < c \in \mathbb{N}$ tal que $mc = n$, consideramos la descomposición de $m$ y de $c$ como producto de primos:
- $m = q_1^{e_1} \dots q_s^{e_s}$.
- $c = r_1^{f_1} \dots r_s^{f_s}$.
con lo que $q_1^{e_1} \dots q_s^{e_s} r_1^{f_1} \dots r_s^{f_s} = mc = n = p_1^{a_1} \dots p_k^{a_k}$. Por la unicidad de la descomposición ([[Teorema fundamental de la aritmética]]), tenemos que $\forall i, q_i = p_j$ para algún $j$ y que $e_i \le a_i, \forall i$.

---
### Referencias

[[Divisibilidad]]