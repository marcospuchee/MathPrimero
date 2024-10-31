### Contenido principal

```ad-Formal
Un problema de programación lineal en formato estándar se expresa como:
$$
\begin{matrix*}[c r l] 
\textrm{(PL)} & \textrm{Min (o Max)} & c^Tx \\ 
& \textrm{s.a.} & Ax = b, \\
& & x \ge 0_n;
\end{matrix*}
$$
donde:
- $x = (x_1, \dots, x_n)^T \in \mathbb R^n$ es el vector de variables de decisión.
- $c = (c_1, \dots, c_n)^T \in \mathbb R^n$ es el vector de costes de la función objetivo, cuya expresión se reduce a
$$c^Tx = \sum_{j = 1}^n c_j x_j.$$
- $A \in \mathbb R^{m \times n}$ es la matriz de coeficientes. Donde $a_{ij}$ es el elemento de la fila $i$, y columna $j$. Cada fila $i$ de la matriz es una restricción del tipo
$$\sum_{j = 1}^n a_{ij}x_j = b_i, \quad i = 1, \dots, m.$$
- $b = (b_1, \dots, b_m)^T \in \mathbb R^m$ es el vector de términos independientes.
```

Definición alternativa:
```ad-Formal
Un problema de programación lineal se expresa como:
$$
\begin{matrix*}[c r l] 
\textrm{(PL)} & \textrm{Min (o Max)} & f(x) \\ 
& \textrm{s.a.} & x \in \mathcal F,
\end{matrix*}
$$
donde:
- $x = (x_1, \dots, x_n)^t \in \mathbb R^n$ es el vector de variables de decisión.
- $f: \mathbb R^n \to \mathbb R$ es la función objetivo.
- $\mathcal F \subset \mathbb R^n$ es el conjunto factible.
```


**Tema:** [[Modelo de programación lineal#1. Introducción al modelo de programación lineal.]]

---
### Anki
