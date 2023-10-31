	### Enunciado Teorema

Sean $a,b \in \mathbb{Z}$ con $a \not = 0$ o $b \not = 0$. Entonces, $\Omega = \{ax + by \in \mathbb{N}: x,y \in \mathbb{Z}\}$. Sea $d = min\Omega$, entonces $d$ verifica:
1. $d > 0$
2. $d | a$ y $d|b$
3. Si $d'|a$ y $d'|b$ entonces $d'|d$.
4. Si $c = ax + by, x, y \in \mathbb{Z}$, entonces $d |c$.

---
### Demostración

Para demostrar que $\Omega \not = \emptyset$, sean $x = a, y = b$, entonces $ax + by = a^2 + b^2 \in \mathbb{N} \implies a^2 + b^2 \in \Omega \implies \Omega \not = \emptyset$. Sea $d = min\Omega$ (por [[Ley de buena ordenación]]), entonces:
1.  $d \in \Omega \subseteq \mathbb{N} \implies d > 0$.
2. Veamos que $d|a$. Consideramos la división euclídea ([[Teorema de la división euclídea]]) de $a$ por $d$, $\exists q, r$ con $0\le r < d$, tal que $a = dq + r$. Como $d \in \Omega \implies d = ax + by$ para ciertos $x,y \in \mathbb{Z}$. $0 \le r = a - dq = a - (ax + by)q = a(1-xq) +byq \in \Omega$. Si $r > 0, r \in \Omega$. Lo cual es una contradicción porque $r < d$ y $d = min \Omega$, por lo que $r \not \in \Omega$. Así, $r = 0$.
3. Sea $d' \in \mathbb{Z}$ tal que $d'|b$, $\exists q, q' \in \mathbb{Z}$ tal que $d'q = a$ y $d'q' = b$. Entonces, $d = ax + by = d'qx + d'q'y = d'(qx+q'y) \in \mathbb{Z}$, por lo que $d'|d$.
4. Sea $c = ax' + by', x', y' \in \mathbb{Z}$, $d = ax + by, c = ax' + by'$. Por (2), $d | a$ ($\exists a' \in \mathbb{Z}$ tal que $da' = a$) y $d|b$ ($\exists b' \in \mathbb{Z}$ tal que $db' = b$). $c = ax' + by' = da'x' +db'y' = d(a'x' + b'y') \implies d | c$.

---
### Referencias

[[Divisibilidad]]
[[Identidad de Bezout]]

24-10-23. Básica