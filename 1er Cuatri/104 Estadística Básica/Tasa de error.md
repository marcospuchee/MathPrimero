### Contenido principal

Para [[Problemas de clasificación]], no podemos utilizar el [[Error cuadrático medio]], sino que adaptamos este a las variables cualitativas a través de la tasa de error:
$$ \frac{1}{n} \sum_{i = 1}^n I(y_i \not = \hat y_i) $$
Aquí, $\hat y_i$ es la clase para la $i$-ésima observación usando $\hat f$, e $I(y_1 \not = \hat y_i)$ es una variable dummy que devuelve 1 si $y_i \not = \hat y_i$ y 0 si $y_i = \hat y_i$.


--- 
### Referencias

[[James#Aprendizaje estadístico]]