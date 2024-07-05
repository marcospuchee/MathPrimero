
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-06-18, 22:09

```ad-theorem
Si $\mathcal B$ es una base para la topología de $X$ ([[base para una topología]]) y $\mathcal C$ es una base para la topología de $Y$, entonces la colección
$$\mathcal D = \{B \times C \, | \, B \in \mathcal B \textrm{ y } C \in \mathcal C \}$$
es una base para la topología sobre $X \times Y$.
```

```ad-proof
Utilizamos el [[lema base a partir de topología]]. Dado un [[conjunto abierto]] $W$ de $X \times Y$ y un punto $x \times y \in W$, por definición de la [[topología producto]], $\exists U \times V$ elemento básico tal que $x \times y \in U \times V \subset W$. Puesto que $\mathcal B$ y $\mathcal C$ son bases para $X$ e $Y$, respectivamente, podemos elegir $B \in \mathcal B$ tal que $x \in B \subset U$, y $C \in \mathcal C$ tal que $y \in C \subset V$. Por tanto, $x \times y \in B \times C \subset W$. Así, la colección $\mathcal D$ cumple el criterio del [[lema base a partir de topología]], por lo que $\mathcal D$ es una base para $X \times Y$.
```


**Tema:** [[Espacios topológicos y funciones continuas#4. Topología producto sobre $X times Y$]]
**Demostrado por:**
**Consecuencias:**

---
### Anki
