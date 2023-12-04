### Contenido principal

El error cuadrático medio es la fórmula de medida que se utiliza para cuantificar como de parecidas son las predicciones extraídas de un método, en comparación con la información observada. Dentro de los problemas de regresión (corresponden a los problemas con variables cuantitativas, como hemos visto en [[Métodos para predecir cantidades]]), es uno de los métodos más usados.
$$MSE = \frac{1}{n} \sum_{i = 1}^n (y_i - \hat{f}(x_i))^2$$
donde $\hat{f}(x_i)$ es la predicción de $\hat{f}$ sobre la $i$-nésima observación y $y_i$ es la respuesta real en la observación. Cuanto más pequeño el valor obtenido, menor la diferencia entre la realidad con la predicción.

De todas maneras, no es lo mismo que el valor del MSE (*mean squared error*) sea pequeño con la información con que se entrena (información sobre la cual ya conocemos el valor real), sino que nos interesa que el MSE de poco con valores nunca antes vistos (quizás hay más valores para practicar con el método que los de entrenamiento).

Si solamente hay un conjunto de datos para entrenar el modelo y calcular el MSE, entonces NO hay que elegir el método según el MSE más bajo en el entrenamiento, dado que no hay garantía de que un bajo MSE en los entrenamientos sea un bajo MSE en realidad. Cuando el MSE del entrenamiento baja, pero el de verdad sube, es por el [[Overfitting]].

Solo se puede usar en problemas de [[Predictibilidad en el aprendizaje estadístico]] y, por tanto, de [[Aprendizaje supervisado]] dado que compara respuestas. Típicamente se calculará en problemas de regresión ([[Métodos para predecir cantidades]]).

[[Esperanza del error cuadrático medio]]

--- 
### Referencias
[[James#Aprendizaje estadístico]]
