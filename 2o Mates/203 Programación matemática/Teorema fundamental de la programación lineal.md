### Contenido Principal


```ad-theorem
Supongamos que el [[problema de PL en formato estándar]] $(P)$ tiene un conjunto factible no vacío $\mathcal F \neq \emptyset$. Entonces,
$$(P) \textrm{ tiene una solución óptima } \iff c^T \overline d \ge 0 , \quad \forall \overline d \textrm{ dirección extrema de } \mathcal F.$$
[[solución óptima]], [[dirección extrema]].

En ese caso, $(P)$ tiene una [[solución óptima]] en un [[punto extremo]] de $\mathcal F$. Si existen varios puntos extremos óptimos, entonces el conjunto de soluciones óptimas del problema es la [[envoltura convexa]] de todos ellos.
```

```ad-proof
Como $\mathcal F$ es un poliedro no vacío, podemos aplicar el [[teorema de representación de poliedros]] y reescribir $(P)$ como
$$
\begin{matrix*}[c c l]
(P') & \textrm{Min} & \sum_{i = 1}^k \lambda_i(c^T \overline x_i) + \sum_{j = 1}^l \mu_j (c^T \overline d_j) \\
& \textrm{s.a.} & \sum_{i = 1}^k \lambda_i = 1, \\
& & \lambda_i \ge 0, \, \forall i = 1, \dots, k, \\
& & \mu_j \ge 0, \, \forall j = 1, \dots, l;
\end{matrix*}
$$
donde $\overline x_1, \dots, \overline x_k \in \mathcal F$ y $\overline d_1, \dots, \overline d_l \in \mathbb R^n$ son, respectivamente, los puntos extremos y las direcciones extremas de $\mathcal F$. Supongamos primero que $\exists j_0 \in \{1, \dots, l\}$ tal que $c^T \overline d_{j0} < 0$. Entonces
$$v(P) \le \lim_{\mu_{j0} \to +\infty} \left ( \sum_{i = 1}^k \lambda_i (c^T \overline x_i) + \sum_{j = 1}^l \mu_j (c^T \overline d_j) \right ) = -\infty,$$
por lo que $(P')$, y por tanto $(P)$, sería no acotado. En cambio, si $c^T \overline d_j \ge 0$ para todo $j = 1, \dots, l$, se cumple que
$$\sum_{i = 1}^k \lambda_i (c^T \overline x_i) + \sum_{j = 1}^l \mu_j (c^T \overline d_j) \ge  \sum_{i = 1}^k \lambda_i (c^T \overline x_i) \ge \sum_{i = 1}^k \lambda_i (c^T \overline x_{i0}) = c^T \overline x_{i0},$$
donde $i_0 \in \hat{\mathcal I} := \textrm{argmin}_{i = 1, \dots, k} \{c^T \overline x_i\}$ (es decir, $c^T \overline x_{i0} = \min_{i = 1, \dots, k} \{c^T \overline x_i\})$. Esto implica que la función objetivo de $(P')$ está acotada inferiormente (en el conjunto factible), y por tanto el problema tiene al menos una solución óptima. De hecho, tomando
$$\lambda_{i0} := 1, \quad \lambda_i := 0, \, \forall i \neq i_0, \quad \mu_j := 0, \, \forall j = 1, \dots, l,$$
obtenemos el punto extremo $\overline x_{i0} \in \mathcal F$ que alcanza la cota de la ecuación de antes; esto es, $\overline x_{i0}$ es una [[solución óptima]] del problema. Por último, supongamos que $i_0$ no es único, es decir, que $\hat{\mathcal I}$ contiene más de un índice. Es fácil comprobar que los puntos de
$$\textrm{conv}_{i \in \hat{\mathcal I}} \{\overline x_i\} = \left \{ \sum_{i \in  \hat{\mathcal I}} \lambda_i \overline x_i \, | \, \sum_{i \in \hat{\mathcal I}} \lambda_i = 1, \, \lambda_i \ge 0, \forall i \in \hat{\mathcal I} \right \}.$$
son los únicos puntos factibles que alcanzan la cota y, por tanto, forman el conjunto de soluciones óptimas.
```

