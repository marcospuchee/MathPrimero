
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-27, 11:45

Sean $A \subset \mathbb R, A \not = \emptyset$ y $f : A \to \mathbb R$
```ad-proposition
Las siguientes afirmaciones equivalen:
1. $f$ no es uniformemente continua ([[Función uniformemente continua]]) en $A$.
2. $\exists \epsilon_0 > 0, x_n, y_n \in A, n \in \mathbb N$ tales que
$$\forall n \in \mathbb N \textrm{ se cumple } |f(x_n) - f(y_n)| \ge \epsilon_0 \land |x_n - y_n < 1/n|$$

```

```ad-proof
**i $\implies$ ii**
Negar que $f$ es uniformemente continua en $A$ significa que $\exists \epsilon_0 > 0$ tal que para cada $\delta > 0$ existen $x(\delta) \in A$, $y(\delta) \in A$ tales que $|x(\delta) - y(\delta)| < \delta$ y $|f(x(\delta)) - f(y(\delta))| \ge \epsilon_0$. Si $x_n := x(1/n)$, $y_n := y(1/n)$, $n \in \mathbb N$ es claro que (ii) se verifica.

**ii $\implies$ i**
No se demuestra porque no se usa en el curso. Está como ejercicio.

```

**Tema:** [[Funciones continuas#3. Funciones uniformemente continuas]]
**Consecuencias:** [[Teorema de Heine (1872)]]

---
### Anki

START
Básico
Anverso: Cuándo decimos que una función no es uniformemente continua?
Reverso: Sean $A \subset \mathbb R, A \not = \emptyset$ y $f : A \to \mathbb R$,

> Las siguientes afirmaciones equivalen:
>1. $f$ no es uniformemente continua ([[Función uniformemente continua]]) en $A$.
>2. $\exists \epsilon_0 > 0, x_n, y_n \in A, n \in \mathbb N$ tales que
>$$\forall n \in \mathbb N \textrm{ se cumple } |f(x_n) - f(y_n)| \ge \epsilon_0 \land |x_n - y_n < 1/n|$$

Tags: proposición/teorema
<!--ID: 1706355204112-->
END

START
Básico
Anverso: Demostración de que sean $A \subset \mathbb R, A \not = \emptyset$ y $f : A \to \mathbb R$,
> Las siguientes afirmaciones equivalen:
>1. $f$ no es uniformemente continua ([[Función uniformemente continua]]) en $A$.
>2. $\exists \epsilon_0 > 0, x_n, y_n \in A, n \in \mathbb N$ tales que
>$$\forall n \in \mathbb N \textrm{ se cumple } |f(x_n) - f(y_n)| \ge \epsilon_0 \land |x_n - y_n < 1/n|$$

Reverso: 
**i $\implies$ ii**
Negar que $f$ es uniformemente continua en $A$ significa que $\exists \epsilon_0 > 0$ tal que para cada $\delta > 0$ existen $x(\delta) \in A$, $y(\delta) \in A$ tales que $|x(\delta) - y(\delta)| < \delta$ y $|f(x(\delta)) - f(y(\delta))| \ge \epsilon_0$. Si $x_n := x(1/n)$, $y_n := y(1/n)$, $n \in \mathbb N$ es claro que (ii) se verifica.

**ii $\implies$ i**
No se demuestra porque no se usa en el curso. Está como ejercicio.
Tags: demostración
<!--ID: 1706355204116-->
END