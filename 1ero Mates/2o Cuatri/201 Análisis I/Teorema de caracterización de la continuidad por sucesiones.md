### Enunciado Teorema

Sea $A \subset \mathbb R, a \in A$ y $f : A \to \mathbb R$, las siguientes afirmaciones equivalen:
1. $f$ es continua ([[Función continua en un punto]]) en $a$
2. $\forall (x_n)^{\infty}_{n = 1}$ con $x_n \in A, n \in \mathbb N$, tal que $\lim_n x_n = a$, se verifica que $\lim_n f(x_n) = f(a)$.

---
### Demostración

##### Caso 1. $a \notin ac(A)$
Sabemos por [[Si a no es punto de acumulación de A, entonces f es continua]] que puesto que $a \notin ac(A)$, la función es continua en $a$, por tanto para probar la equivalencia hemos de demostrar que $\exists \lim_{x \to a} f(x) = f(a)$ ([[Función continua en un punto que es punto de acumulación]]).

Como en [[Si a no es punto de acumulación de A, entonces f es continua]], ha de existir un $\delta_0 > 0$ tal que $]a - \delta_0, a + \delta_0[ \cap A = \{a\}$. Sea $(x_n)_{n=1}^{\infty}, x_n \in A$ tal que $\lim x_n = a$. Debe existir un $n_0 \in \mathbb N$ tal que si $n \ge n_0$, resulta que $|a-x_n| < \delta_0$, es decir $a = x_n$ (por cómo hemos definido el intervalo $\{a\}$) para $n \ge n_0$, así $f(a) = f(x_n)$ para $n \ge n_0$ y $\lim_n f(x_n) = f(a)$.
#### Caso 2. $a \in ac(A)$
##### ii $\implies$ i
Consecuencia de resultados del tema de [[Función]] y de [[Función continua en un punto que es punto de acumulación]].
##### i $\implies$ ii
Sea $(a_n)_1^\infty$, $a_n \in A, n \in \mathbb N$, tal que $\lim_n a_n = a$. Fijemos $\epsilon > 0$. Ha de existir un $\delta > 0$ para el que se verifica [[Función continua en un punto]]. Puesto que $\lim_n a_n = a$, podemos encontrar un $n_0 \in \mathbb N$ tal que $|a- a_n| < \delta$ si $n \ge n_0$, por tanto, de acuerdo con [[Función continua en un punto]], resulta que $|f(a) - f(a_n)| < \delta$ si $n \ge n_0$, y por tanto, $\lim_n f(x_n) = f(a)$.


---
### Referencias

[[Funciones continuas#1. Funciones continuas en un punto]]
[[Sucesión]]
[[Teorema de Heine (1872)]]

---
### Anki

START
Básico
Anverso: Qué dice el teorema de caracterización de la continuidad por sucesiones?
Reverso: Sea $A \subset \mathbb R, a \in A$ y $f : A \to \mathbb R$, las siguientes afirmaciones equivalen:
1. $f$ es continua ([[Función continua en un punto]]) en $a$
2. $\forall (x_n)^{\infty}_{n = 1}$ con $x_n \in A, n \in \mathbb N$, tal que $\lim_n x_n = a$, se verifica que $\lim_n f(x_n) = f(a)$.
Tags: proposición/teorema
<!--ID: 1706215865239-->
END

START
Básico
Anverso: Demostración  del teorema de caracterización de la continuidad por sucesiones en el caso en que $x \notin ac(A)$
Reverso: Sabemos por [[Si a no es punto de acumulación de A, entonces f es continua]] que puesto que $a \notin ac(A)$, la función es continua en $a$, por tanto para probar la equivalencia hemos de demostrar que $\exists \lim_{x \to a} f(x) = f(a)$ ([[Función continua en un punto que es punto de acumulación]]).

Como en [[Si a no es punto de acumulación de A, entonces f es continua]], ha de existir un $\delta_0 > 0$ tal que $]a - \delta_0, a + \delta_0[ \cap A = \{a\}$. Sea $(x_n)_{n=1}^{\infty}, x_n \in A$ tal que $\lim x_n = a$. Debe existir un $n_0 \in \mathbb N$ tal que si $n \ge n_0$, resulta que $|a-x_n| < \delta_0$, es decir $a = x_n$ (por cómo hemos definido el intervalo $\{a\}$) para $n \ge n_0$, así $f(a) = f(x_n)$ para $n \ge n_0$ y $\lim_n f(x_n) = f(a)$.
Tags: demostración
<!--ID: 1706215865243-->
END

START
Básico
Anverso: Demostración del teorema  de caracterización de la continuidad por sucesiones en el caso en  que $x \in ac(A)$
Reverso: 
##### ii $\implies$ i
Consecuencia de resultados del tema de [[Función]] y de [[Función continua en un punto que es punto de acumulación]].
##### i $\implies$ ii
Sea $(a_n)_1^\infty$, $a_n \in A, n \in \mathbb N$, tal que $\lim_n a_n = a$. Fijemos $\epsilon > 0$. Ha de existir un $\delta > 0$ para el que se verifica [[Función continua en un punto]]. Puesto que $\lim_n a_n = a$, podemos encontrar un $n_0 \in \mathbb N$ tal que $|a- a_n| < \delta$ si $n \ge n_0$, por tanto, de acuerdo con [[Función continua en un punto]], resulta que $|f(a) - f(a_n)| < \delta$ si $n \ge n_0$, y por tanto, $\lim_n f(x_n) = f(a)$.
Tags: demostración
<!--ID: 1706254711689-->
END


