### Contenido Principal


```ad-theorem
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)$ una [[solución básica posible]] asociada a la base $B$ que no verifica el [[criterio de optimalidad]], es decir, $\exists s \in \mathcal J_N$ tal que $\overline c_s < 0$. Entonces una de las siguientes afirmaciones se cumple:
1. Si $\alpha_{is} \le 0$, $\forall i \in \mathcal J_B$, entonces $(P)$ es no acotado.
2. En caso contrario, sea $r \in \mathcal J_B$ un índice básico que verifica
$$r \in \textrm{argmin}_{i \in \mathcal J_B} \left \{ \frac{\overline x_i}{\alpha_{is}} : \alpha_{is} > 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s \}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x'_{B'} = (B')^{-1}b$, es una SBP asociada a $B'$ tal que
$$c^T \overline x' \le c^T \overline x.$$
Si, además, $\overline x$ era no degenerada, entonces la desigualdad es estricta.
```

```ad-proof
Para cada $\xi \ge 0$ sea $x^\xi = ((x^\xi_B)^T, (x_N^\xi)^T)^T \in \mathbb R^n$ el punto definido por
$$x_s^\xi := \xi, \quad x_j^\xi := 0, \, \forall j \in \mathcal J_n \textrm{\\} \{s\}, \quad x^\xi_B := \overline x_B - B^{-1}Nx_N^\xi.$$

Por construcción se tiene que $x_N^\xi \ge 0_{n-m}$ y $Ax^\xi = b$. Si analizamos la expresión de las componentes básicas de $x^\xi$ observamos que
$$(*) \quad x_i^\xi = \overline x_i - \sum_{j \in \mathcal J_N} \alpha_{ij} x_j^\xi = \overline x_i - \alpha_{is} \xi, \quad \forall i \in \mathcal J_B.$$
Por otra parte, razonando como en el [[criterio de optimalidad]], donde se obtiene que $z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j$, entonces obtenemos que
$$(**) \quad c^T x^\xi = c^T \overline x + \sum_{j \in \mathcal J_N} \overline c_j x_j^\xi = c^T \overline x + \overline c_s \xi.$$

$(i)$.
Si $\alpha_{is} \le 0$, $\forall i \in \mathcal J_B$, en vista de $(*)$ tenemos que $x_B^\xi \ge 0_m$, $\forall \xi > 0$. Podemos tomar entonces límites cuando $\xi \to +\infty$ en $(**)$ y hacer el objetivo todo lo pequeño que queramos. Por tanto, $v(P) = -\infty$ y el problema es no acotado.


$(ii)$. Supongamos ahora que existe al menos un $\alpha_{is} > 0$ para algún $i \in \mathcal J_B$ y tomemos
$$\overline x' = x^{\xi_0}; \quad \xi_0 := \frac{\overline x_r}{\alpha_{rs}} \ge 0.$$

Sustituyendo en $(*)$ llegamos a
$$\overline x_i' = \overline x_i - \alpha_{is} \frac{\overline x_r}{\alpha_{rs}}, \quad \forall i \in \mathcal J_B.$$
Probaremos que $\overline x_i' \ge 0, \, \forall i \in \mathcal J_B$. Para ello, distinguiremos dos casos:
- Si $i \in \mathcal J_B$ es tal que $\alpha_{is} \le 0$ la conclusión es trivial.
- Si $i \in \mathcal J_B$ es tal que $\alpha_{is} > 0$ entonces, por definición de $r$ en la hipótesis, obtenemos que
$$(***) \quad \overline x_i' = \overline x_i - \alpha_{is} \frac{\overline x_r}{\alpha_{rs}} \ge \overline x_i - \alpha_{is} \frac{\overline x_i}{\alpha_{is}} = 0.$$

Tenemos entonces que $\overline x'$ es una solución factible de $(P)$. Además, como $\overline c_s < 0$ y $\xi_0 \ge 0$, de $(**)$ se deduce
$$c^T \overline x' \le c^T \overline x.$$
Si $\overline x$ es no degenerada podemos asegurar que $\xi_0 > 0$, por lo que la desigualdad anterior sería estricta.

Probaremos ahora que $B'$ forma una base. Sea $\lambda_i \in \mathbb R$, para cada $i \in \mathcal J_B'$, tal que
$$0_m = \sum_{i \in \mathcal J_{B'}} \lambda_i a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} \lambda_i a_i + \lambda_s a_s.$$
Como $B^{-1} a_s = \alpha_s$, entonces $a_s = B\alpha_s = \sum_{i \in \mathcal J_B} \alpha_{is} a_i$ y sustituyendo en la expresión anterior obtenemos
$$0_m = \sum_{i \in \mathcal J_B \textrm{\\} \{r\} } \lambda_i a_i + \lambda_s \sum_{i \in \mathcal J_B} \alpha_{is} a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{ r \} } (\lambda_i + \lambda_s \alpha_{is})a_i + (\lambda_s \alpha_{rs}) a_r.$$
Como $B$ es base, de la ecuación anterior se deriva que
$$\lambda_s \alpha_{rs} = 0, \quad \lambda_i + \lambda_s \alpha_{is} = 0, \, \forall i \in \mathcal J_B \textrm{\\} \{r\}.$$
Como $\alpha_{rs} \neq 0$, se tiene que $\lambda_s = 0$ y, consecuentemente, $\lambda_i = 0$ para todo $i \in \mathcal J_B \textrm{\\} \{r\}$. Queda así demostrado que las columnas de $B'$ son linealmente independientes y, por tanto, $B'$ es base.

Solo falta probar que $\overline x'$ es SBP asociada a $B'$. Para ello consideremos la descomposición $\overline x' = ((\overline x_{B'}')^T, (\overline x_{N'}')^T)^T$. Como ya sabemos que $\overline x'$ es factible, basta comprobar que $\overline x_{N'}' = 0_{n-m}$. En efecto, por construcción se teine que
$$\overline x_j' = 0, \quad \forall j \in \mathcal J_N \textrm{\\} \{s\}.$$

Además, podemos comprobar en $(***)$ que $\overline x_r' = 0$. Como $\mathcal J_{N'} = (\mathcal J_N \textrm{\\} \{s\}) \cup \{r\}$ llegamos al resultado deseado. 
```

