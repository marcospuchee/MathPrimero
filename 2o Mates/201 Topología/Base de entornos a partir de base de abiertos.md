### Contenido Principal

```ad-proposition
Sea $(X, \mathcal T)$ [[espacio topológico]], $\mathcal B$ [[base de abiertos]]. $\forall x \in X$, $\mathcal B (x) = \{B \in \mathcal B : x \in B \}$ es [[base de entornos]] de $x$.
```

```ad-note
$\textrm{2 AN}$ ([[espacio topológico 2 AN]]) $\implies$ $\textrm{ 1 AN}$ ([[espacio topológico 1 AN]]).
```

```ad-proof
1. Sea $B \in \mathcal B(x)$ $\implies$ $B \in \mathcal B$ $\implies$ $B \in \mathcal T$ $\implies$ $B \in \mathcal E(x)$. Luego es [[entorno]] de todos sus puntos.
2. Sea $U \in \mathcal E(x)$, entonces $\exists A \in \mathcal T$ tal que $x \in A \subseteq U$. Como $\mathcal B$ es base de abiertos, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A$. Luego $B \in \mathcal B(x)$, y $B \subseteq U$.

Luego $\mathcal B(x)$ es base de entornos.
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos|Espacios topológicos]]

---
### Anki

START
Básico
Anverso: Cómo se puede formar una base de entornos a partir de una base de abiertos?
Reverso: Sea $(X, \mathcal T)$ [[espacio topológico]], $\mathcal B$ [[base de abiertos]]. $\forall x \in X$, $\mathcal B (x) = \{B \in \mathcal B : x \in B \}$ es [[base de entornos]] de $x$.
<!--ID: 1727966478937-->
END

START
Básico
Anverso: Demostración de que sea $(X, \mathcal T)$ [[espacio topológico]], $\mathcal B$ [[base de abiertos]]. $\forall x \in X$, $\mathcal B (x) = \{B \in \mathcal B : x \in B \}$ es [[base de entornos]] de $x$.
Reverso: 1. Sea $B \in \mathcal B(x)$ $\implies$ $B \in \mathcal B$ $\implies$ $B \in \mathcal T$ $\implies$ $B \in \mathcal E(x)$. Luego es [[entorno]] de todos sus puntos.
2. Sea $U \in \mathcal E(x)$, entonces $\exists A \in \mathcal T$ tal que $x \in A \subseteq U$. Como $\mathcal B$ es base de abiertos, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A$. Luego $B \in \mathcal B(x)$, y $B \subseteq U$.

Luego $\mathcal B(x)$ es base de entornos.
Tags: dem top
<!--ID: 1727966478955-->
END
