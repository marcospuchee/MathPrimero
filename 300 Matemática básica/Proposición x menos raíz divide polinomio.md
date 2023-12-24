### Proposición

Sea $p(x) \in K[x]$, y sea $a \in K$ una raíz ([[Notación polinomios]]) de $p(x)$. Entonces $x-a$ divide a $p(x)$ en $K[x]$.

---
### Demostración

Hacemos la [[División euclídea para polinomios]] de $p(x)$ por $s(x) = x-a$, y tenemos $q(x), r(x) \in K[x]$ tales que
$$p(x) = (x-a)q(x)+r(x)$$
con $r(x) = 0$ o $\delta(r(x)) < \delta(x -a) = 1$. Si $r(x)  = 0$, entonces $x-a$ divide a $p(x)$ ([[Polinomio divisor]]) como queríamos. Por tanto, podemos suponer que $\delta(r(x)) < 1$, con lo que $\delta(r(x)) = 0$ y $r(x) = r \in K$. Ahora bien, $a$ es raíz de $p(x)$, por tanto
$$0 = p(a) = (a-a)q(a) + r(a) = 0 + r \implies r = 0$$
y por tanto, $x-a$ divide a $p(x)$.

---
### Referencias

[[Polinomio#1.1 Divisibilidad de polinomios]]