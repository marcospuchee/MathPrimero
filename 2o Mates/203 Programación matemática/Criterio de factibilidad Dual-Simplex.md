### Contenido Principal

```ad-theorem
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T$ una solución básica asociada a la base $B$ que verifica el criterio de optimalidad pero que no es factible, es decir, $\exists r \in \mathcal J_B$ tal que $\overline x_r < 0$. Entonces, una de las siguientes afirmaciones se cumple:
1. Si $\alpha_{rj} \ge 0$, $\forall j \in \mathcal J_N$, entonces $(P)$ es imposible.
2. En caso contrario, sea $s \in \mathcal J_N$ un índice no básico que verifica
$$s \in \textrm{argmin}_{j \in \mathcal J_N}  \left \{ -\frac{\overline c_j}{\alpha_{rj}} : \alpha_{rj} < 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s\}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x_{B'}' = (B')^{-1}b$, es una solución básica primal-óptima asociada a $B'$ tal que
$$c^T \overline x' \ge c^T \overline x.$$
```

```ad-note
- Variable de salida ($x_r$): la variable saliente debe ser elegida entre aquellas que tienen valor negativo (no factible). De entre todas las candidatas, tomaremos
$$x_r : r \in \mathcal J_B : r \in \textrm{argmin}_{i \in \mathcal J_B} \{\overline x_i : \overline x_i < 0 \}.$$
En caso de empate, tomaremos la variable de menor índice.

- Variable de entrada ($x_s$): la variable entrante se elige siguiendo el criterio del teorema, que ahora dependerá del tipo de problema (maximizar o minimizar): $x_s$ con $s \in \mathcal J_N$ tal que
$$\begin{array}{c c}
s \in \textrm{argmin}_{j \in \mathcal J_N} \left \{ -\frac{\overline c_j}{\alpha_{rj}} : \alpha_{rj} < 0 \right \} & (\textrm{Caso minimizar}) \\
s \in \textrm{argmax}_{j \in \mathcal J_N} \left \{ -\frac{\overline c_j}{\alpha_{rj}} : \alpha_{rj} < 0 \right \} & (\textrm{Caso minimizar}),
\end{array}$$
aunque estos criterios se pueden unificar al $\textrm{argmin}$ si tomamos valor absoluto de los ratios. Como siempre, tomaremos la variable de menor índice en empates.
```


