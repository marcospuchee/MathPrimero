### Contenido Principal

```ad-lemma
El [[problema dual]] de $(D)$ es $(P)$.
```

```ad-proof
Primero escribimos $(D)$ como problema de minimización en formato canónico:
$$\begin{matrix*}[c c l]
(D) & -\textrm{Min} & (-b)^Tw \\
& \textrm{s.a.} & (-A^T)w \ge -c, \\
& & w \ge 0_m;
\end{matrix*}$$
Si ahora aplicamos la definición de dual al problema anterior, obtenemos
$$\begin{matrix*}[c c l]
(D_D) & -\textrm{Max} & (-c)^Tx \\
& \textrm{s.a.} & (-A^T)^Tx \le -b, \\
& & x \ge 0_n;
\end{matrix*}$$
que es equivalente a $(P)$.
```

**Tema:** [[Dualidad y análisis de sensibilidad#1. El problema dual.]]

---
### Anki

START
Básico
Anverso: Demostración de que el problema dual del dual es el primal
Reverso: Primero escribimos $(D)$ como problema de minimización en formato canónico:
$$\begin{matrix*}[c c l]
(D) & -\textrm{Min} & (-b)^Tw \\
& \textrm{s.a.} & (-A^T)w \ge -c, \\
& & w \ge 0_m;
\end{matrix*}$$
Si ahora aplicamos la definición de dual al problema anterior, obtenemos
$$\begin{matrix*}[c c l]
(D_D) & -\textrm{Max} & (-c)^Tx \\
& \textrm{s.a.} & (-A^T)^Tx \le -b, \\
& & x \ge 0_n;
\end{matrix*}$$
que es equivalente a $(P)$.
Tags: dem prm
<!--ID: 1728820185302-->
END