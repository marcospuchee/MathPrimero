### Contenido principal

El test de Shapiro-Wilks (en R-UCA) se utiliza para comprobar que una variable sea normal ([[Distribución normal]]). Este caso se puede dar cuando $n$ sea tan pequeña que no podamos asumir la normalidad de de la variable.

Tomamos como hipótesis nula ($H_0$) que la distribución de la variable sea normal y como hipótesis alternativa ($H_A$) que la variable no sea normal.

Estadísticos -> Resúmenes -> Test de normalidad

Si [[p-valor]] $< \alpha$ ([[Nivel de significación]]) $\implies$ rechazamos normalidad.
Si p-valor $\ge \alpha \implies$ no rechazamos la normalidad.

Cuando rechazamos la normalidad, podemos recurrir a métodos a test no paramétricos como el [[Test de Wilcoxon]]

--- 
### Referencias

[[Inferencia estadística]]