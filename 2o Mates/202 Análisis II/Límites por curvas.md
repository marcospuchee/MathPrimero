### Contenido Principal

```ad-proposition
$f: \mathbb R^2 \to \mathbb R$, $a = (a_1, a_2)$. Sea $g: \mathbb R \to \mathbb R$ continua $g(a_1) = a_2$.
$$\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L \implies \lim_{x \to a_1} f(x,g(x)) = L.$$
```

^b8dbc4

```ad-proof
Tenemos que $\forall \varepsilon > 0$, $\exists \delta_1 > 0$ tal que $0 < ||(x,y) - (a_1, a_2)|| < \delta_1$, entonces $|f(x,y)-L| < \varepsilon$. Por la continuidad de $g$, dado $\delta_1 > 0$, $\exists 0 < \delta < \delta_1/2$ tal que si $|x-a_1| < \delta$, entonces $|g(x) - a_2| < \delta_1$.

Si $|x-a_1| < \delta$,
$$||(x, g(x)) - (a_1, a_2)|| \le |x-a_1| + |a_2 - g(x)| < \delta + \frac{\delta_1}{2} < \delta_1.$$
Si $0 < |x-a_1| < \delta$, entonces $0 < ||(x, g(x)) - (a_1, a_2)|| < \delta_1$, lo que implica que $|(f(x), g(x))-L| < \varepsilon$.
```

**Tema:** [[Funciones de varias variables#2. Dos variables.]]

---
### Anki

START
Básico
Anverso: Cómo se transforma el límite de dos variables a una?
Reverso: $f: \mathbb R^2 \to \mathbb R$, $a = (a_1, a_2)$. Sea $g: \mathbb R \to \mathbb R$ continua $g(a_1) = a_2$.
$$\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L \implies \lim_{x \to a_1} f(x,g(x)) = L.$$
<!--ID: 1727422026716-->
END

START
Básico
Anverso: Demostración de que sea $f: \mathbb R^2 \to \mathbb R$, $a = (a_1, a_2)$. Sea $g: \mathbb R \to \mathbb R$ continua $g(a_1) = a_2$.
$$\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L \implies \lim_{x \to a_1} f(x,g(x)) = L.$$
Reverso: Tenemos que $\forall \varepsilon > 0$, $\exists \delta_1 > 0$ tal que $0 < ||(x,y) - (a_1, a_2)|| < \delta_1$, entonces $|f(x,y)-L| < \varepsilon$. Por la continuidad de $g$, dado $\delta_1 > 0$, $\exists 0 < \delta < \delta_1/2$ tal que si $|x-a_1| < \delta$, entonces $|g(x) - a_2| < \delta_1$.

Si $|x-a_1| < \delta$,
$$||(x, g(x)) - (a_1, a_2)|| \le |x-a_1| + |a_2 - g(x)| < \delta + \frac{\delta_1}{2} < \delta_1.$$
Si $0 < |x-a_1| < \delta$, entonces $0 < ||(x, g(x)) - (a_1, a_2)|| < \delta_1$, lo que implica que $|(f(x), g(x))-L| < \varepsilon$.
Tags: den anII
<!--ID: 1727422026719-->
END
