### Enunciado Teorema

$|\mathcal P(A)| = |2^A|$ ([[Conjunto 2 elevado a A]]).

---
### Demostración

Definimos la aplicación $f: \mathcal P(A) \rightarrow 2^A$ con $B \rightarrow f(B)$. Definimos $f(B) : A \rightarrow \{0,1\}$ con $x \rightarrow 0$ si $x \not \in B$ y $x \rightarrow 1$ si $x \in B$.

Es $f$ inyectiva?
Sea $B,C$ con $f(B) = f(C) \implies B = C?$.
Sea $x \in B$, $f(B)(x) = 1$. Por hipótesis, $f(B)(x) = f(C)(x)$ lo que implica que $x \in C$. Así, $B \subseteq C$. Análogamente, conseguimos que $C \subseteq B$, así $B = C$.

Es $f$ sobreyectiva?
Sea $h : A \rightarrow \{0,1\}$ aplicación y $B = h^{-1}(\{1\}) = \{a \in A : h(a) = 1\} \implies f(B) = h$.

---
### Referencias

[[Numerabilidad]]

---
### Anki

START
Básico
Anverso: Cuál es el cardinal de $| \mathcal P(A)|$?
Reverso: $|\mathcal P(A)| = |2^A|$ ([[Conjunto 2 elevado a A]]).
Tags: proposición/teorema
<!--ID: 1705822944820-->
END

START
Básico
Anverso: Demostración de que $|\mathcal P(A)| = |2^A|$ ([[Conjunto 2 elevado a A]]).
Reverso: Definimos la aplicación $f: \mathcal P(A) \rightarrow 2^A$ con $B \rightarrow f(B)$. Definimos $f(B) : A \rightarrow \{0,1\}$ con $x \rightarrow 0$ si $x \not \in B$ y $x \rightarrow 1$ si $x \in B$.

Es $f$ inyectiva?
Sea $B,C$ con $f(B) = f(C) \implies B = C?$.
Sea $x \in B$, $f(B)(x) = 1$. Por hipótesis, $f(B)(x) = f(C)(x)$ lo que implica que $x \in C$. Así, $B \subseteq C$. Análogamente, conseguimos que $C \subseteq B$, así $B = C$.

Es $f$ sobreyectiva?
Sea $h : A \rightarrow \{0,1\}$ aplicación y $B = h^{-1}(\{1\}) = \{a \in A : h(a) = 1\} \implies f(B) = h$.
Tags: demostración
<!--ID: 1705822944823-->
END