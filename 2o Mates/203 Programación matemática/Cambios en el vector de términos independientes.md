### Contenido principal

```ad-Formal
Consideramos ahora el problema
$$\begin{array}{c c l}
(P_b') & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax = b', \\
& & x \ge 0;
\end{array}$$
donde $b' \in \mathbb R^m$. Si cambiamos el vector de términos independientes, la SB asociada a (la misma) base $B$ será
$$\overline x' = \begin{pmatrix} \overline x_B' \\ 0_m \end{pmatrix} \in \mathbb R^{m + (n-m)}; \quad \overline x_B' := B^{-1}b'.$$
Nótese que los costes reducidos no se ven afectados por este cambio, por lo que $\overline x'$ sigue siendo una SB primal-óptima. Por tanto, solo nos debemos preocupar de la factibilidad de la nueva solución. De no serlo, debemos iterar utilizando el método Dual-Simplex.
```


**Tema:** [[203 Programación matemática#4. Análisis de sensibilidad]]

**Definiciones referenciadas:** -.

---
### Anki
