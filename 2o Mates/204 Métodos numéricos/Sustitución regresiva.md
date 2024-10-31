### Contenido principal

```ad-Algorithm
Dado un sistema triangular superior, donde la ecuación $i$-ésima del sistema es:
$$a_{i,i}x_i + a_{i,i+1} x_{i+1} + \dots + a_{i,n} x_n = b \equiv a_{i,i}x_i + \sum_{j = i+1}^n a_{i,j}x_j = b_i,$$
el algoritmo de sustitución regresiva resuelve $x_i$ de la siguiente forma:
$$x_n = \frac{b_n}{a_{n,n}}; \quad x_i = \frac{1}{a_{i,i}} \left ( b_i - \sum_{j = i+1}^n a_{i,j}x_j \right ), \, i = n-1, \dots, 1.$$
```

- **Número de operaciones para la incógnita $i$-ésima**: $2(n-i)+1$.
- **Número total de operaciones para resolver el sistema:** $n^2$.

**Tema:** [[Descomposición LU#1. Métodos directos y sistemas triangulares.]]

---
### Anki

START
Básico
Anverso: Algoritmo de sustitución regresiva
Reverso: Dado un sistema triangular superior, donde la ecuación $i$-ésima del sistema es:
$$a_{i,i}x_i + a_{i,i+1} x_{i+1} + \dots + a_{i,n} x_n = b \equiv a_{i,i}x_i + \sum_{j = i+1}^n a_{i,j}x_j = b_i,$$
el algoritmo de sustitución regresiva resuelve $x_i$ de la siguiente forma:
$$x_n = \frac{b_n}{a_{n,n}}; \quad x_i = \frac{1}{a_{i,i}} \left ( b_i - \sum_{j = i+1}^n a_{i,j}x_j \right ), \, i = n-1, \dots, 1.$$
Tags:
<!--ID: 1727083427931-->
END

START
Básico
Anverso: Número de operaciones para la incógnita $i$-ésima del algoritmo de sustitución regresiva
Reverso: $2(n-i)+1$.
Tags:
<!--ID: 1727083427933-->
END

START
Básico
Anverso: Número total de operaciones para resolver el sistema del algoritmo de sustitución regresiva
Reverso: $n^2$.
Tags:
<!--ID: 1727083427935-->
END
