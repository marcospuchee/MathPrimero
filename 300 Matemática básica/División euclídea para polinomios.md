### Proposición

Sean $p(x), s(x) \in K[x]$ con $s(x) \not = 0$. Entonces existen polinomios $q(x), r(x) \in K[x]$ que cumplen 
$$p(x) = s(x) q(x) + r(x)$$
y $r(x) = 0$ o $\delta(r(x)) < \delta(s(x))$. Además, $q(x), r(x)$ son los únicos que cumplen esto. A $q(x)$ le llamamos cociente y a $r(x)$ residuo.

---
### Demostración

### Existencia
Vamos a demostrarlo por inducción ([[Principio de inducción fuerte]]) sobre el grado de $p(x)$.

**Caso base**: si $p(x)$ tiene grado 0, es decir, si $p(x) = a \in K$. Si $s(x)$ tiene grado 0, entonces $s(x) = s \in K - \{0\}$ y tomamos $q(x) = as^{-1}$ y $r(x) = 0$, con lo que 
$$p(x) = a = q(x)s(x) + r(x) = as^{-1}s + 0 = a$$
Si $s(x)$ tiene grado $\delta(s(x)) > 0$, entonces tomamos $q(x) = 0$ y $r(x) = a$, con lo que $\delta(r(x)) = 0 < \delta(s(x))$ y
$$p(x) = a = q(x)s(x) + r(x) = 0 s(x) + a = a$$

**Paso inductivo**: supongamos ahora que el resultado es cierto para polinomios de grado menor que el grado de $p(x)$. Sea $p(x) = a_0 + a_1x + \dots + a_n x^n$ y sea $s(x) = b_0 + b_1 + \dots + b_k x^k$, con $a_n, b_k \not = 0$. Distinguimos dos casos:

- Caso $n \ge k$. Definimos $f(x) = a_n b_k^{-1}x^{n-k}$ , entonces
$$p(x) - f(x)s(x) = a_0 + a_1 + \dots + a_{n-1}x^{n-1} + a_n x^n - a_nb_k^{-1} x^{n-k}b_0 - \dots - a_nb_k^{-1}x^{n-k}b_k x^k$$
esto es igual a
$$a_0 + a_1x + \dots + a_{n-1}x^{n-1} - a_n b_k^{-1} x^{n-k} b_0 - \dots - b_{k-1}a_n b_k^{-1}x^{n-1}$$
Sea $g(x) = p(x) -f(x)s(x)$, con lo que $\delta(g(x)) < \delta(p(x))$. Por hipótesis de inducción, el resultado es cierto para $g(x)$, con lo que existen $q'(x), r'(x)$ polinomios en $K[x]$ tales que
$$g(x) = q'(x)s(x) + r'(x)$$
y $r'(x) = 0$ o $\delta(r'(x)) < \delta(s(x))$. Ahora:
$$p(x) = g(x) +f(x)s(x) = q'(x)s(x) + r'(x) + f(x)s(x) = (q'(x) + f(x))s(x) + r'(x)$$ donde $q'(x)+f(x)$ es $q(x)$, y el resultado queda probado para $p(x)$.

- Caso $n < k$. En este caso tomamos $q(x) = 0$ y $r(x) = p(x)$, con lo que $p(x) = q(x)s(x) + r(x)$ y $\delta(r(x)) = n < k = \delta(s(x))$, y queda demostrado.

### Unicidad
Supongamos que existen $q'(x), r'(x)$ tales que $p(x) = q(x)s(x) + r(x) = q'(x)s(x) + r'(x)$ con $r'(x) = 0$ o $\delta(r'(x)) < \delta(s(x))$. Entonces tenemos que $r(x) - r'(x) = s(x)(q'(x) - q(x))$.
Si $q(x) -q'(x) \not = 0$, tenemos que $\delta(s(x)(q'(x) - q(x))) \ge \delta(s(x))$, y por otra parte, $\delta(r(x) - r'(x)) < \delta(s(x))$. Esto es una contradicción. Concluimos que $q(x) = q'(x)$ y por tanto $r(x) = r'(x)$.

---
### Referencias

[[Polinomio#1.1 Divisibilidad de polinomios]]
[[Teorema de la división euclídea]]