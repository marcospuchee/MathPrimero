
---
mathLink:$\exists \lim_{x \to a} \frac{f(x) - P_n(x)}{(x-a)^{n+1}} = \frac{f^{(n+1)}(a)}{(n+1)!}$
---
### Contenido Principal

**Fecha:** 2024-03-27, 14:26

```ad-proposition
Sea $f$ una función definida en el intervalo abierto $I$ y $a \in I$. Supondremos que $f$ es $n+1$ veces derivable en $I$ y que $f^{(n+1)}$ es continua en $a$ ([[Función continua en un punto]]). Si $P_n$ es el [[Polinomio de Taylor]] de $f$, de orden $n$, centrado en $a$, entonces
$$\exists \lim_{x \to a} \frac{f(x) - P_n(x)}{(x-a)^{n+1}} = \frac{f^{(n+1)}(a)}{(n+1)!}.$$
```


```ad-proof
Dado un $\varepsilon > 0$, la continuidad de $f^{(n+1)}$ en $a$ nos asegura la existencia de un $\delta > 0$ tal que
$$x \in I, |x-a| < \delta \implies |f^{(n+1)}(x) - f^{(n+1)}(a)| < \varepsilon.$$
Según la fórmula del [[Teorema de Lagrange (1797)]], si $x \in I$ y $0 < |x-a| < \delta$ ha de existir un $\xi \in I$, tal que $\xi \in ]x, a[$ (o si $x > a$, $\xi \in ]a,x[$) tal que
$$\left | \frac{f(x) - P_n(x)}{(x-a)^{n+1}} - \frac{f^{(n+1)}(a)}{(n+1)!} \right | = \frac{1}{(n+1)!} |f^{(n+1)}(\xi) - f^{(n+1)}(a)|.$$
Como $\xi \in ]x,a[$ (resp. $]a,x[$), y $|x-a| < \delta$, resulta que $| \xi - a| < \delta$, por tanto, de la continuidad de $f^{(n+1)}$, deducimos que si $x \in I$ y $0 < |x-a| < \delta$, entonces
$$\left | \frac{f(x)- P_n(x)}{(x-a)^{n+1}} - \frac{f^{(n+1)}(a)}{(n+1)!} \right | = \frac{1}{(n+1)!} | f^{(n+1)}(\xi) - f^{(n+1)}(a)| < \frac{\varepsilon}{(n+1)!} < \varepsilon.$$
```

**Tema:** [[Funciones derivables#7. El polinomio de Taylor]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $f$ una función definida en el intervalo abierto $I$ y $a \in I$. Supondremos que $f$ es $n+1$ veces derivable en $I$ y que $f^{(n+1)}$ es continua en $a$ ([[Función continua en un punto]]). Si $P_n$ es el [[Polinomio de Taylor]] de $f$, de orden $n$, centrado en $a$, entonces
$${{c1::\exists \lim_{x \to a} \frac{f(x) - P_n(x)}{(x-a)^{n+1}}}} = {{c2::\frac{f^{(n+1)}(a)}{(n+1)!}.}}$$
Tags: proposición/teorema análisisI
<!--ID: 1713093069926-->
END

START
Básico
Anverso: Demostración de que sea $f$ una función definida en el intervalo abierto $I$ y $a \in I$. Supondremos que $f$ es $n+1$ veces derivable en $I$ y que $f^{(n+1)}$ es continua en $a$ ([[Función continua en un punto]]). Si $P_n$ es el [[Polinomio de Taylor]] de $f$, de orden $n$, centrado en $a$, entonces
$$\exists \lim_{x \to a} \frac{f(x) - P_n(x)}{(x-a)^{n+1}} = \frac{f^{(n+1)}(a)}{(n+1)!}.$$ 
Reverso: Dado un $\varepsilon > 0$, la continuidad de $f^{(n+1)}$ en $a$ nos asegura la existencia de un $\delta > 0$ tal que
$$x \in I, |x-a| < \delta \implies |f^{(n+1)}(x) - f^{(n+1)}(a)| < \varepsilon.$$
Según la fórmula del [[Teorema de Lagrange (1797)]], si $x \in I$ y $0 < |x-a| < \delta$ ha de existir un $\xi \in I$, tal que $\xi \in ]x, a[$ (o si $x > a$, $\xi \in ]a,x[$) tal que
$$\left | \frac{f(x) - P_n(x)}{(x-a)^{n+1}} - \frac{f^{(n+1)}(a)}{(n+1)!} \right | = \frac{1}{(n+1)!} |f^{(n+1)}(\xi) - f^{(n+1)}(a)|.$$
Como $\xi \in ]x,a[$ (resp. $]a,x[$), y $|x-a| < \delta$, resulta que $| \xi - a| < \delta$, por tanto, de la continuidad de $f^{(n+1)}$, deducimos que si $x \in I$ y $0 < |x-a| < \delta$, entonces
$$\left | \frac{f(x)- P_n(x)}{(x-a)^{n+1}} - \frac{f^{(n+1)}(a)}{(n+1)!} \right | = \frac{1}{(n+1)!} | f^{(n+1)}(\xi) - f^{(n+1)}(a)| < \frac{\varepsilon}{(n+1)!} < \varepsilon.$$
Tags: demostración análisisI
<!--ID: 1713093069932-->
END
