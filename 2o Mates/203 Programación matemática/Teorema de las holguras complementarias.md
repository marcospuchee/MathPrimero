### Contenido Principal

```ad-theorem
Sean $x^* \in \mathbb R^n$ y $w^* \in \mathbb R^m$ soluciones factibles de $(P)$ y $(D)$, respectivamente. Entonces, dichas soluciones son óptimas para cada problema, respectivamente, $\iff$ se cumplen
$$\begin{matrix} \displaystyle
\left ( c_j - \sum_{i = 1}^m a_{ij} w_i^* \right ) x_j^* = 0, \quad \forall j = 1, \dots, n, \\ \displaystyle
w_i^* \left ( \sum_{j = 1}^n a_{ij}x_j^* - b_i \right ) = 0, \quad \forall i = 1, \dots, m.
\end{matrix}$$
```

```ad-proof
Sean $x^* \in \mathbb R^n$ y $w^* \in \mathbb R^m$ soluciones factibles de $(P)$ y $(D)$, respectivamente. Razonando como en el [[teorema de Dualidad Débil]], llegamos a 
$$c^T x^* = (x^*)^T c \ge (x^*)^T A^T w^* = ((x^*)^T A^T w^*)^T = (w^*)^T Ax^* \ge (w^*)^T b = b^T w^*,$$
que podemos escribir como
$$c^T x^* \ge (w^*)^T Ax^* \ge (w^*)^T b.$$
Supongamos que son soluciones óptimas, por el [[teorema de Dualidad Fuerte]], se tiene que $c^T x^* = b^T w^*$, por lo que obtenemos igualdades en las desigualdades anteriores. Si separamos en dos ecuaciones obtenemos:
$$\begin{eqnarray}
c^Tx^* = (w^*)^T Ax^* &\iff& (c-A^Tw^*)^Tx^* = 0, \\
(w^*)^T Ax^* = (w^*)^T b &\iff& (w^*)^T (Ax^* - b) = 0.
\end{eqnarray}$$
Ambas ecuaciones nos indican que el producto escalar de dos vectores es cero. Por factibilidad, las componentes de cada uno de los vectores son no negativas, por lo que necesariamente el producto componente a componente debe ser nulo, y deducimos lo que queríamos demostrar.

El recíproco se puede probar fácilmente deshaciendo los pasos de la prueba y aplicando el [[corolario del teorema de Dualidad Débil (soluciones óptimas)]].
```

**Tema:** [[Dualidad y análisis de sensibilidad#2. Relaciones primal-dual.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de las holguras complementarias?
Reverso: Sean $x^* \in \mathbb R^n$ y $w^* \in \mathbb R^m$ soluciones factibles de $(P)$ y $(D)$, respectivamente. Entonces, dichas soluciones son óptimas para cada problema, respectivamente, $\iff$ se cumplen
$$\begin{matrix} \displaystyle
\left ( c_j - \sum_{i = 1}^m a_{ij} w_i^* \right ) x_j^* = 0, \quad \forall j = 1, \dots, n, \\ \displaystyle
w_i^* \left ( \sum_{j = 1}^n a_{ij}x_j^* - b_i \right ) = 0, \quad \forall i = 1, \dots, m.
\end{matrix}$$
Tags: prm
<!--ID: 1728820185270-->
END

START
Básico
Anverso: Demostración de que sean $x^* \in \mathbb R^n$ y $w^* \in \mathbb R^m$ soluciones factibles de $(P)$ y $(D)$, respectivamente. Entonces, dichas soluciones son óptimas para cada problema, respectivamente, $\iff$ se cumplen
$$\begin{matrix} \displaystyle
\left ( c_j - \sum_{i = 1}^m a_{ij} w_i^* \right ) x_j^* = 0, \quad \forall j = 1, \dots, n, \\ \displaystyle
w_i^* \left ( \sum_{j = 1}^n a_{ij}x_j^* - b_i \right ) = 0, \quad \forall i = 1, \dots, m.
\end{matrix}$$
Reverso: Sean $x^* \in \mathbb R^n$ y $w^* \in \mathbb R^m$ soluciones factibles de $(P)$ y $(D)$, respectivamente. Razonando como en el [[teorema de Dualidad Débil]], llegamos a 
$$c^T x^* = (x^*)^T c \ge (x^*)^T A^T w^* = ((x^*)^T A^T w^*)^T = (w^*)^T Ax^* \ge (w^*)^T b = b^T w^*,$$
que podemos escribir como
$$c^T x^* \ge (w^*)^T Ax^* \ge (w^*)^T b.$$
Supongamos que son soluciones óptimas, por el [[teorema de Dualidad Fuerte]], se tiene que $c^T x^* = b^T w^*$, por lo que obtenemos igualdades en las desigualdades anteriores. Si separamos en dos ecuaciones obtenemos:
$$\begin{eqnarray}
c^Tx^* = (w^*)^T Ax^* &\iff& (c-A^Tw^*)^Tx^* = 0, \\
(w^*)^T Ax^* = (w^*)^T b &\iff& (w^*)^T (Ax^* - b) = 0.
\end{eqnarray}$$
Ambas ecuaciones nos indican que el producto escalar de dos vectores es cero. Por factibilidad, las componentes de cada uno de los vectores son no negativas, por lo que necesariamente el producto componente a componente debe ser nulo, y deducimos lo que queríamos demostrar.

El recíproco se puede probar fácilmente deshaciendo los pasos de la prueba y aplicando el [[corolario del teorema de Dualidad Débil (soluciones óptimas)]].
Tags: dem prm
<!--ID: 1728820185273-->
END