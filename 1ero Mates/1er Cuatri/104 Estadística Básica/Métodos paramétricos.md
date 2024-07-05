### Contenido principal

Los métodos paramétricos, al igual que los [[Métodos no paramétricos]], son una de las formas de resolver el problema del [[Aprendizaje estadístico]] de encontrar $f$ en la ecuación $\hat{Y} = \hat{f}(X)$. Los métodos paramétricos se componen de dos pasos:
1. Realizar una asunción sobre la forma de $f$. Por ejemplo, asumir que $f(X)$ es lineal, como esto: $f(X) = \beta_0 + \beta_1 X_1 +\beta_2 + X_2 + ... + \beta_p X_p$
2. En el ejemplo en que es lineal, encontramos una forma que aproxime los valores de $\beta_0, \beta_1, \beta_2$… Existen algunos métodos como el de *mínimos cuadrados ordinarios* que sirven para esto.

Se llaman paramétricos porque el problema se reduce a tener que estimar el valor de ciertos parámetros.

Sin embargo este tipo de métodos plantean un problema y es que el modelo lineal que se escoja puede no llegar a dar un resultado cercano a el valor real de $f(X)$. Una forma de resolver este problema es utilizar modelos flexibles, que permiten distintas formas de $f$, pero esto puede desencadenar en otro problema que es el *[[Overfitting]]* de la información.

Un ejemplo de método paramétrico es la *regresión lineal*

--- 
### Referencias
[[James#Aprendizaje estadístico]]