### Contenido Principal

```ad-theorem
Sea $x \in \mathbb R^n$ un punto factible de $(P)$ y $w \in \mathbb R^m$ un punto factible de $(D)$. Entonces se verifica que
$$c^Tx \ge b^Tw.$$
Consecuentemente, siempre se cumple que $v(P) \ge v(D)$.
```

```ad-note
Si el primal es de maximizar y el dual de minimizar, entonces 
$$c^Tx \le b^T w.$$
```

```ad-proof
Sea $x \in \mathbb R^n$ primal-factible y $w \in \mathbb R^m$ dual-factible, es decir,
$$Ax \ge b, \quad A^Tw \le c.$$
Premultiplicando las desigualdades anteriores por $w^T$ y $x^T$, respectivamente, obtenemos
$$w^T Ax \ge w^Tb, \quad x^TA^T w \le x^Tc.$$
Finalmente, reordenando llegamos a
$$c^T x = x^T c \ge x^T A^T w = (x^T A^T w)^T = w^T Ax \ge w^T b = b^T w.$$
```

**Tema:** [[Dualidad y análisis de sensibilidad#2. Relaciones primal-dual.]]
**Corolario:** [[Corolario del teorema de Dualidad Débil (soluciones óptimas)]], [[Primal factible no acotado implica dual imposible (viceversa)]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la dualidad débil?
Reverso: Sea $x \in \mathbb R^n$ un punto factible de $(P)$ y $w \in \mathbb R^m$ un punto factible de $(D)$. Entonces se verifica que
$$c^Tx \ge b^Tw.$$
Consecuentemente, siempre se cumple que $v(P) \ge v(D)$.
Tags: prm
<!--ID: 1728820185281-->
END

START
Básico
Anverso: Demostración de que sea $x \in \mathbb R^n$ un punto factible de $(P)$ y $w \in \mathbb R^m$ un punto factible de $(D)$. Entonces se verifica que
$$c^Tx \ge b^Tw.$$
Consecuentemente, siempre se cumple que $v(P) \ge v(D)$.
Reverso: Sea $x \in \mathbb R^n$ primal-factible y $w \in \mathbb R^m$ dual-factible, es decir,
$$Ax \ge b, \quad A^Tw \le c.$$
Premultiplicando las desigualdades anteriores por $w^T$ y $x^T$, respectivamente, obtenemos
$$w^T Ax \ge w^Tb, \quad x^TA^T w \le x^Tc.$$
Finalmente, reordenando llegamos a
$$c^T x = x^T c \ge x^T A^T w = (x^T A^T w)^T = w^T Ax \ge w^T b = b^T w.$$
Tags: dem prm
<!--ID: 1728820185284-->
END
