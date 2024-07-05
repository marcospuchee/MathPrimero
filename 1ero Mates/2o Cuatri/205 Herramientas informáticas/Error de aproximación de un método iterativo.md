### Contenido principal

**Fecha:** 2024-03-06, 17:57

```ad-formal
title: Formal definition
Dado un iterado $x_k$ de un [[Método iterativo]], el error de esta aproximación viene determinado por
$$\varepsilon_k = |x_k - x^*|.$$
Que la sucesión de iterados $x_k$ converja a $x^*$ es equivalente a que $\epsilon_k$ tienda a cero cuando $k$ tiende a infinito. En la práctica, $\varepsilon_k$ no es calculable, ya que no conocemos $x^*$. En cambio, obtenidos los iterados $x_1, x_2, x_3, \dots, x_k, x_{k+1}, \dots,$ podemos calcular
$$e_k = |x_{k+1} - x_k|, k = 1,2, \dots.$$
Lo que llamamos incremento ([[Sucesión de incrementos de un método iterativo]]). Observemos que $e_k$ aproxima $\varepsilon_k$ siempre que $\varepsilon_{k+1} \ll \varepsilon_k$
```

**Tema:** [[Solución de ecuaciones no lineales#1. Métodos iterativos]]
**Referencias:** [[Incremento de un método iterativo]]
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Error de aproximación de un método iterativo
Reverso: Dado un iterado $x_k$ de un [[Método iterativo]], el error de esta aproximación viene determinado por
$$\varepsilon_k = |x_k - x^*|.$$
Que la sucesión de iterados $x_k$ converja a $x^*$ es equivalente a que $\epsilon_k$ tienda a cero cuando $k$ tiende a infinito. En la práctica, $\varepsilon_k$ no es calculable, ya que no conocemos $x^*$. En cambio, obtenidos los iterados $x_1, x_2, x_3, \dots, x_k, x_{k+1}, \dots,$ podemos calcular
$$e_k = |x_{k+1} - x_k|, k = 1,2, \dots.$$
Lo que llamamos incremento ([[Incremento de un método iterativo]]). Observemos que $e_k$ aproxima $\varepsilon_k$ siempre que $\varepsilon_{k+1} \ll \varepsilon_k$
Tags: definición HI
<!--ID: 1709746655784-->
END