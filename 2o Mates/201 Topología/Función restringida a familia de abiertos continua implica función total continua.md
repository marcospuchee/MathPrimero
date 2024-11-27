### Contenido Principal

```ad-proposition
Sean $f: (X, \mathcal T) \to (Y, \mathcal T')$ y $\{A_i \}_{i \in I} \subseteq \mathcal T$ familia de subconjuntos de $X$ abiertos tales que $X = \bigcup_{i \in I} A_i$ y $f \restriction_{A_i}$ es continua $\forall i \in I$. Entonces, $f$ es continua.
```

```ad-proof
Sea $x \in X = \bigcup_{i \in I} A_i$, entonces $\exists i_0$ tal que $x \in A_{i_0}$. Como $A_{i_0} \in \mathcal T$, entonces $A_{i_0} \in \mathcal E(x)$. Esto implica por el resultado anterior que $f$ es continua.
```

**Tema:** [[Subespacios topológicos#3. Continuidad y subespacios.]]

**Definiciones referenciadas:** [[Función continua]], [[Entorno]]
**Resultados referenciados:** [$f$ continua en $x_0$ $\iff \exists U \in \mathcal E(x_0) : f \restriction_U$ continua en $x_0$](Caracterización continuidad en un punto (restricción del dominio a entorno))

---
### Anki

START
Básico
Anverso: Función continua a partir de restricción del dominio a conjuntos abiertos
Reverso: Sean $f: (X, \mathcal T) \to (Y, \mathcal T')$ y $\{A_i \}_{i \in I} \subseteq \mathcal T$ familia de subconjuntos de $X$ abiertos tales que $X = \bigcup_{i \in I} A_i$ y $f \restriction_{A_i}$ es continua $\forall i \in I$. Entonces, $f$ es continua.
Tags: top
<!--ID: 1732364239615-->
END

START
Básico
Anverso: Demostración de que sean $f: (X, \mathcal T) \to (Y, \mathcal T')$ y $\{A_i \}_{i \in I} \subseteq \mathcal T$ familia de subconjuntos de $X$ abiertos tales que $X = \bigcup_{i \in I} A_i$ y $f \restriction_{A_i}$ es continua $\forall i \in I$. Entonces, $f$ es continua.
Reverso: Sea $x \in X = \bigcup_{i \in I} A_i$, entonces $\exists i_0$ tal que $x \in A_{i_0}$. Como $A_{i_0} \in \mathcal T$, entonces $A_{i_0} \in \mathcal E(x)$. Esto implica por el resultado anterior que $f$ es continua.
Tags: dem top
<!--ID: 1732364239617-->
END
