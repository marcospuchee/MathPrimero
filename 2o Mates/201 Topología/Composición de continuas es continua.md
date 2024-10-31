### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T), (Y, \mathcal T'), (Z, \mathcal T'')$ espacios topológicos, y sean $f: X \mapsto Y$, $g: Y \mapsto Z$ aplicaciones tales que $f$ es continua en $x_0 \in X$ y $g$ es continua en $f(x_0) \in Y$. Entonces $g \circ f$ es continua en $x_0$.
```

```ad-proof
Sea $U \in \mathcal E(g(f(x_0)))$ $\implies$ $\exists V \in \mathcal E(f(x_0))$ tal que $g(V) \subseteq U$ $\implies$ $\exists W \in \mathcal E(x_0)$ tal que $f(W) \subseteq V$. Así, $g(f(W)) \subseteq U$, luego $g \circ f$ es continua en $x_0$.
```

**Tema:** [[Continuidad]]

---
### Anki

START
Respuesta anidada
Sean $(X, \mathcal T), (Y, \mathcal T'), (Z, \mathcal T'')$ espacios topológicos, y sean $f: X \mapsto Y$, $g: Y \mapsto Z$ aplicaciones tales que $f$ es continua en $x_0 \in X$ y $g$ es continua en $f(x_0) \in Y$. Entonces {{c1::$g \circ f$}} es {{c2::continua}} en {{c2::$x_0$.}}
Tags: top
<!--ID: 1730228001600-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T), (Y, \mathcal T'), (Z, \mathcal T'')$ espacios topológicos, y sean $f: X \mapsto Y$, $g: Y \mapsto Z$ aplicaciones tales que $f$ es continua en $x_0 \in X$ y $g$ es continua en $f(x_0) \in Y$. Entonces $g \circ f$ es continua en $x_0$.
Reverso: Sea $U \in \mathcal E(g(f(x_0)))$ $\implies$ $\exists V \in \mathcal E(f(x_0))$ tal que $g(V) \subseteq U$ $\implies$ $\exists W \in \mathcal E(x_0)$ tal que $f(W) \subseteq V$. Así, $g(f(W)) \subseteq U$, luego $g \circ f$ es continua en $x_0$.
Tags:
<!--ID: 1730228001602-->
END
