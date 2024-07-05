
---
mathLink: $a \not \in ac(A) \implies f$ es continua
---

### Proposición

Sean $A \subset \mathbb R, a \in A$ y $f: A \rightarrow \mathbb R$. Entonces:
- Si $a$ no es [[Punto de acumulación]] de $A$ entonces $f$ es continua ([[Función continua en un punto]]) en $a$.

---
### Demostración

Si $a$ no es [[Punto de acumulación]] de $A$, ha de existir un $\delta_0 > 0$ tal que $]a - \delta_0, a + \delta_0[ \cap A \text{\\} \{a\} = \emptyset$. Es decir $]a - \delta_0, a + \delta_0[ \cap A = \{a\}$. Dado $\epsilon > 0$, si $x \in A$, $|x-a| < \delta_0$ tendremos que $x \in ]a - \delta_0, a + \delta_0[\cap A = \{a\}$, por tanto $x = a$, y $|f(x) - f(a)| = |f(a) - f(a)| = 0 < \epsilon$.

---
### Referencias

[[Funciones continuas#1. Funciones continuas en un punto]]

---
### Anki

START
Básico
Anverso: Qué relación tiene la continuidad de una función en un punto $a$ con que $a$ sea un punto de acumulación?
Reverso: Sean $A \subset \mathbb R, a \in A$ y $f: A \rightarrow \mathbb R$. Entonces:
- Si $a$ no es [[Punto de acumulación]] de $A$ entonces $f$ es continua ([[Función continua en un punto]]) en $a$.
Tags: proposición/teorema
<!--ID: 1706209553670-->
END

START
Básico
Anverso: Demuestra que sean $A \subset \mathbb R, a \in A$ y $f: A \rightarrow \mathbb R$. Entonces:
- Si $a$ no es [[Punto de acumulación]] de $A$ entonces $f$ es continua ([[Función continua en un punto]]) en $a$.
Reverso: Si $a$ no es [[Punto de acumulación]] de $A$, ha de existir un $\delta_0 > 0$ tal que $]a - \delta_0, a + \delta_0[ \cap A \text{\\} \{a\} = \emptyset$. Es decir $]a - \delta_0, a + \delta_0[ \cap A = \{a\}$. Dado $\epsilon > 0$, si $x \in A$, $|x-a| < \delta_0$ tendremos que $x \in ]a - \delta_0, a + \delta_0[\cap A = \{a\}$, por tanto $x = a$, y $|f(x) - f(a)| = |f(a) - f(a)| = 0 < \epsilon$.
Tags: demostración
<!--ID: 1706209553672-->
END