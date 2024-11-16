### Contenido Principal

```ad-proposition
Hausdorff es propiedad topológica. Sea $(X, \mathcal T)$ espacio topológico Hausdorff y $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $(Y, \mathcal T')$ es Hausdorff.
```

```ad-proof
Supongamos $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo y $(X, \mathcal T)$ Hausdorff. $\forall y_1 \neq y_2 \in Y$, $\exists x_1 \neq x_2 \in X$ tales que $y_1 = f(x_1)$ e $y_2 = f(x_2)$.
Por ser $(X, \mathcal T)$ Hausdorff, $\exists U_1 \in \mathcal E(x_1)$, $\exists U_2 \in \mathcal E(x_2)$ tales que $U_1 \cap U_2  =\emptyset$. 
Como $f^{-1}$ es continua, por definición, $\exists V_1 \in \mathcal E(f(x_1))$ tal que $f^{-1}(V_1) \subseteq U_1$ y $\exists V_2 \in \mathcal E(f(x_2))$ tal que $f^{-1}(V_2) \subseteq U_2$. Está claro que
$$f^{-1}(V_1 \cap V_2) = f^{-1}(V_1) \cap f^{-1}(V_2) = \emptyset \implies V_1 \cap V_2 = \emptyset,$$
luego $(Y, \mathcal T')$ es Hausdorff.
```

**Tema:** [[Continuidad#2. Homeomorfismos.]]

**Definiciones referenciadas:** [[Espacio topológico Hausdorff]], [[Homeomorfismo]], [[Función continua]], [[Entorno]]
**Resultados referenciados:** *ninguna*.

---
### Anki

START
Básico
Anverso: Demostración de que Hausdorff es propiedad topológica. Sea $(X, \mathcal T)$ espacio topológico Hausdorff y $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $(Y, \mathcal T')$ es Hausdorff.
Reverso: Supongamos $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo y $(X, \mathcal T)$ Hausdorff. $\forall y_1 \neq y_2 \in Y$, $\exists x_1 \neq x_2 \in X$ tales que $y_1 = f(x_1)$ e $y_2 = f(x_2)$.
Por ser $(X, \mathcal T)$ Hausdorff, $\exists U_1 \in \mathcal E(x_1)$, $\exists U_2 \in \mathcal E(x_2)$ tales que $U_1 \cap U_2  =\emptyset$. 
Como $f^{-1}$ es continua, por definición, $\exists V_1 \in \mathcal E(f(x_1))$ tal que $f^{-1}(V_1) \subseteq U_1$ y $\exists V_2 \in \mathcal E(f(x_2))$ tal que $f^{-1}(V_2) \subseteq U_2$. Está claro que
$$f^{-1}(V_1 \cap V_2) \subseteq f^{-1}(V_1) \cap f^{-1}(V_2) = \emptyset \implies V_1 \cap V_2 = \emptyset,$$
luego $(Y, \mathcal T')$ es Hausdorff.
Tags: dem top
<!--ID: 1731446305401-->
END