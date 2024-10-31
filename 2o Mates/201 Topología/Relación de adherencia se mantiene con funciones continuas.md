### Contenido Principal

```ad-proposition
Sean $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$ una aplicación continua en $x_0 \in X$, $S \subseteq X$. Entonces, $x_0 \in \textrm{ad}(S) \implies f(x_0) \in \textrm{ad}(f(S))$.
```

```ad-proof
Sea $U \in \mathcal E(f(x_0)) \implies \exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq U$, y $V \cap S \neq \emptyset$. Luego,
$$\emptyset \neq f(V \cap S) \subseteq f(V) \cap f(S) \subseteq U \cap f(S).$$
Por tanto, $f(x_0) \in \textrm{ad}(f(S))$.
```

**Tema:** [[Continuidad]]

---
### Anki

START
Respuesta anidada
Sean $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$ una aplicación continua en $x_0 \in X$, $S \subseteq X$. Entonces, {{c1::$x_0 \in \textrm{ad}(S)$}} $\implies$ {{c2::$f(x_0) \in \textrm{ad}(f(S))$.}}
Tags: top
<!--ID: 1730228001588-->
END

START
Básico
Anverso: Demostración de que sean $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$ una aplicación continua en $x_0 \in X$, $S \subseteq X$. Entonces, $x_0 \in \textrm{ad}(S) \implies f(x_0) \in \textrm{ad}(f(S))$.
Reverso: Sea $U \in \mathcal E(f(x_0)) \implies \exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq U$, y $V \cap S \neq \emptyset$. Luego,
$$\emptyset \neq f(V \cap S) \subseteq f(V) \cap f(S) \subseteq U \cap f(S).$$
Por tanto, $f(x_0) \in \textrm{ad}(f(S))$.
Tags: dem top
<!--ID: 1730228001591-->
END

