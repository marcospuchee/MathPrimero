### Contenido Principal

```ad-proposition
Sea $f: A \subseteq \mathbb R^2 \to \mathbb R$ y $a = (a_1, a_2) \in A$ tales que $\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L$. Supongamos que l os límites $\lim_{y \to a_2} f(x,y)$ y $\lim_{x \to a_1} f(x,y)$ existen, entonces
$$\lim_{x \to a_1} \left ( \lim_{y \to a_2} f(x,y) \right ) = \lim_{y \to a_2} \left ( \lim_{x \to a_1} f(x,y) \right ) = L,$$
donde llamamos $f_1(x) := \lim_{y \to a_2} f(x,y)$, y $f_2(x) := \lim_{x \to a_1} f(x,y)$.
```

^8c0226

```ad-proof
Veamos que $\lim_{x \to a_1} f_1 (x) = L$. 

Fijamos $\varepsilon > 0$, usando que $\lim_{(x,y) \to (0,0)} f(x,y) = L$, tenemos que $\exists r>0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < r$, entonces $|f(x,y) - L| < \varepsilon/2$. Fijamos $0 < |x-a_1| < r/\sqrt{2}$, como $f_1(x) = \lim_{y \to a_2} f(x,y)$, entonces $\exists \delta_x  0$, y podemos suponer que $\delta_x < r/\sqrt{2}$, tal que $0 < |y-a_2| < \delta_x$. Por lo que tenemos que $|f_1(x) - f(x,y)| < \varepsilon / 2$.

Para $0 < |x-a_1| < r/\sqrt{2}$, y tomo $y$ tal que $0 < |y-a_2| < \delta_x$, entonces $||(x,y) - (a_1, a_2)|| < r$. Por tanto,
$$|f_1(x) - L| \le |f_1(x) - f(x,y) + |f(x,y) - L| < \varepsilon.$$
```

**Tema:** [[Funciones de varias variables#2. Dos variables.]]

---
### Anki

START
Básico
Anverso: Proposición límites iterados
Reverso: Sea $f: A \subseteq \mathbb R^2 \to \mathbb R$ y $a = (a_1, a_2) \in A$ tales que $\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L$. Supongamos que l os límites $\lim_{y \to a_2} f(x,y)$ y $\lim_{x \to a_1} f(x,y)$ existen, entonces
$$\lim_{x \to a_1} \left ( \lim_{y \to a_2} f(x,y) \right ) = \lim_{y \to a_2} \left ( \lim_{x \to a_1} f(x,y) \right ) = L,$$
donde llamamos $f_1(x) := \lim_{y \to a_2} f(x,y)$, y $f_2(x) := \lim_{x \to a_1} f(x,y)$.
<!--ID: 1727966478813-->
END

START
Básico
Anverso: Demostración de que sea $f: A \subseteq \mathbb R^2 \to \mathbb R$ y $a = (a_1, a_2) \in A$ tales que $\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L$. Supongamos que l os límites $\lim_{y \to a_2} f(x,y)$ y $\lim_{x \to a_1} f(x,y)$ existen, entonces
$$\lim_{x \to a_1} \left ( \lim_{y \to a_2} f(x,y) \right ) = \lim_{y \to a_2} \left ( \lim_{x \to a_1} f(x,y) \right ) = L,$$
donde llamamos $f_1(x) := \lim_{y \to a_2} f(x,y)$, y $f_2(x) := \lim_{x \to a_1} f(x,y)$.
Reverso: Veamos que $\lim_{x \to a_1} f_1 (x) = L$. 

Fijamos $\varepsilon > 0$, usando que $\lim_{(x,y) \to (0,0)} f(x,y) = L$, tenemos que $\exists r>0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < r$, entonces $|f(x,y) - L| < \varepsilon/2$. Fijamos $0 < |x-a_1| < r/\sqrt{2}$, como $f_1(x) = \lim_{y \to a_2} f(x,y)$, entonces $\exists \delta_x  0$, y podemos suponer que $\delta_x < r/\sqrt{2}$, tal que $0 < |y-a_2| < \delta_x$. Por lo que tenemos que $|f_1(x) - f(x,y)| < \varepsilon / 2$.

Para $0 < |x-a_1| < r/\sqrt{2}$, y tomo $y$ tal que $0 < |y-a_2| < \delta_x$, entonces $||(x,y) - (a_1, a_2)|| < r$. Por tanto,
$$|f_1(x) - L| \le |f_1(x) - f(x,y) + |f(x,y) - L| < \varepsilon.$$
Tags: dem anII
<!--ID: 1727966478855-->
END
