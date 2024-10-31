### Contenido Principal

```ad-theorem
Sea $G$ un grupo, $H,K \unlhd G$ tales que $H \le K$. Entonces $(G/H)/(K/H) \cong G/K$.
```

^210547

```ad-proof
Consideramos
$$\begin{array}{c c c c}
f: & G/H & \to & G/K \\
& xH & \mapsto & xK.
\end{array}$$

**$f$ bien definida:** sean $g_1 H = g_2 H \iff g_1^{-1} g_2 \in H \le K \implies g_1K = g_2 K$.

**Homomorfismo:** sean $g_1H, g_2H \in G/H$, entonces
$$f((g_1H)(g_2H)) = f((g_1 g_2)H) = (g_1 g_2) K = (g_1 K) (g_2 K) = f(g_1 H) f(g_2 H).$$

**Sobreyectiva:** sea $gK \in G/K \implies gK = f(gH)$.

**Veamos $\textrm{Ker}(f) = K/H$:** Por definición, tenemos que
$$\begin{eqnarray}
\textrm{Ker}(f) &=& \{gH \in G/H : f(gH) = 1_{G/K} \} = \{gH \in G/H : gK = K \} \\
&=& \{gH \in G/H : g \in K \} = K/H.
\end{eqnarray}$$

Por el [[primer teorema de isomorfía]],
- $(G/H)/ \textrm{Ker}(f) \cong \textrm{Im}(f)$. 
- $(G/H)/(K/H) \cong G/K$.
```

**Tema:** [[Teoría de grupos#15. Teoremas de isomorfía.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Tercer teorema de isomorfía
Reverso: Sea $G$ un grupo, $H,K \unlhd G$ tales que $H \le K$. Entonces $(G/H)/(K/H) \cong G/K$.
Tags: est
<!--ID: 1730228001528-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo, $H,K \unlhd G$ tales que $H \le K$. Entonces $(G/H)/(K/H) \cong G/K$.
Reverso: Consideramos
$$\begin{array}{c c c c}
f: & G/H & \to & G/K \\
& xH & \mapsto & xK.
\end{array}$$

**$f$ bien definida:** sean $g_1 H = g_2 H \iff g_1^{-1} g_2 \in H \le K \implies g_1K = g_2 K$.

**Homomorfismo:** sean $g_1H, g_2H \in G/H$, entonces
$$f((g_1H)(g_2H)) = f((g_1 g_2)H) = (g_1 g_2) K = (g_1 K) (g_2 K) = f(g_1 H) f(g_2 H).$$

**Sobreyectiva:** sea $gK \in G/K \implies gK = f(gH)$.

**Veamos $\textrm{Ker}(f) = K/H$:** Por definición, tenemos que
$$\begin{eqnarray}
\textrm{Ker}(f) &=& \{gH \in G/H : f(gH) = 1_{G/K} \} = \{gH \in G/H : gK = K \} \\
&=& \{gH \in G/H : g \in K \} = K/H.
\end{eqnarray}$$

Por el [[primer teorema de isomorfía]],
- $(G/H)/ \textrm{Ker}(f) \cong \textrm{Im}(f)$. 
- $(G/H)/(K/H) \cong G/K$.
Tags: dem est
<!--ID: 1730228001531-->
END
