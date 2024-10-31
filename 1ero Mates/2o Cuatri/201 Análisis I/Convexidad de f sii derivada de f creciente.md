
---
mathLink: $f$ es convexa $\iff f'$ es creciente en $I$
---
### Contenido Principal

**Fecha:** 2024-04-13, 11:41

```ad-theorem
Sea $I$ un [[Intervalo]] abierto no vacío y $f: I \to \mathbb R$ una función derivable en $I$, las siguientes afirmaciones equivalen:
1. $f$ es una [[Función convexa]].
2. $f'$ es creciente en $I$ ([[Función monótona]]) en $I$.
```

```ad-proof
$(i) \implies (ii).$
Sean $a,b \in I, a<b$. Tomemos $c \in I$ de modo que $a<c<b$. Gracias al [[Lema desigualdades de una función convexa]], tenemos que
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a} \le \frac{f(b)-f(c)}{b-c}.$$
En particular,
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a}.$$
Tomando límites en la expresión anterior cuando $c \to a$ resulta que
$$f'(a) \le \frac{f(b)-f(a)}{b-a}.$$
Un argumento similar nos da que
$$\frac{f(b)-f(a)}{b-a} \le f'(b).$$
Por tanto, $f'(a) \le f'(b).$

$(ii) \implies (i).$
Supongamos que $f$ no es convexa, por la nota del [[Lema desigualdades de una función convexa]], $\exists a_0, b_0, c_0$ que cumplen
$$f(\lambda b_0 + (1-\lambda)a_0) > \lambda f(b_0) + (1-\lambda)f(a_0)$$
y
$$\frac{f(c_0) - f(a_0)}{c_0 - a_0} > \frac{f(b_0) - f(a_0)}{b_0 - a_0} > \frac{f(b_0) - f(c_0)}{b_0 - c_0}.$$
Según el [[Teorema del valor medio de Cauchy (1821)]], $\exists \xi \in ]a_0, c_0[$ y $\zeta \in ]c_0, b_0[$ (por tanto $\xi < \zeta$) tales que
$$f'(\xi) = \frac{f(c_0)-f(a_0)}{c_0 - a_0}; \quad f'(\zeta) = \frac{f(b_0) - f(c_0)}{b_0 - c_0}.$$
Según el [[Lema desigualdades de una función convexa]], tenemos que $f'(\xi) > f'(\zeta)$, lo que muestra que $f'$ no es creciente.

```


**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Demostrado por:** [[Lema desigualdades de una función convexa]], [[Teorema del valor medio]]
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sea $I$ un [[Intervalo]] abierto no vacío y $f: I \to \mathbb R$ una función derivable en $I$, las siguientes afirmaciones equivalen:
1. {{c1::$f$ es una [[Función convexa]].}}
2. {{c2::$f'$ es creciente en $I$ ([[Función monótona]]) en $I$.}}
Tags: proposición/teorema análisisI
<!--ID: 1713093070123-->
END

START
Básico
Anverso: Demostración de que sea $I$ un [[Intervalo]] abierto no vacío y $f: I \to \mathbb R$ una función derivable en $I$, las siguientes afirmaciones equivalen:
1. $f$ es una [[Función convexa]].
2. $f'$ es creciente en $I$ ([[Función monótona]]) en $I$.
Reverso: $(i) \implies (ii).$
Sean $a,b \in I, a<b$. Tomemos $c \in I$ de modo que $a<c<b$. Gracias al [[Lema desigualdades de una función convexa]], tenemos que
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a} \le \frac{f(b)-f(c)}{b-c}.$$
En particular,
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a}.$$
Tomando límites en la expresión anterior cuando $c \to a$ resulta que
$$f'(a) \le \frac{f(b)-f(a)}{b-a}.$$
Un argumento similar nos da que
$$\frac{f(b)-f(a)}{b-a} \le f'(b).$$
Por tanto, $f'(a) \le f'(b).$

$(ii) \implies (i).$
Supongamos que $f$ no es convexa, por la nota del [[Lema desigualdades de una función convexa]], $\exists a_0, b_0, c_0$ que cumplen
$$f(\lambda b_0 + (1-\lambda)a_0) > \lambda f(b_0) + (1-\lambda)f(a_0)$$
y
$$\frac{f(c_0) - f(a_0)}{c_0 - a_0} > \frac{f(b_0) - f(a_0)}{b_0 - a_0} > \frac{f(b_0) - f(c_0)}{b_0 - c_0}.$$
Según el [[Teorema del valor medio]], $\exists \xi \in ]a_0, c_0[$ y $\zeta \in ]c_0, b_0[$ (por tanto $\xi < \zeta$) tales que
$$f'(\xi) = \frac{f(c_0)-f(a_0)}{c_0 - a_0}; \quad f'(\zeta) = \frac{f(b_0) - f(c_0)}{b_0 - c_0}.$$
Según el [[Lema desigualdades de una función convexa]], tenemos que $f'(\xi) > f'(\zeta)$, lo que muestra que $f'$ no es creciente.

Tags: demostración análisisI
<!--ID: 1713093070131-->
END

