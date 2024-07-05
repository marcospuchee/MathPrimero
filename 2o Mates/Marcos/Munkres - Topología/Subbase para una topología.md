### Contenido principal

**Fecha:** 2024-06-18, 14:30

```ad-formal
title: Formal definition
Una subbase $\mathcal S$ para una [[topología]] sobre $X$ es una colección de subconjuntos de $X$ cuya unión es igual a $X$. La topología generada por la subbase $\mathcal S$ se define como la colección $\mathcal T$ de todas las uniones de intersecciones finitas de elementos de $\mathcal S$.
```

```ad-note
**Demostración de que la topología $\mathcal T$ generada por la subbase $\mathcal S$ es topología.**
Para este propósito será suficiente mostrar que la colección $\mathcal B$ de todas las intersecciones finitas de elementos de $\mathcal S$ es una base, y consiguientemente, la colección $\mathcal T$ de todas las uniones de elementos de $\mathcal B$ será una topología por el [[lema topología igual a la colección de todas las uniones de la base]].

Dado $x \in X$, pertenece a un elemento de $S$, y de aquí a un elemento de $\mathcal B$; esta es la primera condición para una [[base para una topología]]. Para comprobar la segunda condición, sean
$$B_1 = S_1 \cap \dots \cap S_m, \quad B_2 = S_1' \cap \dots \cap S_n'$$
dos elementos de $\mathcal B$. Su intersección
$$B_1 \cap B_2 = (S_1 \cap \dots \cap S_m) \cap (S_1' \cap \dots \cap S_n')$$
es también una intersección finita de elementos de $\mathcal S$, por lo que pertenece a $\mathcal B$.
```

**Tema:** [[Espacios topológicos y funciones continuas#2. Base de una topología]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Definición de subbase para una topología
Reverso: Una subbase $\mathcal S$ para una [[topología]] sobre $X$ es una colección de subconjuntos de $X$ cuya unión es igual a $X$.
Tags: definición top
<!--ID: 1718723531819-->
END

START
Básico
Anverso: Definición de topología generada por una subbase
Reverso: La topología generada por la subbase $\mathcal S$ se define como la colección $\mathcal T$ de todas las uniones de intersecciones finitas de elementos de $\mathcal S$.
Tags: definición top
<!--ID: 1718723531829-->
END

START
Básico
Anverso: Demostración de que la topología $\mathcal T$ generada por la subbase $\mathcal S$ es topología.
Reverso: Para este propósito será suficiente mostrar que la colección $\mathcal B$ de todas las intersecciones finitas de elementos de $\mathcal S$ es una base, y consiguientemente, la colección $\mathcal T$ de todas las uniones de elementos de $\mathcal B$ será una topología por el [[lema topología igual a la colección de todas las uniones de la base]].

Dado $x \in X$, pertenece a un elemento de $S$, y de aquí a un elemento de $\mathcal B$; esta es la primera condición para una [[base para una topología]]. Para comprobar la segunda condición, sean
$$B_1 = S_1 \cap \dots \cap S_m, \quad B_2 = S_1' \cap \dots \cap S_n'$$
dos elementos de $\mathcal B$. Su intersección
$$B_1 \cap B_2 = (S_1 \cap \dots \cap S_m) \cap (S_1' \cap \dots \cap S_n')$$
es también una intersección finita de elementos de $\mathcal S$, por lo que pertenece a $\mathcal B$.
Tags: demostración top
<!--ID: 1718723531839-->
END