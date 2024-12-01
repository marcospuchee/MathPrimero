### Contenido Principal

```ad-proposition
Supongamos que el problema $(P)$ admite una solución óptima no degerada y supongamos que perturbamos los términos independientes de las restricciones del problema:
$$\begin{array}{c c l}
(\tilde P_b) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax \ge b + \Delta, \\
& & x \ge 0_n.
\end{array}$$
Si las componentes de $\Delta \in \mathbb R^m$ son suficientemente pequeñas, entonces
$$v(\tilde P_b) = v(P) + (w^*)^T \Delta,$$
donde $w^*$ es la solución óptima del dual $(D)$.
```

```ad-note
Podemos interpretar, por tanto, las componentes de la solución óptima dual como
$$\frac{\partial v(P)}{\partial b_i} = w_i^*, \quad i = 1, \dots, m.$$
Llamamos precio dual (o precio sombra) de la restricción $i$-ésima a $w_i^*$, que se interpreta como la tasa de cambio del valor del problema cuando cambia el coeficiente $b_i$.
```

```ad-note
Consideremos que $x_{j_i}$ es la variable de holgura de la restricción $i$ (de tipo "$\le$"), para algún $i \in \{1,2, \dots, m \}$. Entonces, su columna del sistema (en formato estándar) será $a_{j_i} = e_i = (0, \dots, 0,1,0, \dots, 0)^T \in \mathbb R^m$, donde $e_i$ es el vector canónico que tiene un $1$ en la posición $i$ y ceros en el resto. Podemos comprobar que
$$\overline c_{j_i} = c_{j_i} - c_B^T B^{-1}a_{j_i} = 0 - (w^*)^T e_i = -w_i^* \implies w_i^* = - \overline c_{j_i}.$$
Si la restricción $i$-ésima es de tipo "$\ge$" entonces obtendríamos $w_i^* = \overline c_{j_i}$.
```

```ad-proof
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T$ una SBP óptima de $(P)$ no degenerada asociada a la base $B$, es decir, $\overline x_B = B^{-1}b > 0_m$. Para $\Delta$ suficientemente pequeño podemos garantizar que
$$B^{-1}(b+\Delta) = B^{-1}b + B^{-1} \Delta \ge 0_m.$$
Tenemos entonces que $\tilde x := (\tilde x_B^T, 0_{n-m}^T)^T$ con $\tilde x_B = B^{-1}(b + \Delta)$ es SBP para $(\tilde P_b)$. Además, como los costes reducidos no se ven afectados por los términos independientes de las restricciones, $\tilde x$ es SBP óptima de $(\tilde P_b)$. Entonces
$$v(\tilde P_b) = c^T\tilde x = c_B^T B^{-1}(b+\Delta) = c_B^T B^{-1}b + c_B^T B^{-1} \Delta = v(P) + (w^*)^T \Delta,$$
donde la última igualdad viene del hecho que $w^* := (B^T)^{-1}c_B \in \mathbb R^m$ es solución óptima de $(D)$, por la observación del teorema de dualidad fuerte.
```

**Tema:** [[Dualidad y análisis de sensibilidad#2. Relaciones primal-dual.]]

**Definiciones referenciadas:** [[Solución óptima]], [[Problema dual]], [[Coste reducido]], [[Solución básica posible]]
**Resultados referenciados:** [[Teorema de Dualidad Fuerte]], [[Relación primal-dual de soluciones básicas]].

---
### Anki

START
Básico
Anverso: Cómo cambia el valor de un problema con la perturbación del vector $b$?
Reverso: Supongamos que el problema $(P)$ admite una solución óptima no degerada y supongamos que perturbamos los términos independientes de las restricciones del problema:
$$\begin{array}{c c l}
(\tilde P_b) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax \ge b + \Delta, \\
& & x \ge 0_n.
\end{array}$$
Si las componentes de $\Delta \in \mathbb R^m$ son suficientemente pequeñas, entonces
$$v(\tilde P_b) = v(P) + (w^*)^T \Delta,$$
donde $w^*$ es la solución óptima del dual $(D)$.
Tags: prm
<!--ID: 1733051328674-->
END

START
Básico
Anverso: Demostración de que supongamos que el problema $(P)$ admite una solución óptima no degerada y supongamos que perturbamos los términos independientes de las restricciones del problema:
$$\begin{array}{c c l}
(\tilde P_b) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax \ge b + \Delta, \\
& & x \ge 0_n.
\end{array}$$
Si las componentes de $\Delta \in \mathbb R^m$ son suficientemente pequeñas, entonces
$$v(\tilde P_b) = v(P) + (w^*)^T \Delta,$$
donde $w^*$ es la solución óptima del dual $(D)$.
Reverso: Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T$ una SBP óptima de $(P)$ no degenerada asociada a la base $B$, es decir, $\overline x_B = B^{-1}b > 0_m$. Para $\Delta$ suficientemente pequeño podemos garantizar que
$$B^{-1}(b+\Delta) = B^{-1}b + B^{-1} \Delta \ge 0_m.$$
Tenemos entonces que $\tilde x := (\tilde x_B^T, 0_{n-m}^T)^T$ con $\tilde x_B = B^{-1}(b + \Delta)$ es SBP para $(\tilde P_b)$. Además, como los costes reducidos no se ven afectados por los términos independientes de las restricciones, $\tilde x$ es SBP óptima de $(\tilde P_b)$. Entonces
$$v(\tilde P_b) = c^T\tilde x = c_B^T B^{-1}(b+\Delta) = c_B^T B^{-1}b + c_B^T B^{-1} \Delta = v(P) + (w^*)^T \Delta,$$
donde la última igualdad viene del hecho que $w^* := (B^T)^{-1}c_B \in \mathbb R^m$ es solución óptima de $(D)$, por la observación del teorema de dualidad fuerte.
Tags: dem prm
<!--ID: 1733051328677-->
END

START
Básico
Anverso: Interpretación solución óptima problema dual
Reverso: Podemos interpretar, por tanto, las componentes de la solución óptima dual como
$$\frac{\partial v(P)}{\partial b_i} = w_i^*, \quad i = 1, \dots, m.$$
Llamamos precio dual (o precio sombra) de la restricción $i$-ésima a $w_i^*$, que se interpreta como la tasa de cambio del valor del problema cuando cambia el coeficiente $b_i$.
Tags: prm
<!--ID: 1733051328679-->
END

START
Básico
Anverso: Relación precio dual con coste reducido
Reverso: Consideremos que $x_{j_i}$ es la variable de holgura de la restricción $i$ (de tipo "$\le$), para algún $i \in \{1,2, \dots, m \}$. Entonces, su columna del sistema (en formato estándar) será $a_{j_i} = e_i = (0, \dots, 0,1,0, \dots, 0)^T \in \mathbb R^m$, donde $e_i$ es el vector canónico que tiene un $1$ en la posición $i$ y ceros en el resto. Podemos comprobar que
$$\overline c_{j_i} = c_{j_i} - c_B^T B^{-1}a_{j_i} = 0 - (w^*)^T e_i = -w_i^* \implies w_i^* = - \overline c_{j_i}.$$
Si la restricción $i$-ésima es de tipo "$\ge$" entonces obtendríamos $w_i^* = \overline c_{j_i}$.
Tags: prm
<!--ID: 1733051328682-->
END

