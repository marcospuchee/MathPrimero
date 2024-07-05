### Contenido principal

**Fecha:** 2024-03-06, 18:14

Para comparar la eficiencia de los distintos métodos iterativos ([[Método iterativo]]), vamos a medir la rapidez con la que los iterados $x_1, x_2, \dots, x_k, \dots,$ convergen o no a la solución.

```ad-formal
title: Formal definition
Al desconocer la solución, medimos la velocidad de convergencia de la sucesión de incrementos ([[Incremento de un método iterativo]]) $e_k, k=1,2,3, \dots.$
- Si los cocientes $e_{k+1}/e_k$ tienden a $K$, $0<K<1$, diremos que el método converge linealmente. El [[Método de la bisección]] y el [[Método regula falsi]] convergen linealmente.
- Si los cocientes $e_{k+1}/e_k$ tienden a cero y los $e_{k+1}/e_k^2$ tienden a estabilizarse, diremos que el método converge cuadráticamente. El [[Método de Newton-Raphson]] converge cuadráticamente, si se cumplen las condiciones adecuadas.
- Si los cocientes $e_{k+1}/e_k$ tienden a cero y los $e_{k+1}/e_k^p$, para cierto $1 \ll p < 2$, tienden a estabilizarse, se dice que el método tiene convergencia superlineal. El [[Método de la secante]] tiene generalmente convergencia superlineal.
```

En la práctica, el tipo de convergencia nos indica el trabajo necesario para alcanzar determinada precisión. Con un método que converge linealmente, cada tantas iteraciones, se obtiene un dígito adicional exacto en la solución. En cambio, si hay convergencia cuadrática, cada tantas iteraciones se duplica el número de decimales exactos.

**Tema:** [[Solución de ecuaciones no lineales#1. Métodos iterativos]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Qué distintos tipos de convergencia de métodos iterativos existen?
Reverso: Al desconocer la solución, medimos la velocidad de convergencia de la sucesión de incrementos ([[Incremento de un método iterativo]]) $e_k, k=1,2,3, \dots.$
- Si los cocientes $e_{k+1}/e_k$ tienden a $K$, $0<K<1$, diremos que el método converge linealmente. El [[Método de bisección]] y el [[Método regula falsi]] convergen linealmente.
- Si los cocientes $e_{k+1}/e_k$ tienden a cero y los $e_{k+1}/e_k^2$ tienden a estabilizarse, diremos que el método converge cuadráticamente. El [[Método de Newton-Raphson]] converge cuadráticamente, si se cumplen las condiciones adecuadas.
- Si los cocientes $e_{k+1}/e_k$ tienden a cero y los $e_{k+1}/e_k^p$, para cierto $1 \ll p < 2$, tienden a estabilizarse, se dice que el método tiene convergencia superlineal. El [[Método de la secante]] tiene generalmente convergencia superlineal.
Tags: definición HI
<!--ID: 1709746655765-->
END

START
Básico
Anverso: Para qué sirven los tipos de convergencia de un método iterativo?
Reverso: En la práctica, el tipo de convergencia nos indica el trabajo necesario para alcanzar determinada precisión. Con un método que converge linealmente, cada tantas iteraciones, se obtiene un dígito adicional exacto en la solución. En cambio, si hay convergencia cuadrática, cada tantas iteraciones se duplica el número de decimales exactos.

Es decir, se utilizan para medir la eficiencia de los distintos métodos iterativos
Tags: definición HI
<!--ID: 1709746655771-->
END