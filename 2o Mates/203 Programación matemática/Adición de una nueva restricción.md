### Contenido principal

```ad-Formal
Consdideramos el caso en el que queremos añadir a $(P)$ una nueva restricción
$$a^T x \le b_{m+1}; \quad a \in \mathbb R^n, \, b_{m+1} \in \mathbb R.$$
Este cambio conlleva la creación de una nueva variable de holgura $x_{n+1}$ para conseguir el formato estándar. El problema de interés queda de la siguiente forma:
$$\begin{array}{c c l}
(P_{m+1}') & \textrm{Min} & (c^T, 0) \begin{pmatrix} x \\ x_{n+1} \end{pmatrix} \\
& \textrm{s.a.} & \begin{bmatrix} A & 0_m \\ a^T & 1 \end{bmatrix} \begin{pmatrix} x \\ x_{n+1} \end{pmatrix} = \begin{pmatrix} b \\ b_{m+1} \end{pmatrix} \\
& & x \ge 0_n, \, \, x_{n+1} \ge 0.
\end{array}$$
Si la solución óptima original $\overline x$ satisface la nueva restricción, esto es, $a^T \overline x \le b_{m+1}$, la tabla óptima se obtiene introduciendo la nueva restricción (y variable) en la tabla Simplex y pivotando para recuperar la matriz identidad. En otro caso, además, debemos iterar utilizando el método Dual-Simplex.
```

**Tema:** [[203 Programación matemática#4. Análisis de sensibilidad]]

**Definiciones referenciadas:** -. 

---
### Anki
