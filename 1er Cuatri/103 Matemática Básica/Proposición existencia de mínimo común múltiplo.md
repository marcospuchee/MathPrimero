### Proposición

Sean $a,b \in \mathbb{Z} - \{0\}$, $\{c \in \mathbb{N}$ tal que $a|c$ y $b|c\} \not = \emptyset$. Por [[Ley de buena ordenación]] de $\mathbb{N}, \exists m = min\{c \in \mathbb{N} : a|c \land b|c \}$. Entonces:
1. $m > 0$.
2. $a | m$ y $b |m$.
3. Si $m'\in \mathbb{Z}, a|m'$ y $b|m'$, entonces $m|m'$.

$m$ es el mínimo común múltiplo.

---
### Demostración

1. Obvio porque $m \in \mathbb{N}$.
2. Obvio por la definición de conjunto.
3. Sea $m'$ que cumple $a|m'$ y $b|m'$, queremos ver que $m|m'$. Hacemos la división euclídea: $m' = mq +r$, con $0 \le r < m$. Entonces $r = m'-mq$ y tenemos que $a$ y $b$ dividen a $r$ (por dividir a $m'$ y $m$ ([[Lema divisibilidad a,b,c]])). Si $r \not = 0$, tenemos que $r$ pertenece al conjunto y por tanto $m \le r < m$, contradicción. Por tanto, $r = 0$ y $m | m'$.

---
### Referencias

[[Divisibilidad]]