### Contenido Principal

```ad-proposition
$(X, \mathcal T)$ conexo $\iff$ $\forall f: (X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua cumple que $\forall x,y \in X$ tales que $\exists c \in \mathbb R$ tal que $f(x) < c < f(y)$, entonces $\exists z \in X$ tal que $f(z) = c$.
```

```ad-proof
$\Rightarrow$.
Supongamos, por contrarrecíproco, que $\exists f:(X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua tal que $\exists x,y \in X$, $c \in \mathbb R$ con $f(x) < c < f(y)$ tales que $c \notin f(X)$. Entonces, $x \in f(]-\infty, c[)$, $y \in f^{-1}(]c, +\infty[)$ son abiertos no vacíos y distintos del total. Nos damos cuenta de que 
$$f^{-1}(]-\infty, c[) \cup f^{-1}(]c, +\infty[) = X; \quad f^{-1}(]-\infty, c[) \cap f^{-1}(]c, +\infty[) = \emptyset,$$
luego $\exists$ partición por abiertos $\implies$ $(X, \mathcal T)$ es disconexo.

$\Leftarrow$. 
Supongamos, por contrarrecíproco, que $(X, \mathcal T)$ es disconexo. Entonces, $\exists g: (X, \mathcal T) \to (\{0,1\}, \mathcal T_D)$ continua y no constante. A partir de $g$ y la función inclusión de $(\{0,1\}, \mathcal T_D) \to (\mathbb R, \mathcal T_u)$, formamos $f:= i \circ g$, que es continua por ser composición de continuas. Por definición, $f(X) = \{0,1\}$. Es decir, $\exists x, y \in X$ tales que $f(x) = 0$ y $f(y) = 1$. Sin embargo, $c = \frac{1}{2}$, $f(x) < c < f(y)$, pero $\nexists z \in X$ tal que $f(z) = c$.
```
 
**Tema:** [[Conexión#1. Definición.]]

**Definiciones referenciadas:** [Espacio topológico conexo](Espacio topológico disconexo), [[Función continua]],
**Resultados referenciados:** [$(X, \mathcal T)$ conexo $\iff$ $\forall f: (X, \mathcal T) \to (\{0,1\}, \mathcal T_D)$ continua es constante](Caracterización espacio topológico conexo (función topología discreta de un conjunto con dos elementos)), [[Aplicación inclusión es continua]], [[Composición de continuas es continua]]

---
### Anki

START
Básico
Anverso: Caracterización de espacio topológico conexo (teorema de Bolzano)
Reverso: $(X, \mathcal T)$ conexo $\iff$ $\forall f: (X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua cumple que $\forall x,y \in X$ tales que $\exists c \in \mathbb R$ tal que $f(x) < c < f(y)$, entonces $\exists z \in X$ tal que $f(z) = c$.
Tags: top
<!--ID: 1732364239636-->
END

START
Básico
Anverso: Demostración de que $(X, \mathcal T)$ conexo $\iff$ $\forall f: (X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua cumple que $\forall x,y \in X$ tales que $\exists c \in \mathbb R$ tal que $f(x) < c < f(y)$, entonces $\exists z \in X$ tal que $f(z) = c$.
Reverso: $\Rightarrow$.
Supongamos, por contrarrecíproco, que $\exists f:(X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua tal que $\exists x,y \in X$, $c \in \mathbb R$ con $f(x) < c < f(y)$ tales que $c \notin f(X)$. Entonces, $x \in f(]-\infty, c[)$, $y \in f^{-1}(]c, +\infty[)$ son abiertos no vacíos y distintos del total. Nos damos cuenta de que 
$$f^{-1}(]-\infty, c[) \cup f^{-1}(]c, +\infty[) = X; \quad f^{-1}(]-\infty, c[) \cap f^{-1}(]c, +\infty[) = \emptyset,$$
luego $\exists$ partición por abiertos $\implies$ $(X, \mathcal T)$ es disconexo.

$\Leftarrow$. 
Supongamos, por contrarrecíproco, que $(X, \mathcal T)$ es disconexo. Entonces, $\exists g: (X, \mathcal T) \to (\{0,1\}, \mathcal T_D)$ continua y no constante. A partir de $g$ y la función inclusión de $(\{0,1\}, \mathcal T_D) \to (\mathbb R, \mathcal T_u)$, formamos $f:= i \circ g$, que es continua por ser composición de continuas. Por definición, $f(X) = \{0,1\}$. Es decir, $\exists x, y \in X$ tales que $f(x) = 0$ y $f(y) = 1$. Sin embargo, $c = \frac{1}{2}$, $f(x) < c < f(y)$, pero $\nexists z \in X$ tal que $f(z) = c$.
Tags: dem top
<!--ID: 1732364239638-->
END

