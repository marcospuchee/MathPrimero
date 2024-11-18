### Contenido Principal

```ad-proposition
La propiedad de ser metrizable es hereditaria.
```

```ad-proof
Sea $(X, d)$ espacio métrico y $H \subseteq X$. Veremos que $\mathcal T_d \restriction_H = \mathcal T_{d_H}$. 

$\subseteq$.
Sea $A \in \mathcal T_d \restriction_H$, entonces, por definición, $\exists A' \in \mathcal T_d$ tal que $A = A' \cap H$. Es decir, $\forall x \in A \subseteq A'$, $\exists \varepsilon > 0$ tal que $B_d(x; \varepsilon) \subseteq A'$, lo que implica que $B_{d_H}(x; \varepsilon)$ $=$ $B_d(x; \varepsilon) \cap H$ $\subseteq$ $A'\cap H$ $=$ $A$. Por tanto, $A \in \mathcal T_{d_H}$.

$\supseteq$.
Sea $A \in \mathcal T_{d_H}$, $\forall x \in A$, $\exists \varepsilon > 0$ tal que $B_d(x; \varepsilon) \cap H$ $=$ $B_{d_H}(x; \varepsilon)$ $\subseteq$ $A$. Sea $A' = \bigcup_{x \in A} B_d(x; \varepsilon)$, entonces
$$A \subseteq A' \cap H = \left (\bigcup_{x \in A} B_d(x; \varepsilon) \right ) \cap H = \bigcup_{x \in A}(B_d(x; \varepsilon) \cap H) = \bigcup_{x \in A} B_{d_H}(x; \varepsilon) \subseteq A.$$
Así, $A = A' \cap H$, y como $A' \in \mathcal T_d$, entonces $A \in \mathcal T_d \restriction_H$.
```

**Tema:** [[Subespacios topológicos#1. Definición.]]

**Definiciones referenciadas:** [[Espacio métrico]], [$\mathcal T_d \restriction H$](Topología inducida), [$\mathcal T_{d_H}$](Espacio métrico), [$d_H$](Subespacio métrico)
**Resultados referenciados:**

---
### Anki
