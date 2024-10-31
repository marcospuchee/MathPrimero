### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ un [[espacio topológico]], $S \subseteq X$. Entonces,
1. $\textrm{ad}(S)$ ([[adherencia]]) es [[conjunto cerrado]] en $(X, \mathcal T)$.
2. Sea $C$ cerrado tal que $S \subseteq C$, entonces $\textrm{ad}(S) \subseteq C$.
3. $C$ es cerrado $\iff$ $\textrm{ad} (C) = C$.
```

```ad-proof
1. Sea $x \in X \textrm{\\} \textrm{ad}(S)$. Sabemos que $\exists U \in \mathcal E(x)$ tal que $U \cap S = \emptyset$. Como $U \in \mathcal E(x)$, $\exists A \in \mathcal T$ tal que $x \in A \subseteq U$. Por tanto, $A \cap S = \emptyset$. Sea $y \in A$, entonces $A \in \mathcal E(y)$, y como $A \cap S = \emptyset$, entonces $y \notin \textrm{ad}(S)$, luego $x \in A \subseteq X \textrm{\\} \textrm{ad}(S)$. Así, $X \textrm{\\} \textrm{ad} (S) \in \mathcal E(x)$. Luego $\forall x \in X \textrm{\\} \textrm{ad}(S)$, $X \textrm{\\} \textrm{ad}(S) \in \mathcal T$, y por consiguiente, $\textrm{ad}(S)$ cerrado.
2. Sea $C$ cerrado tal que $S \subseteq C$. Supongamos que $\textrm{ad}(S) \not \subseteq C$, luego $\exists x \in \textrm{ad}(S)$ tal que $x \notin C$, pero $(X \textrm{\\} C) \cap S = \emptyset$, y además, $x \in X \textrm{\\} C \in \mathcal T$, lo que implica que $X \textrm{\\} C \in \mathcal E(x)$, luego $x \notin \textrm{ad}(S)$ (contradicción).
3. $\rightarrow$. $C$ cerrado $\implies$ (por $(ii)$) $\textrm{ad}(C) \subseteq C$, y como $C \subseteq \textrm{ad}(C)$, entonces $C = \textrm{ad}(C)$.
$\leftarrow$. $\textrm{ad}(C) = C$ $\implies$ (por $(i)$) que $C$ cerrado.
```

**Tema:** [[Puntos especiales#1. Puntos de adherencia.]]

---
### Anki

START
Básico
Anverso: Proposición relación entre conjunto cerrado y adherencia de un conjunto
Reverso: Sean $(X, \mathcal T)$ un [[espacio topológico]], $S \subseteq X$. Entonces,
1. $\textrm{ad}(S)$ ([[adherencia]]) es [[conjunto cerrado]] en $(X, \mathcal T)$.
2. Sea $C$ cerrado tal que $S \subseteq C$, entonces $\textrm{ad}(S) \subseteq C$.
3. $C$ es cerrado $\iff$ $\textrm{ad} (C) = C$.
Tags: top
<!--ID: 1728549802152-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ un [[espacio topológico]], $S \subseteq X$. Entonces,
1. $\textrm{ad}(S)$ ([[adherencia]]) es [[conjunto cerrado]] en $(X, \mathcal T)$.
2. Sea $C$ cerrado tal que $S \subseteq C$, entonces $\textrm{ad}(S) \subseteq C$.
3. $C$ es cerrado $\iff$ $\textrm{ad} (C) = C$.
Reverso: 
1. Sea $x \in X \textrm{\\} \textrm{ad}(S)$. Sabemos que $\exists U \in \mathcal E(x)$ tal que $U \cap S = \emptyset$. Como $U \in \mathcal E(x)$, $\exists A \in \mathcal T$ tal que $x \in A \subseteq U$. Por tanto, $A \cap S = \emptyset$. Sea $y \in A$, entonces $A \in \mathcal E(y)$, y como $A \cap S = \emptyset$, entonces $y \notin \textrm{ad}(S)$, luego $x \in A \subseteq X \textrm{\\} \textrm{ad}(S)$. Así, $X \textrm{\\} \textrm{ad} (S) \in \mathcal E(x)$. Luego $\forall x \in X \textrm{\\} \textrm{ad}(S)$, $X \textrm{\\} \textrm{ad}(S) \in \mathcal T$, y por consiguiente, $\textrm{ad}(S)$ cerrado.
2. Sea $C$ cerrado tal que $S \subseteq C$. Supongamos que $\textrm{ad}(S) \not \subseteq C$, luego $\exists x \in \textrm{ad}(S)$ tal que $x \notin C$, pero $(X \textrm{\\} C) \cap S = \emptyset$, y además, $x \in X \textrm{\\} C \in \mathcal T$, lo que implica que $X \textrm{\\} C \in \mathcal E(x)$, luego $x \notin \textrm{ad}(S)$ (contradicción).
3. $\rightarrow$. $C$ cerrado $\implies$ (por $(ii)$) $\textrm{ad}(C) \subseteq C$, y como $C \subseteq \textrm{ad}(C)$, entonces $C = \textrm{ad}(C)$.
$\leftarrow$. $\textrm{ad}(C) = C$ $\implies$ (por $(i)$) que $C$ cerrado.
Tags: dem top
<!--ID: 1728549802206-->
END