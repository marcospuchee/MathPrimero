### Contenido Principal

```ad-proposition
Sea $f:(X, \mathcal T) \to (Y, \mathcal T')$ y $\{C_i\}_{1, \dots n}$ una familia finita de de subconjuntos de $X$ cerrados tal que $X = \bigcup_{i =1}^n C_i$ y $f_{\restriction_{C_i}}$ es continua $\forall i = 1, \dots ,n$, entonces $f$ es continua. 
```

```ad-proof
Sea $C'$ cerrado en $\mathcal T'$, entonces
$$\begin{eqnarray} f^{-1}(C') &=& f^{-1}(C') \cap X = f^{-1}(C') \cap \left ( \bigcup_{i = 1}^n C_i \right ) = \bigcup_{i = 1}^n (f^{-1}(C') \cap C_i) \\ &=& \bigcup_{i = 1}^n f^{-1}_{\restriction_{C_i}}(C').
\end{eqnarray}$$
Luego, como $f_{\restriction_{C_i}}$ es continua, $f^{-1}_{\restriction_{C_i}}(C')$ es cerrado en $(C_i, \mathcal T_{C_i})$. Además, Como $C_i$ es cerrado en $\mathcal T$, entonces, $f^{-1}_{\restriction_{C_i}}(C')$ es cerrado en $\mathcal T$. Luego, por ser unión finita de cerrados, $f^{-1}(C')$ es cerrado en $\mathcal T$, lo que implica que $f$ es continua.
```

**Tema:** [[Subespacios topológicos#3. Continuidad y subespacios.]]

**Definiciones referenciadas:** [[Función continua]]
**Resultados referenciados:** [$f^{-1}(C')$ cerrado en $\mathcal T$ $\implies$ $f$ es continua](Caracterización de continuidad global (antiimagen de cerrados)), [Unión finita de cerraod es cerrada](Analogía propiedades conjunto abierto y conjunto cerrado)

---
### Anki

START
Básico
Anverso: Función continua a partir de restricción del dominio a conjuntos cerrados
Reverso: Sea $f:(X, \mathcal T) \to (Y, \mathcal T')$ y $\{C_i\}_{1, \dots n}$ una familia finita de de subconjuntos de $X$ cerrados tal que $X = \bigcup_{i =1}^n C_i$ y $f_{\restriction_{C_i}}$ es continua $\forall i = 1, \dots ,n$, entonces $f$ es continua.
Tags: top
<!--ID: 1732364239611-->
END

START
Básico
Anverso: Demostración de que sea $f:(X, \mathcal T) \to (Y, \mathcal T')$ y $\{C_i\}_{1, \dots n}$ una familia finita de de subconjuntos de $X$ cerrados tal que $X = \bigcup_{i =1}^n C_i$ y $f_{\restriction_{C_i}}$ es continua $\forall i = 1, \dots ,n$, entonces $f$ es continua.
Reverso: Sea $C'$ cerrado en $\mathcal T'$, entonces
$$\begin{eqnarray} f^{-1}(C') &=& f^{-1}(C') \cap X = f^{-1}(C') \cap \left ( \bigcup_{i = 1}^n C_i \right ) = \bigcup_{i = 1}^n (f^{-1}(C') \cap C_i) \\ &=& \bigcup_{i = 1}^n f^{-1}_{\restriction_{C_i}}(C').
\end{eqnarray}$$
Luego, como $f_{\restriction_{C_i}}$ es continua, $f^{-1}_{\restriction_{C_i}}(C')$ es cerrado en $(C_i, \mathcal T_{C_i})$. Además, Como $C_i$ es cerrado en $\mathcal T$, entonces, $f^{-1}_{\restriction_{C_i}}(C')$ es cerrado en $\mathcal T$. Luego, por ser unión finita de cerrados, $f^{-1}(C')$ es cerrado en $\mathcal T$, lo que implica que $f$ es continua.
Tags: dem top
<!--ID: 1732364239613-->
END