```ad-proof
**$(i)$.**
Supongamos que $\alpha_{rj} \ge 0$, $\forall j \in \mathcal J_N$. Dada la base $B$, sabemos que
$$Ax = b \iff Bx_B + Nx_N = b \iff x_B + B^{-1}Nx_N = B^{-1}b,$$
por lo que la fila correspondiente a la variable básica $x_r$ es $x_r + \sum_{j \in \mathcal J_N} \alpha_{rj} x_j = \overline x_r$. Como $x_r \ge 0$ y $\alpha_{rj}, x_j \ge 0$, $\forall j \in \mathcal J_N$, tenemos que $x_r + \sum_{j \in \mathcal J_N} \alpha_{rj} x_j \ge 0$ para toda solución posible de $(P)$. Dado que $\overline x_r < 0$, tenemos una contradicción, por lo que $(P)$ es imposible.

**$(ii)$.**
Demostremos primero que $B'$ es base, sea $\lambda_i \in \mathbb R$, para cada $i \in \mathcal J_{B'}$, tal que
$$0_m = \sum_{i \in \mathcal J_{B'}} \lambda_i a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} \lambda_i a_i + \lambda_s a_s.$$
Como $B^{-1}a_s = \alpha_s$, entonces $a_s = B\alpha_s = \sum_{i \in \mathcal J_B} \alpha_{is} a_i$ y, sustituyendo en la expresión anterior, obtenemos
$$0_m = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} \lambda_i a_i + \lambda_s \sum_{i \in \mathcal J_B} \alpha_{is} a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} (\lambda_i + \lambda_s \alpha_{is})a_i + (\lambda_s \alpha_{rs}) a_r.$$
Como $B$ es base, de la ecuación anterior se deriva que
$$\lambda_s \alpha_{rs} = 0, \quad \lambda_i + \lambda_s \alpha_{is} = 0, \, \, \forall i \in \mathcal J_B \textrm{\\} \{r\}.$$
Como $\alpha_{rs} \neq 0$, se tiene que $\lambda_s = 0$ y, consecuente, $\lambda_i = 0$, $\forall i \in \mathcal J_B \textrm{\\} \{r\}$. Queda así demostrado que las columnas de $B'$ son linealmente independientes y, por tanto, $B'$ es base.
Una vez visto esto, veamos que la SB asociada a la base $B'$, es primal-óptima, esto es, satisface el criterio de optimalidad. Sea $\overline c_j'$ el coste reducido de la variable $x_j$ con la base $B'$. Notar que la tabla del Simplex que se obtiene al pivotar sobre $\alpha_{rs}$ es la asociada con la base $B'$. Los valores de la nueva tabla en la fila $0$ vienen dados por:
$$- \overline c_j' = - \overline c_j - \frac{\alpha_{rj}}{\alpha_{rs}}(- \overline c_s),$$
- Si $\alpha_{rj} \ge 0$, como $\alpha_{rs} < 0$ y $- \overline c_s \le 0$, tenemos que $\frac{\alpha_{rj}}{\alpha_{rs}}(- \overline c_s) \ge 0$ y, en consecuencia, $- \overline c_j' \le - \overline c_j \le 0$.
- Si $\alpha_{rj} < 0$, por la manera que hemos tomado $s$, tenemos que
$$\frac{-\overline c_s}{\alpha_{rs}} \le \frac{-\overline c_j}{\alpha_{rj}},$$
y, multiplicando ambos lados por $\alpha_{rj} < 0$, obtenemos que $- \overline c_j - \frac{\alpha_{rj}}{\alpha_{rs}}(- \overline c_s) \le 0$, esto es, $- \overline c_j' \le 0$.

Por tanto, como los nuevos costes reducidos satisfacen el criterio de optimalidad, la nueva base $B'$ es también dual posible.
El valor de la función objetivo asociado a la base $B'$ viene dado por $c^Tx' = c_B^TB^{-1}b - \frac{\overline x_r}{\alpha_{rs}}(-\overline c_s)$. Ya que $- \overline c_s \le 0$, $\alpha_{rs} < 0$ y $\overline x_r < 0$, tenemos que $- \frac{\overline x_r}{\alpha_{rs}}(- \overline c_s) \ge 0$, por lo que $c^T x' \ge c^T \overline x$.
```

