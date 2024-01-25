### Proposición

Si $p(x) \in \mathbb K [x]$ y $\delta(p) \ge 1$, entonces es producto de polinomios irreducibles ([[Polinomio irreducible]]) en $\mathbb K[x]$.

La expresión de $p(x)$ como producto de polinomios irreducibles se llama factorización, y depende del cuerpo en el que estemos considerando el polinomio.

---
### Demostración

Lo demostramos por inducción sobre el grado. Es decir, la propiedad que queremos demostrar para todo $m \in \mathbb N$ es: $P(m):$ si $f(x) \in \mathbb K [x]$ tiene grado $m$, entonces $f(x)$ es producto de polinomios irreducibles.
- Caso base ($m = 1$). Es cierto por [[Todo polinomio de grado 1 es irreducible]].
- Paso inductivo. Aplicamos inducción fuerte: suponemos que $P(m)$ es cierta para todo $1 \le m < n$ y queremos ver que la propiedad es cierta para $P(n)$. Sea $p(x)$ un polinomio de grado $n$. Queremos ver que $p(x)$ es producto de polinomios irreducibles. Entonces existen $q(x), r(x) \in K[x]$ con $\delta(q(x)), \delta(r(x)) >0$ tal que $p(x) = q(x)r(x)$. Como $n = \delta(p(x)) = \delta(q(x)) + \delta (r(x))$ ([[Proposición grado de un polinomio producto]]), necesariamente $\delta (q(x)), \delta(r(x)) < n$, y por tanto, $P(\delta(q(x)))$ y $P(\delta(r(x)))$ son ciertas. Por tanto, $q(x)$ y $r(x)$ son producto de polinomios irreducibles, con lo que $p(x) = q(x)r(x)$ es también producto de polinomios irreducibles, como queríamos demostrar.

---
### Referencias

[[Polinomio#1.2. Polinomios irreducibles. Factorización.]]

---
### Anki

START
Básico
Anverso: Cuál es la proposición que demuestra factorización de todo polinomio?
Reverso: Si $p(x) \in \mathbb K [x]$ y $\delta(p) \ge 1$, entonces es producto de polinomios irreducibles ([[Polinomio irreducible]]) en $\mathbb K[x]$.

La expresión de $p(x)$ como producto de polinomios irreducibles se llama factorización, y depende del cuerpo en el que estemos considerando el polinomio.
Tags: proposición/teorema
<!--ID: 1705824817198-->
END

START
Básico
Anverso: Demuestra que si $p(x) \in \mathbb K [x]$ y $\delta(p) \ge 1$, entonces es producto de polinomios irreducibles ([[Polinomio irreducible]]) en $\mathbb K[x]$.
Reverso: Lo demostramos por inducción sobre el grado. Es decir, la propiedad que queremos demostrar para todo $m \in \mathbb N$ es: $P(m):$ si $f(x) \in \mathbb K [x]$ tiene grado $m$, entonces $f(x)$ es producto de polinomios irreducibles.
- Caso base ($m = 1$). Es cierto por [[Todo polinomio de grado 1 es irreducible]].
- Paso inductivo. Aplicamos inducción fuerte: suponemos que $P(m)$ es cierta para todo $1 \le m < n$ y queremos ver que la propiedad es cierta para $P(n)$. Sea $p(x)$ un polinomio de grado $n$. Queremos ver que $p(x)$ es producto de polinomios irreducibles. Entonces existen $q(x), r(x) \in K[x]$ con $\delta(q(x)), \delta(r(x)) >0$ tal que $p(x) = q(x)r(x)$. Como $n = \delta(p(x)) = \delta(q(x)) + \delta (r(x))$ ([[Proposición grado de un polinomio producto]]), necesariamente $\delta (q(x)), \delta(r(x)) < n$, y por tanto, $P(\delta(q(x)))$ y $P(\delta(r(x)))$ son ciertas. Por tanto, $q(x)$ y $r(x)$ son producto de polinomios irreducibles, con lo que $p(x) = q(x)r(x)$ es también producto de polinomios irreducibles, como queríamos demostrar.
Tags: demostración
<!--ID: 1705824817201-->
END

