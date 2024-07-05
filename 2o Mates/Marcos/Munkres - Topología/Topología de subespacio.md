### Contenido principal

**Fecha:** 2024-06-19, 14:37

```ad-formal
title: Formal definition
Sea $X$ un [[espacio topológico]] con [[topología]] $\mathcal T$. Si $Y$ es un subconjunto de $X$, la colección
$$\mathcal T_Y = \{Y \cap U \, | \, U \in \mathcal T \}$$
es una [[topología]] sobre $Y$, denominada topología de subespacio o topología relativa. Con esta topología, $Y$ se denomina subespacio de $X$; sus conjuntos abiertos son todas las intersecciones de conjuntos abiertos de $X$ con $Y$.
```

```ad-note
**Demostración de que $\mathcal T_Y$ es una topología.**
Contiene a $\emptyset$ e $Y$, porque
$$\emptyset = Y \cap \emptyset, \quad Y = Y \cap X.$$
donde $\emptyset$ y $X$ son elementos de $\mathcal T$. El hecho de que sea cerrado para intersecciones finitas y uniones arbitrarias se deduce de las ecuaciones
$$\begin{eqnarray}
(U_1 \cap Y) \cap \dots \cap (U_n \cap Y) &=& (U_1 \cap \dots \cap U_n) \cap Y, \\
\bigcup_{\alpha \in J} (U_\alpha \cap Y) &=& (\bigcup_{\alpha \in J} U_\alpha) \cap Y.
\end{eqnarray}$$
```

**Tema:** [[Espacios topológicos y funciones continuas#5. La topología de subespacio]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki
