### Contenido Principal

```ad-theorem
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T$ una solución básica asociada a la base $B$ que verifica el criterio de optimalidad pero que no es factible, es decir, $\exists r \in \mathcal J_B$ tal que $\overline x_r < 0$. Entonces, una de las siguientes afirmacinoes se cumple:
1. Si $\alpha_{rj} \ge 0$, $\forall j \in \mathcal J_N$, entonces $(P)$ es imposible.
2. En caso contrario, sea $s \in \mathcal J_N$ un índice no básico que verifica
$$s \in \textrm{argmin}_{j \in \mathcal J_N}  \left \{ -\frac{\overline c_j}{\alpha_{rj}} : \alpha_{rj} < 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s\}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x_{B'}' = (B')^{-1}b$, es una solución básica primal-óptima asociada a $B'$ tal que
$$c^T \overline x' \ge c^T \overline x.$$
```

```ad-proof


```

**Tema:** [[Dualidad y análisis de sensibilidad#3. Algoritmo Dual-Simplex.]]
**Corolario:**

**Definiciones referenciadas:** [[Solución básica primal-óptima]]
**Resultados referenciados:** [[Criterio de optimalidad]]

---
### Anki
