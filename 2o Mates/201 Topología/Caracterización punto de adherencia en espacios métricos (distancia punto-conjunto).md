### Contenido Principal

```ad-proposition
$(X, d)$ [[espacio métrico]], $S \subseteq X$, $x \in X$. Entonces, $x \in \textrm{ad}(S)$ ([[adherencia]]) $\iff$ $d(x,S) = 0$.
```

```ad-proof
$$x \in \textrm{ad}(S) \iff \forall \varepsilon > 0 \, \, B(x; \varepsilon) \cap S \neq \emptyset \iff \forall \varepsilon > 0, \, \, \exists y_\varepsilon \in S : d(x; y_\varepsilon) < \varepsilon \iff \inf_{y \in S} d(x,y) = 0 \iff d(x, S) = 0.$$
```

**Tema:** [[Puntos especiales#1. Puntos de adherencia.]]

---
### Anki

START
Básico
Anverso: Proposición punto es de adherencia sii la distancia al conjunto es 0
Reverso: $(X, d)$ [[espacio métrico]], $S \subseteq X$, $x \in X$. Entonces, $x \in \textrm{ad}(S)$ ([[adherencia]]) $\iff$ $d(x,S) = 0$.
Tags: top
<!--ID: 1728549802275-->
END

START
Básico
Anverso: Demostración de que sea $(X, d)$ [[espacio métrico]], $S \subseteq X$, $x \in X$. Entonces, $x \in \textrm{ad}(S)$ ([[adherencia]]) $\iff$ $d(x,S) = 0$.
Reverso: 
$$x \in \textrm{ad}(S) \iff \forall \varepsilon > 0 \, \, B(x; \varepsilon) \cap S \neq \emptyset \iff \forall \varepsilon > 0 \, \, \exists y_\varepsilon : d(x; y_\varepsilon) < \varepsilon \iff \inf_{y \in S} d(x,y) = 0 \iff d(x, S) = 0.$$
Tags: dem top
<!--ID: 1728549802329-->
END