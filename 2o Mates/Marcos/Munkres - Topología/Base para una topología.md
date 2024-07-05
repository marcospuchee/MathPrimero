### Contenido principal

**Fecha:** 2024-06-06, 19:51

```ad-formal
title: Formal definition
Si $X$ es un conjunto, una base para una [[topología]] sobre $X$ es una colección $\mathcal B$ de subconjuntos de $X$ (llamados elementos básicos) tales que:
1. Para cada $x \in X$, hay al menos un elemento básico $B$ que contiene a $x$.
2. Si $x$ pertenece a la intersección de dos elementos básicos $B_1$ y $B_2$, entonces $\exists B_3$ elemento básico que contiene a $x$ y tal que $B_3 \subset B_1 \cap B_2$.

Si $\mathcal B$ satisface estas dos condiciones, se define la topología $\mathcal T$ generada por $\mathcal B$ como sigue: *$U \subset X$ se dice que es [[conjunto abierto]] en $\mathcal T$, si para cada $x \in U$, $\exists B \in \mathcal B$ tal que $x \in B$ y $B \subset U$*. Definición alternativa en [[Lema topología igual a la colección de todas las uniones de la base]]
```

```ad-note
**Demostración de que una colección $\mathcal T$ generada por una base $\mathcal B$ es una topología sobre $X$.**
Si $U$ es el conjunto vacío, satisface la condición de ser abierto trivialmente. De la misma forma, $X \in \mathcal T$, puesto que $\forall x \in X, \exists B$ elemento básico tal que $x \in B$ y $B \subset X$ (por definición).

Tomemos una familia indexada $\{U_\alpha \}_{\alpha \in J}$ de elementos de $\mathcal T$ y probemos que
$$U = \bigcup_{\alpha \in J} U_\alpha$$
pertenece a $\mathcal T$. Dado $x \in U, \exists \alpha \in J$ tal que $x \in U_\alpha$. Puesto que $U_\alpha \in \mathcal T, \exists B \in \mathcal B$ tal que $x \in B \subset U_\alpha$. Entonces $x \in B$ y $B \subset U$, por lo que $U$ es abierto, por definición.

Tomemos ahora dos elementos $U_1$ y $U_2$ de $\mathcal T$, y probemos que $U_1 \cap U_2 \in \mathcal T$. Dado $x \in U_1 \cap U_2$, elegimos $B_1 \in \mathcal B$ tal que $x \in B_1$ y $B_1 \subset U_1$; elijamos también $B_2 \in \mathcal B$ tal que $x \in B_2$ y $B_2 \subset U_2$. La segunda condición para ser una base nos permite elegir un $B_3 \in \mathcal B$ que contenga $x$ y tal que $B_3 \subset B_1 \cap B_2$. Por tanto, $x \in B_3$ y $B_3 \subset U_1 \cap U_2$, por lo que $U_1 \cap U_2 \in \mathcal T$, por definición.

Finalmente, mostramos por inducción que cualquier intersección finita de elementos de $\mathcal T$ está en $\mathcal T$. Este hecho es trivial para $n=1$; supongamos que es cierto para $n-1$ y probémoslo para $n$. Tenemos:
$$(U_1 \cap \dots \cap U_n) = (U_1 \cap \dots \cap U_{n-1}) \cap U_n.$$
Por hipótesis, $U_1 \cap \dots \cap U_{n-1} \in \mathcal T$; utilizando el resultado que acabamos de probar, la intersección de $U_1 \cap \dots \cap U_{n-1}$ y $U_n$ también pertenece a $\mathcal T$.

Así, hemos comprobado que la colección de conjuntos abiertos geenrados por una base $\mathcal B$ es una [[topología]].
```

**Tema:** [[Espacios topológicos y funciones continuas#2. Base de una topología]]
**Referencias:**
**Proposiciones:** [[Lema base a partir de topología]]
**Teoremas:**

---
### Anki

START
Básico
Anverso: Definición de base para una topología
Reverso: Si $X$ es un conjunto, una base para una [[topología]] sobre $X$ es una colección $\mathcal B$ de subconjuntos de $X$ (llamados elementos básicos) tales que:
1. Para cada $x \in X$, hay al menos un elemento básico $B$ que contiene a $x$.
2. Si $x$ pertenece a la intersección de dos elementos básicos $B_1$ y $B_2$, entonces $\exists B_3$ elemento básico que contiene a $x$ y tal que $B_3 \subset B_1 \cap B_2$.
Tags: definición top
<!--ID: 1718723531925-->
END

START
Básico
Anverso: Definición de topología generada por una base
Reverso: Si $\mathcal B$ satisface es una base para una topología, se define la topología $\mathcal T$ generada por $\mathcal B$ como sigue: *$U \subset X$ se dice que es [[conjunto abierto]] en $\mathcal T$, si para cada $x \in U$, $\exists B \in \mathcal B$ tal que $x \in B$ y $B \subset U$*. Definición alternativa en [[Lema topología igual a la colección de todas las uniones de la base]]
Tags: definición top
<!--ID: 1718723531935-->
END

START
Básico
Anverso: Demostración de que la topología generada por una base es una topología
Reverso: Si $U$ es el conjunto vacío, satisface la condición de ser abierto trivialmente. De la misma forma, $X \in \mathcal T$, puesto que $\forall x \in X, \exists B$ elemento básico tal que $x \in B$ y $B \subset X$ (por definición).

Tomemos una familia indexada $\{U_\alpha \}_{\alpha \in J}$ de elementos de $\mathcal T$ y probemos que
$$U = \bigcup_{\alpha \in J} U_\alpha$$
pertenece a $\mathcal T$. Dado $x \in U, \exists \alpha \in J$ tal que $x \in U_\alpha$. Puesto que $U_\alpha \in \mathcal T, \exists B \in \mathcal B$ tal que $x \in B \subset U_\alpha$. Entonces $x \in B$ y $B \subset U$, por lo que $U$ es abierto, por definición.

Tomemos ahora dos elementos $U_1$ y $U_2$ de $\mathcal T$, y probemos que $U_1 \cap U_2 \in \mathcal T$. Dado $x \in U_1 \cap U_2$, elegimos $B_1 \in \mathcal B$ tal que $x \in B_1$ y $B_1 \subset U_1$; elijamos también $B_2 \in \mathcal B$ tal que $x \in B_2$ y $B_2 \subset U_2$. La segunda condición para ser una base nos permite elegir un $B_3 \in \mathcal B$ que contenga $x$ y tal que $B_3 \subset B_1 \cap B_2$. Por tanto, $x \in B_3$ y $B_3 \subset U_1 \cap U_2$, por lo que $U_1 \cap U_2 \in \mathcal T$, por definición.

Finalmente, mostramos por inducción que cualquier intersección finita de elementos de $\mathcal T$ está en $\mathcal T$. Este hecho es trivial para $n=1$; supongamos que es cierto para $n-1$ y probémoslo para $n$. Tenemos:
$$(U_1 \cap \dots \cap U_n) = (U_1 \cap \dots \cap U_{n-1}) \cap U_n.$$
Por hipótesis, $U_1 \cap \dots \cap U_{n-1} \in \mathcal T$; utilizando el resultado que acabamos de probar, la intersección de $U_1 \cap \dots \cap U_{n-1}$ y $U_n$ también pertenece a $\mathcal T$.

Así, hemos comprobado que la colección de conjuntos abiertos geenrados por una base $\mathcal B$ es una [[topología]].
Tags: demostración top
<!--ID: 1718723531946-->
END