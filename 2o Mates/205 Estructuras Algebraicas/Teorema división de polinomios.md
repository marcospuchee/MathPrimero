### Contenido Principal

```ad-theorem
Sea $R$ un anillo con identidad y $p,q \in R[x]$ con
$$p = \sum_{i = 0}^n r_i x^i; \quad q = \sum_{i = 0}^m s_i x^i$$
donde $\delta(p) = n$ y $\delta(q) = m$. Si $q \neq 0_{R[x]}$ y $s_m \in R^\times$, entonces $\exists c,r \in R[x]$ únicos tales que
$$p = cq + r$$
con $\delta(r) < \delta(q)$.
```

```ad-proof
**Existencia.** Procederemos por inducción fuerte sobre $\delta(p)$.

Distinguiremos dos casos:
1. $\delta(p) < \delta(q)$. Entonces podemos considerar:
$$p = 0_{R[x]}q+p.$$
2. $\delta(p) \ge \delta(q)$. En particular, como $q \neq 0_{R[x]}$, entonces $p \neq 0_{R[x]}$ y $r_n \neq 0_R$.
Como $s_m$ es un elemento invertible, consideramos
$$p' = (r_n s^{-1}_m x^{n-m})q \in R[x].$$
Sabemos que $\delta(p') \le (n-m)+m = n$. Además, el coeficiente de grado $n$ es $r_ns_m^{-1}s_m = r_n \neq 0_R$. Por tanto, $\delta(p') = n$.
Por hipótesis inductiva, $\exists c,r \in R[x]$ tales que
$$p-p' = cq + r$$
con $\delta(r) < \delta(q)$. Entonces:
$$\begin{eqnarray}
p=p'+cq+r &=& (r_ns_m^{-1}x^{n-m})q + cq + r \\
&=& (r_ns^{-1}_m x^{n-m}+c)q+r
\end{eqnarray}$$
con $\delta(r) < \delta(q)$.

**Unicidad.** Supongamos que $\exists c,c',r,r' \in R[x]$ tales que
$$p=cq+r=c'q+r'$$
con $\delta(r)< \delta(q)$, $\delta(r') < \delta(q)$. Entonces,
$$r-r' = (p-cq)-(p-c'q) = (c'-c)q.$$
Supongamos por reducción al absurdo que $c \neq c'$. Entonces, $c'-c \neq 0_{R[x]}$. Por tanto,
$$\begin{eqnarray}
\delta(q) &\le& \delta(c'-c)+\delta(q) \overset{(*)}{=} \delta((c'-c)q) \\
&=& \delta(r-r') \le \max \{\delta(r), \delta(r') \} < \delta(q),
\end{eqnarray}$$
lo cual es una contradicción.
*Justificación de* $(*)$: Recordamos $q = \sum_{i = 1}^m s_i x^i$ con $s_m \neq 0_R$ invertible. Denotamos $c'-c = \sum_{i = 1}^{m'} t_i x^i$ con $t_{m'} \neq 0_R$. Sabemos que $\delta((c'-c)q) \le m+m'$. Además, el coeficiente $m+m'$ de $(c'-c)q$ es $t_{m'}s_m$. Así, si $t_{m'}s_m = 0_R$, entonces $t_{m'} = t_{m'}s_m s_m^{-1} = 0_R s_m = 0_R$, lo cual es una contradicción. Por tanto, $\delta((c'-c)q) = m+m'$.

Así, $c=c'$ y entonces $r=p-cq = p-c'q = r'$.
```

**Tema:** [[Anillo de polinomios#4. $K[x]$]]

**Definiciones referenciadas:** [[Anillo con identidad]], [[Polinomio]], [$\delta(p)$](Grado de un polinomio), [$R^\times$](Unidad)
**Resultados referenciados:**

---
### Anki
