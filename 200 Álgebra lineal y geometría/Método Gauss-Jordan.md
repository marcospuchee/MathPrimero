### Contenido principal

El método Gauss-Jordan es capaz de resolver un [[Sistemas de ecuaciones lineales]], además, es la demostración del [[Teorema existencia singular de matriz escalonada reducida por filas equivalente]], que afirma que para cada matriz existe una [[matriz escalonada reducida por filas]] equivalente. Estos son los pasos a seguir:
1. Intercambiando filas, si fuese necesario, llevamos a la primera fila una cuyo pivote ([[Pivote de una matriz]]) se encuentre en la primera columna.
2. Si la entrada (1,1) es $a \in k - \{0\}$, entonces, multiplicamos la primera fila por $a^{-1}$.
3. Sumar a las demás filas un múltiple adecuado de la primera fila para obtener ceros por debajo y que su pivote se encuentre estrictamente a la derecha de la fila cuyo múltiple multiplicamos.
4. Repetir los tres primeros pasos con las filas por debajo del pivote con el que hemos estado trabajando.

Con estos 4 pasos llegamos a una [[Matriz escalonada por filas]].

6. Haciendo algo similar al paso 3 obtenemos ceros por encima de los pivotes.


--- 
### Referencias
[[Sistemas de ecuaciones lineales]]