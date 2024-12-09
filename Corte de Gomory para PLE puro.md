### Contenido Principal

```ad-theorem
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T) \in \mathbb R^n$ una SBP de la relajación lineal del problema de programación lineal entera puro en formato estándar $(\textrm{PLE})$. Supongamos que $\overline x$ no es entera y sea $\overline x_r \notin \mathbb Z$, $r \in \mathcal J_B$, una variable básica que toma valor fraccionario. Entonces, la desigualdad
$$\sum_{j \in \mathcal J_N} f_{rj} x_j \ge f_r, \quad f_r := \overline x_r - \lfloor \overline x_r \rfloor, \quad f_{rj} := \alpha_{rj} - \lfloor \alpha_{rj} \rfloor, \, \forall j \in \mathcal J_N;$$
es válida para $(\textrm{PLE})$ y corta al punto $\overline x$.
```

```ad-proof
Primero probaremos que es una desigualdad válida para $(\textrm{PLE})$. Para ello sea $x = (x_B^T, x_N^T)^T \in \mathbb Z^n$ una solución factible cualquiera de $(\textrm{PLE})$. Del sistema de ecuaciones de factibilidad $$Ax = b \iff x_B + B^{-1}Nx_N = B^{-1}b = \overline x_B,$$
nos fijamos en la $r$-ésima ecuación:
$$x_r + \sum_{j \in \mathcal J_N} \alpha_{rj} x_j = \overline x_r. \quad \quad (*)$$ Como $x \ge 0_n$, podemos acotar la ecuación anterior por $$x_r + \sum_{j \in \mathcal J_N} \lfloor \alpha_{rj} \rfloor x_j \le x_r + \sum_{j \in \mathcal J_N} \alpha_{rj}x_j = \overline x_r.$$ Ahora, al ser las variables enteras, el término de la izquierda es un número entero. Por lo tanto, obtenemos que
$$x_r + \sum_{j \in \mathcal J_N} \lfloor \alpha_{rj} \rfloor x_j \le \lfloor \overline x_r \rfloor. \quad \quad (**)$$ Restando $(**) - (*)$ se obtiene la desigualdad.

Que la desigualdad corte a $\overline x$ viene del hecho que $f_r > 0$ y $\overline x_j = 0$, $\forall j \in \mathcal J_N$.
```

```ad-note
**Cortes de Gomory: tabla Simplex.**
Si tenemos la tabla Simplex óptima de la relajación lineal, la ecuación de partida $$x_r + \sum_{j \in \mathcal J_N} \alpha_{rj}x_j = \overline x_r,$$ es una de las filas de la tabla y podemos identificar todos los elementos. Una vez calculado el corte de Gomory, debemos incorporarlo al problema. Para ello, reescribimos la desigualdad como $$\sum_{j \in \mathcal J_N} (-f_{rj})x_j + x_h = -f_r,$$ donde $x_h \ge 0$ es una nueva variable de holgura. La nueva restricción (y variable) se añaden a la tabla Simplex, la cual se puede continuar pivotando con el algoritmo Dual-Simplex.
```

```ad-note
**Cortes de Gomory: integridad de las variables de holgura**
Para poder generar cortes de Gomory válidos, necesitamos que todas las variables del problema en formato estándar sean enteras. Esto incluye a las variables de holgura que se necesite introducir, lo que estará garantizado siempre que en el PLE original (en formato libre) tanto los coeficientes de las restricciones como los términos independientes sean enteros. En cambio, si no podemos asegurar la integridad de las holguras, debemos recurrir a cortes de Gomory para problemas mixtos que veremos en la siguiente sección.
```

```ad-note
**Cortes de Gomory: variable de holgura para PLE puro**
Supongamos que, tras introducir el corte generado y actualizar la solución óptima de la relajación lineal, obtenemos de nuevo una solución fraccionaria. Para poder generar un nuevo corte de Gomory, también debemos garantizar la integridad de la nueva variable de holgura del corte anterior. En principio como los coeficientes de Gomory del tipo del teorema nunca son enteros, no podemos deducir nada sobre la variable $x_h$ de la restricción que añadimos. No obstante, podemos comprobar que $$\begin{eqnarray} 
x_h &=& \sum_{j \in \mathcal J_N} f_{rj} x_j - f_r = \sum_{j \in \mathcal J_N} (\alpha_{rj} - \lfloor \alpha_{rj} \rfloor)x_j - (\overline x_r - \lfloor \overline x_r \rfloor) \\
&=& \left ( \sum_{j \in \mathcal J_N} \alpha_{rj} x_j - \overline x_r \right ) + \left ( \lfloor \overline x_r \rfloor - \sum_{j \in \mathcal J_N} \lfloor \alpha_{rj} \rfloor x_j \right ) \\
&=& - x_r + \lfloor \overline x_r \rfloor - \sum_{j \in \mathcal J_N} \lfloor \alpha_{rj} \rfloor x_j \in \mathbb Z;
\end{eqnarray}$$
es decir, la variable de holgura de un corte de Gomory generado en un problema PLE puro siempre toma valores enteros.
```

```ad-note
**Corte de Gomory generado por la función objetivo.**
Cuando aplicamos el método Simplex en formato tabla, en el fondo tratamos la función objetivo como si fuera una nueva restricción (que involucra la variable $z$). Si podemos garantizar que el valor de $z^*$ ha de ser entero, podemos utilizar esta fila para generar un corte de Gomory.
```

**Tema:** [[Métodos de PLE#1. Métodos exactos de resolución de problemas PLE]]

**Definiciones referenciadas:** [[Relajación lineal]], [[Solución básica posible]].
**Resultados referenciados:** -.

---
### Anki
