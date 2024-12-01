### Contenido Principal

```ad-theorem
Sea $(\textrm{RL})$ la relajación lineal de un problema de programación entera $(\textrm{PLE})$.. Las siguientes afirmaciones se cumplen:
1. Si $(\textrm{RL})$ es imposible, entonces $(\textrm{PLE})$ también lo es.
2. Si $(\textrm{RL})$ tiene solución óptima, entonces $v(\textrm{PLE}) \ge v(\textrm{RL})$ (en el caso de maximizar, $v(\textrm{PLE}) \le v(\textrm{RL})$). Sea $x^*$ una solución óptima de $(\textrm{RL})$, si es solución factible para $(\textrm{PLE})$, entonces
$$x^* \textrm{ es solución óptima de } (\textrm{PLE}),$$
y se cumple que $v(\textrm{PLE}) = v(\textrm{RL})$.
3. Supongamos que $A \in \mathbb R^{m \times n}$ y $b \in \mathbb R^m$ tienen componentes racionales. Si $(\textrm{RL})$ es no acotado, entonces $(\textrm{PLE})$ es imposible o no acotado.
```

```ad-proof
**$(i), (ii)$.** Ejercicio.

**$(iii)$.**
Supongamos que $(\textrm{RL})$ es no acotado, que las componentes de $A$ y $b$ son racionales y que $(\textrm{PLE})$ es factible. Entonces existe una dirección extrema $d \in \mathbb R^n$ con componentes racionales tal que
$$x+ \lambda d \in \mathcal S, \, \, \forall x \in \mathcal S, \, \, \forall \lambda > 0 \quad \land \quad \lim_{\lambda \to \infty} c^T(x+\lambda d) = -\infty.$$
Sea $m$ el mínimo común múltiplo de los denominadores de las componentes de $d$, es decir, $md \in \mathbb Z^n$, y sea $y \in \mathcal F$. Entonces se tiene que
$$y + kmd \in \mathcal F, \, \, \forall k \in \mathbb N \quad \land \quad \lim_{k \to \infty} c^T(y+kmd)= -\infty,$$
por lo que $(\textrm{PLE})$ sería no acotado.
```

**Tema:** [[Programación lineal entera#1. El modelo lineal entero.]]

**Definiciones referenciadas:** [[Relajación lineal]], [[Solución óptima]], [[Valor de un problema]]
**Resultados referenciados:**[[Teorema fundamental de la programación lineal]]

---
### Anki