**Tema:** [[El método Simplex#1.2. Criterio de optimalidad.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Criterio de factibilidad
Reverso: Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)$ una [[solución básica posible]] asociada a la base $B$ que no verifica el [[criterio de optimalidad]], es decir, $\exists s \in \mathcal J_N$ tal que $\overline c_s < 0$. Entonces una de las siguientes afirmaciones se cumple:
1. Si $\alpha_{is} \le 0$, $\forall i \in \mathcal J_B$, entonces $(P)$ es no acotado.
2. En caso contrario, sea $r \in \mathcal J_B$ un índice básico que verifica
$$r \in \textrm{argmin}_{i \in \mathcal J_B} \left \{ \frac{\overline x_i}{\alpha_{is}} : \alpha_{is} > 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s \}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x'_{B'} = (B')^{-1}b$, es una SBP asociada a $B'$ tal que
$$c^T \overline x' \le c^T \overline x.$$
Si, además, $\overline x$ era no degenerada, entonces la desigualdad es estricta.
<!--ID: 1728138052313-->
END

START
Básico
Anverso: Demostración de que sea $\overline x = (\overline x_B^T, 0_{n-m}^T)$ una [[solución básica posible]] asociada a la base $B$ que no verifica el [[criterio de optimalidad]], es decir, $\exists s \in \mathcal J_N$ tal que $\overline c_s < 0$. Entonces una de las siguientes afirmaciones se cumple:
1. Si $\alpha_{is} \le 0$, $\forall i \in \mathcal J_B$, entonces $(P)$ es no acotado.
2. En caso contrario, sea $r \in \mathcal J_B$ un índice básico que verifica
$$r \in \textrm{argmin}_{i \in \mathcal J_B} \left \{ \frac{\overline x_i}{\alpha_{is}} : \alpha_{is} > 0 \right \}.$$
Consideremos el sistema de columnas $B' = (B \textrm{\\} \{a_r\}) \cup \{a_s \}$. Entonces $B'$ es una base y el punto $\overline x' = (\overline x_{B'}^T, 0_{n-m}^T)^T$, con $\overline x'_{B'} = (B')^{-1}b$, es una SBP asociada a $B'$ tal que
$$c^T \overline x' \le c^T \overline x.$$
Si, además, $\overline x$ era no degenerada, entonces la desigualdad es estricta.
Reverso: Para cada $\xi \ge 0$ sea $x^\xi = ((x^\xi_B)^T, (x_N^\xi)^T)^T \in \mathbb R^n$ el punto definido por
$$x_s^\xi := \xi, \quad x_j^\xi := 0, \, \forall j \in \mathcal J_n \textrm{\\} \{s\}, \quad x^\xi_B := \overline x_B - B^{-1}Nx_N^\xi.$$

Por construcción se tiene que $x_N^\xi \ge 0_{n-m}$ y $Ax^\xi = b$. Si analizamos la expresión de las componentes básicas de $x^\xi$ observamos que
$$(*) \quad x_i^\xi = \overline x_i - \sum_{j \in \mathcal J_N} \alpha_{ij} x_j^\xi = \overline x_i - \alpha_{is} \xi, \quad \forall i \in \mathcal J_B.$$
Por otra parte, razonando como en el [[criterio de optimalidad]], donde se obtiene que $z = \overline z + \sum_{j \in \mathcal J_N} \overline c_j x_j$, entonces obtenemos que
$$(**) \quad c^T x^\xi = c^T \overline x + \sum_{j \in \mathcal J_N} \overline c_j x_j^\xi = c^T \overline x + \overline c_s \xi.$$

$(i)$.
Si $\alpha_{is} \le 0$, $\forall i \in \mathcal J_B$, en vista de $(*)$ tenemos que $x_B^\xi \ge 0_m$, $\forall \xi > 0$. Podemos tomar entonces límites cuando $\xi \to +\infty$ en $(**)$ y hacer el objetivo todo lo pequeño que queramos. Por tanto, $v(P) = -\infty$ y el problema es no acotado.


$(ii)$. Supongamos ahora que existe al menos un $\alpha_{is} > 0$ para algún $i \in \mathcal J_B$ y tomemos
$$\overline x' = x^{\xi_0}; \quad \xi_0 := \frac{\overline x_r}{\alpha_{rs}} \ge 0.$$

Sustituyendo en $(*)$ llegamos a
$$\overline x_i' = \overline x_i - \alpha_{is} \frac{\overline x_r}{\alpha_{rs}}, \quad \forall i \in \mathcal J_B.$$
Probaremos que $\overline x_i' \ge 0, \, \forall i \in \mathcal J_B$. Para ello, distinguiremos dos casos:
- Si $i \in \mathcal J_B$ es tal que $\alpha_{is} \le 0$ la conclusión es trivial.
- Si $i \in \mathcal J_B$ es tal que $\alpha_{is} > 0$ entonces, por definición de $r$ en la hipótesis, obtenemos que
$$(***) \quad \overline x_i' = \overline x_i - \alpha_{is} \frac{\overline x_r}{\alpha_{rs}} \ge \overline x_i - \alpha_{is} \frac{\overline x_i}{\alpha_{is}} = 0.$$

Tenemos entonces que $\overline x'$ es una solución factible de $(P)$. Además, como $\overline c_s < 0$ y $\xi_0 \ge 0$, de $(**)$ se deduce
$$c^T \overline x' \le c^T \overline x.$$
Si $\overline x$ es no degenerada podemos asegurar que $\xi_0 > 0$, por lo que la desigualdad anterior sería estricta.

Probaremos ahora que $B'$ forma una base. Sea $\lambda_i \in \mathbb R$, para cada $i \in \mathcal J_B'$, tal que
$$0_m = \sum_{i \in \mathcal J_{B'}} \lambda_i a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{r\}} \lambda_i a_i + \lambda_s a_s.$$
Como $B^{-1} a_s = \alpha_s$, entonces $a_s = B\alpha_s = \sum_{i \in \mathcal J_B} \alpha_{is} a_i$ y sustituyendo en la expresión anterior obtenemos
$$0_m = \sum_{i \in \mathcal J_B \textrm{\\} \{r\} } \lambda_i a_i + \lambda_s \sum_{i \in \mathcal J_B} \alpha_{is} a_i = \sum_{i \in \mathcal J_B \textrm{\\} \{ r \} } (\lambda_i + \lambda_s \alpha_{is})a_i + (\lambda_s \alpha_{rs}) a_r.$$
Como $B$ es base, de la ecuación anterior se deriva que
$$\lambda_s \alpha_{rs} = 0, \quad \lambda_i + \lambda_s \alpha_{is} = 0, \, \forall i \in \mathcal J_B \textrm{\\} \{r\}.$$
Como $\alpha_{rs} \neq 0$, se tiene que $\lambda_s = 0$ y, consecuentemente, $\lambda_i = 0$ para todo $i \in \mathcal J_B \textrm{\\} \{r\}$. Queda así demostrado que las columnas de $B'$ son linealmente independientes y, por tanto, $B'$ es base.

Solo falta probar que $\overline x'$ es SBP asociada a $B'$. Para ello consideremos la descomposición $\overline x' = ((\overline x_{B'}')^T, (\overline x_{N'}')^T)^T$. Como ya sabemos que $\overline x'$ es factible, basta comprobar que $\overline x_{N'}' = 0_{n-m}$. En efecto, por construcción se teine que
$$\overline x_j' = 0, \quad \forall j \in \mathcal J_N \textrm{\\} \{s\}.$$

Además, podemos comprobar en $(***)$ que $\overline x_r' = 0$. Como $\mathcal J_{N'} = (\mathcal J_N \textrm{\\} \{s\}) \cup \{r\}$ llegamos al resultado deseado.
Tags: dem prm
<!--ID: 1728138052319-->
END
