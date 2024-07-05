
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-13, 12:19

```ad-theorem
Sean $I$ un [[Intervalo]] abierto y $f: I \to \mathbb R$ derivable en $I$, las siguientes afirmaciones equivalen:
1. $f$ es [[Función convexa]] en $I$;
2. $\forall a \in I$, la gráfica de $f$ está por encima de su tangente en $(a,f(a))$, esto es:
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x \in I.$$
```


```ad-proof
$(i) \implies (ii).$
Sea $a,x \in I$, distinguiremos dos posibilidades:

$a<x.$
Sea $y$ un elemento arbitrario de $y \in ]a,x[$, según el [[Lema desigualdades de una función convexa]], tendremos que
$$\frac{f(y)-f(a)}{y-a} \le \frac{f(x)-f(a)}{x-a}.$$
Puesto que $f$ es [[Función derivable en un punto]] $a$, podemos tomar límites cuando $y \to a$ en la expresión anterior y obtener que
$$f'(a) \le \frac{f(x)-f(a)}{x-a}, \quad \forall x > a.$$
Por tanto,
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x > a.$$

$a>x.$
Como antes, sea $y \in ]x,a[$, según el [[Lema desigualdades de una función convexa]], tendremos que
$$\frac{f(a)-f(x)}{a-x} \le \frac{f(a)-f(y)}{a-y};$$
esto es,
$$\frac{f(x)-f(a)}{x-a} \le \frac{f(y) - f(a)}{y-a}.$$
Puesto que $f$ es derivable en $a$, podemos tomar límites cuando $y \to a$ en la expresión anterior y obtener que
$$\frac{f(x)-f(a)}{x-a} \le f'(a), \quad \forall x < a.$$
En este caso, $x-a < 0$, por tanto al multiplicar por este número las desigualdades cambian y obtenemos
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x < a.$$


$(ii) \implies (i).$
Por reducción al absurdo, supongamos que no es convexa, luego $\exists a,b,c \in I$ tales que $a<c<b$ y
$$\tag{*} f(c) > \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a).$$
Sea la función afín
$$h(x) := -f(a) - \frac{f(b)-f(a)}{b-a}(x-a), x \in \mathbb R.$$
Sea $g := f+h$, por cálculo directo, resulta que $g(a) = g(b) = 0$ y
$$
\begin{eqnarray}
g(c) &=& f(c) + h(c) >^{(*)} \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a) - f(a) - \frac{f(b)-f(a)}{b-a}(c-a) = \\
&=& \left ( \frac{b-c}{b-a} - 1 + \frac{c-a}{b-a} \right ) f(a) = 0 = g(a) = g(b).
\end{eqnarray}
$$
Según [[Existencia máximo y mínimo del conjunto de imagenes de una función con un valor]], tiene sentido considerar $a_0 := \max \{x \in [a,c]: g(x) = 0 \}$ y $b_0 := \min \{x \in [c,b]: g(x) = 0 \}$, tendremos $a_0 < c < b_0$ y $g(c) > g(a_0) = g(b_0) = 0$. El [[Teorema de Bolzano (1817)]] nos da que $g(x) > g(a_0) = g(b_0), \forall x \in ]a_0, b_0[$. Además, el [[Teorema de Rolle (1690)]] nos asegura que $\exists \xi \in ]a_0, b_0[$ tal que $g'(\xi) = 0$, con lo que la tangente en el punto $\xi$ es
$$g(\xi) + g'(\xi)(x - \xi) = g(\xi) > g(a_0) = g(b_0).$$
La implicación $(i) \implies (ii)$ que ya hemos probado, nos dice que $g$ no es convexa. Según [[Suma de función convexa y función afín es convexa]], la función $f = g-h$ tampoco puede ser convexa.
```


