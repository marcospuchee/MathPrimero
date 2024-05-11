
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 19:49

```ad-theorem
Sea $f \in R[a,b]$ [[integral de Riemann]] y definimos $F(x) = \int_a^x f(t) \, dt$ con $a < x \le b$ y $F(a) = 0$. Entonces:
1. $F: [a,b] \to \mathbb R$ es continua.
2. Si $f: [a,b] \to \mathbb R$ continua, entonces $\exists F'(x) = f(x), \quad \forall x \in ]a,b[$.

Luego $F$ es una [[función primitiva]] de $f$.
```


```ad-proof
$(i).$
Tomamos $a \le x < y \le b$. Tenemos:
$$F(y) - F(x) = \int_a^y f(t) \, dt - \int_a^x f(t) \, dt = \int_x^y f(t) \, dt.$$
Luego
$$|F(y) - F(x)| = \left | \int_x^y f(t) \, dt \right | \le \int_x^y |f(t)| \, dt.$$
Al ser $f$ acotada, $\exists M>0$ tal que $|f(t)| \le M, \quad \forall t \in [a,b]$. Por tanto, $|F(y) - F(x)| \le M|y-x|$, $\forall x, y \in [a,b]$.

Dado $\varepsilon > 0$, tomamos $\delta := \frac{\varepsilon}{M}$. Entonces $|x-y| < \implies$ $|F(x) - F(y)| < M \delta = \varepsilon$. Luego $F$ es [[función uniformemente continua]] en $[a,b]$.

$(ii).$
Sea $a<x<b$. Veamos que
$$\lim_{h \to 0^+} \frac{F(x+h) - F(x)}{h} = f(x).$$
Sea $0 < h < b-x$. Entonces
$$\frac{F(x+h) - F(x)}{h} = \frac{1}{h} \left ( \int_a^{x+h} f(t) \, dt - \int_a^x f(t) \, dt \right ) = \frac{1}{h} \int_x^{x+h} f(t) \, dt.$$
Además, $f(x) = 1/h \int_x^{x+h} f(x) \, dt$. Por tanto,
$$\begin{eqnarray}
\left | \frac{F(x+h) - F(x)}{h} - f(x) \right | &=& \left | \frac{1}{h} \int_x^{x+h} f(t) \, dt - \frac{1}{h} \int_x^{x+h} f(x) \, dt \right | \\ 
&=& \frac{1}{h} \left | \int_x^{x+h} (f(t) - f(x)) \, dt \right | \le \frac{1}{h} \int_x^{x+h} |f(t) - f(x)| \, dt.
\end{eqnarray}$$
Por ser continua en $x$, dado $\varepsilon > 0, \exists \delta > 0$ tal que si $|t-x| < \delta$, entonces $|f(t) - f(x)| < \varepsilon$. Tomamos $0 < h < \min \{\delta, b-x \}$. Tenemos:
$$x \le t \le x+h \implies |x-t| \le h < \delta \implies |f(t) - f(x)| < \varepsilon.$$
Así,
$$\left | \frac{F(x+h) - F(x)}{h} - f(x) \right | \le \frac{1}{h} \int_x^{x+h} |f(t) - f(x)| \, dt \le \frac{1}{h} \int_x^{x+h} \varepsilon \, dt = \varepsilon.$$
Esto quiere decir que
$$\lim_{h \to 0^+} \frac{F(x+h) - F(x)}{h} = f(x).$$
Si $h < 0$ entonces $x+h < x$, luego
$$F(x+h) - F(x) = \int_x^{x+h} f(t) \, dt - \int_a^x f(t) \, dt = - \int_{x+h}^x f(t) \, dt.$$
Luego $f(x) = - \frac{1}{h} \int_{x+h}^x f(x) \, dt$.
```

**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Definición alternativa de función primitiva
Reverso: Sea $f \in R[a,b]$ [[integral de Riemann]] y definimos $F(x) = \int_a^x f(t) \, dt$ con $a < x \le b$ y $F(a) = 0$. Entonces:
1. $F: [a,b] \to \mathbb R$ es continua.
2. Si $f: [a,b] \to \mathbb R$ continua, entonces $\exists F'(x) = f(x), \quad \forall x \in ]a,b[$.

