### Contenido Principal

```ad-theorem
Sea $X$ conjunto y $\mathcal B$ familia de subconjuntos que cumple
1. $X = \bigcup_{B \in \mathcal B} B$.
2. Dados $B_1, B_2 \in \mathcal B$ y $x \in B_1 \cap B_2$, entonces $\exists B_3 \in \mathcal B$ tal que $x \in B_3 \subseteq B_1 \cap B_2$.

Entonces $\mathcal T_B = \{A \subseteq X : \, \forall x \in A \quad \exists B \in \mathcal B : x \in B \subseteq A \}$ es una [[topología]] en $X$. Además, $\mathcal B$ es base de abiertos de $\mathcal T_B$.
```

```ad-note
Para definir una topología es suficiente con dar una familia de subconjuntos que cumple B1 y B2.
```

```ad-proof
Vamos a demostrar que cumple con las tres propiedades de toda [[topología]]:
1. $\emptyset \in \mathcal T_B$ es trivial por la definición de $\mathcal T_B$. Sea $x \in X = \bigcup_{B \in \mathcal B} B$, entonces $\exists B_0 \in \mathcal B$ tal que $x \in B_0 \subseteq \bigcup_{B \in \mathcal B} B = X$, lo que implica que $X \in \mathcal T_B$.
2. $A_1, A_2 \in \mathcal T_B$. Sea $x \in A_1 \cap A_2$. Como $A_1 \in \mathcal T_B$, entonces $\exists B_1 \in \mathcal B$ tal que $x \in B_1 \subseteq A_1$. Como $A_2 \in \mathcal T_B$, entonces $\exists B_2 \in \mathcal B$ tal que $x \in B_2 \subseteq A_2$. Por tanto, $x \in B_1 \cap B_2$, lo que implica que $\exists B_3 \in \mathcal B$ tal que $x \in B_3 \subseteq B_1 \cap B_2 \subseteq A_1 \cap A_2$, lo que implica que $A_1 \cap A_2 \in \mathcal T_B$.
3. $\{A_i\}_{i \in I} \subseteq \mathcal T_B$. Sea $x \in \bigcup_{i \in I} A_i$, entonces $\exists i_x \in I$ tal que $x \in A_{i_x}$. Como $A_{i_x} \in \mathcal T_B$, entonces $\exists B \in \mathcal B$ tal que $x \in B \subseteq A_{i_x} \subseteq \bigcup_{i \in I} A_i$, lo que implica que $\bigcup_{i \in I} A_i \in \mathcal T_B$.

Que $\mathcal B$ sea [[base de abiertos]] de $\mathcal T_B$ es consecuencia de [[caracterización de base de abiertos]].
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos|Espacios topológicos]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Teorema que permite crear una topología a partir de un subconjunto de familias de un conjunto
Reverso: Sea $X$ conjunto y $\mathcal B$ familia de subconjuntos que cumple
1. $X = \bigcup_{B \in \mathcal B} B$.
2. Dados $B_1, B_2 \in \mathcal B$ y $x \in B_1 \cap B_2$, entonces $\exists B_3 \in \mathcal B$ tal que $x \in B_3 \subseteq B_1 \cap B_2$.

Entonces $\mathcal T_B = \{A \subseteq X : \, \forall x \in A \quad \exists B \in \mathcal B : x \in B \subseteq A \}$ es una [[topología]] en $X$. Además, $\mathcal B$ es base de abiertos de $\mathcal T_B$.
<!--ID: 1727422026741-->
END

START
Básico
Anverso: Demostración de que sea $X$ conjunto y $\mathcal B$ familia de subconjuntos que cumple
1. $X = \bigcup_{B \in \mathcal B} B$.
2. Dados $B_1, B_2 \in \mathcal B$ y $x \in B_1 \cap B_2$, entonces $\exists B_3 \in \mathcal B$ tal que $x \in B_3 \subseteq B_1 \cap B_2$.

Entonces $\mathcal T_B = \{A \subseteq X : \, \forall x \in A \quad \exists B \in \mathcal B : x \in B \subseteq A \}$ es una [[topología]] en $X$. Además, $\mathcal B$ es base de abiertos de $\mathcal T_B$.
Reverso: Vamos a demostrar que cumple con las tres propiedades de toda [[topología]]:
1. $\emptyset \in \mathcal T_B$ es trivial por la definición de $\mathcal T_B$. Sea $x \in X = \bigcup_{B \in \mathcal B} B$, entonces $\exists B_0 \in \mathcal B$ tal que $x \in B_0 \subseteq \bigcup_{B \in \mathcal B} B = X$, lo que implica que $X \in \mathcal T_B$.
2. $A_1, A_2 \in \mathcal T_B$. Sea $x \in A_1 \cap A_2$. Como $A_1 \in \mathcal T_B$, entonces $\exists B_1 \in \mathcal B$ tal que $x \in B_1 \subseteq A_1$. Como $A_2 \in \mathcal T_B$, entonces $\exists B_2 \in \mathcal B$ tal que $x \in B_2 \subseteq A_2$. Por tanto, $x \in B_1 \cap B_2$, lo que implica que $\exists B_3 \in \mathcal B$ tal que $x \in B_3 \subseteq B_1 \cap B_2 \subseteq A_1 \cap A_2$, lo que implica que $A_1 \cap A_2 \in \mathcal T_B$.
3. $\{A_i\}_{i \in I} \subseteq \mathcal T_B$. Sea $x \in \bigcup_{i \in I} A_i$, entonces $\exists i_x \in I$ tal que $x \in A_{i_x}$. Como $A_{i_x} \in \mathcal T_B$, entonces $\exists B \in \mathcal B$ tal que $x \in B \subseteq A_{i_x} \subseteq \bigcup_{i \in I} A_i$, lo que implica que $\bigcup_{i \in I} A_i \in \mathcal T_B$.

Que $\mathcal B$ sea [[base de abiertos]] de $\mathcal T_B$ es consecuencia de [[caracterización de base de abiertos]].
Tags: dem top
<!--ID: 1727422026744-->
END