**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Demostrado por:** [[Lema desigualdades de una función convexa]], [[Teorema de Bolzano (1817)]], [[Teorema de Rolle (1690)]], [[Suma de función convexa y función afín es convexa]], [[Existencia máximo y mínimo del conjunto de imagenes de una función con un valor]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que nos dice que la función es convexa sii la gráfica de $f$ está por encima de su tangente?
Reverso: Sean $I$ un [[Intervalo]] abierto y $f: I \to \mathbb R$ derivable en $I$, las siguientes afirmaciones equivalen:
1. $f$ es [[Función convexa]] en $I$;
2. $\forall a \in I$, la gráfica de $f$ está por encima de su tangente en $(a,f(a))$, esto es:
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x \in I.$$
Tags: proposición/teorema análisisI
<!--ID: 1713093069903-->
END

START
Básico
Anverso: Demostración de que sean $I$ un [[Intervalo]] abierto y $f: I \to \mathbb R$ derivable en $I$, las siguientes afirmaciones equivalen:
1. $f$ es [[Función convexa]] en $I$;
2. $\forall a \in I$, la gráfica de $f$ está por encima de su tangente en $(a,f(a))$, esto es:
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x \in I.$$
Reverso: $(i) \implies (ii).$
Sea $a,x \in I$, distinguiremos dos posibilidades:

$a<x.$
Sea $y$ un elemento arbitrario de $y \in ]a,x[$, según el [[Lema desigualdades de una función convexa]], tendremos que
$$\frac{f(y)-f(a)}{y-a} \le \frac{f(x)-f(a)}{x-a}.$$
Puesto que $f$ es [[Función derivable en un punto]] $a$, podemos tomar límites cuando $y \to a$ en la expresión anterior y obtener que
$$f'(a) \le \frac{f(x)-f(a)}{x-a}, \quad \forall x > a.$$
Por tanto,
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x > a.$$

$a>x.$
Como antes, sea $y \in ]x,a[$, según el [[Lema desigualdades de una función convexa]], tendremos que
$$\frac{f(a)-f(x)}{a-x} \le \frac{f(a)-f(y)}{a-y};$$
esto es,
$$\frac{f(x)-f(a)}{x-a} \le \frac{f(y) - f(a)}{y-a}.$$
Puesto que $f$ es derivable en $a$, podemos tomar límites cuando $y \to a$ en la expresión anterior y obtener que
$$\frac{f(x)-f(a)}{x-a} \le f'(a), \quad \forall x < a.$$
En este caso, $x-a < 0$, por tanto al multiplicar por este número las desigualdades cambian y obtenemos
$$f(a) + f'(a)(x-a) \le f(x), \quad \forall x < a.$$


$(ii) \implies (i).$
Por reducción al absurdo, supongamos que no es convexa, luego $\exists a,b,c \in I$ tales que $a<c<b$ y
$$\tag{*} f(c) > \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a).$$
Sea la función afín
$$h(x) := -f(a) - \frac{f(b)-f(a)}{b-a}(x-a), x \in \mathbb R.$$
Sea $g := f+h$, por cálculo directo, resulta que $g(a) = g(b) = 0$ y
$$
\begin{eqnarray}
g(c) &=& f(c) + h(c) >^{(*)} \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a) - f(a) - \frac{f(b)-f(a)}{b-a}(c-a) = \\
&=& \left ( \frac{b-c}{b-a} - 1 + \frac{c-a}{b-a} \right ) f(a) = 0 = g(a) = g(b).
\end{eqnarray}
$$
Según [[Existencia máximo y mínimo del conjunto de imagenes de una función con un valor]], tiene sentido considerar $a_0 := \max \{x \in [a,c]: g(x) = 0 \}$ y $b_0 := \min \{x \in [c,b]: g(x) = 0 \}$, tendremos $a_0 < c < b_0$ y $g(c) > g(a_0) = g(b_0) = 0$. El [[Teorema de Bolzano (1817)]] nos da que $g(x) > g(a_0) = g(b_0), \forall x \in ]a_0, b_0[$. Además, el [[Teorema de Rolle (1690)]] nos asegura que $\exists \xi \in ]a_0, b_0[$ tal que $g'(\xi) = 0$, con lo que la tangente en el punto $\xi$ es
$$g(\xi) + g'(\xi)(x - \xi) = g(\xi) > g(a_0) = g(b_0).$$
La implicación $(i) \implies (ii)$ que ya hemos probado, nos dice que $g$ no es convexa. Según [[Suma de función convexa y función afín es convexa]], la función $f = g-h$ tampoco puede ser convexa.
Tags: demostración análisisI
<!--ID: 1713093069906-->
END

