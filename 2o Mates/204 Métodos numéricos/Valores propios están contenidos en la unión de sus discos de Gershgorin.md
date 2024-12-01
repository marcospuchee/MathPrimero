### Contenido Principal

```ad-theorem
Los valores propios de $A$ están contenidos en la unión de sus discos de Gershgorin
```

```ad-proof
Sea $\lambda \in \mathbb C$ valor propio de $A$, queremos probar que $\lambda \in \bigcup_{i = 1}^n D_i$. Esto es equivalente a decir que $\exists i_0 \in \mathbb N$, $1 \le i_0 \le n$ tal que $\lambda \in D_{i_0}$. 

Como $\lambda$ valor propio de $A$, sabemos que $\exists x \in \mathbb C^n \textrm{\\} \{0\}$ tal que $Ax = \lambda x$. Sea $i_0 := \textrm{argmax}_{1 \le i \le n} |x_{i_0}|$, entonces $x_{i_0} \neq 0$. Vamos a probar que $\lambda \in D_{i_0}$.

Notemos que $Ax = \lambda x \implies [Ax](i_0) = [\lambda x](i_0)$. Por tanto, se tiene que
$$[\lambda x](i_0) = \lambda x_{i_0}; \quad [Ax](i_0) = A(i_0, :)x = \sum_{j = 1}^n a_{i_0,j} x_j.$$
Entonces,
$$\lambda x_{i_0} = \sum_{j = 1}^n a_{i_0,j} x_j = a_{i_0, i_0} x_{i_0} + \sum_{j = 1, j \neq i_0}^n a_{i_0, j} x_j,$$
pero pasando el término $a_{i_0, i_0}$ y sacando factor común queda:
$$(\lambda - a_{i_0, i_0})x_{i_0} = \sum_{j = 1, j \neq i_0}^n a_{i_0, j} x_j.$$
Tomando módulos a ambos lados:
$$\begin{eqnarray}
|\lambda - a_{i_0, i_0}| \cdot |x_{i_0}| &=& \left | \sum_{j = 1, j \neq i_0}^n a_{i_0, j} x_j \right | \\
&\le& \sum_{j = 1, j \neq i_0}^n |a_{i_0, j}| \, |x_j|,
\end{eqnarray}$$
que, diviendo a ambos lados por $|x_{i_0}|$, queda
$$|\lambda - a_{i_0, i_0}| \le \sum_{j = 1, j \neq i_0}^n |a_{i_0, j}| \cdot \frac{|x_j|}{|x_{i_0}|} \le \sum_{j = 1, j \neq i_0}^n |a_{i_0, j}|,$$
de donde deducimos que $\lambda \in D_{i_0}$, y $\lambda \in \bigcup_{i = 1}^n D_i$.
```

**Tema:** [[Métodos para valores y vectores propios#2. Discos de Gershgorin.]]

**Definiciones referenciadas:** [[Valor propio de una matriz]], [[Discos de Gershgorin]]
**Resultados referenciados:** -.

---
### Anki
