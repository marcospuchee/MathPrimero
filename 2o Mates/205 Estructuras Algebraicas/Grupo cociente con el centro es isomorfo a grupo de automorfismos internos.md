### Contenido Principal

```ad-theorem
Sea $G$ un grupo. Entonces
$$G/Z(G) \cong \textrm{Int}(G),$$
donde $Z(G) = \{x \in G : xy = yx, \, \forall y \in G\}$.
```

^fc1f04

```ad-proof
Consideramos la aplicación
$$\begin{array}{c c c l}
f: & G & \to & \textrm{Int}(G) \\
& g & \mapsto & \alpha_g.
\end{array}$$


1. Veamos que $f$ homomorfismo: sean $g,h \in G$, entonces
$$f(gh) = \alpha_{gh} = \alpha_g \circ \alpha_h = f(g) \circ f(h).$$
2. Para poder aplicar el primer teorema de isomorfía, veamos que $\textrm{Ker}(f) = Z(G)$:
$$\begin{eqnarray}
\textrm{Ker}(f) &=& \{g \in G : f(g) = 1_{\textrm{Int}(G)} \} = \{g \in G : \alpha_g = \textrm{id}_G \} \\ &=& \{g \in G : \forall x \in G, \, \alpha_g(x) = \textrm{id}_G(x) \} = \{g \in G : \forall x \in G, \, gxg^{-1} = x \} \\ &=& \{g \in G : \forall x \in G, \, gx = xg \} = Z(G)
\end{eqnarray}
$$
3. Para poder aplicar el primer teorema de isomorfía, veamos que $\textrm{Im}(f) = \textrm{Int}(G)$:
$$\textrm{Im}(f) = \{f(g) : g \in G \} = \{\alpha_g : g \in G \} = \textrm{Int}(G).$$

Por tanto, aplicando el primer teorema de isomorfía, queda demostrado.
```

**Tema:** [[Teoría de grupos#17. Los grupos $ textrm{Aut}(G)$ e $ textrm{Int}(G)$.]]
**Corolario:**

**Definiciones referenciadas:** [$\textrm{Int}(G)$](Grupo de automorfismos internos), [[Homomorfismo]]
**Resultados referenciados:** [[Primer teorema de isomorfía]]

---
### Anki

START
Respuesta anidada
Sea $G$ un grupo. Entonces
$${{c1::G/Z(G)}} \cong {{c2::\textrm{Int}(G)}},$$
donde {{c1::$Z(G) = \{x \in G : xy = yx, \, \forall y \in G\}$}}.
Tags: est
<!--ID: 1731446305264-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo. Entonces
$$G/Z(G) \cong \textrm{Int}(G),$$
donde $Z(G) = \{x \in G : xy = yx, \, \forall y \in G\}$.
Reverso: Consideramos la aplicación
$$\begin{array}{c c c l}
f: & G & \to & \textrm{Int}(G) \\
& g & \mapsto & \alpha_g.
\end{array}$$


1. Veamos que $f$ homomorfismo: sean $g,h \in G$, entonces
$$f(gh) = \alpha_{gh} = \alpha_g \circ \alpha_h = f(g) \circ f(h).$$
2. Para poder aplicar el primer teorema de isomorfía, veamos que $\textrm{Ker}(f) = Z(G)$:
$$\begin{eqnarray}
\textrm{Ker}(f) &=& \{g \in G : f(g) = 1_{\textrm{Int}(G)} \} = \{g \in G : \alpha_g = \textrm{id}_G \} \\ &=& \{g \in G : \forall x \in G, \, \alpha_g(x) = \textrm{id}_G(x) \} = \{g \in G : \forall x \in G, \, gxg^{-1} = x \} \\ &=& \{g \in G : \forall x \in G, \, gx = xg \} = Z(G)
\end{eqnarray}
$$
3. Para poder aplicar el primer teorema de isomorfía, veamos que $\textrm{Im}(f) = \textrm{Int}(G)$:
$$\textrm{Im}(f) = \{f(g) : g \in G \} = \{\alpha_g : g \in G \} = \textrm{Int}(G).$$

Por tanto, aplicando el primer teorema de isomorfía, queda demostrado.
Tags: dem est
<!--ID: 1731446305274-->
END

