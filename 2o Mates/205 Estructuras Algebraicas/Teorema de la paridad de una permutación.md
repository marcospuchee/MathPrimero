### Contenido Principal

```ad-theorem
Sea $\sigma \in S_n$ con
$$\sigma = t_1 \circ t_2 \circ \dots \circ t_r = t_1' \circ t_2' \circ \dots \circ t_s',$$
donde $t_1, t_2, \dots, t_r t_1', t_2', \dots, t_s' \in S_n$ son transposiciones. Entonces $r \equiv s \pmod 2$. Es decir, $r$ y $s$ tienen la misma paridad.
```

^d10534

```ad-proof
Notemos que si $(i,j) = t \in S_n$ es una transposición y $A \in GL(n, \mathbb R)$, entonces $|t(A)| = -|A|$. Por [[matriz permutada por una composición]] junto con lo que acabamos de ver, tenemos que
$$\begin{eqnarray}
|\sigma(A)| &=& |t_1 \circ t_2 \circ \dots \circ t_r(A)| = |t_1(t_2(\dots(t_r(A))\dots))| = -|t_2(\dots(t_r(A)\dots)) \\
&=& \dots = (-1)^r |A|
\end{eqnarray}$$
Por otro lado, por el mismo razonamiento, $|\sigma(A)| = \dots = (-1)^s |A|$. Así, $(-1)^r |A| = |\sigma(A)| = (-1)^s |A|$. En particular, si $A = I_n \in GL(n, \mathbb R)$, tenemos que $(-1)^r = (-1)^s$. Por tanto, $r \equiv s \pmod 2$.
```

**Tema:** [[Teoría de grupos#13. El grupo alternado $A_n$.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la paridad de una permutación
Reverso: Sea $\sigma \in S_n$ con
$$\sigma = t_1 \circ t_2 \circ \dots \circ t_r = t_1' \circ t_2' \circ \dots \circ t_s',$$
donde $t_1, t_2, \dots, t_r t_1', t_2', \dots, t_s' \in S_n$ son transposiciones. Entonces $r \equiv s \pmod 2$. Es decir, $r$ y $s$ tienen la misma paridad.
Tags: est
<!--ID: 1729160606396-->
END

START
Básico
Anverso: Demostración de que sea $\sigma \in S_n$ con
$$\sigma = t_1 \circ t_2 \circ \dots \circ t_r = t_1' \circ t_2' \circ \dots \circ t_s',$$
donde $t_1, t_2, \dots, t_r t_1', t_2', \dots, t_s' \in S_n$ son transposiciones. Entonces $r \equiv s \pmod 2$. Es decir, $r$ y $s$ tienen la misma paridad.
Reverso: Notemos que si $(i,j) = t \in S_n$ es una transposición y $A \in GL(n, \mathbb R)$, entonces $|t(A)| = -|A|$. Por [[Matriz permutada por una composición]] junto con lo que acabamos de ver, tenemos que
$$\begin{eqnarray}
|\sigma(A)| &=& |t_1 \circ t_2 \circ \dots \circ t_r(A)| = |t_1(t_2(\dots(t_r(A))\dots))| = -|t_2(\dots(t_r(A)\dots)) \\
&=& \dots = (-1)^r |A|
\end{eqnarray}$$
Por otro lado, por el mismo razonamiento, $|\sigma(A)| = \dots = (-1)^s |A|$. Así, $(-1)^r |A| = |\sigma(A)| = (-1)^s |A|$. En particular, si $A = I_n \in GL(n, \mathbb R)$, tenemos que $(-1)^r = (-1)^s$. Por tanto, $r \equiv s \pmod 2$.
Tags: dem est
<!--ID: 1729160606398-->
END
