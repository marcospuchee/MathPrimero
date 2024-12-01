### Contenido Principal

```ad-proposition
Sea $G$ un grupo. Entonces $\textrm{Int}(G) \unlhd \textrm{Aut}(G)$.
```

^a74a58

```ad-proof
En primer lugar demostramos que $\textrm{Int}(G) \le \textrm{Aut}(G)$:
1. Como $\alpha_{1_G}(x) = 1_G x 1_G^{-1} = x$, tenemos que $\textrm{id}_G = \alpha_{1_G} \in \textrm{Int}(G)$.
2. Dados $\alpha_g, \alpha_h \in \textrm{Int}(G)$, como $\alpha_g \circ \alpha_h(x)$ $=$ $\alpha_g(hxh^{-1})$ $=$ $(gh)x(gh)^{-1}$ $=$ $\alpha_{gh}(x)$, entonces $\alpha_g \circ \alpha_h = \alpha_{gh} \in \textrm{Int}(G)$.
3. Si $\alpha_g \in \textrm{Int}(G)$, entonces $\alpha_g \circ \alpha_{g^{-1}} = \alpha_{gg^{-1}} = \alpha_{1_G} = \textrm{id}_G$. Entonces, $(\alpha_g)^{-1}$ $=$ $\alpha_{g^{-1}} \in \textrm{Int}(G)$.

Ahora demostramos que $\textrm{Int}(G) \unlhd \textrm{Aut}(G)$: si $\alpha_g \in \textrm{Int}(G)$ y $\varphi \in \textrm{Aut}(G)$, entonces
$$ \begin{eqnarray}
^\varphi \alpha_g &=& \varphi \circ \alpha_g \circ \varphi^{-1}(x) = \varphi \circ \alpha_g(\varphi^{-1}(x)) = \varphi(g \varphi^{-1}(x) g^{-1}) = \varphi(g) x \varphi(g)^{-1} \\ &=& \alpha_{\varphi(g)}(x) \in \textrm{Int}(G) .\end{eqnarray}$$
```

**Tema:** [[Teoría de grupos#17. Los grupos $ textrm{Aut}(G)$ e $ textrm{Int}(G)$.]]

**Definiciones referenciadas:** [$\textrm{Aut}(G)$](Grupo de automorfismos), [$\textrm{Int}(G)$](Grupo de automorfismos internos), [[Subgrupo]], [[Subgrupo normal]]
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Relación entre $\textrm{Aut}(G)$ e $\textrm{Int}(G)$.
Reverso: Sea $G$ un grupo. Entonces $\textrm{Int}(G) \unlhd \textrm{Aut}(G)$.
Tags: est
<!--ID: 1731446305238-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo. Entonces $\textrm{Int}(G) \unlhd \textrm{Aut}(G)$.
Reverso: En primer lugar demostramos que $\textrm{Int}(G) \le \textrm{Aut}(G)$:
1. Como $\alpha_{1_G}(x) = 1_G x 1_G^{-1} = x$, tenemos que $\textrm{id}_G = \alpha_{1_G} \in \textrm{Int}(G)$.
2. Dados $\alpha_g, \alpha_h \in \textrm{Int}(G)$, como $\alpha_g \circ \alpha_h(x)$ $=$ $\alpha_g(hxh^{-1})$ $=$ $(gh)x(gh)^{-1}$ $=$ $\alpha_{gh}(x)$, entonces $\alpha_g \circ \alpha_h = \alpha_{gh} \in \textrm{Int}(G)$.
3. Si $\alpha_g \in \textrm{Int}(G)$, entonces $\alpha_g \circ \alpha_{g^{-1}} = \alpha_{gg^{-1}} = \alpha_{1_G} = \textrm{id}_G$. Entonces, $(\alpha_g)^{-1}$ $=$ $\alpha_{g^{-1}} \in \textrm{Int}(G)$.

Ahora demostramos que $\textrm{Int}(G) \unlhd \textrm{Aut}(G)$: si $\alpha_g \in \textrm{Int}(G)$ y $\varphi \in \textrm{Aut}(G)$, entonces
$$ \begin{eqnarray}
^\varphi \alpha_g &=& \varphi \circ \alpha_g \circ \varphi^{-1}(x) = \varphi \circ \alpha_g(\varphi^{-1}(x)) = \varphi(g \varphi^{-1}(x) g^{-1}) = \varphi(g) x \varphi(g)^{-1} \\ &=& \alpha_{\varphi(g)}(x) \in \textrm{Int}(G) .\end{eqnarray}$$
Tags: dem est
<!--ID: 1731446305247-->
END

