
---
mathLink: $f \notin C(A) \implies f(A)$ no es intervalo
---

### Contenido Principal

**Fecha:** 2024-01-27, 17:16

Sean $A \subset \mathbb R$ con $A \not = \emptyset$, $f: A \to \mathbb R$ una [[Función monótona]]
```ad-lemma
Si $f$ no es continua en $A$ ([[Función continua en un conjunto]]), entonces $f(A)$ no es un [[Intervalo]].
```


```ad-proof
Podemos suponer, sin pérdida de generalidad, que $f$ es creciente. Sea $a \in A$ tal que $f$ no es continua en $a$ ([[Función continua en un punto]]). Haremos uso del lema [[Definición función continua en un punto con supremo e ínfimo]], y supondremos, por ejemplo, que $\{x : x <a, x \in A \} \not = \emptyset$ y $\sup\{f(x) : x < a, x \in A \}$. Sea $\xi \in \mathbb R$ tal que
$$\sup\{f(x) : x<a, x \in A \} < \xi < f(a)$$
Tendremos que si $x \in A$
- $x \ge a \implies f(x) \ge f(a) > \xi$
- $x < a \implies f(x) \le \sup\{f(x) : x<a, x\in A \}$

De las implicaciones anteriores resulta que $\xi \notin f(A)$. Por otra parte como $\{x : x<a, x \in A\} \not = \emptyset$ podemos tomar $c$ tal que $c<a$ y $c \in A$. Como $c \in A$ y $c < a$, de la segunda de las implicaciones anteriores deducimos que $f(c) < \xi$. Resumiendo,
$$f(c) < \xi < f(a), \xi \notin f(A)$$

```


**Tema:** [[Funciones continuas#4. Funciones monótonas]]
**Consecuencias:** [[Teorema función inversa mantiene continuidad y monotonía]]

---
### Anki

START
Básico
Anverso: Qué implica la no continuidad de una función monótona en un conjunto, con la imagen del conjunto en la función?
Reverso: Sean $A \subset \mathbb R$ con $A \not = \emptyset$, $f: A \to \mathbb R$ una [[Función monótona]], si $f$ no es continua en $A$ ([[Función continua en un conjunto]]), entonces $f(A)$ no es un [[Intervalo]].
Tags: proposición/teorema
<!--ID: 1706457343528-->
END

START
Básico
Anverso: Demuestra que sean $A \subset \mathbb R$ con $A \not = \emptyset$, $f: A \to \mathbb R$ una [[Función monótona]], si $f$ no es continua en $A$ ([[Función continua en un conjunto]]), entonces $f(A)$ no es un [[Intervalo]].
Reverso: Podemos suponer, sin pérdida de generalidad, que $f$ es creciente. Sea $a \in A$ tal que $f$ no es continua en $a$ ([[Función continua en un punto]]). Haremos uso del lema [[Definición función continua en un punto con supremo e ínfimo]], y supondremos, por ejemplo, que $\{x : x <a, x \in A \} \not = \emptyset$ y $\sup\{f(x) : x < a, x \in A \}$. Sea $\xi \in \mathbb R$ tal que
$$\sup\{f(x) : x<a, x \in A \} < \xi < f(a)$$
Tendremos que si $x \in A$
- $x \ge a \implies f(x) \ge f(a) > \xi$
- $x < a \implies f(x) \le \sup\{f(x) : x<a, x\in A \}$

De las implicaciones anteriores resulta que $\xi \notin f(A)$. Por otra parte como $\{x : x<a, x \in A\} \not = \emptyset$ podemos tomar $c$ tal que $c<a$ y $c \in A$. Como $c \in A$ y $c < a$, de la segunda de las implicaciones anteriores deducimos que $f(c) < \xi$. Resumiendo,
$$f(c) < \xi < f(a), \xi \notin f(A)$$
Tags: demostración
<!--ID: 1706457343530-->
END