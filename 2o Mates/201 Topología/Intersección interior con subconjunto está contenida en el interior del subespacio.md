### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ espacio topológico, $S \subseteq H \subseteq X$. Entonces, $\textrm{int}(S) \cap H \subseteq \textrm{int}_H(S)$.
```

```ad-proof
Como $\textrm{int}(S) \in \mathcal T_H$, entonces $\textrm{int}(S) \cap H \in \mathcal T_H$. Además, como $\textrm{int}(S) \subseteq S$, queda claro que $\textrm{int}(S) \cap H \subseteq S$. Como $\textrm{int}_H(S)$ es el mayor abierto contenido en $S$, entonces
$$\textrm{int}(S) \cap H \subseteq \textrm{int}_H(S).$$
```

**Tema:** [[Subespacios topológicos#2. Adherencia, interior y frontera relativa.]]

**Definiciones referenciadas:** [$\textrm{int}(S)$](Punto interior), [$\mathcal T_H$](Topología inducida),
**Resultados referenciados:** [$\textrm{int}(S) \in \mathcal T_H$](Propiedades conjuntos abiertos (respecto a su interior y frontera)), [$\textrm{int}_ H(S)$ es el mayor abierto contenido en $S$](Propiedades conjuntos abiertos (respecto a su interior y frontera))

---

```ad-cor
title: Corollarium
$$\textrm{fr}_H(S) \subseteq \textrm{fr}(S) \cap H.$$
```

```ad-proof
$$\begin{eqnarray}
\textrm{fr}_H(S) &=& \textrm{ad}_H(S) \textrm{\\} \textrm{int}_H(S) \subseteq (\textrm{ad}(S) \cap H) \textrm{\\}(\textrm{int}(S) \cap H) = (\textrm{ad}(S) \textrm{\\} \textrm{int}(S)) \cap H \\ &=& \textrm{fr}(S) \cap H.
\end{eqnarray}$$
```


**Tema:** [[Subespacios topológicos#2. Adherencia, interior y frontera relativa.]]

**Definiciones referenciadas:** [$\textrm{fr}(S)$](Frontera topológica)
**Resultados referenciados:** [$\textrm{fr}(S) = \textrm{ad}(S) \textrm{\\} \textrm{int}(S)$](Caracterización de frontera (definición alternativa)), [$\textrm{int}(S) \cap H \subseteq \textrm{int}_ H(S)$](Intersección interior con subconjunto está contenida en el interior del subespacio)

---
### Anki

START
Básico
Anverso: Cómo es el interior de un subespacio topológico con relación al espacio total
Reverso: Sean $(X, \mathcal T)$ espacio topológico, $S \subseteq H \subseteq X$. Entonces, $\textrm{int}(S) \cap H \subseteq \textrm{int}_H(S)$.
Tags: top
<!--ID: 1731931805246-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ espacio topológico, $S \subseteq H \subseteq X$. Entonces, $\textrm{int}(S) \cap H \subseteq \textrm{int}_H(S)$.
Reverso: Como $\textrm{int}(S) \in \mathcal T_H$, entonces $\textrm{int}(S) \cap H \in \mathcal T_H$. Además, como $\textrm{int}(S) \subseteq S$, queda claro que $\textrm{int}(S) \cap H \subseteq S$. Como $\textrm{int}_H(S)$ es el mayor abierto contenido en $S$, entonces
$$\textrm{int}(S) \cap H \subseteq \textrm{int}_H(S).$$
Tags: dem top
<!--ID: 1731931805255-->
END

START
Básico
Anverso: Cómo es la frontera topológica de un subespacio topológico con relación al espacio total
Reverso: $$\textrm{fr}_H(S) \subseteq \textrm{fr}(S) \cap H.$$
Tags: top
<!--ID: 1731931805264-->
END

START
Básico
Anverso: Demostración de que $$\textrm{fr}_H(S) \subseteq \textrm{fr}(S) \cap H.$$
Reverso: $$\begin{eqnarray}
\textrm{fr}_H(S) &=& \textrm{ad}_H(S) \textrm{\\} \textrm{int}_H(S) \subseteq (\textrm{ad}(S) \cap H) \textrm{\\}(\textrm{int}(S) \cap H) = (\textrm{ad}(S) \textrm{\\} \textrm{int}(S)) \cap H \\ &=& \textrm{fr}(S) \cap H.
\end{eqnarray}$$
Tags: dem top
<!--ID: 1731931805273-->
END



