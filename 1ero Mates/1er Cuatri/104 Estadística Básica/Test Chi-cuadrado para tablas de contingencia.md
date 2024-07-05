2023-12-20, 07:00
### Contenido principal

El [[Estadístico de contraste]] se basa en las diferencias entre las frecuencias observadas y las frecuencias esperadas en todas las celdas de la tabla:
$$ \chi_s^2 = \sum_{j = 1}^k \sum_{i = 1}^r \frac{(O_{ij} - E_{ij})^2}{E_{ij}}$$
donde
$O_{ij}:$ frecuencia observada en cada celda $(i,j)$.
$E_{ij}:$ frecuencia esperada en cada celda $(i,j)$. Además, $E(\textrm{Fila } i, \textrm{ Columna } j) = \frac{(\textrm{Total fila } i) \times (\textrm{ Total columna } j)}{\textrm{Total general}}$.

Si la hipótesis nula es cierta ([[Tablas de contingencia (independencia)]], [[Tablas de contingencia (homogeneidad)]]), el estadístico sigue unan [[Distribución Chi-Cuadrado]] con grados de libertad $= (r-1)(k-1)$ donde $r =$ número de filas y $k =$ número de columnas.

--- 
### Referencias

[[Análisis de datos categóricos]]

---
### Anki

START
Básico
Anverso: Para qué sirve el Test Chi-cuadrado?
Reverso: Para resolver tablas de contingencia (tanto homogeneidad como independencia).
Tags: definición
<!--ID: 1704379117111-->
END

START
Básico
Anverso: Cuáles son las hipótesis del Test Chi-cuadrado.
Reverso: Las mismas que la tabla a resolver.
Tags: definición
<!--ID: 1704379117120-->
END

START
Básico
Anverso: Cuáles es el estadístico de contraste del Test Chi-cuadrado.
Reverso: El [[Estadístico de contraste]] se basa en las diferencias entre las frecuencias observadas y las frecuencias esperadas en todas las celdas de la tabla:
$$ \chi_s^2 = \sum_{j = 1}^k \sum_{i = 1}^r \frac{(O_{ij} - E_{ij})^2}{E_{ij}}$$
donde
$O_{ij}:$ frecuencia observada en cada celda $(i,j)$.
$E_{ij}:$ frecuencia esperada en cada celda $(i,j)$. Además, $E(\textrm{Fila } i, \textrm{ Columna } j) = \frac{(\textrm{Total fila } i) \times (\textrm{ Total columna } j)}{\textrm{Total general}}$.

Si la hipótesis nula es cierta ([[Tablas de contingencia (independencia)]], [[Tablas de contingencia (homogeneidad)]]), el estadístico sigue unan [[Distribución Chi-Cuadrado]] con grados de libertad $= (r-1)(k-1)$ donde $r =$ número de filas y $k =$ número de columnas.
Tags: definición
<!--ID: 1704379117131-->
END