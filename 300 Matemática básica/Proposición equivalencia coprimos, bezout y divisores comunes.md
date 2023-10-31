### Proposición

Sean $a,b \in \mathbb{Z}, a \not = 0 \not = b$, son equivalentes:
1. $\exists x,y \in \mathbb{Z}$ tal que $ax +by = 1$.
2. $mcd(a,b)=1$.
3. Los únicos divisores comunes de $a$ y $b$ son $1, -1$.

---
### Demostración

#### $1 \implies 2$
$1 = ax + by \in \Omega$ ([[Teorema de Bezout]]) $\implies 1 = min\Omega$ porque $\Omega \subseteq \mathbb{N}$. Como $1 = min \Omega, 1 = mcd(a,b)$.
#### $2 \implies 3$
Supongamos que existe $d$ tal que $d|a$ y $d|b \implies d|1$ ([[Proposición divisibilidad de un divisor]]). Como $1|d$, se da que $d = \pm 1$ [[Proposición cuando dos números se dividen simultáneamente son iguales]].
#### $3 \implies 1$
$mcd(a,b)|a$ y $mcd(a,b)|b \implies mcd(a,b)=1$ (iii). Así, aplicando la [[Identidad de Bezout]], $\exists x,y \in \mathbb{Z}$ tal que $ax + by =1$.

---
### Referencias

[[Divisibilidad]]