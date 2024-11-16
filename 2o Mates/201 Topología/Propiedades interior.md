### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ [[espacio topológico]], $S_1, S_2 \subseteq X$.
1. $S_1 \subseteq S_2 \implies \textrm{int}(S_1) \subseteq \textrm{int}(S_2)$.
2. $\textrm{int}(S_1 \cap S_2) = \textrm{int}(S_1) \cap \textrm{int}(S_2)$.
```

```ad-proof
1. $x \in \textrm{int}(S_1) \implies S_1 \in \mathcal E(x) \implies S_2 \in \mathcal E(x) \implies x \in \textrm{int}(S_2)$.
2. $\textrm{int} (S_1) \cap \textrm{int}(S_2) = (X \textrm{\\} \textrm{ad}(X \textrm{\\} S_1)) \cap (X \textrm{\\} \textrm{ad}(X \textrm{\\} S_2))=$ $X \textrm{\\} ( \textrm{ad}(X \textrm{\\} S_1) \cup \textrm{ad}(X \textrm{\\} S_2)) = X \textrm{\\} \textrm{ad}((X \textrm{\\} S_1) \cup (X \textrm{\\} S_2))$ $=$ $X \textrm{\\} \textrm{ad}(X \textrm{\\} (S_1 \cap S_2))$ $=$ $\textrm{int}(S_1 \cap S_2)$.
```

**Tema:** [[Puntos especiales#3. Puntos interiores.]]

---
### Anki

START
Básico
Anverso: Propiedades del interior de un conjunto
Reverso: Sean $(X, \mathcal T)$ [[Espacio topológico]], $S_1, S_2 \subseteq X$.
1. $S_1 \subseteq S_2 \implies \textrm{int}(S_1) \subseteq \textrm{int}(S_2)$.
2. $\textrm{int}(S_1 \cap S_2) = \textrm{int}(S_1) \cap \textrm{int}(S_2)$.
Tags: top
<!--ID: 1729160606433-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ [[Espacio topológico]], $S_1, S_2 \subseteq X$.
1. $S_1 \subseteq S_2 \implies \textrm{int}(S_1) \subseteq \textrm{int}(S_2)$.
2. $\textrm{int}(S_1 \cap S_2) = \textrm{int}(S_1) \cap \textrm{int}(S_2)$.
Reverso:
1. $x \in \textrm{int}(S_1) \implies S_1 \in \mathcal E(x) \implies S_2 \in \mathcal E(x) \implies x \in \textrm{int}(S_2)$.
2. $\textrm{int} (S_1) \cap \textrm{int}(S_2) = (X \textrm{\\} \textrm{ad}(X \textrm{\\} S_1)) \cap (X \textrm{\\} \textrm{ad}(X \textrm{\\} S_2))=$ $X \textrm{\\} ( \textrm{ad}(X \textrm{\\} S_1) \cup \textrm{ad}(X \textrm{\\} S_2)) = X \textrm{\\} \textrm{ad}((X \textrm{\\} S_1) \cup (X \textrm{\\} S_2))$ $=$ $X \textrm{\\} \textrm{ad}(X \textrm{\\} (S_1 \cap S_2))$ $=$ $\textrm{int}(S_1 \cap S_2)$.
Tags: dem top
<!--ID: 1729160606435-->
END