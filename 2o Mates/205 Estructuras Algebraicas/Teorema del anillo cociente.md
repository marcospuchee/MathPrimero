### Contenido Principal

```ad-theorem
Sea $R$ un anillo e $I \subseteq R$ un ideal. Entonces el conjunto cociente $R/I = \{x+I : x \in R \}$ tiene estructura de anillo con la suma y el producto definidos como
$$\begin{array}{c c c}

\begin{array}{c c c l}
+: & R/I \times R/I & \to & R/I \\
& (r+I,s+I) & \mapsto & (r+s)+I
\end{array}

& \quad &

\begin{array}{c c c l}
\cdot: & R/I \times R/I & \to & R/I \\
&(r+I, s+I) & \mapsto & (rs)+I
\end{array}

\end{array}$$
llamado el anillo cociente de $R$ sobre $I$. Además,
1. $R$ conmutativo $\implies R/I$ conmutativo.
2. $1_R$ identidad de $R$ $\implies$ $1_{R/I} = 1_R + I$ identidad de $R/I$.
```

```ad-proof
Que $(R/I, +)$ es grupo abeliano, se tiene del teorema del grupo cociente.

Todas las demás propiedades (asociatividad, distributividad, $(1)$, $(2)$) se deducen de las propiedades de $R$.

Sólo queda demostrar que $\cdot$ está bien definido. Sean $r_1+I$ $=$ $r_2+I$, $s_1+I$ $=$ $s_2+I$. Demostramos que $(r_1s_1)+I=(r_2s_2)+I$. Por las propiedades de las coclases, sabemos que $r_1+I = r_2+I \iff r_1-r_2 \in I$, análogamente, $s_1+I = s_2+I$ $\iff$ $s_1-s_2 \in I$. Queremos ver que $r_1s_1 - r_2s_2 \in I$. Para ello,
$$\begin{eqnarray}
r_1s_1 - r_2 s_2 &=& r_1 s_1 - r_1 s_2 + r_1s_2 - r_2s_2 \\
&=& r_1(s_1-s_2)+(r_1-r_2)s_2 \in I,
\end{eqnarray}$$
dado que $(s_1-s_2), (r_1-r_2) \in I \implies r_1(s_1-s_2), (r_1-r_2)s_2 \in I$. Y, por tanto,$r_1s_1 + I = r_2s_2 + I$.
```

 **Tema:** [[Anillo de polinomios#3. Ideales y anillos cociente.]]

**Definiciones referenciadas:** [[Anillo]], [[Ideal]], [[Anillo conmutativo]], [[Coclase]]
**Resultados referenciados:** [Teorema del grupo cociente](Grupo cociente), [[Propiedades coclases]]

---
### Anki

START
Básico
Anverso: Teorema del anillo cociente
Reverso: Sea $R$ un anillo e $I \subseteq R$ un ideal. Entonces el conjunto cociente $R/I = \{x+I : x \in R \}$ tiene estructura de anillo con la suma y el producto definidos como
$$\begin{array}{c c c}

\begin{array}{c c c l}
+: & R/I \times R/I & \to & R/I \\
& (r+I,s+I) & \mapsto & (r+s)+I
\end{array}

& \quad &

\begin{array}{c c c l}
\cdot: & R/I \times R/I & \to & R/I \\
&(r+I, s+I) & \mapsto & (rs)+I
\end{array}

\end{array}$$
llamado el anillo cociente de $R$ sobre $I$. Además,
1. $R$ conmutativo $\implies R/I$ conmutativo.
2. $1_R$ identidad de $R$ $\implies$ $1_{R/I} = 1_R + I$ identidad de $R/I$.
Tags: est
<!--ID: 1733312055975-->
END

START
Básico
Anverso: Demostración de que sea $R$ un anillo e $I \subseteq R$ un ideal. Entonces el conjunto cociente $R/I = \{x+I : x \in R \}$ tiene estructura de anillo con la suma y el producto definidos como
$$\begin{array}{c c c}

\begin{array}{c c c l}
+: & R/I \times R/I & \to & R/I \\
& (r+I,s+I) & \mapsto & (r+s)+I
\end{array}

& \quad &

\begin{array}{c c c l}
\cdot: & R/I \times R/I & \to & R/I \\
&(r+I, s+I) & \mapsto & (rs)+I
\end{array}

\end{array}$$
llamado el anillo cociente de $R$ sobre $I$. Además,
1. $R$ conmutativo $\implies R/I$ conmutativo.
2. $1_R$ identidad de $R$ $\implies$ $1_{R/I} = 1_R + I$ identidad de $R/I$.
Reverso: Que $(R/I, +)$ es grupo abeliano, se tiene del teorema del grupo cociente.

Todas las demás propiedades (asociatividad, distributividad, $(1)$, $(2)$) se deducen de las propiedades de $R$.

Sólo queda demostrar que $\cdot$ está bien definido. Sean $r_1+I$ $=$ $r_2+I$, $s_1+I$ $=$ $s_2+I$. Demostramos que $(r_1s_1)+I=(r_2s_2)+I$. Por las propiedades de las coclases, sabemos que $r_1+I = r_2+I \iff r_1-r_2 \in I$, análogamente, $s_1+I = s_2+I$ $\iff$ $s_1-s_2 \in I$. Queremos ver que $r_1s_1 - r_2s_2 \in I$. Para ello,
$$\begin{eqnarray}
r_1s_1 - r_2 s_2 &=& r_1 s_1 - r_1 s_2 + r_1s_2 - r_2s_2 \\
&=& r_1(s_1-s_2)+(r_1-r_2)s_2 \in I,
\end{eqnarray}$$
dado que $(s_1-s_2), (r_1-r_2) \in I \implies r_1(s_1-s_2), (r_1-r_2)s_2 \in I$. Y, por tanto,$r_1s_1 + I = r_2s_2 + I$.
Tags: dem est
<!--ID: 1733312055978-->
END