**Tema:** [[Dualidad y análisis de sensibilidad#3. Algoritmo Dual-Simplex.]]
**Corolario:**

**Definiciones referenciadas:** [[Solución básica primal-óptima]], [[Coste reducido]]
**Resultados referenciados:** [[Criterio de optimalidad]]

---
### Anki

START
Básico
Anverso: Criterio de factibilidad Dual-Simplex
Reverso: Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T$ una solución básica asociada a la base $B$ que verifica el criterio de optimalidad pero que no es factible, es decir, $\exists r \in \mathcal J_B$ tal que $\overline x_r < 0$. Entonces, una de las siguientes afirmaciones se cumple:
1. Si $\alpha_{rj} \ge 0$, $\forall j \in \mathcal J_N$, entonces $(P)$ es imposible.
2. En caso contrario, sea $s \in \mathcal J_N$ un índice no básico que verifica
$$s \in \textrm{argmin}_{j \in \mathcal J_N}  \left \{ -\frac{\overline c_j}{\alpha_{rj}} : \alpha_{rj} < 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s\}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x_{B'}' = (B')^{-1}b$, es una solución básica primal-óptima asociada a $B'$ tal que
$$c^T \overline x' \ge c^T \overline x.$$
Tags: prm
<!--ID: 1733051328685-->
END

START
Básico
Anverso: Demostración de que sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T$ una solución básica asociada a la base $B$ que verifica el criterio de optimalidad pero que no es factible, es decir, $\exists r \in \mathcal J_B$ tal que $\overline x_r < 0$. Entonces, una de las siguientes afirmaciones se cumple:
1. Si $\alpha_{rj} \ge 0$, $\forall j \in \mathcal J_N$, entonces $(P)$ es imposible.
2. En caso contrario, sea $s \in \mathcal J_N$ un índice no básico que verifica
$$s \in \textrm{argmin}_{j \in \mathcal J_N}  \left \{ -\frac{\overline c_j}{\alpha_{rj}} : \alpha_{rj} < 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s\}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x_{B'}' = (B')^{-1}b$, es una solución básica primal-óptima asociada a $B'$ tal que
$$c^T \overline x' \ge c^T \overline x.$$
Reverso: **$(i)$.**
Supongamos que $\alpha_{rj} \ge 0$, $\forall j \in \mathcal J_N$. Dada la base $B$, sabemos que
$$Ax = b \iff Bx_B + Nx_N = b \iff x_B + B^{-1}Nx_N = B^{-1}b,$$
por lo que la fila correspondiente a la variable básica $x_r$ es $x_r + \sum_{j \in \mathcal J_N} \alpha_{rj} x_j = \overline x_r$. Como $x_r \ge 0$ y $\alpha_{rj}, x_j \ge 0$, $\forall j \in \mathcal J_N$, tenemos que $x_r + \sum_{j \in \mathcal J_N} \alpha_{rj} x_j \ge 0$ para toda solución posible de $(P)$. Dado que $\overline x_r < 0$, tenemos una contradicción, por lo que $(P)$ es imposible.

**$(ii)$.**
Demostremos primero que $B'$ es base, sea $\lambda_i \in \mathbb R$, para cada $i \in \mathcal J_{B'}$, tal que
$$0_m = \sum_{i \in \mathcal J_{B'}} \lambda_i a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} \lambda_i a_i + \lambda a_s.$$
Como $B^{-1}a_s = \alpha_s$, entonces $a_s = B\alpha_s = \sum_{i \in \mathcal J_B} \alpha_{is} a_i$ y, sustituyendo en la expresión anterior, obtenemos
$$0_m = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} \lambda_i a_i + \lambda_s \sum_{i \in \mathcal J_B} \alpha_{is} a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} (\lambda_i + \lambda_s \alpha_{is})a_i + (\lambda_s \alpha_{rs}) a_r.$$
Como $B$ es base, de la ecuación anterior se deriva que
$$\lambda_s \alpha_{rs} = 0, \quad \lambda_i + \lambda_s \alpha_{is} = 0, \, \, \forall i \in \mathcal J_B \textrm{\\} \{r\}.$$
Como $\alpha_{rs} \neq 0$, se tiene que $\lambda_s = 0$ y, consecuente, $\lambda_i = 0$, $\forall i \in \mathcal J_B \textrm{\\} \{r\}$. Queda así demostrado que las columnas de $B'$ son linealmente independientes y, por tanto, $B'$ es base.
Una vez visto esto, veamos que la SB asociada a la base $B'$, es primal-óptima, esto es, satisface el criterio de optimalidad. Sea $\overline c_j'$ el coste reducido de la variable $x_j$ con la base $B'$. Notar que la tabla del Simplex que se obtiene al pivotar sobre $\alpha_{rs}$ es la asociada con la base $B'$. Los valores de la nueva tabla en la fila $0$ vienen dados por:
$$- \overline c_j' = - \overline c_j - \frac{\alpha_{rj}}{\alpha_{rs}}(- \overline c_s),$$
- Si $\alpha_{rj} \ge 0$, como $\alpha_{rs} < 0$ y $- \overline c_s \le 0$, tenemos que $\frac{\alpha_{rj}}{\alpha_{rs}}(- \overline c_s) \ge 0$ y, en consecuencia, $- \overline c_j' \le - \overline c_j \le 0$.
- Si $\alpha_{rj} < 0$, por la manera que hemos tomado $s$, tenemos que
$$\frac{-\overline c_s}{\alpha_{rs}} \le \frac{-\overline c_j}{\alpha_{rj}},$$
y, multiplicando ambos lados por $\alpha_{rj} < 0$, obtenemos que $- \overline c_j - \frac{\alpha_{rj}}{\alpha_{rs}}(- \overline c_s) \le 0$, esto es, $- \overline c_j' \le 0$.

Por tanto, como los nuevos costes reducidos satisfacen el criterio de optimalidad, la nueva base $B'$ es también dual posible.
El valor de la función objetivo asociado a la base $B'$ viene dado por $c^Tx' = c_B^TB^{-1}b - \frac{\overline x_r}{\alpha_{rs}}(-\overline c_s)$. Ya que $- \overline c_s \le 0$, $\alpha_{rs} < 0$ y $\overline x_r < 0$, tenemos que $- \frac{\overline x_r}{\alpha_{rs}}(- \overline c_s) \ge 0$, por lo que $c^T x' \ge c^T \overline x$.
Tags: dem prm
<!--ID: 1733051328688-->
END

