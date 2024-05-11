
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-26, 10:55

Sean $I \subset \mathbb R$ un [[Intervalo]] no vacío, y $f : I \to \mathbb R$ una función continua en $I$ ([[Función continua en un conjunto]])
> [!theorem]
> Si $a,b \in I, a < b$ y verifican que $f(a) < \xi < f(b)$ (respectivamente $f(b) < \xi < f(a)$) entonces $\exists c \in [a,b]$ tal que $f(c) = \xi$.
>
> Esto es equivalente a: $f(I)$ es un [[Intervalo]].

> [!proof]
> Es suficiente probar el caso donde $f(a) < \xi < f(b)$. Comenzaremos probando el caso particular en que $\xi = 0$, es decir
> $$f(a) < 0 < f(b) \implies \exists c \in [a,b] \textrm{ con } f(c) = 0$$
> En efecto, el conjunto $\{x \in [a,b] : f(x) < 0\}$ es no vacío y acotado superiormente por $b$, por tanto, tiene sentido considerar
> $$ c := sup\{x \in [a,b] : f(x) < 0 \}$$
> Tenemos $a \le c \le b$. Ahora distinguimos dos posibilidades:
> 
> **Caso 1.**$f(c) < 0$
> Tendremos $c < b$. De acuerdo con [[Función continua en un punto que es punto de acumulación]] , $\lim_{x \to c} f(x) < 0$. Entonces por [[Lema valor del límite en un punto a]] (en este caso, el respectivo caso en que $l<0$; ver más en la nota), $\exists \delta > 0$ tal que $f(x) < 0, \forall x \in [a,b]\cap ]c-\delta, c+\delta[ \text{\\} \{c\}$, sin pérdida de generalidad, podemos suponer que $\delta < b-c$. Sea $d \in ]c, c+\delta[\subset]c,b[$, tendremos $f(d) < 0$ y $c < d$, lo que contradice la elección de $c$.
>
> **Caso 2.** $f(c) > 0$
> Tendremos $c > a$. De acuerdo con [[Función continua en un punto que es punto de acumulación]], $\lim_{x \to c} f(x) > 0$, entonces, [[Lema valor del límite en un punto a]] nos asegura que $\exists \delta > 0$ tal que $f(x) > 0$,$\forall x \in [a,b] \cap ]c - \delta, c + \delta[$, sin pérdida de generalidad podemos suponer que $\delta < c-a$. Tendremos que $f(x) > 0$ si $x \in ]c-\delta, c[ \subset ]a, c[$, por tanto $f(x) > 0$ si $x \in ]c-\delta, b]$, lo que contradice la elección de $c$.
>
>Para demostrar el caso general, basta aplicar el resultado que acabamos de probar a la función $g := f - \xi$.


**Tema:** [[Funciones continuas#2. Funciones continuas en ciertos conjuntos]]
**Demostrado por:** [[Lema valor del límite en un punto a]], [[Función continua en un punto que es punto de acumulación]]
**Consecuencias:** Como consecuencia del teorema de Bolzano, es fácil deducir, por ejemplo, que existe un número real $x \in \mathbb R$ tal que $x^2 = 2$. [[Teorema función es convexa sii la gráfica de f está por encima de su tangente]]

---
### Anki

START
Básico
Anverso: Qué dice el Teorema de Bolzano (1817)?
Reverso: Sean $I \subset \mathbb R$ un [[Intervalo]] no vacío, y $f : I \to \mathbb R$ una función continua en $I$ ([[Función continua en un conjunto]])
> Si $a,b \in I, a < b$ y verifican que $f(a) < \xi < f(b)$ (respectivamente $f(b) < \xi < f(a)$) entonces $\exists c \in [a,b]$ tal que $f(c) = \xi$.
>
> Esto es equivalente a: $f(I)$ es un [[Intervalo]].

Tags: proposición/teorema
<!--ID: 1706298589357-->
END

START
Básico
Anverso: Demostración del Teorema de Bolzano (1817)?
Reverso:  Es suficiente probar el caso donde $f(a) < \xi < f(b)$. Comenzaremos probando el caso particular en que $\xi = 0$, es decir
 $$f(a) < 0 < f(b) \implies \exists c \in [a,b] \textrm{ con } f(c) = 0$$
 En efecto, el conjunto $\{x \in [a,b] : f(x) < 0\}$ es no vacío y acotado superiormente por $b$, por tanto, tiene sentido considerar
 $$ c := sup\{x \in [a,b] : f(x) < 0 \}$$
Tenemos $a \le c \le b$. Ahora distinguimos dos posibilidades:

**Caso 1.**$f(c) < 0$
Tendremos $c < b$. De acuerdo con [[Función continua en un punto que es punto de acumulación]] , $\lim_{x \to c} f(x) < 0$. Entonces por [[Lema valor del límite en un punto a]] (en este caso, el respectivo caso en que $l<0$; ver más en la nota), $\exists \delta > 0$ tal que $f(x) < 0, \forall x \in [a,b]\cap ]c-\delta, c+\delta[ \text{\\} \{c\}$, sin pérdida de generalidad, podemos suponer que $\delta < b-c$. Sea $d \in ]c, c+\delta[\subset]c,b[$, tendremos $f(d) < 0$ y $c < d$, lo que contradice la elección de $c$.

**Caso 2.** $f(c) > 0$
Tendremos $c > a$. De acuerdo con [[Función continua en un punto que es punto de acumulación]], $\lim_{x \to c} f(x) > 0$, entonces, [[Lema valor del límite en un punto a]] nos asegura que $\exists \delta > 0$ tal que $f(x) > 0$,$\forall x \in [a,b] \cap ]c - \delta, c + \delta[$, sin pérdida de generalidad podemos suponer que $\delta < c-a$. Tendremos que $f(x) > 0$ si $x \in ]c-\delta, c[ \subset ]a, c[$, por tanto $f(x) > 0$ si $x \in ]c-\delta, b]$, lo que contradice la elección de $c$.

Para demostrar el caso general, basta aplicar el resultado que acabamos de probar a la función $g := f - \xi$.

Tags: demostración
<!--ID: 1706298589361-->
END