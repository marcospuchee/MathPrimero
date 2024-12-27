### Contenido Principal

```ad-proposition
Si la brecha de optimalidad es $0$, entonces la solución incumbente es la solución óptima de $(P_0)$.
```

```ad-proof
Trivial dado que $z_{\textrm{RL}} \le v(P) \le z_{\textrm{incumb}}$.
```

```ad-note
**Criterios de poda.**
Existen tres razones que nos permiten "podar" un nodo del árbol que no necesitará ser ramificado:
- Poda por optimalidad: la solución óptima de la relajación de ese nodo es entera.
- Poda por dominación: la cota proporcionada por la relajación lineal del nodo ($z_{RL}$) cumple que $z_{RL} \ge z_{\textrm{incumb}}$, en el caso de minimizar, o $z_{RL} \le z_{\textrm{incumb}}$ en el caso de maximizar.
- Poda por imposibilidad: el problema de ese nodo es imposible.
```

```ad-note
**PLE no acotado.**
Podría pasar que el problema entero inicial $(P_0)$ fuera no acotado. En ese caso, su relajación $(R_0)$ será no acotada también. Sin embargo, el recíproco no siempre es cierto y necesitamos la factibilidad de $(P_0)$ en vista del teorema de la solución óptima de la relajación lineal. Para comprobarla, podemos aplicar el algoritmo de Branch & Bound al problema $$\begin{array}{c c l} (P_0') & \textrm{Min} & 1_n^Tx \\ & \textrm{s.a.} & Ax = b, \\ & & x\ge 0_n, \, x \in \mathbb Z^n; \end{array}$$ donde $1_n \in \mathbb R^n$ es el vector de unos. El problema $(P_0')$ tiene el mismo conjunto factible que $(P_0)$ pero nunca será no acotado.
```

**Tema:** [[Métodos de PLE#2. Algoritmo de Branch & Bound.]]

**Definiciones referenciadas:** [[Algoritmo de Branch & Bound]], [[Brecha de optimalidad]], [[Solución incumbente]]
**Resultados referenciados:** [$z_{\textrm{RL}} \le v(P) \le z_{\textrm{incumb}}$](Solución incumbente), [[Teorema solución óptima de PLE según relajación lineal]]

---
### Anki

START
Básico
Anverso: Criterio de optimalidad en Branch & Bound
Reverso: Si la brecha de optimalidad es $0$, entonces la solución incumbente es la solución óptima de $(P_0)$.
Tags: prm
<!--ID: 1735044171500-->
END

START
Básico
Anverso: Criterios de cota en Branch & Bound
Reverso:
Existen tres razones que nos permiten "podar" un nodo del árbol que no necesitará ser ramificado:
- Poda por optimalidad: la solución óptima de la relajación de ese nodo es entera.
- Poda por dominación: la cota proporcionada por la relajación lineal del nodo ($z_{RL}$) cumple que $z_{RL} \ge z_{\textrm{incumb}}$, en el caso de minimizar, o $z_{RL} \le z_{\textrm{incumb}}$ en el caso de maximizar.
- Poda por imposibilidad: el problema de ese nodo es imposible.
Tags: prm
<!--ID: 1735044171501-->
END

START
Básico
Anverso: Algoritmo Branch & Boundn para PLE no acotado
Reverso:
Podría pasar que el problema entero inicial $(P_0)$ fuera no acotado. En ese caso, su relajación $(R_0)$ será no acotada también. Sin embargo, el recíproco no siempre es cierto y necesitamos la factibilidad de $(P_0)$ en vista del teorema de la solución óptima de la relajación lineal. Para comprobarla, podemos aplicar el algoritmo de Branch & Bound al problema $$\begin{array}{c c l} (P_0') & \textrm{Min} & 1_n^Tx \\ & \textrm{s.a.} & Ax = b, \\ & & x\ge 0_n, \, x \in \mathbb Z^n; \end{array}$$ donde $1_n \in \mathbb R^n$ es el vector de unos. El problema $(P_0')$ tiene el mismo conjunto factible que $(P_0)$ pero nunca será no acotado.
Tags: prm
<!--ID: 1735044171503-->
END
