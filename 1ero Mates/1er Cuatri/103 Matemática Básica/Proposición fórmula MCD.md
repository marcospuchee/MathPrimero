### Proposición

Sean $a,b \ge 2$ con factorizaciones: $a = p_1^{r_1} p_2^{r_2} \dots p_m^{r_m}$ y $b = p_1^{s_1} p_2^{s_2} \dots p_m^{s_m}$ donde $0 \le r_i, s_i$, entonces: $mcd(a,b) = \prod_{i=1}^m p_i^{min(r_i, s_i)}$.

---
### Demostración

Sea $d = \prod_{i=1}^m p_i^{min(r_i, s_i)}$, queremos ver que $d = mcd(a,b)$. Como $mcd(a,b) | a$ y $mcd(a,b) | b$, por el [[Corolario diferencia factorización entre dos números, uno divisor del otro]], podemos escribir $mcd(a,b) = p_1^{t_1} \dots p_m^{t_m}$ con $0\le t_i \le min(r_i, s_i)$. Por tanto $(a,b) | d$. Por otra parte, está claro que $d|a$ y $d|b$ por lo que $d|(a,b)$. [[Proposición cuando dos números se dividen simultáneamente son iguales]].

---
### Referencias

[[Divisibilidad]]
[[Máximo común divisor]]