### Contenido Principal

```ad-proposition
Ser metrizable es propiedad topológica. Sea $(X, \mathcal T)$ espacio topológico metrizable y $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $(Y, \mathcal T')$ es metrizable.
```

```ad-proof
Definimos $d'(y_1, y_2):=d(x_1, x_2)$ donde $x_1, x-2 \in X$; $f(x_1) = y_1$, $f(x_2)= y_2$. Trivialmente, $d'$ es métrica.

Veamos que $\mathcal T_{d'} = \mathcal T'$.

$\supseteq$. Sea $A \in \mathcal T'$. Como $f$ es continua, $f^{-1}(A) \in \mathcal T_d$ $\implies$ $\exists \varepsilon > 0$ tal que $B_d(x; \varepsilon) \subseteq f^{-1}(A)$ $\implies$ $B_{d'}(f(x); \varepsilon)$ $=$ $f(\{z \in X: d(x, z) < \varepsilon \})$ $=$ $f(B_d(x; \varepsilon))$ $\subseteq$ $f(f^{-1}(A))$ $=$ $A$. Luego $A \in \mathcal T_{d'}$, lo que implica que $\mathcal T' \subseteq \mathcal T_{d'}$.

$\subseteq$. Sea $z \in B_d(x; \varepsilon)$ $\implies$ $d'(f(z), f(x)) = d(x,z) < \varepsilon$ $\implies$ $f(z) \in B_{d'}(f(x); \varepsilon)$. Sea $y \in B_{d'}(a; \varepsilon$ $\implies$ $d'(y,a) = d(f^{-1}(y), f^{-1}(a)) < \varepsilon$ $\implies$ $f^{-1}(y) \in B_d(f^{-1}(a); \varepsilon)$. Por tanto, acabamos de ver que dado $A \in \mathcal T_{d'}$, entonces $f^{-1}(A) \in \mathcal T_d$, lo que implica que $f(f^{-1}(A)) = A \in \mathcal T'$, luego $\mathcal T_{d'} \subseteq \mathcal T'$.


```

**Tema:** [[Continuidad#2. Homeomorfismos.]]

**Definiciones referenciadas:** [[Homeomorfismo]], [[Métrica]], [[Bola abierta]]
**Resultados referenciados:** [[Caracterización de continuidad global (antiimagen de abiertos)]]

---
### Anki

START
Básico
Anverso: Qué propiedades son topológicas?
Reverso: 2AN, 1AN, separable, metrizable, Hausdorff
Tags: top
<!--ID: 1731446305362-->
END


START
Básico
Anverso: Demostración de que ser metrizable es propiedad topológica. Sea $(X, \mathcal T)$ espacio topológico metrizable y $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $(Y, \mathcal T')$ es metrizable.
Reverso: Definimos $d'(y_1, y_2):=d(x_1, x_2)$ donde $x_1, x-2 \in X$; $f(x_1) = y_1$, $f(x_2)= y_2$. Trivialmente, $d'$ es métrica.

Veamos que $\mathcal T_{d'} = \mathcal T'$.

$\supseteq$. Sea $A \in \mathcal T'$. Como $f$ es continua, $f^{-1}(A) \in \mathcal T_d$ $\implies$ $\exists \varepsilon > 0$ tal que $B_d(x; \varepsilon) \subseteq f^{-1}(A)$ $\implies$ $B_{d'}(f(x); \varepsilon)$ $=$ $f(\{z \in X: d(x, z) < \varepsilon \})$ $=$ $f(B_d(x; \varepsilon))$ $\subseteq$ $f(f^{-1}(A))$ $=$ $A$. Luego $A \in \mathcal T_{d'}$, lo que implica que $\mathcal T' \subseteq \mathcal T_{d'}$.

$\subseteq$. Sea $z \in B_d(x; \varepsilon)$ $\implies$ $d'(f(z), f(x)) = d(x,z) < \varepsilon$ $\implies$ $f(z) \in B_{d'}(f(x); \varepsilon)$. Sea $y \in B_{d'}(a; \varepsilon$ $\implies$ $d'(y,a) = d(f^{-1}(y), f^{-1}(a)) < \varepsilon$ $\implies$ $f^{-1}(y) \in B_d(f^{-1}(a); \varepsilon)$. Por tanto, acabamos de ver que dado $A \in \mathcal T_{d'}$, entonces $f^{-1}(A) \in \mathcal T_d$, lo que implica que $f(f^{-1}(A)) = A \in \mathcal T'$, luego $\mathcal T_{d'} \subseteq \mathcal T'$.
Tags: dem top
<!--ID: 1731446305365-->
END