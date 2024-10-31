### Contenido Principal

```ad-theorem
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)$ una [[solución básica posible]] asociada a la base $B$. Si se verifica que
$$\overline c_j \ge 0, \quad \forall j \in \mathcal J_N,$$
entonces $\overline x$ es una [[solución óptima]] de $(P)$. El recíproco es cierto si $\overline x$ es, además, no degenerada.
```

```ad-note
Si el problema es de maximizar, el criterio de optimalidad se reescribe con la desigualdad contraria:
$$\overline c_j \le 0, \quad \forall j \in \mathcal J_N.$$
```

```ad-proof
De la factibilidad de $\overline x$ se tiene que $\overline x_B = B^{-1}b \ge 0_m$. Sea $\overline z := c^T \overline x = c_B^T \overline x_B$ el valor objetivo en $\overline x$, y sea $x \in \mathbb R^n$ un punto factible arbitrario de $(P)$ con valor objetivo $z := c^T x$. Tomemos la descomposición $x = (x_B^T, x_N^T)^T$. Como $x$ es factible se tiene que $x_B \ge 0_m$, $x_N \ge 0_{n-m}$ y
$$\begin{eqnarray}
Ax = b &\iff& [B \quad N] \begin{pmatrix} x_B \\ x_N \end{pmatrix} = b \\
&\iff& Bx_B + Nx_N = b \\
&\iff& x_B = B^{-1}b - B^{-1}Nx_N = \overline x_B - B^{-1}Nx_N (*).
\end{eqnarray}$$

Se cumple entonces que
$$z = c^T x = c_B^T x_B + c_N^T x_N = c_B^T(\overline x_B - B^{-1}Nx_N) + c_N^T x_N = \overline z + (c_N^T - c_B^T B^{-1}N)x_N,$$
o, equivalentemente,
$$z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j.$$
Como $x_j \ge 0$, $\forall j \in \mathcal J_N$, de la expresión anterior deducimos que, si se cumple que $\overline c_j \ge 0, \, \forall j \in \mathcal J_N$, entonces $\overline z \le z$, lo que prueba que $\overline x$ es una solución óptima de $(P)$.

Para el recíproco supongamos que $\exists j_0 \in \mathcal J_N$ tal que $\overline c_{j_0} < 0$, y tomemos $x$ tal que
$$x_{j_0} := \varepsilon > 0 \quad \land \quad x_j := 0, \, \forall j \in \mathcal J_N \textrm{\\} \{j_0\}.$$
El resto de componentes, $x_B$, vienen determinadas por $(*)$ para que $Ax = b$. De la misma ecuación obtenemos que, suponiendo que $\overline x$ es no degenerada ($\overline x_B > 0_m$), para $\varepsilon > 0$ suficientemente pequeño podemos garantizar que $x_B \ge 0_m$. De esta forma, $x$ es una solución factible con valor objetivo $z = \overline z + \overline c_{j_0} x_{j_0}$. Por lo tanto, $\overline x$ no puede ser óptimo de $(P)$ y concluimos la prueba.
```

**Tema:**  [[El método Simplex#1.2. Criterio de optimalidad.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el criterio de optimalidad?
Reverso: Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)$ una [[solución básica posible]] asociada a la base $B$. Si se verifica que
$$\overline c_j \ge 0, \quad \forall j \in \mathcal J_N,$$
entonces $\overline x$ es una [[solución óptima]] de $(P)$. El recíproco es cierto si $\overline x$ es, además, no degenerada.
<!--ID: 1727966478590-->
END

START
Básico
Anverso: Demostración de que sea $\overline x = (\overline x_B^T, 0_{n-m}^T)$ una [[solución básica posible]] asociada a la base $B$. Si se verifica que
$$\overline c_j \ge 0, \quad \forall j \in \mathcal J_N,$$
entonces $\overline x$ es una [[solución óptima]] de $(P)$. El recíproco es cierto si $\overline x$ es, además, no degenerada.
Reverso: De la factibilidad de $\overline x$ se tiene que $\overline x_B = B^{-1}b \ge 0_m$. Sea $\overline z := c^T \overline x = c_B^T \overline x_B$ el valor objetivo en $\overline x$, y sea $x \in \mathbb R^n$ un punto factible arbitrario de $(P)$ con valor objetivo $z := c^T x$. Tomemos la descomposición $x = (x_B^T, x_N^T)^T$. Como $x$ es factible se tiene que $x_B \ge 0_m$, $x_N \ge 0_{n-m}$ y
$$\begin{eqnarray}
Ax = b &\iff& [B \quad N] \begin{pmatrix} x_B \\ x_N \end{pmatrix} = b \\
&\iff& Bx_B + Nx_N = b \\
&\iff& x_B = B^{-1}b - B^{-1}Nx_N = \overline x_B - B^{-1}Nx_N (*).
\end{eqnarray}$$

Se cumple entonces que
$$z = c^T x = c_B^T x_B + c_N^T x_N = c_B^T(\overline x_B - B^{-1}Nx_N) + c_N^T x_N = \overline z + (c_N^T - c_B^T B^{-1}N)x_N,$$
o, equivalentemente,
$$z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j.$$
Como $x_j \ge 0$, $\forall j \in \mathcal J_N$, de la expresión anterior deducimos que, si se cumple que $\overline c_j \ge 0, \, \forall j \in \mathcal J_N$, entonces $\overline z \le z$, lo que prueba que $\overline x$ es una solución óptima de $(P)$.

Para el recíproco supongamos que $\exists j_0 \in \mathcal J_N$ tal que $\overline c_{j_0} < 0$, y tomemos $x$ tal que
$$x_{j_0} := \varepsilon > 0 \quad \land \quad x_j := 0, \, \forall j \in \mathcal J_N \textrm{\\} \{j_0\}.$$
El resto de componentes, $x_B$, vienen determinadas por $(*)$ para que $Ax = b$. De la misma ecuación obtenemos que, suponiendo que $\overline x$ es no degenerada ($\overline x_B > 0_m$), para $\varepsilon > 0$ suficientemente pequeño podemos garantizar que $x_B \ge 0_m$. De esta forma, $x$ es una solución factible con valor objetivo $z = \overline z + \overline c_{j_0} x_{j_0}$. Por lo tanto, $\overline x$ no puede ser óptimo de $(P)$ y concluimos la prueba.
Tags: dem prm
<!--ID: 1727966478648-->
END

START
Básico
Anverso: Criterio de optimalidad en el caso de problema de maximizar
Reverso: Si el problema es de maximizar, el criterio de optimalidad se reescribe con la desigualdad contraria:
$$\overline c_j \le 0, \quad \forall j \in \mathcal J_N.$$
<!--ID: 1727966478700-->
END
