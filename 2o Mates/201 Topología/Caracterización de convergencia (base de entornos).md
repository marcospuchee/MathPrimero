### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ [[espacio topológico]], $\{x_n \}_{n = 1}^\infty \subseteq X$, $\mathcal B(x)$ [[base de entornos]] de $X$. Entonces, $\{x_n\} \to x$ $\iff$ $\forall B \in \mathcal B(x)$, $\exists n_0 \in \mathbb N$ tal que $\forall n > n_0$, $x_n \in B$.
```

```ad-proof
$\rightarrow$. $\{x_n\} \to x$. Sea $B \in \mathcal B(x)$, entonces $B \in \mathcal (x)$, luego $\exists n_0$ tal que $\forall n > n_0$ $x_n \in B$.
$\leftarrow$. Sea $U \in \mathcal E(x)$, entonces $\exists B \in \mathcal B(x)$ tal que $B \subseteq U$. Por hipótesis, $\exists n_0$ tal que $\forall n > n_0$, $x_n \in B \subseteq U$, luego $\{x_n\} \to x$.
```

**Tema:** [[Puntos especiales#4. Caracterización de adherencia por sucesiones]]

---
### Anki

START
Básico
Anverso: Caracterización de convergencia de una sucesión con base de entornos
Reverso: Sean $(X, \mathcal T)$ [[Espacio topológico]], $\{x_n \}_{n = 1}^\infty \subseteq X$, $\mathcal B(x)$ [[base de entornos]] de $X$. Entonces, $\{x_n\} \to x$ $\iff$ $\forall B \in \mathcal B(x)$, $\exists n_0 \in \mathbb N$ tal que $\forall n > n_0$, $x_n \in B$.
Tags: top
<!--ID: 1729160606459-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ [[Espacio topológico]], $\{x_n \}_{n = 1}^\infty \subseteq X$, $\mathcal B(x)$ [[base de entornos]] de $X$. Entonces, $\{x_n\} \to x$ $\iff$ $\forall B \in \mathcal B(x)$, $\exists n_0 \in \mathbb N$ tal que $\forall n > n_0$, $x_n \in B$.
Reverso:
$\rightarrow$. $\{x_n\} \to x$. Sea $B \in \mathcal B(x)$, entonces $B \in \mathcal (x)$, luego $\exists n_0$ tal que $\forall n > n_0$ $x_n \in B$.
$\leftarrow$. Sea $U \in \mathcal E(x)$, entonces $\exists B \in \mathcal B(x)$ tal que $B \subseteq U$. Por hipótesis, $\exists n_0$ tal que $\forall n > n_0$, $x_n \in B \subseteq U$, luego $\{x_n\} \to x$.
Tags: dem top
<!--ID: 1729160606461-->
END
