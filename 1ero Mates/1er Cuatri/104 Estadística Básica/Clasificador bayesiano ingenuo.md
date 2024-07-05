### Contenido principal

El clasificador bayesiano ingenuo es uno de los clasificadores de los [[Problemas de clasificación]] que puede llegar a minimizar la [[Tasa de error]]. En este caso, se asigna a cada observación $x_0$ el grupo $j$ cuya
![[Pasted image 20231205191327.png]]
sea la mayor. Se ha de asumir que las probabilidades son independientes.

En realidad, nunca vamos a saber la distribución condicional de $Y$ dada $X$, por eso, existen métodos que buscan estimar esta distribución, como el algoritmo de los [[K vecinos más próximos]].

Para aquellos en que la pertenencia a los grupos sea equiprobable, decimos que están en al límite de la decisión bayesiana.

De la fórmula de probabilidad que se utiliza en el clasificador bayesiano ingenuo, la tasa de error se queda como:
$$1- E(max_j P(Y = j / X)) $$
donde la esperanza es la media de todas las probabilidades de asignar las observaciones $x_0 (\in X)$ al grupo con mayor probabilidad.

--- 
### Referencias

[[James#Aprendizaje estadístico]]