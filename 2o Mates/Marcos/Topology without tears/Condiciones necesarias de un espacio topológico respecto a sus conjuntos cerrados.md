
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-06-04, 21:20

```ad-proposition
Sea $(X, \mathcal T)$ un [[espacio topológico]] cualquiera. Entonces,
1. $\emptyset$ y $X$ son conjuntos cerrados ([[conjunto cerrado]]).
2. La intersección de un número (finito o infinito) cualquiera de conjuntos cerrados es un conjunto cerrado.
3. La unión de un número finito de conjuntos cerrados es cerrado.
```


```ad-proof
$(i)$.
Se sigue inmediatamente de [[condiciones necesarias de un espacio topológico respecto a sus conjuntos abiertos]] y de la definición de [[conjunto cerrado]].

$(ii)$.
Se demuestra parecido a $(iii)$, sin embargo, hay que distinguir casos para intersecciones infinitas no numerables de conjuntos.

$(iii)$.
Sean $S_1, S_2, \dots, S_n$ conjuntos cerrados. Tenemos que comprobar que $S_1 \cup S_2 \cup \dots \cup S_n$ es un conjunto cerrado. Por definición de conjunto cerrado, basta demostrar que $X \textrm{\\} (S_1 \cup S_2 \cup \dots \cup S_n)$ es un [[conjunto abierto]].
Como $S_1, S_2, \dots, S_n$ son conjuntos cerrados, sus complementos $X \textrm{\\} S_1, X \textrm{\\} S_2, \dots, X \textrm{\\} S_n$ son conjuntos abiertos. Pero,
$$X \textrm{\\} (S_1 \cup S_2 \cup \dots \cup S_n) = (X \textrm{\\} S_1) \cap (X \textrm{\\} S_2) \cap \dots \cap (X \textrm{\\} S_n).$$
Como a la derecha tenemos una intersección finita de conjuntos abiertos, es un conjunto abierto. Por tanto, $X \textrm{\\} (S_1 \cup S_2 \cup \dots \cup S_n)$ es un conjunto abierto. Así, $S_1 \cup S_2 \cup \dots \cup S_n$ es un conjunto cerrado.
```

**Tema:** [[2o Mates/Marcos/Topology without tears/Espacios topológicos#2. Conjuntos abiertos, conjuntos cerrados y conjuntos clopen]]
**Corolarios:**

---
### Anki
