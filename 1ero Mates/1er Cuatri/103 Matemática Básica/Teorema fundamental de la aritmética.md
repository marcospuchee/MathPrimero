### Enunciado Teorema

Sea $1<n \in \mathbb{N}$, entonces existen primos $p_1, p_2, \dots, p_k \in \mathbb{N}$ tales que $n = p_1p_2 \dots p_k$. Además, esta expresión es única salvo orden de los factores.

---
### Demostración

##### Existencia de la descomposición
Procedemos por inducción fuerte. El caso inicial es $n_0 = 2$, que está claro. Ahora veamos para $n$. Si $n$ es primo, el resultado está probado. Por tanto, podemos suponer que no es primo, con lo que existen $a,b \in \mathbb{N}$ tal que $n = ab$, con $1<a<n$ y $1<b<n$. Por hipótesis de inducción, tenemos que el resultado es cierto para $a$ y $b$: $a = p_1 p_2 \dots p_k$, b = $p_{k`+1} \dots p_r$ y por tanto, $n = p_1 p_2 \dots p_r$.

##### Unicidad
Supongamos que tenemos dos descomposiciones de $n$: $p_1p_2\dots p_k = n = q_1 q_2 \dots q_r$, con $k \le r$. Cancelamos todos los términos que sean iguales, así que podemos suponer sin pérdida de generalidad que $p_1 \dots p_s = q_1 \dots q_m$, con $p_i \not = q_j, \forall i,j$.
Tenemos que $p_1 | p_1 \dots p_s = q_1 \dots q_m$, pero el [[Máximo común divisor]] entre $p_i$ y $q_1$ es $1$, lo que nos queda que $p_1 | q_2 \dots q_m$; sucesivamente, tenemos que $p_1 | q_m$ lo cual es una contradicción. Así, la descomposición es única.

---
### Referencias

[[Divisibilidad]]