2023-12-19, 18:49
### Contenido principal

Supongamos que tenemos una muestra aleatoria de tamaño $n$ de una población cuyos elementos pertenecen a una de las $k$ categorías en las que una variable categórica divide a la población: $C_1, C_2, \dots, C_k$.

Sean $\pi_1, \pi_2, \dots, \pi_k$ las proporciones poblacionales de $C_1, C_2, \dots, C_k$. El análisis de Bondad de Ajuste se utiliza cuando estamos interesados en contrastar ([[Contraste de hipótesis]]) una teoría (hipótesis nula) que especifica cada uno de los valores de las proporciones poblacionales (probabilidades) de las diferentes categorías.

Por tanto, estos son los [[Elementos de un contraste de hipótesis]]:
$H_0: \pi_i = p_{i0}$, para $i = 1,2,\dots,k$.
$H_A :$ Existe al menos un $j$ tal que $\pi_j \not = p_{j0}$.

El [[Estadístico de contraste]] es $\chi^2_s = \sum_{i = 1}^k \frac{(O_i - E_i)^2}{E_i}$ donde $O_i$ es la frecuencia observada de cada categoría y $E_i$ es la frecuencia esperada de cada categoría. $\sum_{i = 1}^k O_i = n$ y $E_i = n · p_{i0}$.

**SÓLO SE PUEDE APLICAR CUANDO $E_i \ge 5$ EN TODAS LAS CATEGORÍAS.**

Si la hipótesis nula $H_0$ es cierta, el estadístico $\chi^2_s$ tiene una [[Distribución Chi-Cuadrado]] con $k-1$ grados de libertad, donde $k =$ número de categorías.

--- 
### Referencias

[[Análisis de datos categóricos]]