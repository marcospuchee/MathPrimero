2024-01-24, 11:44
### Contenido principal

El descenso del gradiente es una técnica para encontrar el mínimo de una función multivariable. Sea $C$ una función de $m$ variables $v_1, \dots, v_m$.

El cambio $\Delta C$ en $C$ está producido por un pequeño cambio en $\Delta v = (\Delta v_1, \dots, \Delta v_m)^T$. Esto lo cuantifica:
$$\Delta C \approx \nabla C · \Delta v$$
donde el [[Gradiente]] $\Delta C$ es el vector
$$\Delta C \equiv (\frac{\partial C}{\partial v_1}, \dots, \frac{\partial C}{\partial v_m})^T$$
entonces, elegimos $\Delta v = - \eta \nabla C$, y así estamos seguros de que $\Delta C$ va a ser negativo, es decir, va a descender. Entonces, conseguiremos el mínimo de la función aplicando repetidas veces la siguiente fórmula:
$$v \rightarrow v' = v - \eta \nabla C$$

--- 
### Referencias



---
### Anki
