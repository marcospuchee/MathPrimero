### Contenido Principal

```ad-theorem
Un subespacio de $(\mathbb R, \mathcal T_u)$ es conexo $\iff$ es un intervalo.
```

```ad-proof
$\Rightarrow$.
Supongamos, por contrarrecíproco, que $S$ no es un intervalo, luego $\exists x,y \in S$, $z \in \mathbb R \textrm{\\}S$ tal que $x < z < y$. Entonces, $]-\infty, z[ \cap S \in \mathcal T_S$ y $]z, + \infty[ \cap S \in \mathcal T_S$. Notemos que
$$ (]-\infty, z[ \cap S) \cup (]z, + \infty[ \cap S) = S; \quad (]-\infty, z[ \cap S) \cap (]z, + \infty[ \cap S) = \emptyset.$$
Luego, tenemos una partición de abiertos, y entonces, $S$ es disconexo.

$\Leftarrow$.
Supongamos, por reducción al absurdo, que $S$ es intervalo y no conexo. Entonces, $\exists f: (S, \mathcal T_{u_S}) \to (\mathbb R, \mathcal T_u)$ continua tal que $\exists x,y \in S$ con $x<y$ tales que $f(x) \neq f(y)$, $\exists c \in \mathbb R$ tal que $f(x) < c < f(y)$ y $\forall z \in S$, $f(z) \neq c$, entonces $\exists f:[x,y] \to \mathbb R$ continua y no cumple el teorema de Bolzano, lo cual es una contradicción. Por tanto, $S$ es conexo.
```

**Tema:** [[Conexión#2. Subespacios conexos de $( mathbb R, mathcal T_u)$.]]

**Definiciones referenciadas:** [Espacio topológico conexo](Espacio topológico disconexo), [[Intervalo]], [[Espacio topológico disconexo]], 
**Resultados referenciados:** [$(X, \mathcal T)$ conexo $\iff \forall f:(X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua cumple que $\forall x,y \in X$ $:$ $(\exists c \in \mathbb R$ $:$ $f(x) < c < f(y))$ $\implies$ $\exists z \in X$ $:$ $f(z) = z$](Caracterización de espacio topológico conexo (función a los reales con la topología usual))

---
### Corolarios

```ad-cor
$(\mathbb R, \mathcal T_u)$ es conexo.
```

```ad-cor
title: Corollarium

$f:(X, \mathcal T) \to (\mathbb R, \mathcal  T_u)$ continua y $(X, \mathcal T)$ conexo, entonces $f(X)$ es un intervalo.
```


**Tema:** [[Conexión#2. Subespacios conexos de $( mathbb R, mathcal T_u)$.]]

**Definiciones referenciadas:** [Espacio topológico conexo](Espacio topológico disconexo), [[Función continua]], [[Intervalo]]

---
### Anki.

START
Básico
Anverso: Caracterización de subespacio de $(\mathbb R, \mathcal T_u)$ conexo (intervalo)
Reverso: Un subespacio de $(\mathbb R, \mathcal T_u)$ es conexo $\iff$ es un intervalo.
Tags: top
<!--ID: 1732364239598-->
END

START
Básico
Anverso: Demostración de que un subespacio de $(\mathbb R, \mathcal T_u)$ es conexo $\iff$ es un intervalo.
Reverso: $\Rightarrow$.
Supongamos, por contrarrecíproco, que $S$ no es un intervalo, luego $\exists x,y \in S$, $z \in \mathbb R \textrm{\\}S$ tal que $x < z < y$. Entonces, $]-\infty, z[ \cap S \in \mathcal T_S$ y $]z, + \infty[ \cap S \in \mathcal T_S$. Notemos que
$$ (]-\infty, z[ \cap S) \cup (]z, + \infty[ \cap S) = S; \quad (]-\infty, z[ \cap S) \cap (]z, + \infty[ \cap S) = \emptyset.$$
Luego, tenemos una partición de abiertos, y entonces, $S$ es disconexo.

$\Leftarrow$.
Supongamos, por reducción al absurdo, que $S$ es intervalo y no conexo. Entonces, $\exists f: (S, \mathcal T_{u_S}) \to (\mathbb R, \mathcal T_u)$ continua tal que $\exists x,y \in S$ con $x<y$ tales que $f(x) \neq f(y)$, $\exists c \in \mathbb R$ tal que $f(x) < c < f(y)$ y $\forall z \in S$, $f(z) \neq c$, entonces $\exists f:[x,y] \to \mathbb R$ continua y no cumple el teorema de Bolzano, lo cual es una contradicción. Por tanto, $S$ es conexo.
Tags: dem top
<!--ID: 1732364239600-->
END

START
Básico
Anverso: Corolarios de que un subespacio de $(\mathbb R, \mathcal T_u)$ es conexo $\iff$ es un intervalo.
Reverso: $(\mathbb R, \mathcal T_u)$ es conexo, y $f:(X, \mathcal T) \to (\mathbb R, \mathcal  T_u)$ continua y $(X, \mathcal T)$ conexo, entonces $f(X)$ es un intervalo.
Tags: top
<!--ID: 1732364239602-->
END
