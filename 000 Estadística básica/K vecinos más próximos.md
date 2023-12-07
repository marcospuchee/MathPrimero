### Contenido principal

Como no en realidad no conocemos la distribución de probabilidad condicional de $Y$ dada $X$ en el [[Clasificador bayesiano ingenuo]], lo estimamos a través de este algoritmo.

Dado un entero positivo $K$ y una observación $x_0$, el KNN (K-Nearest Neighbors) identifica las $K$ observaciones más cercanas a $x_0$ en el conjunto de datos de entrenamiento, representados por $\mathcal N_0$. Entonces, estima la probabilidad condicional de la clase $j$ como la fracción de puntos en $\mathcal N_0$ cuya clasificación es $j$:
$$P(Y = j / X = x_0) = \frac{1}{K} \sum_{i \in \mathcal N_0} I(y_i = j)$$
Así, el KNN clasifica la observación $x_0$ al $j$ con mayor probabilidad.

Sin embargo, la dependencia del KNN en la $K$ hace que sea un método muy flexible. Con $K$ muy pequeña, el clasificador tiene un sesgo muy pequeño ([[Sesgadez]]) pero una varianza muy grande. Según crece $K$, el método se convierte menos flexible, con baja varianza pero alto sesgo.

Dada una $K$ más o menos flexible, le ocurre lo mismo a la [[Tasa de error]] que al [[Error cuadrático medio]], que forma una U. Cuando $K = 1$ (muy flexible), la tasa de error es muy alta y cuando $K = 100$ (poco flexible) la tasa de error también es muy alta, y por lo general las tasas de error cuando $1 < K < 100$ son más bajas. Al igual, con los conjuntos de datos de entrenamiento, cuando la $K$ es muy flexible, la tasa de error de entrenamiento es prácticamente nula, y cuando la $K$ es poco flexible, la tasa de error de entrenamiento es alta.

--- 
### Referencias

[[James#Aprendizaje estadístico]]