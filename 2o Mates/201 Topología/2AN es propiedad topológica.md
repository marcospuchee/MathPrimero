### Contenido Principal

```ad-proposition
$2 \textrm{AN}$ es propiedad topológica. Sea $(X, \mathcal T)$ [[espacio topológico 2 AN]] y $f: (X, \mathcal T) \to (Y, \mathcal T')$ [[homeomorfismo]], entonces $(Y, \mathcal T')$ es $2\textrm{AN}$.
```

```ad-proof
Como $(X, \mathcal T)$ es $2 \textrm{AN}$, entonces $\exists \mathcal B = \{B_n \}_{n \in \mathbb N}$ base de abiertos numerable. Como $f^{-1}$ es continua, entonces $f(B_n) \in \mathcal T'$, $\forall n \in \mathbb N$. Sea $A \in \mathcal T'$, como $f$ continua, $f^{-1}(A) \in \mathcal T$, y como $\mathcal B$ es base, $f^{-1}(A) = \bigcup_{m \in I \subseteq \mathbb N} B_m$, lo que implica que
$$A = f(f^{-1}(A)) = f \left (\bigcup_{m \in I} B_m \right ) = \bigcup_{m \in I} f(B_m).$$
Y, por tanto, $\mathcal B' = \{f(B_n) \}_{n \in \mathbb N}$ es base de abiertos numerable de $(Y, \mathcal T')$, luego $(Y, \mathcal T)$ es $2\textrm{AN}$.
```

**Tema:**  [[Continuidad#2. Homeomorfismos.]]

---
### Anki

START
Básico
Anverso: Demostración de que $2\textrm{AN}$ es una propiedad topológica
Reverso: Como $(X, \mathcal T)$ es $2 \textrm{AN}$, entonces $\exists \mathcal B = \{B_n \}_{n \in \mathbb N}$ base de abiertos numerable. Como $f^{-1}$ es continua, entonces $f(B_n) \in \mathcal T'$, $\forall n \in \mathbb N$. Sea $A \in \mathcal T'$, como $f$ continua, $f^{-1}(A) \in \mathcal T$, y como $\mathcal B$ es base, $f^{-1}(A) = \bigcup_{m \in I \subseteq \mathbb N} B_m$, lo que implica que
$$A = f(f^{-1}(A)) = f \left (\bigcup_{m \in I} B_m \right ) = \bigcup_{m \in I} f(B_m).$$
Y, por tanto, $\mathcal B' = \{f(B_n) \}_{n \in \mathbb N}$ es base de abiertos numerable de $(Y, \mathcal T')$, luego $(Y, \mathcal T)$ es $2\textrm{AN}$.
Tags: dem top
<!--ID: 1730228001629-->
END
