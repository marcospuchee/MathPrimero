### Contenido principal

```ad-Formal
Consideramos el problema
$$\begin{array}{c c l}
(P_c') & \textrm{Min} & (c')^Tx \\
& \textrm{s.a.} & Ax = b, \\
& & x \ge 0_n;
\end{array}$$
donde $c' := c + \Delta e_j$, con $\Delta \in \mathbb R$. Es decir, $(P_c')$ equivalen al problema $(P)$, donde hemos perturbado el coste de una, y solo una, de las variables. Distinguiremos dos casos dependiendo de si el coste perturbado corresponde a una variable básica o a una no básica.
- Variable no básica.
$$c_s' := c_s + \Delta \quad (s \in \mathcal J_N) \, \, \land \, \, c_j' := c_j, \, \, \forall j \in \mathcal J \textrm{\\}\{s\}.$$
solo cambia el coste reducido de la variable $x_s$. Por tanto,
	- Debemos incluir el nuevo valor del coste reducido en la tabla óptima.
	- Si dicho valor es no negativo, la base $B$ y la SBP siguen siendo óptimas. En otro caso, debemos introducir $x_s$ en la base y pivotar.
- Variable básica.
$$c_r' := c_r + \Delta \quad (r \in \mathcal J_B) \, \, \land \, \, c_j' := c_j, \, \forall j \in \mathcal J \textrm{\\} \{r \},$$
podrían cambiar todos los costes reducidos de las variables no básicas. Por tanto,
	- Debemos incluir los valores actualizados de los costes reducidos en la tabla óptima.
	- Si todos son no negativos, la base $B$ y la SBP siguen siendo óptimas. En otro caso, debemos introducir la variable no básica más prometedora en la base y pivotar.
```

**Tema:** [[203 Programación matemática#4. Análisis de sensibilidad]]

**Definiciones referenciadas:** -.

---
### Anki

START
Básico
Anverso: Análisis de sensiblidad con un cambio en el vector de costes
Reverso: Consideramos el problema
$$\begin{array}{c c l}
(P_c') & \textrm{Min} & (c')^Tx \\
& \textrm{s.a.} & Ax = b, \\
& & x \ge 0_n;
\end{array}$$
donde $c' := c + \Delta e_j$, con $\Delta \in \mathbb R$. Es decir, $(P_c')$ equivalen al problema $(P)$, donde hemos perturbado el coste de una, y solo una, de las variables. Distinguiremos dos casos dependiendo de si el coste perturbado corresponde a una variable básica o a una no básica.
- Variable no básica.
$$c_s' := c_s + \Delta \quad (s \in \mathcal J_N) \, \, \land \, \, c_j' := c_j, \, \, \forall j \in \mathcal J \textrm{\\}\{s\}.$$
solo cambia el coste reducido de la variable $x_s$. Por tanto,
	- Debemos incluir el nuevo valor del coste reducido en la tabla óptima.
	- Si dicho valor es no negativo, la base $B$ y la SBP siguen siendo óptimas. En otro caso, debemos introducir $x_s$ en la base y pivotar.
- Variable básica.
$$c_r' := c_r + \Delta \quad (r \in \mathcal J_B) \, \, \land \, \, c_j' := c_j, \, \forall j \in \mathcal J \textrm{\\} \{r \},$$
podrían cambiar todos los costes reducidos de las variables no básicas. Por tanto,
	- Debemos incluir los valores actualizados de los costes reducidos en la tabla óptima.
	- Si todos son no negativos, la base $B$ y la SBP siguen siendo óptimas. En otro caso, debemos introducir la variable no básica más prometedora en la base y pivotar.
Tags: prm
<!--ID: 1733051328693-->
END
