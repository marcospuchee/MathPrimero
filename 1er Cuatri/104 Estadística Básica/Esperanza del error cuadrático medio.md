### Contenido principal

Sabemos que si tomamos tres métodos distintos, ordenados de menor a mayor flexibilidad, y calculamos el [[Error cuadrático medio]] con un conjunto de datos de entrenamiento, por el [[Overfitting]] el error cuadrático medio va a descender cuanto más flexible sea el método. Sin embargo, calculando el MSE con datos nunca antes vistos, forma una U:
![[Pasted image 20231203174827.png]]
en rojo el MSE con datos nunca antes vistos, y en gris el MSE con datos de entrenamiento.

Esto ocurre debido a que la esperanza del error cuadrático medio (MSE) con datos nunca antes vistos se puede calcular de la siguiente forma:
$$ E(y_0 - \hat f(x_0))^2 = \textrm{Var}(\hat f(x_0)) + [\textrm{Sesgo}(\hat f(x_0))]^2 + \textrm{Var}(\epsilon)$$
donde $E(y_0 - \hat f(x_0))^2$ es la esperanza del error cuadrático medio para valores nunca antes vistos, y hace referencia a la media que tendría el MSE si estimásemos $f$ repetidamente con muchos conjuntos de datos de entrenamientos, las varianzas de $\hat f(x_0)$ y del margen de error ($\epsilon$) además del sesgo cuadrado de $\hat f(x_0)$ ([[Sesgadez]]). Sabemos que $\textrm{Var}(\epsilon)$ es el error irreducible ([[Errores en la predictibilidad]]).

La varianza hace referencia a cuánto cambiaría $\hat f$ si lo calculásemos con otro conjunto de datos. Mayor varianza suele conllevar menor sesgo.
El sesgo hace referencia al error inherente a aproximar un problema de la vida real (que puede ser muy complicado) a algo mucho más simple. Por ejemplo, asumir que la relación entre $Y$ y $X_i$ es lineal conlleva un sesgo. Mayor sesgo suele conllevar menor varianza.

--- 
### Referencias

[[James#Aprendizaje estadístico]]