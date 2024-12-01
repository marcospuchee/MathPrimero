### Contenido principal

```ad-Formal
Supongamos que queremos añadir a $(P)$ una nueva variable $x_{n+1}$, con coste $c_{n+1}$ y vector de coeficientes en las restricciones $a_{n+1} \in \mathbb R^m$. Planteamos por tanto el problema
$$\begin{array}{c c l}
(P_{n+1}') & \textrm{Min} & (c^t, c_{n+1}) \begin{pmatrix} x \\ x_{n+1} \end{pmatrix} \\
& \textrm{s.a.} & [A \quad a_{n+1}] \begin{pmatrix} x \\ x_{n+1} \end{pmatrix} = b, \\
& & x \ge 0_n, \, \, x_{n+1} \ge 0
\end{array}$$
Sea $B$ la base óptima del problema original. Si el coste reducido de la variable $\overline c_{n+1} \ge 0$, la base es óptima. En otro caso, $x_{n+1}$ entra en la base.
```

**Tema:** [[203 Programación matemática#4. Análisis de sensibilidad]]

**Definiciones referenciadas:** -.

---
### Anki

START
Básico
Anverso: Análisis de sensbilidad con la adición de una nueva variable
Reverso: Supongamos que queremos añadir a $(P)$ una nueva variable $x_{n+1}$, con coste $c_{n+1}$ y vector de coeficientes en las restricciones $a_{n+1} \in \mathbb R^m$. Planteamos por tanto el problema
$$\begin{array}{c c l}
(P_{n+1}') & \textrm{Min} & (c^t, c_{n+1}) \begin{pmatrix} x \\ x_{n+1} \end{pmatrix} \\
& \textrm{s.a.} & [A \quad a_{n+1}] \begin{pmatrix} x \\ x_{n+1} \end{pmatrix} = b, \\
& & x \ge 0_n, \, \, x_{n+1} \ge 0
\end{array}$$
Sea $B$ la base óptima del problema original. Si el coste reducido de la variable $\overline c_{n+1} \ge 0$, la base es óptima. En otro caso, $x_{n+1}$ entra en la base.
Tags: prm
<!--ID: 1733051328696-->
END
