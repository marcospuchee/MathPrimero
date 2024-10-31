### Contenido Principal

```ad-proposition
$(X, \mathcal T)$ [[espacio topológico]], $\mathcal B \subseteq \mathcal T$. $\mathcal B$ es [[base de abiertos]] $\iff$ $\forall A \in \mathcal T$, $\forall x \in A$, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A$.
```

```ad-proof
$\rightarrow$. $\mathcal B$ es base de abiertos. Sea $x \in A \in \mathcal T$, tenemos que $A = \bigcup_{i \in I}B_i$ con $B_i \in \mathcal B$, $\forall i \in I$. Luego, $\exists i_0 \in I$ tal que $x \in B_{i_0} \subseteq A$ con $B_{i_0} \in \mathcal B$.

$\leftarrow$. Sea $A \in \mathcal T$, $\forall x \in A \quad \exists B_x \in B$ tal que $x \in B_x \subseteq A$. Por tanto,
$$A = \bigcup_{x \in A} \{x\} \subseteq \bigcup_{x \in A} B_x \subseteq A \implies A = \bigcup_{x \in A} B_x,$$
y por tanto, $\mathcal B$ es base de abiertos.
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos|Espacios topológicos]]

---
### Anki

START
Básico
Anverso: Caracterización de base de abiertos
Reverso: $(X, \mathcal T)$ [[espacio topológico]], $\mathcal B \subseteq \mathcal T$. $\mathcal B$ es [[base de abiertos]] $\iff$ $\forall A \in \mathcal T$, $\forall x \in A$, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A$.
<!--ID: 1727422026751-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ [[espacio topológico]], $\mathcal B \subseteq \mathcal T$. $\mathcal B$ es [[base de abiertos]] $\iff$ $\forall A \in \mathcal T$, $\forall x \in A$, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A$.
Reverso: 
$\rightarrow$. $\mathcal B$ es base de abiertos. Sea $x \in A \in \mathcal T$, tenemos que $A = \bigcup_{i \in I}B_i$ con $B_i \in \mathcal B$, $\forall i \in I$. Luego, $\exists i_0 \in I$ tal que $x \in B_{i_0} \subseteq A$ con $B_{i_0} \in \mathcal B$.

$\leftarrow$. Sea $A \in \mathcal T$, $\forall x \in A \quad \exists B_x \in B$ tal que $x \in B_x \subseteq A$. Por tanto,
$$A = \bigcup_{x \in A} \{x\} \subseteq \bigcup_{x \in A} B_x \subseteq A \implies A = \bigcup_{x \in A} B_x,$$
y por tanto, $\mathcal B$ es base de abiertos.
Tags: dem top
<!--ID: 1727422026755-->
END
