### Contenido Principal

```ad-proposition
Sea $(X, \mathcal T)$ [[espacio topológico]]. La familia de [[conjunto cerrado]] cumple:
1. $X, \emptyset$ son cerrados.
2. $C,D$ cerrados $\implies C \cup D$ cerrados.
3. $\{C_i\}_{i \in I}$ familia de cerrados $\implies \bigcap_{i \in I} C_i$ cerrado.
```

^ebc1ec

```ad-proof
1. Trivial.
2. $C, D$ cerrados $\implies X \textrm{\\} C, X \textrm{\\} D \in \mathcal T$. $X \textrm{\\}(C \cup D) = (X \textrm{\\} C) \cap (X \textrm{\\} D) \in \mathcal T$. Por tanto, $C \cup D$ cerrado.
3. $\{C_i\}_{i \in I}$ familia de cerrados. $X \textrm{\\} C_i \in \mathcal T$. $X \textrm{\\} (\bigcap_{i \in I} C_i) = \bigcup_{i \in I}X \textrm{\\} C_i \in \mathcal T$. Por tanto, $\bigcap_{i \in I} C_i$ es cerrado.
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos|Espacios topológicos]]

---
### Anki

START
Básico
Anverso: Analogía de las propiedades de un conjunto abierto con las propiedades de un conjunto cerrado
Reverso: Sea $(X, \mathcal T)$ [[espacio topológico]]. La familia de [[conjunto cerrado]] cumple:
1. $X, \emptyset$ son cerrados.
2. $C,D$ cerrados $\implies C \cup D$ cerrados.
3. $\{C_i\}_{i \in I}$ familia de cerrados $\implies \bigcap_{i \in I} C_i$ cerrado.
Tags: 
<!--ID: 1727083427877-->
END

START
Básico
Anverso: Demostración de que sea $(X, \mathcal T)$ [[espacio topológico]]. La familia de [[conjunto cerrado]] cumple:
1. $X, \emptyset$ son cerrados.
2. $C,D$ cerrados $\implies C \cup D$ cerrados.
3. $\{C_i\}_{i \in I}$ familia de cerrados $\implies \bigcap_{i \in I} C_i$ cerrado.
Reverso: 1. Trivial.
2. $C, D$ cerrados $\implies X \textrm{\\} C, X \textrm{\\} D \in \mathcal T$. $X \textrm{\\}(C \cup D) = (X \textrm{\\} C) \cap (X \textrm{\\} D) \in \mathcal T$. Por tanto, $C \cup D$ cerrado.
3. $\{C_i\}_{i \in I}$ familia de cerrados. $X \textrm{\\} C_i \in \mathcal T$. $X \textrm{\\} (\bigcap_{i \in I} C_i) = \bigcup_{i \in I}X \textrm{\\} C_i \in \mathcal T$. Por tanto, $\bigcap_{i \in I} C_i$ es cerrado.
Tags: dem top
<!--ID: 1727083427879-->
END
