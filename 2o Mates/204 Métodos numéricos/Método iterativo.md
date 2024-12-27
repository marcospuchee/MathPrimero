### Método iterativo para resolver sistemas de ecuaciones lineales.

```ad-Formal
Dado un sistema de ecuaciones lineal: $$Ax = b, \quad A \in \mathbb R^{n \times n}, \, b \in \mathbb R^n,$$
un método iterativo genera una sucesión de vectores $x^k$ que queremos que converjan a $x$, la solución del sistema.

Escribimos $A = M+N$ con $M$ fácilmente invertible: $$\begin{eqnarray}
Ax &=& b \\
(M+N)x &=& b \\
Mx &=& b-Nx,
\end{eqnarray}$$ definimos el método iterativo $Mx^k = b - N x^{k-1}$.
```

```ad-note
**Ejemplos.**
- Método de Jacobi: $M = \textrm{diag}(A)$.
- Método de Gauss-Seidel: $M = \textrm{tril}(A)$.
```


**Tema:** [[Métodos iterativos para resolver sistemas de ecuaciones lineales#1. Definición]]

**Definiciones referenciadas:** -.

---
### Contenido Principal (Herramientas informáticas).

Dado que no existen fórmulas generales para obtener la solución de [[Polinomio]]s de grado $\ge 5$, utilizamos métodos iterativos que consisten en obtener una sucesión de valores $x_1, x_2, \dots, x_n$ cada vez más aproximados a la raíz buscada.

```ad-formal
Los métodos iterativos consisten en:
- Obtener una aproximación inicial $x_1$ de la solución. Esta aproximación es la información previa que disponemos. En algunos métodos, la elección de la aproximación inicial determina la convergencia del método. La representación gráfica de la función suele proporcionar aproximaciones iniciales aceptables.
- Refinar la aproximación inicial mediante una fórmula iterativa que genera nuevos valores (llamado iterados), $x_2, x_3, x_4, \dots$, que idealmente, convergerán a la solución buscada $x^*$.
- Establecer un criterio de parada ([[Criterios de parada de un método iterativo]]) o test de finalización, satisfecho el cual, se detiene el proceso de obtención de iterados. En caso de convergencia, se toma el último iterado como raíz aproximada.

A $x_k$ lo llamamos iterado k-ésimo ($x_k$ seria $(a_k + b_k)/2$ en el caso de intervalos ([[Método iterativo con intervalos]])).
```

**Tema:** [[Solución de ecuaciones no lineales#1. Métodos iterativos]]
**Referencias:** [[Error de aproximación de un método iterativo]], [[Incremento de un método iterativo]], [[Tipos de convergencia de un método iterativo]]

---
### Anki

START
Básico
Anverso: Cuál es el método de Jacobi?
Reverso: $M = \textrm{diag}(A)$, $Mx^k = b - N x^{k-1}$.
Tags: met
<!--ID: 1735044171394-->
END

START
Básico
Anverso: Cuál es el método de Gauss-Seidel?
Reverso: $M = \textrm{tril}(A)$, $Mx^k = b - N x^{k-1}$.
Tags: met
<!--ID: 1735044171397-->
END

START
Básico
Anverso: Definición de método iterativo para resolver sistemas de ecuaciones lineales
Reverso: Dado un sistema de ecuaciones lineal: $$Ax = b, \quad A \in \mathbb R^{n \times n}, \, b \in \mathbb R^n,$$
un método iterativo genera una sucesión de vectores $x^k$ que queremos que converjan a $x$, la solución del sistema.

Escribimos $A = M+N$ con $M$ fácilmente invertible: $$\begin{eqnarray}
Ax &=& b \\
(M+N)x &=& b \\
Mx &=& b-Nx,
\end{eqnarray}$$ definimos el método iterativo $Mx^k = b - N x^{k-1}$.
Tags: met
<!--ID: 1735044171399-->
END


START
Básico
Anverso: En qué consiste un método iterativo?
Reverso: Los métodos iterativos consisten en:
- Obtener una aproximación inicial $x_1$ de la solución. Esta aproximación es la información previa que disponemos. En algunos métodos, la elección de la aproximación inicial determina la convergencia del método. La representación gráfica de la función suele proporcionar aproximaciones iniciales aceptables.
- Refinar la aproximación inicial mediante una fórmula iterativa que genera nuevos valores (llamado iterados), $x_2, x_3, x_4, \dots$, que idealmente, convergerán a la solución buscada $x^*$.
- Establecer un criterio de parada ([[Criterios de parada de un método iterativo]]) o test de finalización, satisfecho el cual, se detiene el proceso de obtención de iterados. En caso de convergencia, se toma el último iterado como raíz aproximada.

A $x_k$ lo llamamos iterado k-ésimo ($x_k$ seria $(a_k + b_k)/2$ en el caso de intervalos ([[Método iterativo con intervalos]])).
Tags: definición HI
<!--ID: 1709746655794-->
END

START
Básico
Anverso: Cuál es el uso de los métodos iterativos?
Reverso: Dado que no existen fórmulas generales para obtener la solución de [[Polinomio]]s de grado $\ge 5$, utilizamos métodos iterativos que consisten en obtener una sucesión de valores $x_1, x_2, \dots, x_n$ cada vez más aproximados a la raíz buscada.
Tags: definición HI
<!--ID: 1709746655804-->
END