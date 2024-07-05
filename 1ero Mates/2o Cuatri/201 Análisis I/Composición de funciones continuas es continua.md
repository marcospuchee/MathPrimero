
---
mathLink: $f \circ g$ continua en $a$
---
### Proposición

Sean $A, B \subset \mathbb R, a \in A, f : A \rightarrow \mathbb R, f(A) \subset B, b = f(a)$ y $g : B \rightarrow \mathbb R$. Entonces:
- Si $f$ es continua en $a$ ([[Función continua en un punto]]) y $g$ es continua en $b$, entonces $g \circ f$ es continua en $a$.

---
### Demostración

Sea $\epsilon > 0$. Puesto que $g$ es continua en $b$, ha de existir un $p > 0$ tal que
$$\forall y \in B \textrm { con } |y-b| < p \implies |g(y) - g(b)| < \epsilon$$
es decir,
$$\forall y \in B \textrm{ con } |y-b| < p \implies |g(y) - g(f(a))| < \epsilon$$
Puesto que $f$ es continua en $a$ ha de existir un $\delta > 0$ tal que
$$\forall x \in A \textrm{ con } |x-a| < \delta \implies |f(x) - f(a) < p$$
es decir
$$\forall x \in A \textrm { con } |x-a| < \delta \implies |f(x) - b| < p$$
Por tanto, se deduce que
$$\forall x \in A \textrm { con } |x-a| < \delta \implies |g(f(x)) - g(f(a)) < \delta$$


---
### Referencias

[[Funciones continuas#1. Funciones continuas en un punto]]

---
### Anki

START
Básico
Anverso: Qué se debe de dar para que la [[Composición de aplicaciones]] sea una [[Función continua en un punto]]
Reverso: Sean $A, B \subset \mathbb R, a \in A, f : A \rightarrow \mathbb R, f(A) \subset B, b = f(a)$ y $g : B \rightarrow \mathbb R$. Entonces:
- Si $f$ es continua en $a$ ([[Función continua en un punto]]) y $g$ es continua en $b$, entonces $g \circ f$ es continua en $a$.
Tags: proposición/teorema
<!--ID: 1706209553675-->
END

START
Básico
Anverso: Demostración de que sean $A, B \subset \mathbb R, a \in A, f : A \rightarrow \mathbb R, f(A) \subset B, b = f(a)$ y $g : B \rightarrow \mathbb R$. Entonces:
- Si $f$ es continua en $a$ ([[Función continua en un punto]]) y $g$ es continua en $b$, entonces $g \circ f$ es continua en $a$.
Reverso: Sea $\epsilon > 0$. Puesto que $g$ es continua en $b$, ha de existir un $p > 0$ tal que
$$\forall y \in B \textrm { con } |y-b| < p \implies |g(y) - g(b)| < \epsilon$$
es decir,
$$\forall y \in B \textrm{ con } |y-b| < p \implies |g(y) - g(f(a))| < \epsilon$$
Puesto que $f$ es continua en $a$ ha de existir un $\delta > 0$ tal que
$$\forall x \in A \textrm{ con } |x-a| < \delta \implies |f(x) - f(a) < p$$
es decir
$$\forall x \in A \textrm { con } |x-a| < \delta \implies |f(x) - b| < p$$
Por tanto, se deduce que
$$\forall x \in A \textrm { con } |x-a| < \delta \implies |g(f(x)) - g(f(a)) < \delta$$
Tags: demostración
<!--ID: 1706209553678-->
END