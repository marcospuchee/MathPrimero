### Contenido Principal

```ad-proposition
Sea $G$ un grupo y $H \le G$. Entonces
1. $\textrm{Core}_G(H) \unlhd H$.
2. Si $L \unlhd G$ tal que $L \le H$, entonces $L \le \textrm{Core}_G(H)$.
Es decir, $\textrm{Core}_G(H)$ es el mayor subgrupo normal contenido en $H$.
```

```ad-proof
*Prácticas.*

Por definición, sabemos que $$\textrm{Core}_G(H) := \textrm{Ker}(\rho) = \bigcap_{x \in G} \textrm{Stab}_xH = \bigcap_{x \in G} \{g \in G : x^{-1}gx \in H \}.$$ Por tanto, basta con ver que $\forall l \in L$, se cumple que $\forall x \in G$, $xlx^{-1} \in H$.

Como $L \unlhd G$, $\forall x \in G$, se cumple que $xLx^{-1} = L$, luego $xlx^{-1} \in L \subseteq H$. En particular, $xlx^{-1} \in H$. Por tanto, es cierto que $L \le \textrm{Core}_G(H)$.
```

**Tema:** [[Acciones de grupos#4. La acción sobre clases]]

**Definiciones referenciadas:** [$\textrm{Core} \\_ G (H)$](Acción sobre clases), 
**Resultados referenciados:** [[Definiciones equivalentes a subgrupo normal]]

---
### Anki
