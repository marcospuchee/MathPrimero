### Contenido principal

```ad-Formal
Sea $(X, \mathcal T)$ espacio topológico y $H \subseteq X$. La topología inducida por $\mathcal T$ en $H$ (o topología relativa), se define como
$$\mathcal T \restriction_H = \mathcal T_H = \{A \cap H : A \in \mathcal T \}.$$
Los abiertos se llaman abiertos relativos. $(H, \mathcal T_H)$ se llama subespacio topológico.
```

```ad-proof
Veamos que $\mathcal T_H$ es topología sobre $H$:
1. $\emptyset = \emptyset \cap H \in \mathcal T_H$, $H = X \cap H \in \mathcal T_H$.
2. Dados $A, B \in \mathcal T_H$, entonces $\exists A', B' \in \mathcal T$ tales que $A = A' \cap H$ y $B = B' \cap H$. Entonces,
$$A \cap B = (A' \cap H) \cap (B' \cap H) = (A' \cap B') \cap H$$
donde $A' \cap B' \in \mathcal T$, lo que implica que $A \cap B = (A' \cap B') \cap H \in \mathcal T_H$.

3. Dados $A_i \in \mathcal T_H$, $\forall i \in I$, entonces $\exists A_i' \in \mathcal T$ tales que $A_i = A_i' \cap H$, $\forall i \in I$. Así,
$$\bigcup_{i \in I} A_i = \bigcup_{i \in I} (A_i' \cap H) = \left ( \bigcup_{i \in } A_i' \right ) \cap H,$$
donde $\bigcup_{i \in I} A_i' \in \mathcal T$. Luego, $\bigcup_{i \in I} A_i = \left ( \bigcup_{i \in I} A_i' \right ) \cap H \in \mathcal T_H$.
```

**Tema:** [[Subespacios topológicos#1. Definición.]]

**Definiciones referenciadas:**

---
### Anki

START
Básico
Anverso: Definición de topología inducida
Reverso: Sea $(X, \mathcal T)$ espacio topológico y $H \subseteq X$. La topología inducida por $\mathcal T$ en $H$ (o topología relativa), se define como
$$\mathcal T \restriction_H = \mathcal T_H = \{A \cap H : A \in \mathcal T \}.$$
Los abiertos se llaman abiertos relativos. $(H, \mathcal T_H)$ se llama subespacio topológico.
Tags: top
<!--ID: 1731931805198-->
END

START
Básico
Anverso: Demostración de que la topología inducida es topología
Reverso: Veamos que $\mathcal T_H$ es topología sobre $H$:
1. $\emptyset = \emptyset \cap H \in \mathcal T_H$, $H = X \cap H \in \mathcal T_H$.
2. Dados $A, B \in \mathcal T_H$, entonces $\exists A', B' \in \mathcal T$ tales que $A = A' \cap H$ y $B = B' \cap H$. Entonces,
$$A \cap B = (A' \cap H) \cap (B' \cap H) = (A' \cap B') \cap H$$
donde $A' \cap B' \in \mathcal T$, lo que implica que $A \cap B = (A' \cap B') \cap H \in \mathcal T_H$.

3. Dados $A_i \in \mathcal T_H$, $\forall i \in I$, entonces $\exists A_i' \in \mathcal T$ tales que $A_i = A_i' \cap H$, $\forall i \in I$. Así,
$$\bigcup_{i \in I} A_i = \bigcup_{i \in I} (A_i' \cap H) = \left ( \bigcup_{i \in } A_i' \right ) \cap H,$$
donde $\bigcup_{i \in I} A_i' \in \mathcal T$. Luego, $\bigcup_{i \in I} A_i = \left ( \bigcup_{i \in I} A_i' \right ) \cap H \in \mathcal T_H$.
Tags: dem top
<!--ID: 1731931805209-->
END

