### Contenido Principal

```ad-proposition
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)PT$ una [[solución básica posible]] asociada a la base $B$. Si se verifica que
$$\overline c_j > 0, \quad \forall j \in \mathcal J_N,$$
entonces $\overline x$ es la única solución óptima de $(P)$. El recíproco es cierto si $\overline x$ es, además, no degenerada ([[solución básica posible degenerada]]).
```

```ad-note
Si el problema es de maximizar, el criterio de unicidad de solución óptima se escribe con la desigualdad contraria, es decir,
$$\overline c_j < 0, \quad \forall j \in \mathcal J_N.$$
```

```ad-proof
Por el [[criterio de optimalidad]], sabemos que si $\overline c_j > 0$, $\forall j \in \mathcal J_N$, entonces $\overline x$ es [[solución óptima]] de $(P)$. Sea $x \in \mathbb R^n$ un punto factible arbitrario tal que
$$z := c^T x = c^T \overline x =: \overline z.$$


Como $z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j$, entonces,
$$\sum_{j \in \mathcal J_N} \overline c_j x_j = 0.$$
Como $\overline c_j > 0$ y $x_j \ge 0$, $\forall j \in \mathcal J_N$, necesariamente $x_j = 0, \forall j \in \mathcal J_N$. Esto significa que $x_N = 0_{n-m}$ y, consecuentemente, $x_B = \overline x_B$, lo que prueba que $x = \overline x$.

Supongamos ahora que $\overline x$ es la única solución óptima de $(P)$, siendo una SBP no degenerada.
Por el [[criterio de optimalidad]] tenemos que $\overline c_j \ge 0$, $\forall j \in \mathcal J_N$. Razonando por reducción al absurdo y supongamos que $\exists j_0 \in \mathcal J_N$ tal que $\overline c_{j_0} = 0$. Construyamos el punto $x = (x_B^T, x_N^T)^T$ dado por
$$x_{j_0} := \varepsilon > 0, \quad x_j := 0, \quad \forall j \in \mathcal J_N \textrm{\\} \{j_0 \}, \quad x_B = \overline x_B - B^{-1}Nx_N.$$
Para $\varepsilon > 0$ suficientemente pequeño tenemos que $x$ es factible. Además, como $z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j$, entonces $z = \overline z$. Como $x \neq \overline x$, llegamos a la contradicción.
```

**Tema:** [[El método Simplex#1.2. Criterio de optimalidad.]]

---
### Anki

START
Básico
Anverso: Cuál es el criterio de unicidad de solución óptima?
Reverso: Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)PT$ una [[solución básica posible]] asociada a la base $B$. Si se verifica que
$$\overline c_j > 0, \quad \forall j \in \mathcal J_N,$$
entonces $\overline x$ es la única solución óptima de $(P)$. El recíproco es cierto si $\overline x$ es, además, no degenerada ([[solución básica posible degenerada]]).
<!--ID: 1727966478441-->
END

START
Básico
Anverso: Demostración de que sea $\overline x = (\overline x_B^T, 0_{n-m}^T)PT$ una [[solución básica posible]] asociada a la base $B$. Si se verifica que
$$\overline c_j > 0, \quad \forall j \in \mathcal J_N,$$
entonces $\overline x$ es la única solución óptima de $(P)$. El recíproco es cierto si $\overline x$ es, además, no degenerada ([[solución básica posible degenerada]]).
Reverso: Por el [[criterio de optimalidad]], sabemos que si $\overline c_j > 0$, $\forall j \in \mathcal J_N$, entonces $\overline x$ es [[solución óptima]] de $(P)$. Sea $x \in \mathbb R^n$ un punto factible arbitrario tal que
$$z := c^T x = c^T \overline x =: \overline z.$$


Como $z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j$, entonces,
$$\sum_{j \in \mathcal J_N} \overline c_j x_j = 0.$$
Como $\overline c_j > 0$ y $x_j \ge 0$, $\forall j \in \mathcal J_N$, necesariamente $x_j = 0, \forall j \in \mathcal J_N$. Esto significa que $x_N = 0_{n-m}$ y, consecuentemente, $x_B = \overline x_B$, lo que prueba que $x = \overline x$.

Supongamos ahora que $\overline x$ es la única solución óptima de $(P)$, siendo una SBP no degenerada.
Por el [[criterio de optimalidad]] tenemos que $\overline c_j \ge 0$, $\forall j \in \mathcal J_N$. Razonando por reducción al absurdo y supongamos que $\exists j_0 \in \mathcal J_N$ tal que $\overline c_{j_0} = 0$. Construyamos el punto $x = (x_B^T, x_N^T)^T$ dado por
$$x_{j_0} := \varepsilon > 0, \quad x_j := 0, \quad \forall j \in \mathcal J_N \textrm{\\} \{j_0 \}, \quad x_B = \overline x_B - B^{-1}Nx_N.$$
Para $\varepsilon > 0$ suficientemente pequeño tenemos que $x$ es factible. Además, como $z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j$, entonces $z = \overline z$. Como $x \neq \overline x$, llegamos a la contradicción.
Tags: dem prm
<!--ID: 1727966478481-->
END

START
Básico
Anverso: Criterio de unicidad de solución óptima para un problema de maximizar
Reverso: Si el problema es de maximizar, el criterio de unicidad de solución óptima se escribe con la desigualdad contraria, es decir,
$$\overline c_j < 0, \quad \forall j \in \mathcal J_N.$$
<!--ID: 1727966478535-->
END

