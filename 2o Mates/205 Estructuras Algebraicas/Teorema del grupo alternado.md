### Contenido Principal

```ad-theorem
Sea $n \ge 2$. Entonces:
1. $A_n \le S_n$.
2. $|S_n: A_n| = 2$.

Por tanto, $A_n \unlhd S_n$ y $|A_n| = \frac{n!}{2}$.
```

^246449

```ad-proof

Veamos perimero que $A_n \le S_n$. Como $\textrm{id} = (1,2) \circ (1,2)$, entonces $\textrm{id} \in A_n$. Sean $\sigma, \tau \in A_n$. Demostramos que $\sigma \circ \tau^{-1} \in A_n$. Sabemos que $\exists t_1, t_2, \dots, t_{2r} \in S_n$ transposiciones tales que $\sigma = t_1 \circ \dots t_{2r}$. Por otra parte, $\exists t_1', \dots, t_{2s}' \in S_n$ transposiciones tales que $\tau = t_1' \circ \dots \circ t_{2s}'$. Combinando, tenemos:
$$\begin{eqnarray}
\sigma \circ \tau^{-1} &=& (t_1 \circ \dots \circ t_{2r}) \circ (t_1' \circ \dots t_{2s}')^{-1} = t_1 \circ \dots \circ t_{2r} \circ (t_{2s}')^{-1} \circ \dots \circ (t_1')^{-1} \\
&=& t_1 \circ \dots \circ t_{2r} \circ t_{2s}' \circ \dots \circ t_1' \in A_n
\end{eqnarray}$$
Luego por la [[caracterización de subgrupo]], $\sigma \circ \tau^{-1} \in A_n$.

Veamos ahora que $|S_n : A_n| = 2$. Sea $t \in S_n$ una transposición. Demostramos que $\mathcal L_{A_n} = \{A_n, tA_n \}$. En particular, demostramos que $tA_n = S_n \textrm{\\} A_n = \{\textrm{impares} \}$.
$\subseteq$. Evidente.
$\supseteq$. Sea $\sigma \in S_n \textrm{\\} A_n$, esto es, $\sigma$ es impar. Entonces,  $\exists t_1, t_2, \dots, t_{2r+1} \in S_n$ transposiciones tales que
$$\sigma = t_1 \circ t_2 \circ \dots \circ t_{2r+1} = t \circ t \circ t_1 \circ \dots \circ t_{2r+1} \in tA_n,$$
dado que $t \circ t_1 \circ \dots \circ t_{2r+1} \in A_n$.
```

**Tema:** [[Teoría de grupos#13. El grupo alternado $A_n$.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Teorema del grupo alternado
Reverso: Sea $n \ge 2$. Entonces:
1. $A_n \le S_n$.
2. $|S_n: A_n| = 2$.

Por tanto, $A_n \unlhd S_n$ y $|A_n| = \frac{n!}{2}$.
Tags: est
<!--ID: 1729160606387-->
END

START
Básico
Anverso: Demostración de que sea $n \ge 2$. Entonces:
1. $A_n \le S_n$.
2. $|S_n: A_n| = 2$.

Por tanto, $A_n \unlhd S_n$ y $|A_n| = \frac{n!}{2}$.
Reverso: Veamos perimero que $A_n \le S_n$. Como $\textrm{id} = (1,2) \circ (1,2)$, entonces $\textrm{id} \in A_n$. Sean $\sigma, \tau \in A_n$. Demostramos que $\sigma \circ \tau^{-1} \in A_n$. Sabemos que $\exists t_1, t_2, \dots, t_{2r} \in S_n$ transposiciones tales que $\sigma = t_1 \circ \dots t_{2r}$. Por otra parte, $\exists t_1', \dots, t_{2s}' \in S_n$ transposiciones tales que $\tau = t_1' \circ \dots \circ t_{2s}'$. Combinando, tenemos:
$$\begin{eqnarray}
\sigma \circ \tau^{-1} &=& (t_1 \circ \dots \circ t_{2r}) \circ (t_1' \circ \dots t_{2s}')^{-1} = t_1 \circ \dots \circ t_{2r} \circ (t_{2s}')^{-1} \circ \dots \circ (t_1')^{-1} \\
&=& t_1 \circ \dots \circ t_{2r} \circ t_{2s}' \circ \dots \circ t_1' \in A_n
\end{eqnarray}$$
Luego por la [[caracterización de subgrupo]], $\sigma \circ \tau^{-1} \in A_n$.

Veamos ahora que $|S_n : A_n| = 2$. Sea $t \in S_n$ una transposición. Demostramos que $\mathcal L_{A_n} = \{A_n, tA_n \}$. En particular, demostramos que $tA_n = S_n \textrm{\\} A_n = \{\textrm{impares} \}$.
$\subseteq$. Evidente.
$\supseteq$. Sea $\sigma \in S_n \textrm{\\} A_n$, esto es, $\sigma$ es impar. Entonces,  $\exists t_1, t_2, \dots, t_{2r+1} \in S_n$ transposiciones tales que
$$\sigma = t_1 \circ t_2 \circ \dots \circ t_{2r+1} = t \circ t \circ t_1 \circ \dots \circ t_{2r+1} \in tA_n,$$
dado que $t \circ t_1 \circ \dots \circ t_{2r+1} \in A_n$.
Tags: dem est
<!--ID: 1729160606391-->
END
