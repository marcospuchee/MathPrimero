### Contenido principal

Para dibujar un diagrama de cajas es necesario calcular:
$b_1 = Q_1 - 1,5 * IQR$ _(rango intercuartílico)_.
$b_2 = Q_3 + 1,5 * IQR$.
$min = min \{x_i\}$
$max = max\{x_i\}$

Una vez calculados estos, calculamos la altura de los bigotes con el siguiente criterio:
- Bigote bajo. Si $min < b_1$, el valor del bigote bajo se queda en $b_1$, sino el valor se queda en $min$.
- Bigote alto. Si $max > b_2$, el valor del bigote alto se queda en $b_2$, sino el valor se queda en $max$.

De esta forma, si el valor de $min$ o $max$ es más extremo que $b_1$ y $b_2$ respectivamente, no altera la forma del diagrama de cajas, sino que se dibujan como puntos.



--- 
### Referencias
[[Diagramas de cajas]]