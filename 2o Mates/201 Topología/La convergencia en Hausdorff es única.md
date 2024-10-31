### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ [[espacio topológico Hausdorff]], $\{x_n \}_{n = 1}^\infty \subseteq X$. Si $\{x_n\}$ converge a dos puntos $x,y$, entonces $x = y$.
```

```ad-proof
Supongamos que $x \neq y$. Por Hausdorff, $\exists U \in \mathcal E(x), \exists V \in \mathcal E(y)$ tales que $U \cap V = \emptyset$. Como $\{ x_n\} \to x$, entonces $\exists n_1$ tal que $\forall n > n_2$, $x_n \in U$. Por el mismo razonamiento para $y$, $\exists n_2$ tal que $\forall n > n_2$, $x_n \in V$.
Sea $n_0 = \max \{n_1, n_2 \}$, $\forall n > n_0$, $x_n \in U \cap V \neq \emptyset$. Esto es una contradicción, por lo que $x = y$.
```

**Tema:** [[Puntos especiales#4. Caracterización de adherencia por sucesiones]]

---
### Anki

START
Respuesta anidada
Sean $(X, \mathcal T)$ [[espacio topológico Hausdorff]], $\{x_n \}_{n = 1}^\infty \subseteq X$. Si $\{x_n\}$ {{c1::converge a}} dos puntos $x,y$, entonces {{c2::$x = y$}}.
Tags: top
<!--ID: 1729503364437-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ [[espacio topológico Hausdorff]], $\{x_n \}_{n = 1}^\infty \subseteq X$. Si $\{x_n\}$ converge a dos puntos $x,y$, entonces $x = y$.
Reverso: Supongamos que $x \neq y$. Por Hausdorff, $\exists U \in \mathcal E(x), \exists V \in \mathcal E(y)$ tales que $U \cap V = \emptyset$. Como $\{ x_n\} \to x$, entonces $\exists n_1$ tal que $\forall n > n_2$, $x_n \in U$. Por el mismo razonamiento para $y$, $\exists n_2$ tal que $\forall n > n_2$, $x_n \in V$.
Sea $n_0 = \max \{n_1, n_2 \}$, $\forall n > n_0$, $x_n \in U \cap V \neq \emptyset$. Esto es una contradicción, por lo que $x = y$.
Tags: dem top
<!--ID: 1730368366096-->
END
