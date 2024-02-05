
---
mathLink: Sea $x \in ac(A)$, $f$ continua en $a \iff \exists \lim_{x \to a} f(x) = f(a)$
---
### Proposición

Sean $A \subset \mathbb R, a \in A$ y $f : A \rightarrow \mathbb R$. Entonces:
- Si $a \in ac(A)$ ([[Punto de acumulación]]), entonces $f$ es continua ([[Función continua en un punto]]) $\iff$ $\exists \lim_{x \to a} f(x)$ y además $\lim_{x \to a} f(x) = f(a)$.

---
### Demostración

Si $f$ es continua, entonces $\forall \epsilon > 0, \exists \delta > 0$ tal que $\forall x \in A$ con $|x - a| < \delta$, entonces $|f(x) - f(a)| < \epsilon$. Sin embargo, $|x-a| < \delta \iff 0<|x-a|<\delta$. Entonces $\forall \epsilon > 0, \exists \delta > 0$ tal que $\forall x \in A$ con $0 < |x-a| < \delta$, entonces $|f(x)-f(a)| < \epsilon$. Esto es, $\exists \lim_{x \to a} f(x) = f(a)$ ([[Límite funcional]]). 

---
### Referencias

[[Funciones continuas#1. Funciones continuas en un punto]]
[[Teorema de Bolzano (1817)]]

---
### Anki

START
Básico
Anverso: Cuál es la definición de función continua en un punto de acumulación?
Reverso: Sean $A \subset \mathbb R, a \in A$ y $f : A \rightarrow \mathbb R$. Entonces:
- Si $a \in ac(A)$ ([[Punto de acumulación]]), entonces $f$ es continua ([[Función continua en un punto]]) $\iff$ $\exists \lim_{x \to a} f(x)$ y además $\lim_{x \to a} f(x) = f(a)$.
Tags: proposición/teorema
<!--ID: 1706209553664-->
END

START
Básico
Anverso: Demuestra que sean $A \subset \mathbb R, a \in A$ y $f : A \rightarrow \mathbb R$. Entonces:
- Si $a \in ac(A)$ ([[Punto de acumulación]]), entonces $f$ es continua ([[Función continua en un punto]]) $\iff$ $\exists \lim_{x \to a} f(x)$ y además $\lim_{x \to a} f(x) = f(a)$.
Reverso: Si $f$ es continua, entonces $\forall \epsilon > 0, \exists \delta > 0$ tal que $\forall x \in A$ con $|x - a| < \delta$, entonces $|f(x) - f(a)| < \epsilon$. Sin embargo, $|x-a| < \delta \iff 0<|x-a|<\delta$. Entonces $\forall \epsilon > 0, \exists \delta > 0$ tal que $\forall x \in A$ con $0 < |x-a| < \delta$, entonces $|f(x)-f(a)| < \epsilon$. Esto es, $\exists \lim_{x \to a} f(x) = f(a)$ ([[Límite funcional]]). 
Tags: demostración
<!--ID: 1706209553667-->
END
