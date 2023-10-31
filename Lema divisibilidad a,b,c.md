### Lema

Sean $a,b,c \in \mathbb{Z}$, entonces:
1. $a|b$ y $a|c \implies a |b+c$.
2. $a|b+c$ y $a |b \implies a |c$
3. $a|b \implies a|bk, \forall k \in \mathbb{Z}$
4. $a \not = 0, ab|ac \implies b|c$.

---
### Demostración

1. $\exists b', c' \in \mathbb{Z}$ tal que $ab' = b$ y $ac' = c \implies  b+c = ab' + ac' = a(b' +c')$.
2. $a|b+c$ y $a|b \implies \exists a' \in \mathbb{Z}$ tal que $aa' = b+c$ y $\exists b' \in \mathbb{Z}$ tal que $ab' = b$. Así, tenemos que $c = b+c-c = aa' -ab' = a(a'-b') \implies c = a(a'-b') \implies a|c$.
3. Como $a|b, b = aq$ para algún $q \in \mathbb{Z}$. Ahora, $bk = aqk = a(qk) \implies a|bk$.
4. Como $ab|ac$, tenemos que $\exists q \in \mathbb{Z}$ tal que $abq = ac$. Por tanto, como $a \not = 0$, tenemos que $bq = c$, con lo que $b |c$.

---
### Referencias

[[Divisibilidad]]