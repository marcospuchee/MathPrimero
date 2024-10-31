### Contenido principal

```ad-Algorithm
Dado un sistema triangular inferior, donde la ecuación $i$-ésima del sistema es:
$$a_{i,1}x_1 + a_{i,2}x_2 + \dots + a_{i,i}x_i = b_i \equiv a_{i,i}x_i + \sum_{j = 1}^{i-1} a_{i,j}x_j = b_i.$$
El algoritmo de sustitución progresiva resuelve $x_i$ de la siguiente forma:
$$x_1 = \frac{b_1}{a_{1,1}}; \quad x_i = \frac{1}{a_{i,i}} \left ( b_i - \sum_{j = 1}^{i-1} a_{i,j} x_j \right ), \, i = 2, \dots, n.$$
```

**Número de operaciones para la incógnita $i$-ésima:** $2(i-1)+1$.
**Número total de operaciones para resolver el sistema:** $n^2$.

**Tema:** [[Descomposición LU#1. Métodos directos y sistemas triangulares.]]

---
### Anki

START
Básico
Anverso: Algoritmo de sustitución progresiva
Reverso: Dado un sistema triangular inferior, donde la ecuación $i$-ésima del sistema es:
$$a_{i,1}x_1 + a_{i,2}x_2 + \dots + a_{i,i}x_i = b_i \equiv a_{i,i}x_i + \sum_{j = 1}^{i-1} a_{i,j}x_j = b_i.$$
El algoritmo de sustitución progresiva resuelve $x_i$ de la siguiente forma:
$$x_1 = \frac{b_1}{a_{1,1}}; \quad x_i = \frac{1}{a_{i,i}} \left ( b_i - \sum_{j = 1}^{i-1} a_{i,j} x_j \right ), \, i = 2, \dots, n.$$
Tags:
<!--ID: 1727083427937-->
END

START
Básico
Anverso: Número de operaciones para la incógnita $i$-ésima del algoritmo de sustitución progresiva
Reverso: $2(i-1)+1$.
Tags:
<!--ID: 1727083427939-->
END

START
Básico
Anverso: Número total de operaciones para resolver el sistema del algoritmo de sustitución progresiva
Reverso: $n^2$.
Tags:
<!--ID: 1727083427941-->
END