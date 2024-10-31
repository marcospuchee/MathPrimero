### Contenido Principal

```ad-proposition
Sea $f: \mathbb R^2 \to \mathbb R$, $a = (a_1, a_2) \in \mathbb R^2$, $h : \mathbb R^2 \to \mathbb R$ tal que $\lim_{(x,y) \to (a_1, a_2)} h(x,y) = 0$.

Supongamos que $\exists R > 0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < R$, entonces $|f(x,y) - L| \le h(x,y)$. Entonces, $\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L$.
```

^ca2f22

```ad-proof
$\forall \varepsilon > 0$, $\exists \delta_1 > 0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < \delta_1$, entonces $|h(x,y)| < \varepsilon$. 

Sea $0 < \delta := \min (\delta_1, R)$ y $0 < ||(x,y) - (a_1, a_2)|| < \delta$. Entonces, $|f(x,y) - L| \le h(x,y) < \varepsilon$.
```

**Tema:** [[Funciones de varias variables#2. Dos variables.]]

---
### Anki

START
Básico
Anverso: Cómo puede una función tomar el papel de epsilon en la definición de límite multivariable?
Reverso: Sea $f: \mathbb R^2 \to \mathbb R$, $a = (a_1, a_2) \in \mathbb R^2$, $h : \mathbb R^2 \to \mathbb R$ tal que $\lim_{(x,y) \to (a_1, a_2)} h(x,y) = 0$.

Supongamos que $\exists R > 0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < R$, entonces $|f(x,y) - L| \le h(x,y)$. Entonces, $\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L$.
<!--ID: 1727422026723-->
END

START
Básico
Anverso: Demostración de que sea $f: \mathbb R^2 \to \mathbb R$, $a = (a_1, a_2) \in \mathbb R^2$, $h : \mathbb R^2 \to \mathbb R$ tal que $\lim_{(x,y) \to (a_1, a_2)} h(x,y) = 0$.

Supongamos que $\exists R > 0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < R$, entonces $|f(x,y) - L| \le h(x,y)$. Entonces, $\lim_{(x,y) \to (a_1, a_2)} f(x,y) = L$.
Reverso: $\forall \varepsilon > 0$, $\exists \delta_1 > 0$ tal que si $0 < ||(x,y) - (a_1, a_2)|| < \delta_1$, entonces $|h(x,y)| < \varepsilon$. 

Sea $0 < \delta := \min (\delta_1, R)$ y $0 < ||(x,y) - (a_1, a_2)|| < \delta$. Entonces, $|f(x,y) - L| \le h(x,y) < \varepsilon$.
Tags: anII dem
<!--ID: 1727422026726-->
END
