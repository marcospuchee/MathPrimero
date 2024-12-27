### Contenido principal

```ad-Algorithm
Consideremos el problema de programación lineal entera $(\textrm{PLE})$, $$\begin{array}{c c l}
(P_0) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b \\
& & x \ge 0_n, \, x \in \mathbb Z^n.
\end{array}$$ Sea $x^0$ una solución óptima de su relajación lineal, que denotaremos por $(\textrm{R}_0)$. Tenemos dos posibilidades:
- $x^0$ tiene componentes enteras $\implies$ $x^0$ es solución óptima de $(\textrm{PLE})$.
- En otro caso, sea $x_{j_0}$ una variable tal que $x_{j_0}^0 \in \mathbb R \textrm{\\} \mathbb Z$ y consideremos los dos subproblemas: $$\begin{array}{c c} 
\begin{array}{c c l}
(P_1) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b \\
& & x_{j_0} \le \lfloor x_{j_0}^0 \rfloor, \\
& & x \ge 0_n, \, x \in \mathbb Z^n.
\end{array} & \begin{array}{c c l}
(P_2) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b \\
& &x_{j_0} \ge \lfloor x_{j_0}^0 \rfloor +1, \\
& & x \ge 0_n, \, x \in \mathbb Z^n.
\end{array}
\end{array}$$

Sean ahora $x^1$ y $x^2$ soluciones óptimas de las relajaciones lineales $(\textrm{R}_1)$ y $(\textrm{R}_2)$.
- Si $x^1$ y $x^2$ son enteras, entonces son soluciones óptimas de $(P_1)$ y $(P_2)$, y podremos resolver $(P_0)$ mediante el resultado de solución óptima por particiones.
- En otro caso, las soluciones óptimas relajadas nos proporcionan cotas superiores sobre $v(P_0)$ en vista del corolario del resultado de solución óptima por particiones. Para las cotas inferiores necesitaríamos soluciones enteras. Para intentar obtenerlas, ramificamos de nuevo cada problema en dos subproblemas que separen una de las variables fraccionarias.

Repitiendo el proceso exploramos todo el árbol de ramificación en busca de soluciones óptimas enteras y vamos acotando el valor del problema original.
```

**Tema:** [[Métodos de PLE#2. Algoritmo de Branch & Bound.]]

**Definiciones referenciadas:** [[Relajación lineal]]
**Resultados referenciados:** [[Solución óptima por particiones]]

---
### Anki

START
Básico
Anverso: Cuál es el algoritmo de Branch & Bound
Reverso: Consideremos el problema de programación lineal entera $(\textrm{PLE})$, $$\begin{array}{c c l}
(P_0) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b \\
& & x \ge 0_n, \, x \in \mathbb Z^n.
\end{array}$$ Sea $x^0$ una solución óptima de su relajación lineal, que denotaremos por $(\textrm{R}_0)$. Tenemos dos posibilidades:
- $x^0$ tiene componentes enteras $\implies$ $x^0$ es solución óptima de $(\textrm{PLE})$.
- En otro caso, sea $x_{j_0}$ una variable tal que $x_{j_0}^0 \in \mathbb R \textrm{\\} \mathbb Z$ y consideremos los dos subproblemas: $$\begin{array}{c c} 
\begin{array}{c c l}
(P_1) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b \\
& & x_{j_0} \le \lfloor x_{j_0}^0 \rfloor, \\
& & x \ge 0_n, \, x \in \mathbb Z^n.
\end{array} & \begin{array}{c c l}
(P_2) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b \\
& &x_{j_0} \ge \lfloor x_{j_0}^0 \rfloor +1, \\
& & x \ge 0_n, \, x \in \mathbb Z^n.
\end{array}
\end{array}$$

Sean ahora $x^1$ y $x^2$ soluciones óptimas de las relajaciones lineales $(\textrm{R}_1)$ y $(\textrm{R}_2)$.
- Si $x^1$ y $x^2$ son enteras, entonces son soluciones óptimas de $(P_1)$ y $(P_2)$, y podremos resolver $(P_0)$ mediante el resultado de solución óptima por particiones.
- En otro caso, las soluciones óptimas relajadas nos proporcionan cotas superiores sobre $v(P_0)$ en vista del corolario del resultado de solución óptima por particiones. Para las cotas inferiores necesitaríamos soluciones enteras. Para intentar obtenerlas, ramificamos de nuevo cada problema en dos subproblemas que separen una de las variables fraccionarias.

Repitiendo el proceso exploramos todo el árbol de ramificación en busca de soluciones óptimas enteras y vamos acotando el valor del problema original.
Tags: prm
<!--ID: 1735044171508-->
END
