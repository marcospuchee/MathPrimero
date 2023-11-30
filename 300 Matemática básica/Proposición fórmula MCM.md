### Proposición

Sean $a,b \ge 2$ con factorizaciones: $a = p_1^{r_1} p_2^{r_2} \dots p_m^{r_m}$ y $b = p_1^{s_1} p_2^{s_2} \dots p_m^{s_m}$ donde $0 \le r_i, s_i$, entonces: $mcm(a,b) = \prod_{i=1}^m p_i^{max(r_i, s_i)}$.

---
### Demostración

Sea $m = \prod_{i=1}^m p_i^{max(r_i, s_i)}$. Está claro que $a|m$ y $b|m$, con lo que $[a,b] | m$ ([[Proposición existencia de mínimo común múltiplo]]) Por tanto, por el [[Corolario diferencia factorización entre dos números, uno divisor del otro]], podemos escribir $[a,b] = p_1^{t_1} \dots p_m^{t_m}$ con $0 \le t_i \le max(r_i, s_i)$. Supongamos que $\exists i$ tal que $t_i < max(r_i, s_i)$. Entonces $t_i < r_i$ o $t_i < s_i$. Supongamos sin pérdida de generalidad que $t_i < r_i$. De la definición de $a$ sacamos que $p_i^{r_i} | a |[a,b] = p_1^{t_1} \dots p_m^{t_m}$, de lo que nos quedamos que $p_i^{r_i} | p_1^{t_1} \dots p_m^{t_m}$. Como $(p_i^{r_i}, p_j^{t_j}) = 1$ (son [[Coprimos]]) si $i \not = j$, necesariamente $p_i^{r_i} | p_i^{t_i} < p_i^{r_i}$, lo cual es una contradicción.

---
### Referencias

[[Divisibilidad]]
[[Proposición existencia de mínimo común múltiplo]]