### Contenido Principal

```ad-proposition
Dado un problema en formato estándar $(P)$, definimos el siguiente problema:
$$\begin{matrix*}[c c l]
(\tilde P_a) & \textrm{Min} & 1_m^Tx_a \\
& \textrm{s.a.} & Ax + I_m x_a = b, \\
& & x \ge 0_n, x_a \ge 0_m
\end{matrix*}.$$
Este problema siempre se puede atacar con el método simplex empezando por la SBP $(0_n^T, b^T)^T$.

El problema $(\tilde P_a)$ tiene solución óptima. Sea $\tilde x^* = ((x^*)^T, (x^*_a)^T)^T \in \mathbb R^{n+m}$ una solución óptima. Entonces:
1. Si $x^*_a = 0_m$ entonces $x^*$ es una solución factible de $(P)$.
2. Si $x^*_a \neq 0_m$, entonces $(P)$ no es no factible.
```

```ad-proof
$(\tilde P_a)$ es factible pues $(0_n^T, b^T)^T$ es una [[solución básica posible]] del problema. Para probar que tiene solución óptima basta justificar que es acotado, lo cual se deduce del hecho de que estamos minimizando la suma de variables no negativas, por lo que la función objetivo está acotada inferiormente por $0$. El resto de implicaciones se deducen fácilmente. (EJERCICIO).
```

**Tema:** [[El método Simplex#4. Obtención de una base inicial.]]

---
### Anki

START
Básico
Anverso: Solución óptima de la fase I del método de las dos fases (prm)
Reverso: Dado un problema en formato estándar $(P)$, definimos el siguiente problema:
$$\begin{matrix*}[c c l]
(\tilde P_a) & \textrm{Min} & 1_m^Tx_a \\
& \textrm{s.a.} & Ax + I_m x_a = b, \\
& & x \ge 0_n, x_a \ge 0_m
\end{matrix*}.$$
Donde $x_a$ son variables artificiales. Este problema siempre se puede atacar con el método simplex empezando por la SBP $(0_n^T, b^T)^T$.

El problema $(\tilde P_a)$ tiene solución óptima. Sea $\tilde x^* = ((x^*)^T, (x^*_a)^T)^T \in \mathbb R^{n+m}$ una solución óptima. Entonces:
1. Si $x^*_a = 0_m$ entonces $x^*$ es una solución factible de $(P)$.
2. Si $x^*_a \neq 0_m$, entonces $(P)$ no es no factible.
Tags: prm
<!--ID: 1728549801471-->
END

