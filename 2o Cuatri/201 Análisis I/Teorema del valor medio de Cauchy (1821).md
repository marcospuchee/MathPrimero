
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-29, 18:57

Sean $f$ y $g$ funciones reales.

```ad-theorem
Si $f$ y $g$ son continuas en $[a,b]$ ([[Función continua en un conjunto]]), y derivables en $]a,b[$ ([[Función derivable en un punto]]), entonces $\exists \xi \in ]a,b[$ tal que
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
En particular, para cualquier función real $f$, continua en $[a,b]$, derivable en $]a,b[$, $\exists \xi \in ]a,b[$ en el cual
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
```


```ad-proof
La igualdad
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi)$$
es consecuencia directa de aplicar el [[Teorema de Rolle (1690)]] a $h(x) = (f(b) - f(a))g(x) - (g(b) - g(a))f(x).$

Para
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
basta hacer $g(x) := x, x \in [a,b]$ en
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
```

**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:** [[Teorema de Rolle (1690)]]
**Consecuencias:** [[Teorema fundamental del cálculo diferencial]], [[Función derivable en el interior de un intervalo monótona]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema del valor medio de Cauchy (1821)?
Reverso: Sean $f$ y $g$ funciones reales. Si $f$ y $g$ son continuas en $[a,b]$ ([[Función continua en un conjunto]]), y derivables en $]a,b[$ ([[Función derivable en un punto]]), entonces $\exists \xi \in ]a,b[$ tal que
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
En particular, para cualquier función real $f$, continua en $[a,b]$, derivable en $]a,b[$, $\exists \xi \in ]a,b[$ en el cual
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
Tags: proposición/teorema análisisI
<!--ID: 1709231331157-->
END

START
Básico
Anverso: Demostración de que sean $f$ y $g$ funciones reales. Si $f$ y $g$ son continuas en $[a,b]$ ([[Función continua en un conjunto]]), y derivables en $]a,b[$ ([[Función derivable en un punto]]), entonces $\exists \xi \in ]a,b[$ tal que
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
En particular, para cualquier función real $f$, continua en $[a,b]$, derivable en $]a,b[$, $\exists \xi \in ]a,b[$ en el cual
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
(TEOREMA DEL VALOR MEDIO DE CAUCHY (1821))
Reverso: La igualdad
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi)$$
es consecuencia directa de aplicar el [[Teorema de Rolle (1690)]] a $h(x) = (f(b) - f(a))g(x) - (g(b) - g(a))f(x).$

Para
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
basta hacer $g(x) := x, x \in [a,b]$ en
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
Tags: demostración análisisI
<!--ID: 1709231331166-->
END