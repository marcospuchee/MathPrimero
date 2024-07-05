
---
mathLink: $\mathcal T = \{\bigcup B: B \subseteq \mathcal B \}$
---
### Contenido Principal

**Fecha:** 2024-06-06, 20:56

```ad-lemma
Sean $X$ un conjunto y $\mathcal B$ una [[base para una topología]] $\mathcal T$ ([[topología]]) sobre $X$. Entonces $\mathcal T$ es igual a la colección de todas las uniones de elementos de $\mathcal B$.
```

```ad-proof
Dada una colección de elementos de $\mathcal B$, también son elementos de $\mathcal T$. Puesto que $\mathcal T$ es una [[topología]], la unión de ellos pertenece a $\mathcal T$. Recíprocamente, dado $U \in \mathcal T$, elijamos para cada $x \in U$ un elemento $B_x$ de $\mathcal B$ tal que $x \in B_x \subset U$. Entonces $U = \bigcup_{x \in U} B_x$, por lo que $U$ es igual a la unión de elementos de $\mathcal B$.
```



**Tema:** [[Espacios topológicos y funciones continuas#2. Base de una topología]]
**Corolarios:** [[Lema base a partir de topología]], [[Subbase para una topología]]

---
### Anki

START
Básico
Anverso: Qué lema nos permite formar una topología a partir de una base?
Reverso: Sean $X$ un conjunto y $\mathcal B$ una [[base para una topología]] $\mathcal T$ ([[topología]]) sobre $X$. Entonces $\mathcal T$ es igual a la colección de todas las uniones de elementos de $\mathcal B$.
Tags: proposición/teorema top
<!--ID: 1718723531904-->
END

START
Básico
Anverso: Demostración de que sean $X$ un conjunto y $\mathcal B$ una [[base para una topología]] $\mathcal T$ ([[topología]]) sobre $X$. Entonces $\mathcal T$ es igual a la colección de todas las uniones de elementos de $\mathcal B$.
Reverso: Dada una colección de elementos de $\mathcal B$, también son elementos de $\mathcal T$. Puesto que $\mathcal T$ es una [[topología]], la unión de ellos pertenece a $\mathcal T$. Recíprocamente, dado $U \in \mathcal T$, elijamos para cada $x \in U$ un elemento $B_x$ de $\mathcal B$ tal que $x \in B_x \subset U$. Entonces $U = \bigcup_{x \in U} B_x$, por lo que $U$ es igual a la unión de elementos de $\mathcal B$.
Tags: demostración top
<!--ID: 1718723531915-->
END