
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 19:02

```ad-theorem
Sea $f \in R[a,b]$. Entonces $|f| \in R[a,b]$ y
$$ \left | \int_a^b f(x) \, dx \right | \le \int_a^b |f(x)| \, dx.$$
```


```ad-proof
Sea $\varepsilon > 0$, entonces $\exists P \in P[a,b]$ tal que $U(f, P) - L(f, P) < \varepsilon$. Por [[Lema supremo menos ínfimo de una función y relación de orden con valor absoluto de función]]:
$$U(|f|, P) - L(|f|, P) \le U(f, P) - L(f, P) < \varepsilon.$$
Esto implica que $|f| \in R[a,b]$.

Dado que se cumple que $-|f(x)| \le f(x) \le |f(x)|, \forall x \in [a,b]$. Luego tenemos:
$$- \int_a^b |f(x)| \, dx \le \int_a^b f(x) \, dx \le \int_a^b |f(x)| \, dx \implies \left|\int_a^b f(x) \, dx \right | \le \int_a^b |f(x)| \, dx.$$ 

```


**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sea $f \in R[a,b]$. Entonces {{c1::$|f| \in R[a,b]$}} y
{{c2::$$ \left | \int_a^b f(x) \, dx \right | \le \int_a^b |f(x)| \, dx.$$}}
Tags: proposición/teorema análisisI
<!--ID: 1714669443660-->
END

START
Básico
Anverso: Demostración de que sea $f \in R[a,b]$. Entonces $|f| \in R[a,b]$ y
$$ \left | \int_a^b f(x) \, dx \right | \le \int_a^b |f(x)| \, dx.$$
Reverso: Sea $\varepsilon > 0$, entonces $\exists P \in P[a,b]$ tal que $U(f, P) - L(f, P) < \varepsilon$. Por [[Lema supremo menos ínfimo de una función y relación de orden con valor absoluto de función]]:
$$U(|f|, P) - L(|f|, P) \le U(f, P) - L(f, P) < \varepsilon.$$
Esto implica que $|f| \in R[a,b]$.

Dado que se cumple que $-|f(x)| \le f(x) \le |f(x)|, \forall x \in [a,b]$. Luego tenemos:
$$- \int_a^b |f(x)| \, dx \le \int_a^b f(x) \, dx \le \int_a^b |f(x)| \, dx \implies \left|\int_a^b f(x) \, dx \right | \le \int_a^b |f(x)| \, dx.$$ 

Tags: demostración análisisI
<!--ID: 1714669443668-->
END

