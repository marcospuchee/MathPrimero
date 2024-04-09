
---
mathLinkat:
---
### Contenido Principal

**Fecha:** 2024-03-20, 21:33

```ad-theorem
Sean $a,b \in \mathbb R, a<b, f: [a,b] \to \mathbb R$ y $g: [a,b] \to \mathbb R$ continuas en $[a,b]$ ([[Función continua en un conjunto]]), derivables en $]a,b[$ ([[Función derivable en un punto]]) y de modo que $f(a) = g(a) = 0, g(x) \neq 0, \forall x \in ]a,b[$ y $f'$ y $g'$ no se anulan simultáneamente en $]a,b[$. Si $\exists \lim_{x \to a+} f'(x)/g'(x)$, entonces $\exists \lim_{x \to a+} f(x)/g(x)$ y
$$\lim_{x \to a+} \frac{f'(x)}{g'(x)} = \lim_{x \to a+} \frac{f(x)}{g(x)}.$$
```


```ad-proof
Observemos que la función $f'/g'$ se considera definida en los puntos donde $g'(x) \neq 0$. ¿Hay muchos puntos cumpliendo esta condición? Sí los hay. En efecto, sea $\delta, 0 < \delta < b-a$, según el [[Teorema del valor medio de Cauchy (1821)]], resulta
$$g'(\xi) f(a+\delta) = g'(\xi)(f(a + \delta) - f(a)) = f'(\xi)(g(a+\delta) - g(a)) = f'(\xi)g(a+\delta).$$
Como $g$ no se anula, si $g'(\xi) = 0$ esto implica que $f'(\xi) = 0$ lo que por hipótesis es falso. Tenemos pues que el punto $a$ es de acumulación del dominio $f'/g'$.

Supongamos pues que $\displaystyle \exists \lim_{x \to a+} \frac{f'(x)}{g'(x)} = L$. Escribamos el dominio de $f'/g'$ como $D := \{x \in ]a,b[: g'(x) \neq 0\}$. Fijemos $\varepsilon > 0$. Debe existir un $\delta, 0 < \delta < b-a$, tal que $\forall x \in ]a, a+ \delta] \cap D$ tengamos $\displaystyle \left | \frac{f'(x)}{g'(x)} - L \right | < \varepsilon$. Sea $x \in ]a, a+\delta]$, el [[Teorema del valor medio de Cauchy (1821)]] nos da un $\xi \in ]a, a+\delta[$ tal que
$$f'(\xi)g(x) = f'(\xi)(g(x) - g(a)) = g'(\xi)(f(x) - f(a)) = g'(\xi) f(x).$$
Si fuera $g'(\xi) = 0$, tendríamos $f'(\xi) = 0$, lo que es imposible, luego $\xi \in D \cap ]a, a+ \delta[$, la elección de $\delta$ nos da que
$$\left | \frac{f(x)}{g(x)} - L \right | = \left | \frac{f'(\xi)}{g'(\xi)} - L \right | < \varepsilon.$$
```


**Tema:** [[Funciones derivables#6. Reglas de L'Hôpital]]
**Demostrado por:** [[Teorema del valor medio de Cauchy (1821)]]
**Consecuencias:**

---
### Anki
