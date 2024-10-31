### Contenido Principal

```ad-theorem
Sea $f: (X, \mathcal T) \to (Y, \mathcal T')$. $f$ es continua $\iff$ $\forall A \in \mathcal T'$, $f^{-1}(A) \in \mathcal T$.
```

```ad-proof
$\Rightarrow$.
Sean $A \in \mathcal T'$, $x_0 \in f^{-1}(A)$. Entonces, $f(x_0) \in A$ y $A \in \mathcal E(f(x_0))$. Como $f$ continua, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq A$ $\implies$ $V \subseteq f^{-1}(A)$ $\implies$ $f^{-1}(A) \in \mathcal E(x_0)$ $\implies$ $f^{-1}(A)$ es entorno de todos sus puntos $\implies$ $f^{-1}(A) \in \mathcal T$.

$\Leftarrow$.
Sean $x_0 \in X$, $U \in \mathcal E(f(x_0))$, entonces $\exists A \in \mathcal T'$ tal que $f(x_0) \in A \subseteq U$. Entonces, por hipótesis, $f^{-1}(A) \in \mathcal T$ y $x_0 \in f^{-1}(A)$. Por tanto, $f^{-1}(A) \in \mathcal E(x_0)$, y $f(V) = f(f^{-1}(A)) \subseteq A \subseteq U$, luego $f$ continua en $x_0$.
```

**Tema:** [[Continuidad#1. Continuidad global.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Caracterización de continuidad global por antiimagen de abiertos
Reverso: Sea $f: (X, \mathcal T) \to (Y, \mathcal T')$. $f$ es continua $\iff$ $\forall A \in \mathcal T'$, $f^{-1}(A) \in \mathcal T$.
Tags: top
<!--ID: 1730228001611-->
END

START
Básico
Anverso: Demostración de que sea $f: (X, \mathcal T) \to (Y, \mathcal T')$. $f$ es continua $\iff$ $\forall A \in \mathcal T'$, $f^{-1}(A) \in \mathcal T$.
Reverso: $\Rightarrow$.
Sean $A \in \mathcal T'$, $x_0 \in f^{-1}(A)$. Entonces, $f(x_0) \in A$ y $A \in \mathcal E(f(x_0))$. Como $f$ continua, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq A$ $\implies$ $V \subseteq f^{-1}(A)$ $\implies$ $f^{-1}(A) \in \mathcal E(x_0)$ $\implies$ $f^{-1}(A)$ es entorno de todos sus puntos $\implies$ $f^{-1}(A) \in \mathcal T$.

$\Leftarrow$.
Sean $x_0 \in X$, $U \in \mathcal E(f(x_0))$, entonces $\exists A \in \mathcal T'$ tal que $f(x_0) \in A \subseteq U$. Entonces, por hipótesis, $f^{-1}(A) \in \mathcal T$ y $x_0 \in f^{-1}(A)$. Por tanto, $f^{-1}(A) \in \mathcal E(x_0)$, y $f(V) = f(f^{-1}(A)) \subseteq A \subseteq U$, luego $f$ continua en $x_0$.
Tags: dem top
<!--ID: 1730228001613-->
END

