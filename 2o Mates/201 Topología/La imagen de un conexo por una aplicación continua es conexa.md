### Contenido Principal

```ad-proposition
$f: (X, \mathcal T) \to (Y, \mathcal T')$ aplicación continua y $(X, \mathcal T)$ conexo, entonces $f(X)$ es subespacio conexo de $(Y, \mathcal T')$.
```

```ad-proof
Sea $B \subseteq f(X)$ abierto y cerrado a la vez en $\mathcal T'_{f(X)}$. Notemos que $f:(X, \mathcal T) \to (f(X), \mathcal T_{f(X)}')$ es continua, entonces $f^{-1}(B)$ es abierto y cerrado a la vez, pero como $(X, \mathcal T)$ es conexo, los único abiertos y cerrados a la vez son $X$ o $\emptyset$, lo que implica que o $f^{-1}(B) = \emptyset$ o $f^{-1}(B) = X$. Si $f^{-1}(B) = \emptyset$, entonces $B = \emptyset$. Si $f^{-1}(B) = X$, entonces $B = f(f^{-1}(B)) = f(X)$. Por tanto, los únicos abiertos y cerrados a la vez en $(f(X), \mathcal T_{f(X)}')$ son $\emptyset$ o $f(X)$, lo que implica que $(f(X), \mathcal T_{f(X)}')$ es conexo.
```

**Tema:** [[Conexión#1. Definición.]]

**Definiciones referenciadas:** [[Función continua]], [Espacio topológico conexo](Espacio topológico disconexo), 
**Resultados referenciados:** [$(X, \mathcal T)$ conexo $\iff$ $X, \emptyset$ son los únicos abiertos y cerrados a la vez](Caracterización de espacio topológico conexo (total y vacío unicos abiertos y cerrados a la vez)), [$f$ es continua $\iff$ $\forall A \in \mathcal T'$, $f^{-1}(A) \in \mathcal T$](Caracterización de continuidad global (antiimagen de abiertos)), [$f$ es continua $\iff$ $\forall C$ cerrado en $\mathcal T'$, $f^{-1}(C)$ es cerrado en $\mathcal T$](Caracterización de continuidad global (antiimagen de cerrados))

---
### Corolario

```ad-cor
La conexión es propiedad topológica. Es decir, si $(X, \mathcal T)$ y $(Y, \mathcal T')$ son homeomorfos y $(X, \mathcal T)$ es conexo, entonces $(Y, \mathcal T')$ es conexo.
```

**Tema:** [[Conexión#1. Definición.]]

**Definiciones referenciadas:** [Homeomorfos](Homeomorfismo), [Espacio topológico conexo](Espacio topológico disconexo).

---
### Anki

START
Respuesta anidada
$f: (X, \mathcal T) \to (Y, \mathcal T')$ {{c1::aplicación continua}} y $(X, \mathcal T)$ {{c1::conexo}}, entonces $f(X)$ es {{c2::subespacio conexo de $(Y, \mathcal T')$}}.
Tags: top
<!--ID: 1732364239605-->
END

START
Básico
Anverso: Demostración de que $f: (X, \mathcal T) \to (Y, \mathcal T')$ aplicación continua y $(X, \mathcal T)$ conexo, entonces $f(X)$ es subespacio conexo de $(Y, \mathcal T')$.
Reverso: Sea $B \subseteq f(X)$ abierto y cerrado a la vez en $\mathcal T'_{f(X)}$. Notemos que $f:(X, \mathcal T) \to (f(X), \mathcal T_{f(X)}')$ es continua, entonces $f^{-1}(B)$ es abierto y cerrado a la vez, pero como $(X, \mathcal T)$ es conexo, los único abiertos y cerrados a la vez son $X$ o $\emptyset$, lo que implica que o $f^{-1}(B) = \emptyset$ o $f^{-1}(B) = X$. Si $f^{-1}(B) = \emptyset$, entonces $B = \emptyset$. Si $f^{-1}(B) = X$, entonces $B = f(f^{-1}(B)) = f(X)$. Por tanto, los únicos abiertos y cerrados a la vez en $(f(X), \mathcal T_{f(X)}')$ son $\emptyset$ o $f(X)$, lo que implica que $(f(X), \mathcal T_{f(X)}')$ es conexo.
Tags: dem top
<!--ID: 1732364239607-->
END

START
Básico
Anverso: Corolario de que $f: (X, \mathcal T) \to (Y, \mathcal T')$ aplicación continua y $(X, \mathcal T)$ conexo, entonces $f(X)$ es subespacio conexo de $(Y, \mathcal T')$.
Reverso: La conexión es propiedad topológica. Es decir, si $(X, \mathcal T)$ y $(Y, \mathcal T')$ son homeomorfos y $(X, \mathcal T)$ es conexo, entonces $(Y, \mathcal T')$ es conexo.
Tags: top
<!--ID: 1732364239609-->
END


