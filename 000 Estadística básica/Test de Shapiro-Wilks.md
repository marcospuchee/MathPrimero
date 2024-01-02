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

---
### Anki

START
KaTeX and Markdown Basic
Front: Para qué se usa el Test de Shapiro-Wilks?
Back: El test de Shapiro-Wilks (en R-UCA) se utiliza para comprobar que una variable sea normal ([[Distribución normal]]). Este caso se puede dar cuando $n$ sea tan pequeña que no podamos asumir la normalidad de de la variable.
Tags: definición
<!--ID: 1704106901696-->
END

START
KaTeX and Markdown Basic
Front: Hipótesis del Test de Shapiro-Wilks
Back: Tomamos como hipótesis nula ($H_0$) que la distribución de la variable sea normal y como hipótesis alternativa ($H_A$) que la variable no sea normal.

Si [[p-valor]] $< \alpha$ ([[Nivel de significación]]) $\implies$ rechazamos normalidad.
Si p-valor $\ge \alpha \implies$ no rechazamos la normalidad.
Tags: definición
<!--ID: 1704106901704-->
END

START
KaTeX and Markdown Basic
Front: Qué podemos utilizar cuando no podemos suponer la normalidad de una muestra?
Back: Cuando rechazamos la normalidad, podemos recurrir a métodos a test no paramétricos como el [[Test de Wilcoxon]]. 
Tags: definición
<!--ID: 1704106901709-->
END