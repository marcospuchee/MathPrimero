### Contenido Principal

```ad-proposition
Sea $f: A \subseteq \mathbb R^n \to \mathbb R^m$, $a \in A$.

$f$ es continua en $a$ $\iff$ $\forall V \in \mathcal E(f(a))$ ([[entorno]]), $f^{-1}(V)$ es un entorno de $a$ relativo a $A$.
```

^d80f00

```ad-proof
$\rightarrow$.
$V$ entorno de $f(a)$ $\implies$ $\exists \varepsilon > 0$ tal que $B(f(a); \varepsilon) \subseteq V$. Como $f$ continua en $a$, $\exists \delta > 0$ de forma que $f(B(a; \delta) \cap A) \subseteq B(f(a); \varepsilon) \subseteq V$. Por tanto, $B(a, \delta) \cap A \subseteq f^{-1}(B(f(a); \varepsilon))  \subseteq f^{-1}(V)$.

$\leftarrow$.
$\varepsilon > 0$, $B(f(a); \varepsilon)$ es entorno de $f(a)$ $\implies$ $f^{-1}(B(f(a); \varepsilon))$ es un entorno de $a$ en $A$. Luego $\exists \delta > 0$ tal que $B(a, \delta) \cap A \subseteq f^{-1}(B(f(a); \varepsilon))$. Por tanto, $f$ continua.
```

**Tema:** [[Funciones de varias variables#3. Continuidad.]]

---
### Anki

START
Básico
Anverso: Caracterización de la continuidad de una función multivariable a través de entornos
Reverso: Sea $f: A \subseteq \mathbb R^n \to \mathbb R^m$, $a \in A$.

$f$ es continua en $a$ $\iff$ $\forall V \in \mathcal E(f(a))$ ([[entorno]]), $f^{-1}(V)$ es un entorno de $a$ relativo a $A$.
<!--ID: 1727966478882-->
END

START
Básico
Anverso: Demostración de que sea $f: A \subseteq \mathbb R^n \to \mathbb R^m$, $a \in A$.

$f$ es continua en $a$ $\iff$ $\forall V \in \mathcal E(f(a))$ ([[entorno]]), $f^{-1}(V)$ es un entorno de $a$ relativo a $A$.
Reverso: $\rightarrow$.
$V$ entorno de $f(a)$ $\implies$ $\exists \varepsilon > 0$ tal que $B(f(a); \varepsilon) \subseteq V$. Como $f$ continua en $a$, $\exists \delta > 0$ de forma que $f(B(a; \delta) \cap A) \subseteq B(f(a); \varepsilon) \subseteq V$. Por tanto, $B(a, \delta) \cap A \subseteq f^{-1}(B(f(a); \varepsilon))  \subseteq f^{-1}(V)$.

$\leftarrow$.
$\varepsilon > 0$, $B(f(a); \varepsilon)$ es entorno de $f(a)$ $\implies$ $f^{-1}(B(f(a); \varepsilon))$ es un entorno de $a$ en $A$. Luego $\exists \delta > 0$ tal que $B(a, \delta) \cap A \subseteq f^{-1}(B(f(a); \varepsilon))$. Por tanto, $f$ continua.
Tags: dem anII
<!--ID: 1727966478902-->
END
