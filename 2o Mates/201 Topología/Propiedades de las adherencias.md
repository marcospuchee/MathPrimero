### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ un [[espacio topológico]], $S_1, S_2 \subseteq X$. Entonces,
1. $S_1 \subseteq S_2 \implies \textrm{ad}(S_1) \subseteq \textrm{ad}(S_2)$.
2. $\textrm{ad}(S_1 \cup S_2) = \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$.
```

```ad-proof
1. Sea $x \in \textrm{ad}(S_1)$. Entonces, $\forall U \in \mathcal E(x)$, $U \cap S_1 \neq \emptyset$. Por tanto, $U \cap S_2 \neq \emptyset$, luego $x \in \textrm{ad}(S_2)$.
2. Como $S_1, S_2 \subseteq S_1 \cup S_2$, tenemos que $\textrm{ad}(S_1), \textrm{ad}(S_2) \subseteq \textrm{ad}(S_1 \cup S_2)$. Luego $\textrm{ad}(S_1) \cup \textrm{ad}(S_2) \subseteq \textrm{ad}(S_1 \cup S_2)$. El sentido contrario lo vamos a demostrar por contrarrecíproco: supongamos $x \notin \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$, por tanto, $x \notin \textrm{ad}(S_1)$ implica que $\exists U_1 \in \mathcal E(x)$ tal que $U_1 \cap S_1 = \emptyset$. Análogamente, como $x \notin \textrm{ad}(S_2)$, entonces $\exists U_2 \in \mathcal E(x)$ tal que $U_2 \cap S_2 = \emptyset$. Así, $U_1 \cap U_2 \in \mathcal E(x)$ y $(U_1 \cap U_2)\cap(S_1 \cap S_2) = \emptyset$, lo que implica que $x \notin \textrm{ad}(S_1 \cup S_2)$, y $\textrm{ad}(S_1 \cup S_2) \subseteq \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$.
```

**Tema:** [[Puntos especiales#1. Puntos de adherencia.]]

---
### Anki

START
Básico
Anverso: Qué propiedades cumplen las adherencias
Reverso: Sean $(X, \mathcal T)$ un [[espacio topológico]], $S_1, S_2 \subseteq X$. Entonces,
1. $S_1 \subseteq S_2 \implies \textrm{ad}(S_1) \subseteq \textrm{ad}(S_2)$.
2. $\textrm{ad}(S_1 \cup S_2) = \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$.
Tags: top
<!--ID: 1728549802373-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ un [[espacio topológico]], $S_1, S_2 \subseteq X$. Entonces,
1. $S_1 \subseteq S_2 \implies \textrm{ad}(S_1) \subseteq \textrm{ad}(S_2)$.
2. $\textrm{ad}(S_1 \cup S_2) = \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$.
Reverso: 1. Sea $x \in \textrm{ad}(S_1)$. Entonces, $\forall U \in \mathcal E(x)$, $U \cap S_1 \neq \emptyset$. Por tanto, $U \cap S_2 \neq \emptyset$, luego $x \in \textrm{ad}(S_2)$.
2. Como $S_1, S_2 \subseteq S_1 \cup S_2$, tenemos que $\textrm{ad}(S_1), \textrm{ad}(S_2) \subseteq \textrm{ad}(S_1 \cup S_2)$. Luego $\textrm{ad}(S_1) \cup \textrm{ad}(S_2) \subseteq \textrm{ad}(S_1 \cup S_2)$. El sentido contrario lo vamos a demostrar por contrarrecíproco: supongamos $x \notin \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$, por tanto, $x \notin \textrm{ad}(S_1)$ implica que $\exists U_1 \in \mathcal E(x)$ tal que $U_1 \cap S_1 = \emptyset$. Análogamente, como $x \notin \textrm{ad}(S_2)$, entonces $\exists U_2 \in \mathcal E(x)$ tal que $U_2 \cap S_2 = \emptyset$. Así, $U_1 \cap U_2 \in \mathcal E(x)$ y $(U_1 \cap U_2)\cap(S_1 \cap S_2) = \emptyset$, lo que implica que $x \notin \textrm{ad}(S_1 \cup S_2)$, y $\textrm{ad}(S_1 \cup S_2) \subseteq \textrm{ad}(S_1) \cup \textrm{ad}(S_2)$.
Tags: dem top
<!--ID: 1728549802423-->
END