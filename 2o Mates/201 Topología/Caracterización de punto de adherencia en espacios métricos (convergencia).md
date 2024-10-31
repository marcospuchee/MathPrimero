### Contenido Principal

```ad-proposition
Sea $(X, d)$ [[espacio métrico]], $S \subseteq X$, $x \in X$. Entonces,
$$x \in \textrm{ad}(S) \iff \exists \{x_n \}_{n = 1}^\infty \subseteq S : \{x_n\} \to x.$$
```

```ad-note
title: Ejercicio
Esto es cierto para espacios topológicos $1\textrm{AN}$.
```

```ad-proof
$\Leftarrow$. Sea $U \in \mathcal E(x)$, como $\{x_n\} \to x$, $\exists n_0$ tal que $\forall n > n_0$, $x_n \in U$. Así, $U \cap S \neq \emptyset$, y $x \in \textrm{ad}(S)$.

$\Rightarrow$. $x \in \textrm{ad}(S) \implies \forall n$, $B(x; 1/n) \cap S \neq \emptyset$, luego podemos elegir $x_n \in B(x; 1/n) \cap S$, $\forall n$. Por tanto, tenemos que $\{x_n\} \to x$, y $\{x_n\} \subseteq S$.
```

**Tema:** [[Puntos especiales#4. Caracterización de adherencia por sucesiones]]

---
### Anki

START
Básico
Anverso: Caracterización de punto de adherencia en espacios métricos (convergencia)
Reverso: Sea $(X, d)$ [[espacio métrico]], $S \subseteq X$, $x \in X$. Entonces,
$$x \in \textrm{ad}(S) \iff \exists \{x_n \}_{n = 1}^\infty \subseteq S : \{x_n\} \to x.$$
Tags: top
<!--ID: 1729503364424-->
END

START
Básico
Anverso: Demostración de que sea $(X, d)$ [[espacio métrico]], $S \subseteq X$, $x \in X$. Entonces,
$$x \in \textrm{ad}(S) \iff \exists \{x_n \}_{n = 1}^\infty \subseteq S : \{x_n\} \to x.$$
Reverso: $\Leftarrow$. Sea $U \in \mathcal E(x)$, como $\{x_n\} \to x$, $\exists n_0$ tal que $\forall n > n_0$, $x_n \in U$. Así, $U \cap S \neq \emptyset$, y $x \in \textrm{ad}(S)$.

$\Rightarrow$. $x \in \textrm{ad}(S) \implies \forall n$, $B(x; 1/n) \cap S \neq \emptyset$, luego podemos elegir $x_n \in B(x; 1/n) \cap S$, $\forall n$. Por tanto, tenemos que $\{x_n\} \to x$, y $\{x_n\} \subseteq S$.

Notemos, por tanto, que este resultado es cierto para cualquier [[espacio topológico 1 AN]]
Tags: dem top
<!--ID: 1729503364427-->
END
