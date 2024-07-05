
---
mathLink: $l > 0 \implies \exists \delta > 0$ tal que $f(x) > 0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$
---
### Contenido Principal

**Fecha:** 2024-01-26, 11:02

Sean $A \subset \mathbb R, a \in ac(A)$ ([[Punto de acumulación]]) y $f : A \to \mathbb R$ tales que $\exists lim_{x \to a} f(x) = l$,
> [!lemma]
> Si $l>0$, entonces $\exists \delta > 0$ tal que $f(x)>0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$
> 
> Si $l<0$, entonces $\exists \delta > 0$ tal que $f(x)<0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$

> [!proof]
> Es suficiente hacer la prueba para $l>0$. Sea $\epsilon := l$, ha de existir un $\delta > 0$ tal que
> $$x \in A \cap]a-\delta, a + \delta[ \text{\\}\{a\} \implies |f(x)-l|<l$$
> Si $x \in A \cap ]a - \delta, a + \delta[ \text{\\} \{a\}$ tendremos
> $$f(x) = l-(l-f(x)) \ge l-|f(x) - l| > l-l > 0$$

**Tema:** [[Funciones continuas#2. Funciones continuas en ciertos conjuntos]]
**Corolarios:** [[Teorema de Bolzano (1817)]], [[Teorema derivada de un extremo relativo]]

---
### Anki

START
Respuesta anidada
Sean $A \subset \mathbb R, a \in ac(A)$ ([[Punto de acumulación]]) y $f : A \to \mathbb R$ tales que $\exists lim_{x \to a} f(x) = l$,
> Si $l>0$, entonces {{c1::$\exists \delta > 0$ tal que $f(x)>0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$}}
> 
> Si $l<0$, entonces {{c1::$\exists \delta > 0$ tal que $f(x)<0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$}}

Tags: proposición/teorema
<!--ID: 1706298644623-->
END

START
Básico
Anverso: Demuestra que sean $A \subset \mathbb R, a \in ac(A)$ ([[Punto de acumulación]]) y $f : A \to \mathbb R$ tales que $\exists lim_{x \to a} f(x) = l$,
> Si $l>0$, entonces $\exists \delta > 0$ tal que $f(x)>0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$
> 
> Si $l<0$, entonces $\exists \delta > 0$ tal que $f(x)<0, \forall x \in A \cap ]a-\delta, a + \delta[ \text{\\} \{a\}$

Reverso: Es suficiente hacer la prueba para $l>0$. Sea $\epsilon := l$, ha de existir un $\delta > 0$ tal que
$$x \in A \cap]a-\delta, a + \delta[ \text{\\}\{a\} \implies |f(x)-l|<l$$
Si $x \in A \cap ]a - \delta, a + \delta[ \text{\\} \{a\}$ tendremos
$$f(x) = l-(l-f(x)) \ge l-|f(x) - l| > l-l > 0$$
Tags: demostración
<!--ID: 1706298886031-->
END

