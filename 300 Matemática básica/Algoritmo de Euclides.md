### Contenido principal

El algoritmo de Euclides sirve para encontrar $mcd(a,b)$, y funciona realizando las siguientes divisiones sucesivas:
1. $a$ entre $b$: $\exists q_1, r_1 \in \mathbb{Z}$ tales que $a = q_1b + r_1$, con $0 \le r_1 < |b|$.
2. $b$ entre $r_1$: $\exists q_2, r_2 \in \mathbb{Z}$ tales que $b = q_2 r_1 + r_2$, con $0 \le r_2 < r_1 < |b|$.
3. $r_1$ entre $r_2$: $\exists q_3, r_3 \in \mathbb{Z}$ tales que $r_1 = q_3 r_2 + r_3$, con $0 \le r_3 < r_2 < r_1 < |b|$.

Dado que esta secuencia es estrictamente decreciente y de números no negativos, ha de alcanzar el $0$. Sea $r_k$ el primer resto nulo, entonces, aplicando el [[Lema mcd de un entero y otro obtenido a partir de este]], tenemos que:
$mcd(a,b) = mcd(b,r_1) = mcd(r_1, r_2) = \dots = (r_{k-1}, 0) = r_{k-1}$.


--- 
### Referencias

[[Divisibilidad]]

25-10-23