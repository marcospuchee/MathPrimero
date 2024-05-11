
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-20, 20:40

```ad-theorem
Sean $I$ un intervalo abierto y $f: I \to \mathbb R$ una función derivable en todos los puntos de $I$ tal que $f'(x) \neq 0, \forall x \in I$. Entonces $f$ inyectiva, su inversa $g$ es derivable en todos los puntos de $f(I)$, y $g'(f(x)) = 1/f'(x), \forall x \in I$.
```


```ad-proof
Según el [[Teorema de Darboux]], el signo de la derivada de $f$ en $I$ es constante, es decir, $f'$ es estrictamente positiva, o negativa, en todos los puntos. Así, $f$ es estrictamente monótona ([[Función monótona]]), por tanto es inyectiva y tiene sentido hablar de $g := f^{-1}$.
Supongamos, por ejemplo, que $f$ es estrictamente creciente. Sea $b \in f(I)$ vamos a ver que $g$ es derivable en $b$ ([[Función derivable en un punto]]). Dividiremos la prueba en tres pasos:
1. Por definición de derivada, debemos comprobar que
$$\exists \delta > 0: ]b-\delta, b + \delta \subset f(I).$$
Sea $a \in I$ tal que $f(a) = b$. Puesto que $I$ es abierto, $\exists \alpha, \beta \in I$ tales que $\alpha < a < \beta$. Puesto que $f$ es estrictamente creciente en $I$, tendremos que $f(\alpha) < b = f(a) < f(\beta)$. Sabemos que $f(\alpha), f(\beta) \in f([\alpha, \beta])$, y por el [[Teorema de Bolzano (1817)]] $f([\alpha, \beta])$ ha de ser un intervalo, entonces $[f(\alpha), f(\beta)] \subset f([\alpha, \beta])$. Por tanto,
$$b \in ]f(\alpha), f(\beta)[ \subset f([\alpha, \beta]) \subset f(i).$$
Para deducir que $\exists \delta > 0: ]b-\delta, b + \delta \subset f(I)$, basta con aplicar [[Lema subintervalo con el mínimo]].

2. Veamos que
$$]f(\alpha), f(\beta)[ = f(]\alpha, \beta[).$$
De hecho mostraremos que $[f(\alpha), f(\beta)] = f([\alpha, \beta])$, de esta igualdad y la inyectividad de $f$ se deduce que $]f(\alpha), f(\beta)[ = f(]\alpha, \beta[)$. En efecto, en $b \in ]f(\alpha), f(\beta)[ \subset f([\alpha, \beta]) \subset f(i)$, hemos visto ya una inclusión, por otra parte, la monotonía de $f$ nos da que $f([\alpha, \beta]) \subset [f(\alpha), f(\beta)]$, deduciéndose la igualdad.

3. Observemos que la restricción $f \restriction_{]\alpha, \beta[} : ]\alpha, \beta[ \to ]f(\alpha), f(\beta)[$ cumple todas las hipótesis del [[Teorema de la función inversa]], por tanto basta aplicar la segunda nota de [[Función derivable en un punto]].
```


**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué dice el teorema de la función inversa (II)?
Reverso: Sean $I$ un intervalo abierto y $f: I \to \mathbb R$ una función derivable en todos los puntos de $I$ tal que $f'(x) \neq 0, \forall x \in I$. Entonces $f$ inyectiva, su inversa $g$ es derivable en todos los puntos de $f(I)$, y $g'(f(x)) = 1/f'(x), \forall x \in I$.
Tags: proposición/teorema análisisI
<!--ID: 1713093069911-->
END

START
Básico
Anverso: Demostración del teorema de la función inversa (II)
Reverso: Según el [[Teorema de Darboux]], el signo de la derivada de $f$ en $I$ es constante, es decir, $f'$ es estrictamente positiva, o negativa, en todos los puntos. Así, $f$ es estrictamente monótona ([[Función monótona]]), por tanto es inyectiva y tiene sentido hablar de $g := f^{-1}$.
Supongamos, por ejemplo, que $f$ es estrictamente creciente. Sea $b \in f(I)$ vamos a ver que $g$ es derivable en $b$ ([[Función derivable en un punto]]). Dividiremos la prueba en tres pasos:
1. Por definición de derivada, debemos comprobar que
$$\exists \delta > 0: ]b-\delta, b + \delta \subset f(I).$$
Sea $a \in I$ tal que $f(a) = b$. Puesto que $I$ es abierto, $\exists \alpha, \beta \in I$ tales que $\alpha < a < \beta$. Puesto que $f$ es estrictamente creciente en $I$, tendremos que $f(\alpha) < b = f(a) < f(\beta)$. Sabemos que $f(\alpha), f(\beta) \in f([\alpha, \beta])$, y por el [[Teorema de Bolzano (1817)]] $f([\alpha, \beta])$ ha de ser un intervalo, entonces $[f(\alpha), f(\beta)] \subset f([\alpha, \beta])$. Por tanto,
$$b \in ]f(\alpha), f(\beta)[ \subset f([\alpha, \beta]) \subset f(i).$$
Para deducir que $\exists \delta > 0: ]b-\delta, b + \delta \subset f(I)$, basta con aplicar [[Lema subintervalo con el mínimo]].

2. Veamos que
$$]f(\alpha), f(\beta)[ = f(]\alpha, \beta[).$$
De hecho mostraremos que $[f(\alpha), f(\beta)] = f([\alpha, \beta])$, de esta igualdad y la inyectividad de $f$ se deduce que $]f(\alpha), f(\beta)[ = f(]\alpha, \beta[)$. En efecto, en $b \in ]f(\alpha), f(\beta)[ \subset f([\alpha, \beta]) \subset f(i)$, hemos visto ya una inclusión, por otra parte, la monotonía de $f$ nos da que $f([\alpha, \beta]) \subset [f(\alpha), f(\beta)]$, deduciéndose la igualdad.

3. Observemos que la restricción $f \restriction_{]\alpha, \beta[} : ]\alpha, \beta[ \to ]f(\alpha), f(\beta)[$ cumple todas las hipótesis del [[Teorema de la función inversa]], por tanto basta aplicar la segunda nota de [[Función derivable en un punto]].
Tags: demostración análisisI
<!--ID: 1713093069915-->
END