**Tema:** [[Modelo de programación lineal#3. Identificación analítica de soluciones.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema fundamental de la programación  lineal?
Reverso: Supongamos que el [[problema de PL en formato estándar]] $(P)$ tiene un conjunto factible no vacío $\mathcal F \neq \emptyset$. Entonces,
$$(P) \textrm{ tiene una solución óptima } \iff c^T \overline d \ge 0 , \quad \forall \overline d \textrm{ dirección extrema de } \mathcal F.$$
[[solución óptima]], [[dirección extrema]].

En ese caso, $(P)$ tiene una [[solución óptima]] en un [[punto extremo]] de $\mathcal F$. Si exsten varios puntos extremos óptimos, entonces el conjunto de soluciones óptimas del problema es la [[envoltura convexa]] de todos ellos.
Tags:
<!--ID: 1727083427956-->
END

START
Básico
Anverso: Demostración de que supongamos que el [[problema de PL en formato estándar]] $(P)$ tiene un conjunto factible no vacío $\mathcal F \neq \emptyset$. Entonces,
$$(P) \textrm{ tiene una solución óptima } \iff c^T \overline d \ge 0 , \quad \forall \overline d \textrm{ dirección extrema de } \mathcal F.$$
[[solución óptima]], [[dirección extrema]].

En ese caso, $(P)$ tiene una [[solución óptima]] en un [[punto extremo]] de $\mathcal F$. Si exsten varios puntos extremos óptimos, entonces el conjunto de soluciones óptimas del problema es la [[envoltura convexa]] de todos ellos.
Reverso: Como $\mathcal F$ es un poliedro no vacío, podemos aplicar el [[teorema de representación de poliedros]] y reescribir $(P)$ como
$$
\begin{matrix*}[c c l]
(P') & \textrm{Min} & \sum_{i = 1}^k \lambda_i(c^T \overline x_i) + \sum_{j = 1}^l \mu_j (c^T \overline d_j) \\
& \textrm{s.a.} & \sum_{i = 1}^k \lambda_i = 1, \\
& & \lambda_i \ge 0, \, \forall i = 1, \dots, k, \\
& & \mu_j \ge 0, \, \forall j = 1, \dots, l;
\end{matrix*}
$$
donde $\overline x_1, \dots, \overline x_k \in \mathcal F$ y $\overline d_1, \dots, \overline d_l \in \mathbb R^n$ son, respectivamente, los puntos extremos y las direcciones extremas de $\mathcal F$. Supongamos primero que $\exists j_0 \in \{1, \dots, l\}$ tal que $c^T \overline d_{j0} < 0$. Entonces
$$v(P) \le \lim_{\mu_{j0} \to +\infty} \left ( \sum_{i = 1}^k \lambda_i (c^T \overline x_i) + \sum_{j = 1}^l \mu_j (c^T \overline d_j) \right ) = -\infty,$$
por lo que $(P')$, y por tanto $(P)$, sería no acotado. En cambio, si $c^T \overline d_j \ge 0$ para todo $j = 1, \dots, l$, se cumple que
$$\sum_{i = 1}^k \lambda_i (c^T \overline x_i) + \sum_{j = 1}^l \mu_j (c^T \overline d_j) \ge  \sum_{i = 1}^k \lambda_i (c^T \overline x_i) \ge \sum_{i = 1}^k \lambda_i (c^T \overline x_{i0}) = c^T \overline x_{i0},$$
donde $i_0 \in \hat{\mathcal I} := \textrm{argmin}_{i = 1, \dots, k} \{c^T \overline x_i\}$ (es decir, $c^T \overline x_{i0} = \min_{i = 1, \dots, k} \{c^T \overline x_i\})$. Esto implica que la función objetivo de $(P')$ está acotada inferiormente (en el conjunto factible), y por tanto el problema tiene al menos una solución óptima. De hecho, tomando
$$\lambda_{i0} := 1, \quad \lambda_i := 0, \, \forall i \neq i_0, \quad \mu_j := 0, \, \forall j = 1, \dots, l,$$
obtenemos el punto extremo $\overline x_{i0} \in \mathcal F$ que alcanza la cota de la ecuación de antes; esto es, $\overline x_{i0}$ es una [[solución óptima]] del problema. Por último, supongamos que $i_0$ no es único, es decir, que $\hat{\mathcal I}$ contiene más de un índice. Es fácil comprobar que los puntos de
$$\textrm{conv}_{i \in \hat{\mathcal I}} \{\overline x_i\} = \left \{ \sum_{i \in  \hat{\mathcal I}} \lambda_i \overline x_i \, | \, \sum_{i \in \hat{\mathcal I}} \lambda_i = 1, \, \lambda_i \ge 0, \forall i \in \hat{\mathcal I} \right \}.$$
son los únicos puntos factibles que alcanzan la cota y, por tanto, forman el conjunto de soluciones óptimas.
Tags: prm dem
<!--ID: 1727083427958-->
END