### Contenido principal

**Fecha:** 2024-03-06, 17:59

```ad-formal
title: Formal definition
Observemos que $e_k$ ([[Incremento de un método iterativo]]) aproxima $\varepsilon_k$ ([[Error de aproximación de un método iterativo]]) siempre que $\varepsilon_{k+1} \ll \varepsilon_k$. Por ello, podemos utilizar en nuestros métodos iterativos ([[Método iterativo]]) como criterio de parada que la cantidad $e_k$ sea suficientemente pequeña,
$$|x_{k+1} - x_k| < tol \textrm{ o } 0,5 * |x_{k-1} - x_k| < tol.$$
Debemos tener en cuenta que si el método converge lentamente, estamos subestimando el error, al contrario, si converge rápidamente, el error será seguramente inferior a $tol$. Otro posible criterio es la satisfacción aproximada de la ecuación, es decir, que
$$|f(x_k)|< tol.$$
Conviene tambier limitar el número máximo de iteraciones, en previsión de que el algoritmo diverja, oscile indefinidamente o converja muy lentamente.
```

**Tema:** [[Solución de ecuaciones no lineales#1. Métodos iterativos]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Qué distintos criterios de parada existen para un método iterativo?
Reverso: Observemos que $e_k$ ([[Incremento de un método iterativo]]) aproxima $\varepsilon_k$ ([[Error de aproximación de un método iterativo]]) siempre que $\varepsilon_{k+1} \ll \varepsilon_k$. Por ello, podemos utilizar en nuestros métodos iterativos ([[Método iterativo]]) como criterio de parada que la cantidad $e_k$ sea suficientemente pequeña,
$$|x_{k+1} - x_k| < tol \textrm{ o } 0,5 * |x_{k-1} - x_k| < tol.$$
Debemos tener en cuenta que si el método converge lentamente, estamos subestimando el error, al contrario, si converge rápidamente, el error será seguramente inferior a $tol$. Otro posible criterio es la satisfacción aproximada de la ecuación, es decir, que
$$|f(x_k)|< tol.$$
Conviene tambier limitar el número máximo de iteraciones, en previsión de que el algoritmo diverja, oscile indefinidamente o converja muy lentamente.
Tags: definición HI
<!--ID: 1709746655777-->
END