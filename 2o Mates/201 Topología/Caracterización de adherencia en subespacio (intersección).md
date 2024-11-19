### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ espacio topológico y $S \subseteq H \subseteq X$. Se tiene que
$$\textrm{ad}_ H(S) = \textrm{ad}(S) \cap H.$$
```

```ad-proof
$\subseteq$.
Notemos que $\textrm{ad}(S) \cap H$ es cerrado en $\mathcal T_H$ por ser intersección de cerrados. Tenemos que $S \subseteq \textrm{ad}(S) \cap H$, y como $\textrm{ad}_H(S)$ es el menor cerrado en $\mathcal T_H$ que contiene a $S$, $\textrm{ad}_H(S) \subseteq \textrm{ad}(S) \cap H$.

$\supseteq$.
Sean $x \in \textrm{ad}(S) \cap H$, $U \in \mathcal E_H(x)$, entonces $\exists U' \in \mathcal E(x)$ tal que $U = U' \cap H$, y como $x \in \textrm{ad}(S)$, entonces $U' \cap S \neq \emptyset$. Entonces,
$$U \cap S = U' \cap H \cap S = U' \cap S \neq \emptyset \implies x \in \textrm{ad}_H(S).$$
```

**Tema:** [[Subespacios topológicos#2. Adherencia, interior y frontera relativa.]]

**Definiciones referenciadas:** [$\mathcal T_H$](Topología inducida), [$\textrm{ad}(S)$](Adherencia), [$\mathcal E(x)$](Entorno)
**Resultados referenciados:** [$\textrm{ad}(S) \cap H$ es cerrado](Analogía propiedades conjunto abierto y conjunto cerrado), [$\textrm{ad}_ H(S)$ es el menor cerrado en $\mathcal T_H$ que contiene a $S$](Relación conjunto cerrado con adherencia), [$U \in \mathcal E_H(x) \iff \exists U' \in \mathcal E(x) : U = U' \cap H$](Caracterización entorno en topología inducida (entorno topología padre))

---
### Anki

START
Básico
Anverso: Cómo es la adherencia de un subespacio topológico con respecto a la adherencia del subespacio total?
Reverso: Sean $(X, \mathcal T)$ espacio topológico y $S \subseteq H \subseteq X$. Se tiene que
$$\textrm{ad}_ H(S) = \textrm{ad}(S) \cap H.$$
Tags: top
<!--ID: 1731931805301-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ espacio topológico y $S \subseteq H \subseteq X$. Se tiene que
$$\textrm{ad}_ H(S) = \textrm{ad}(S) \cap H.$$
Reverso: $\subseteq$.
Notemos que $\textrm{ad}(S) \cap H$ es cerrado en $\mathcal T_H$ por ser intersección de cerrados. Tenemos que $S \subseteq \textrm{ad}(S) \cap H$, y como $\textrm{ad}_H(S)$ es el menor cerrado en $\mathcal T_H$ que contiene a $S$, $\textrm{ad}_H(S) \subseteq \textrm{ad}(S) \cap H$.

$\supseteq$.
Sean $x \in \textrm{ad}(S) \cap H$, $U \in \mathcal E_H(x)$, entonces $\exists U' \in \mathcal E(x)$ tal que $U = U' \cap H$, y como $x \in \textrm{ad}(S)$, entonces $U' \cap S \neq \emptyset$. Entonces,
$$U \cap S = U' \cap H \cap S = U' \cap S \neq \emptyset \implies x \in \textrm{ad}_H(S).$$
Tags: dem top
<!--ID: 1731931805311-->
END

