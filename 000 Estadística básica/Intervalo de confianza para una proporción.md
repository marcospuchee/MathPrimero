2023-12-19, 18:30
### Contenido principal

La construcción de un [[Intervalo de confianza]] para la proporción $\pi$ se basa en la aproximación de la [[Distribución binomial]] mediante la [[Distribución normal]]:
- Si $Y \sim Bi(n, \pi)$ y $n$ es grande, $Y \sim N(n\pi, \sqrt{n\pi (1- \pi)})$ (si $n\pi \ge 5$ y $n(1-\pi) \ge 5$).

Ahora, la proporción $\hat \pi = Y/n$, y siendo $n$ grande, $\hat \pi \sim N(\pi, \sqrt{\pi(1-\pi)/n})$

Como la proporción $\pi$ es desconocida, sustituimos en la desviación típica de la normal, el valor de $\pi$ por su estimación, obteniendo así el error estándar de la proporción: [[Error estándar de la proporción]].

Por tanto, el intervalo de confianza del $100(1- \alpha)\%$ para una proporción $\pi$ desconocida es:
$$ P(\pi \in IC) = 1- \alpha \textrm{ con } IC = [\hat \pi \pm t_{1-\alpha, n-1} SE_{\hat \pi}]$$

--- 
### Referencias

[[Análisis de datos categóricos]]