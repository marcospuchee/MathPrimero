### Contenido principal

Los métodos paramétricos, al igual que los [[Métodos no paramétricos]], son una de las formas de resolver el problema del [[Aprendizaje estadístico]] de encontrar $f$ en la ecuación $\hat{Y} = \hat{f}(X)$. Los métodos paramétricos se componen de dos pasos:
1. Asumir que $f(X)$ es lineal, como esto: $f(X) = \beta0 + \beta1 X1 +\beta2 + X2 + ... + \beta p Xp$.
2. Encontrar una forma que aproxime los valores de $\beta 0, \beta1, \beta2$… Existen algunos métodos como el de *mínimos cuadrados ordinarios* que sirven para esto.

Se llaman paramétricos porque el problema se reduce a tener que estimar el valor de ciertos parámetros.
 
Sin embargo este tipo de métodos plantean un problema y es que el modelo linear que se escoja puede no llegar a dar un resultado cercano a el valor real de $f(X)$. Una forma de resolver este problema es utilizar modelos flexibles, que permiten distintas formas de $f$, pero esto puede desencadenar en otro problema que es el *[[Overfitting]]* de la información.

--- 
### Referencias
[[James#Aprendizaje estadístico]]