Luego $F$ es una [[función primitiva]] de $f$.
Tags: proposición/teorema análisisI
<!--ID: 1714669443646-->
END

START
Básico
Anverso: Demostración de que sea $f \in R[a,b]$ [[integral de Riemann]] y definimos $F(x) = \int_a^x f(t) \, dt$ con $a < x \le b$ y $F(a) = 0$. Entonces:
1. $F: [a,b] \to \mathbb R$ es continua.
2. Si $f: [a,b] \to \mathbb R$ continua, entonces $\exists F'(x) = f(x), \quad \forall x \in ]a,b[$.

Luego $F$ es una [[función primitiva]] de $f$.
Reverso: $(i).$
Tomamos $a \le x < y \le b$. Tenemos:
$$F(y) - F(x) = \int_a^y f(t) \, dt - \int_a^x f(t) \, dt = \int_x^y f(t) \, dt.$$
Luego
$$|F(y) - F(x)| = \left | \int_x^y f(t) \, dt \right | \le \int_x^y |f(t)| \, dt.$$
Al ser $f$ acotada, $\exists M>0$ tal que $|f(t)| \le M, \quad \forall t \in [a,b]$. Por tanto, $|F(y) - F(x)| \le M|y-x|$, $\forall x, y \in [a,b]$.

Dado $\varepsilon > 0$, tomamos $\delta := \frac{\varepsilon}{M}$. Entonces $|x-y| < \implies$ $|F(x) - F(y)| < M \delta = \varepsilon$. Luego $F$ es [[función uniformemente continua]] en $[a,b]$.

$(ii).$
Sea $a<x<b$. Veamos que
$$\lim_{h \to 0^+} \frac{F(x+h) - F(x)}{h} = f(x).$$
Sea $0 < h < b-x$. Entonces
$$\frac{F(x+h) - F(x)}{h} = \frac{1}{h} \left ( \int_a^{x+h} f(t) \, dt - \int_a^x f(t) \, dt \right ) = \frac{1}{h} \int_x^{x+h} f(t) \, dt.$$
Además, $f(x) = 1/h \int_x^{x+h} f(x) \, dt$. Por tanto,
$$\begin{eqnarray}
\left | \frac{F(x+h) - F(x)}{h} - f(x) \right | &=& \left | \frac{1}{h} \int_x^{x+h} f(t) \, dt - \frac{1}{h} \int_x^{x+h} f(x) \, dt \right | \\ 
&=& \frac{1}{h} \left | \int_x^{x+h} (f(t) - f(x)) \, dt \right | \le \frac{1}{h} \int_x^{x+h} |f(t) - f(x)| \, dt.
\end{eqnarray}$$
Por ser continua en $x$, dado $\varepsilon > 0, \exists \delta > 0$ tal que si $|t-x| < \delta$, entonces $|f(t) - f(x)| < \varepsilon$. Tomamos $0 < h < \min \{\delta, b-x \}$. Tenemos:
$$x \le t \le x+h \implies |x-t| \le h < \delta \implies |f(t) - f(x)| < \varepsilon.$$
Así,
$$\left | \frac{F(x+h) - F(x)}{h} - f(x) \right | \le \frac{1}{h} \int_x^{x+h} |f(t) - f(x)| \, dt \le \frac{1}{h} \int_x^{x+h} \varepsilon \, dt = \varepsilon.$$
Esto quiere decir que
$$\lim_{h \to 0^+} \frac{F(x+h) - F(x)}{h} = f(x).$$
Si $h < 0$ entonces $x+h < x$, luego
$$F(x+h) - F(x) = \int_x^{x+h} f(t) \, dt - \int_a^x f(t) \, dt = - \int_{x+h}^x f(t) \, dt.$$
Luego $f(x) = - \frac{1}{h} \int_{x+h}^x f(x) \, dt$.
Tags: demostración análisisI
<!--ID: 1714669443651-->
END