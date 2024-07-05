
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-06-17, 16:29

```ad-lemma
Sea $X$ un [[espacio topológico]]. Supongamos que $\mathcal C$ es una colección de conjuntos abiertos de $X$ tal que, para cada conjunto abierto $U$ de $X$ y $x \in U$, $\exists C \in \mathcal C$ tal que $x \in C \subset U$. Entonces $\mathcal C$ es una base para la topología de $X$ ([[base para una topología]]).
```

```ad-proof
**Primera condición de base.**
Dado $x \in X$, puesto que $X$ es un [[conjunto abierto]], existe, por hipótesis, un elemento $C \in \mathcal C$ tal que $x \in C \subset X$.

**Segunda condición de base.**
Sea $X \in C_1 \cap C_2$, donde $C_1, C_2 \in \mathcal C$. Puesto que $C_1$ y $C_2$ son abiertos, también lo es $C_1 \cap C_2$. Luego existe, por hipótesis, un elemento $C_3 \in \mathcal C$ tal que $x \in C_3 \subset C_1 \cap C_2$.

Sea $\mathcal T$ la colección de conjuntos abiertos de $X$; debemos probar que la [[topología]] $\mathcal T'$ generada por $\mathcal C$ coincide con la topología $\mathcal T$. En primer lugar, nótese que si $U \in \mathcal T$ y $x \in U$, entonces, por hipótesis, $\exists C \in \mathcal C$ tal que $x \in C \subset U$. Se sigue que $U \in \mathcal T'$, por definición. Recíprocamente, si $W \in \mathcal T'$, entonces $W$ es igual a una unión de elementos de $\mathcal C$ por [[lema topología igual a la colección de todas las uniones de la base]]. Ya que cada elemento de $\mathcal C$ pertenece a $\mathcal T$ y $\mathcal T$ es una topología, $W \in \mathcal T$ también.
```

**Tema:** [[Espacios topológicos y funciones continuas#2. Base de una topología]]
**Corolarios:** [[Teorema base topología producto]]

---
### Anki

START
Básico
Anverso: Qué lema nos permite formar una base a partir de una topología?
Reverso: Sea $X$ un [[espacio topológico]]. Supongamos que $\mathcal C$ es una colección de conjuntos abiertos de $X$ tal que, para cada conjunto abierto $U$ de $X$ y $x \in U$, $\exists C \in \mathcal C$ tal que $x \in C \subset U$. Entonces $\mathcal C$ es una base para la topología de $X$ ([[base para una topología]]).
Tags: proposición/teorema top
<!--ID: 1718723531851-->
END

START
Básico
Anverso: Demostración de que sea $X$ un [[espacio topológico]]. Supongamos que $\mathcal C$ es una colección de conjuntos abiertos de $X$ tal que, para cada conjunto abierto $U$ de $X$ y $x \in U$, $\exists C \in \mathcal C$ tal que $x \in C \subset U$. Entonces $\mathcal C$ es una base para la topología de $X$ ([[base para una topología]]).
Reverso:
**Primera condición de base.**
Dado $x \in X$, puesto que $X$ es un [[conjunto abierto]], existe, por hipótesis, un elemento $C \in \mathcal C$ tal que $x \in C \subset X$.

**Segunda condición de base.**
Sea $X \in C_1 \cap C_2$, donde $C_1, C_2 \in \mathcal C$. Puesto que $C_1$ y $C_2$ son abiertos, también lo es $C_1 \cap C_2$. Luego existe, por hipótesis, un elemento $C_3 \in \mathcal C$ tal que $x \in C_3 \subset C_1 \cap C_2$.

Sea $\mathcal T$ la colección de conjuntos abiertos de $X$; debemos probar que la [[topología]] $\mathcal T'$ generada por $\mathcal C$ coincide con la topología $\mathcal T$. En primer lugar, nótese que si $U \in \mathcal T$ y $x \in U$, entonces, por hipótesis, $\exists C \in \mathcal C$ tal que $x \in C \subset U$. Se sigue que $U \in \mathcal T'$, por definición. Recíprocamente, si $W \in \mathcal T'$, entonces $W$ es igual a una unión de elementos de $\mathcal C$ por [[lema topología igual a la colección de todas las uniones de la base]]. Ya que cada elemento de $\mathcal C$ pertenece a $\mathcal T$ y $\mathcal T$ es una topología, $W \in \mathcal T$ también.
Tags: demostración top
<!--ID: 1718723531861-->
END