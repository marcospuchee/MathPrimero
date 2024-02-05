
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-27, 16:58

Sean $A \subset \mathbb R, a \in A$ y $f : A \to \mathbb R$ una [[Función monótona]] creciente,
```ad-lemma
Si 
$$\{x : x < a, x \in A\} \not = \emptyset \implies f(a) = \sup\{f(x): x < a , x \in A \}$$
y además
$$\{x : x > a, x \in A \} \not = \emptyset \implies f(a) = \inf\{f(x) : x>a, x \in A \}$$
entonces $f$ es continua en $a$ ([[Función continua en un punto]])
```


```ad-proof
En la prueba hay que distinguir los casos en que ninguno, uno o los dos conjuntos $\{x: x < a, x \in A \}, \{x : x>a, x \in A \}$ sean vacíos. La haremos únicamente cuando ambos conjuntos sean no vacíos. Sea $\epsilon > 0$, puesto que $f(a) + \epsilon$ no es cota inferior de $\{f(x) : x>a, x \in A \}$ ha de existir un $d > a, d \in A$ tal que
$$f(d) < f(a) + \epsilon$$
Una observación similar con $f(a) - \epsilon$ nos permite afirmar que existe un $c<a, c \in A$ tal que
$$f(a) - \epsilon < f(c)$$
De ambas observaciones y de la monotonía de la función, deducimos que
$$x \in ]c,d[ \implies f(a) - \epsilon < f(c) \le f(x) \le f(d) < f(a) + \epsilon \implies |f(x) - f(a)| < \epsilon$$
Sea $\delta := min\{a-c,d-a\}$, de acuerdo con [[Lema subintervalo con el mínimo]],
$$]a - \delta, a + \delta[\subset]c,d[.$$
Finalmente, si $|x-a| < \delta$, de las últimas dos observaciones, resulta que $|f(x) - f(a)| < \epsilon$.
```



**Tema:** [[Funciones continuas#4. Funciones monótonas]]
**Corolarios:** [[f no es continua en A, f(A) no es un intervalo]]

---
### Anki

START
Básico
Anverso: Cómo podemos definir una función continua en un punto a través del ínfimo y del supremo?
Reverso: Sean $A \subset \mathbb R, a \in A$ y $f : A \to \mathbb R$ una [[Función monótona]] creciente, si
$$\{x : x < a, x \in A\} \not = \emptyset \implies f(a) = \sup\{f(x): x < a , x \in A \}$$
y además
$$\{x : x > a, x \in A \} \not = \emptyset \implies f(a) = \inf\{f(x) : x>a, x \in A \}$$
entonces $f$ es continua en $a$ ([[Función continua en un punto]])
Tags: proposición/teorema
<!--ID: 1706457343533-->
END

START
Básico
Anverso: Demuestra que sean $A \subset \mathbb R, a \in A$ y $f : A \to \mathbb R$ una [[Función monótona]] creciente, si
$$\{x : x < a, x \in A\} \not = \emptyset \implies f(a) = \sup\{f(x): x < a , x \in A \}$$
y además
$$\{x : x > a, x \in A \} \not = \emptyset \implies f(a) = \inf\{f(x) : x>a, x \in A \}$$
entonces $f$ es continua en $a$ ([[Función continua en un punto]])
Reverso: En la prueba hay que distinguir los casos en que ninguno, uno o los dos conjuntos $\{x: x < a, x \in A \}, \{x : x>a, x \in A \}$ sean vacíos. La haremos únicamente cuando ambos conjuntos sean no vacíos. Sea $\epsilon > 0$, puesto que $f(a) + \epsilon$ no es cota inferior de $\{f(x) : x>a, x \in A \}$ ha de existir un $d > a, d \in A$ tal que
$$f(d) < f(a) + \epsilon$$
Una observación similar con $f(a) - \epsilon$ nos permite afirmar que existe un $c<a, c \in A$ tal que
$$f(a) - \epsilon < f(c)$$
De ambas observaciones y de la monotonía de la función, deducimos que
$$x \in ]c,d[ \implies f(a) - \epsilon < f(c) \le f(x) \le f(d) < f(a) + \epsilon \implies |f(x) - f(a)| < \epsilon$$
Sea $\delta := min\{a-c,d-a\}$, de acuerdo con [[Lema subintervalo con el mínimo]],
$$]a - \delta, a + \delta[\subset]c,d[.$$
Finalmente, si $|x-a| < \delta$, de las últimas dos observaciones, resulta que $|f(x) - f(a)| < \epsilon$.
Tags: demostración
<!--ID: 1706457343536-->
END
