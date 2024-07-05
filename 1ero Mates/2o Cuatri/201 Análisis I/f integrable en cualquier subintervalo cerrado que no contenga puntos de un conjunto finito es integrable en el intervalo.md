
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 18:22

```ad-theorem
Sea $f: [a,b] \to \mathbb R$ acotada. $A \subset [a,b]$ finito. Suponemos $f$ integrable ([[integral de Riemann]]) en cualquier subintervalo cerrado que no contenga puntos de $A$. Entonces $f \in R[a,b]$.
```

```ad-proof
$A \subset \{a,b\}$.
Sea $K < 0$ tal que $-K \le f(x) \le K, \forall x \in [a,b]$ ($f$ acotada). Fijamos $\varepsilon > 0$, seleccionamos $a<c<d<b$ tal que $c-a < \varepsilon/6K$ y $b-d < \varepsilon/6K$. Como $f \in R[c,d]$, $\exists Q \in P[c,d]$ ([[partición de un intervalo]]) tal que $U(f, Q) - L(f, Q) < \varepsilon/3$. Tomamos $P = Q \cup \{a,b\} \in P[a,b]$, tenemos que
$$U(f, P) - L(f, P) = U(f, Q) - L(f, Q).$$
Además,
$$U(f, P) - L(f, P) \le U(f, Q) - L(f, Q) + 2K(c-a) + 2K(b-d) < \varepsilon/3 + 2K \varepsilon /6K + 2K \varepsilon /6K = \varepsilon.$$
Esto implica que $U(f, P) - L(f, P) < \varepsilon$. Luego $f \in R[a,b]$.

**Caso general.**
Tenemos que $A = \{ \delta_1, \delta_2, \dots, \delta_p \}$. Tenemos los intervalos $[a, \delta_1], [\delta_1, \delta_2], \dots, [\delta_p, b]$. Por el anterior caso, es integrable en cada subintervalo ya que los extremos pertenecen a $A$, y por el teorema [[Integral dividida en dos intervalos]], $f \in R[a,b]$.
```


**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:**
**Consecuencias:** [[f continua (o monótona) excepto en un conjunto finito de puntos, entonces f es integrable]]

---
### Anki

START
Respuesta anidada
Sea $f: [a,b] \to \mathbb R$ acotada. $A \subset [a,b]$ finito. Suponemos $f$ integrable ([[Integral de Riemann]]) {{c1::en cualquier subintervalo cerrado que no contenga puntos de $A$}}. Entonces {{c2::$f \in R[a,b]$.}}
Tags: proposición/teorema análisisI
<!--ID: 1714669443802-->
END

START
Básico
Anverso: Demostración de que sea $f: [a,b] \to \mathbb R$ acotada. $A \subset [a,b]$ finito. Suponemos $f$ integrable ([[Integral de Riemann]]) en cualquier subintervalo cerrado que no contenga puntos de $A$. Entonces $f \in R[a,b]$.
Reverso: $A \subset \{a,b\}$.
Sea $K < 0$ tal que $-K \le f(x) \le K, \forall x \in [a,b]$ ($f$ acotada). Fijamos $\varepsilon > 0$, seleccionamos $a<c<d<b$ tal que $c-a < \varepsilon/6K$ y $b-d < \varepsilon/6K$. Como $f \in R[c,d]$, $\exists Q \in P[c,d]$ ([[Partición de un intervalo]]) tal que $U(f, Q) - L(f, Q) < \varepsilon/3$. Tomamos $P = Q \cup \{a,b\} \in P[a,b]$, tenemos que
$$U(f, P) - L(f, P) = U(f, Q) - L(f, Q).$$
Además,
$$U(f, P) - L(f, P) \le U(f, Q) - L(f, Q) + 2K(c-a) + 2K(b-a) < \varepsilon/3 + 2K \varepsilon /6K + 2K \varepsilon /6K = \varepsilon.$$
Esto implica que $U(f, P) - L(f, P) < \varepsilon$. Luego $f \in R[a,b]$.

**Caso general.**
Tenemos que $A = \{ \delta_1, \delta_2, \dots, \delta_p \}$. Tenemos los intervalos $[a, \delta_1], [\delta_1, \delta_2], \dots, [\delta_p, b]$. Por el anterior caso, es integrable en cada subintervalo ya que los extremos pertenecen a $A$, y por el teorema [[Integral dividida en dos intervalos]], $f \in R[a,b]$.
Tags demostración análisisI
<!--ID: 1714669443806-->
END

