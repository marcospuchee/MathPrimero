### Enunciado Teorema

$|A| < |\mathcal P(A)|$

---
### Demostración

Veamos que $|A| \le |\mathcal P(A)|$ ([[Aplicaciones inyectivas en numerabilidad]]). Sea $f : A \rightarrow \mathcal P(A)$ con $a \rightarrow \{a\}$. Supongamos que $f(a) = f(b)$, entonces $\{a\} = \{b\}$ y $a = b$.

Veamos que $\not \exists h : A \rightarrow \mathcal P(A)$ biyectiva. Supongamos por reducción al absurdo que $\exists h : A \rightarrow \mathcal P(A)$ biyectiva. Sea $B = \{a \in A : a \not \in h(a)\} \subseteq A$. Como $B \in \mathcal P(A)$ y $h$ es biyectiva, $\exists x \in A$ tal que $h(x) = B$ (antimagen?). Pero si $x \in B \implies x \not \in h(x) = B$. Contradicción. Si $x \not \in B = h(x) \implies x \in B$. Contradicción. Entonces no existe $h$ biyectiva tal que $h : A \rightarrow \mathcal P(A)$.

Esta demostración sirve para ver que $\mathcal P(\mathbb N)$ no es numerable.

---
### Referencias

[[Numerabilidad]]

---
### Anki

START
Básico
Anverso: Qué dice el Teorema de Cantor?
Reverso: $|A| < |\mathcal P(A)|$
Tags: proposición/teorema
<!--ID: 1705822944835-->
END

START
Básico
Anverso: Demostración del Teorema de Cantor
Reverso: Veamos que $|A| \le |\mathcal P(A)|$ ([[Aplicaciones inyectivas en numerabilidad]]). Sea $f : A \rightarrow \mathcal P(A)$ con $a \rightarrow \{a\}$. Supongamos que $f(a) = f(b)$, entonces $\{a\} = \{b\}$ y $a = b$.

Veamos que $\not \exists h : A \rightarrow \mathcal P(A)$ biyectiva. Supongamos por reducción al absurdo que $\exists h : A \rightarrow \mathcal P(A)$ biyectiva. Sea $B = \{a \in A : a \not \in h(a)\} \subseteq A$. Como $B \in \mathcal P(A)$ y $h$ es biyectiva, $\exists x \in A$ tal que $h(x) = B$ (antimagen?). Pero si $x \in B \implies x \not \in h(x) = B$. Contradicción. Si $x \not \in B = h(x) \implies x \in B$. Contradicción. Entonces no existe $h$ biyectiva tal que $h : A \rightarrow \mathcal P(A)$.

Esta demostración sirve para ver que $\mathcal P(\mathbb N)$ no es numerable.
Tags: demostración
<!--ID: 1705822944838-->
END