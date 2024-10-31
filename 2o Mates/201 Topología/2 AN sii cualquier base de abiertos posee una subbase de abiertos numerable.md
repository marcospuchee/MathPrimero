### Contenido Principal


```ad-theorem
Sean $(X, \mathcal T)$ un [[espacio topológico]], $\mathcal B$ [[base de abiertos]].

$(X, \mathcal T)$ es [[espacio topológico 2 AN]] $\iff$ $\exists$ una subfamilia $\mathcal B' \subseteq \mathcal B$ que es una base de abiertos numerable.
```

```ad-proof
$(X, \mathcal T) \textrm{ 2 AN} \implies \exists \mathcal C$ base de abiertos numerable. Sea $C \in \mathcal C$, como $\mathcal B$ base de abiertos, $C = \bigcup_{i \in I} B_i$, con $B_i \in \mathcal B$, $\forall i \in I$. Sin embargo,
$$B_i \in \mathcal T \implies B_i = \bigcup_{j \in J} C_{j} \implies C = \bigcup_{i \in I} \bigcup_{j \in J} C_{ij}.$$ 
Como $\mathcal C$ es numerable, $(C_{ij})_{i \in I, \, j \in J} = \{C_1, C_2, \dots, C_n, \dots \}$. Luego $\forall C_n$, $\exists B_{i_n} \in \mathcal B$ tal que $C_n \subseteq B_{i_n} \subseteq C$.
$$C = \bigcup_{n \in \mathbb N} C_n \subseteq \bigcup_{n \in \mathbb N} B_{i_n} \subseteq C \implies C = \bigcup_{n \in \mathbb N} B_{i_n}.$$

Entonces, $\forall A \in \mathcal T$, $A = \bigcup_{k \in \mathbb N} C_k = \bigcup_{k \in \mathbb N} \bigcup_{n \in \mathbb N} B_{i_n}^k$, lo que implica que $(B_{i_n}^k)_{k,n \in \mathbb N} \subseteq \mathcal B$ y es base de abiertos numerable.
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos|Espacios topológicos]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Caracterización de espacio topológico $\textrm{ 2 AN}$.
Reverso: Sean $(X, \mathcal T)$ un [[espacio topológico]], $\mathcal B$ [[base de abiertos]].

$(X, \mathcal T)$ es [[espacio topológico 2 AN]] $\iff$ $\exists$ una subfamilia $\mathcal B' \subseteq \mathcal B$ que es una base de abiertos numerable.
<!--ID: 1727966478979-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ un [[espacio topológico]], $\mathcal B$ [[base de abiertos]].

$(X, \mathcal T)$ es [[espacio topológico 2 AN]] $\iff$ $\exists$ una subfamilia $\mathcal B' \subseteq \mathcal B$ que es una base de abiertos numerable.
Reverso: $(X, \mathcal T) \textrm{ 2 AN} \implies \exists \mathcal C$ base de abiertos numerable. Sea $C \in \mathcal C$, como $\mathcal B$ base de abiertos, $C = \bigcup_{i \in I} B_i$, con $B_i \in \mathcal B$, $\forall i \in I$. Sin embargo,
$$B_i \in \mathcal T \implies B_i = \bigcup_{j \in J} C_{j} \implies C = \bigcup_{i \in I} \bigcup_{j \in J} C_{ij}.$$ 
Como $\mathcal C$ es numerable, $(C_{ij})_{i \in I, \, j \in J} = \{C_1, C_2, \dots, C_n, \dots \}$. Luego $\forall C_n$, $\exists B_{i_n} \in \mathcal B$ tal que $C_n \subseteq B_{i_n} \subseteq C$.
$$C = \bigcup_{n \in \mathbb N} C_n \subseteq \bigcup_{n \in \mathbb N} B_{i_n} \subseteq C \implies C = \bigcup_{n \in \mathbb N} B_{i_n}.$$

Entonces, $\forall A \in \mathcal T$, $A = \bigcup_{k \in \mathbb N} C_k = \bigcup_{k \in \mathbb N} \bigcup_{n \in \mathbb N} B_{i_n}^k$, lo que implica que $(B_{i_n}^k)_{k,n \in \mathbb N} \subseteq \mathcal B$ y es base de abiertos numerable.
Tags: dem top
<!--ID: 1727966479003-->
END

