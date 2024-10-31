### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ [[espacio topológico]], $S \subseteq X$, $x \in X$ y $\mathcal B(x)$ [[base de entornos]] de $x$.

$$x \in \textrm{ad}(S) \iff \forall B \in \mathcal B(x), \, B \cap S \neq \emptyset.$$
```

```ad-note
Notemos que si $(X, d)$ [[espacio métrico]] y $S \subseteq X$. Entonces,
$$x \in \textrm{ad}(S) \iff \forall \varepsilon >0 \quad B(x; \varepsilon) \cap S \neq \emptyset.$$
```

```ad-proof
$\rightarrow$. $x \in \textrm{ad}(S)$. Sea $B \in \mathcal B(x)$, entonces $B \in \mathcal E(x)$, luego por definición $B \cap S \neq \emptyset$.

$\leftarrow$. Supongamos que $\forall B \in \mathcal B(x)$ se cumple que $B \cap S \neq \emptyset$. Sea $U \in \mathcal E(x)$, entonces $\exists B \in \mathcal B(x)$ tal que $B \subseteq U$. Como $B \cap S \neq \emptyset$, entonces $U \cap S \neq \emptyset$, luego $x \in \textrm{ad}(S)$.
```

**Tema:** [[Puntos especiales#1. Puntos de adherencia.]]

---
### Anki

START
Básico
Anverso: Caracterización de punto de adherencia
Reverso: Sean $(X, \mathcal T)$ [[espacio topológico]], $S \subseteq X$, $x \in X$ y $\mathcal B(x)$ [[base de entornos]] de $x$.

$$x \in \textrm{ad}(S) \iff \forall B \in \mathcal B(x), \, B \cap S \neq \emptyset.$$
<!--ID: 1728138052366-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ [[espacio topológico]], $S \subseteq X$, $x \in X$ y $\mathcal B(x)$ [[base de entornos]] de $x$.

$$x \in \textrm{ad}(S) \iff \forall B \in \mathcal B(x), \, B \cap S \neq \emptyset.$$
Reverso: 
$\rightarrow$. $x \in \textrm{ad}(S)$. Sea $B \in \mathcal B(x)$, entonces $B \in \mathcal E(x)$, luego por definición $B \cap S \neq \emptyset$.

$\leftarrow$. Supongamos que $\forall B \in \mathcal B(x)$ se cumple que $B \cap S \neq \emptyset$. Sea $U \in \mathcal E(x)$, entonces $\exists B \in \mathcal B(x)$ tal que $B \subseteq U$. Como $B \cap S \neq \emptyset$, entonces $U \cap S \neq \emptyset$, luego $x \in \textrm{ad}(S)$.
Tags: dem top
<!--ID: 1728138052368-->
END
