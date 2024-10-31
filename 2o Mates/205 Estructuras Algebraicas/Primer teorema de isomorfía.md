### Contenido Principal

```ad-theorem
Sea $f: G \to H$. Entonces la aplicación
$$\begin{array}{c c c c}
f^b: & G/\textrm{Ker}(f) & \to & \textrm{Im}(f) \\
& x \textrm{Ker}(f) & \mapsto & f(x)
\end{array}$$
es un isomorfismo de grupos. En particular, $G / \textrm{Ker}(f) \cong \textrm{Im}(f)$.
```

^640dad

```ad-proof
Por 1.71 sabemos que $\textrm{Im}(f) \le H$ y por 1.82 sabemos que $\textrm{Ker}(f) \unlhd G$.

Sean $g_1, g_2 \in G$, tenemos que

$$\begin{eqnarray}
g_1 \textrm{Ker}(f) = g_2 \textrm{Ker}(f) &\iff& g_2^{-1}g_1 \in \textrm{Ker}(f) \iff f(g_2^{-1}g_1) = 1_H \\
&\iff& f(g_2)^{-1}f(g_1) = 1_H \iff f(g_1) = f(g_2) \\
&\iff& f^b(g_1\textrm{Ker}(f)) = f^b(g_2\textrm{Ker}(f)).
\end{eqnarray}.$$

Sin embargo, la implicación hacia la izquierda demuestra que $f^b$ es inyectiva, y la implicación hacia la derecha demuestra que $f^b$ está bien definida.

**Sobreyectiva:**
Sea $x \in \textrm{Im}(f)$, entonces $\exists g \in G$ tal que $x = f(g) = f^b(g\textrm{Ker}(f))$.

**Homomorfismo.**
Sean $g_1 \textrm{Ker}(f), g_2 \textrm{Ker}(f) \in G/\textrm{Ker}(f)$. Tenemos que
$$\begin{eqnarray}
f^b(g_1\textrm{Ker}(f) \cdot g_2 \textrm{Ker}(f)) &=& f^b (g_1 g_2 \textrm{Ker}(f)) = f(g_1 g_2) = f(g_1) f(g_2) \\ &=& f^b(g_1 \textrm{Ker}(f)) \cdot f^b(g_2 \textrm{Ker}(f)).
\end{eqnarray}$$
```

**Tema:** [[Teoría de grupos#15. Teoremas de isomorfía.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Primer teorema de isomorfía
Reverso: Sea $f: G \to H$. Entonces la aplicación
$$\begin{array}{c c c c}
f^b: & G/\textrm{Ker}(f) & \to & \textrm{Im}(f) \\
& x \textrm{Ker}(f) & \mapsto & f(x)
\end{array}$$
es un isomorfismo de grupos. En particular, $G / \textrm{Ker}(f) \cong \textrm{Im}(f)$.
Tags: est
<!--ID: 1730228001541-->
END

START
Básico
Anverso: Demostración de que sea $f: G \to H$. Entonces la aplicación
$$\begin{array}{c c c c}
f^b: & G/\textrm{Ker}(f) & \to & \textrm{Im}(f) \\
& x \textrm{Ker}(f) & \mapsto & f(x)
\end{array}$$
es un isomorfismo de grupos. En particular, $G / \textrm{Ker}(f) \cong \textrm{Im}(f)$.
Reverso: Por 1.71 sabemos que $\textrm{Im}(f) \le H$ y por 1.82 sabemos que $\textrm{Ker}(f) \unlhd G$.

Sean $g_1, g_2 \in G$, tenemos que

$$\begin{eqnarray}
g_1 \textrm{Ker}(f) = g_2 \textrm{Ker}(f) &\iff& g_2^{-1}g_1 \in \textrm{Ker}(f) \iff f(g_2^{-1}g_1) = 1_H \\
&\iff& f(g_2)^{-1}f(g_1) = 1_H \iff f(g_1) = f(g_2) \\
&\iff& f^b(g_1\textrm{Ker}(f)) = f^b(g_2\textrm{Ker}(f)).
\end{eqnarray}.$$

Sin embargo, la implicación hacia la izquierda demuestra que $f^b$ es inyectiva, y la implicación hacia la derecha demuestra que $f^b$ está bien definida.

**Sobreyectiva:**
Sea $x \in \textrm{Im}(f)$, entonces $\exists g \in G$ tal que $x = f(g) = f^b(g\textrm{Ker}(f))$.

**Homomorfismo.**
Sean $g_1 \textrm{Ker}(f), g_2 \textrm{Ker}(f) \in G/\textrm{Ker}(f)$. Tenemos que
$$\begin{eqnarray}
f^b(g_1\textrm{Ker}(f) \cdot g_2 \textrm{Ker}(f)) &=& f^b (g_1 g_2 \textrm{Ker}(f)) = f(g_1 g_2) = f(g_1) f(g_2) \\ &=& f^b(g_1 \textrm{Ker}(f)) \cdot f^b(g_2 \textrm{Ker}(f)).
\end{eqnarray}$$
Tags: dem est
<!--ID: 1730228001543-->
END

