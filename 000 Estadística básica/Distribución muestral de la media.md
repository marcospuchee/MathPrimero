### Contenido principal

$X$ es una [[Variable aleatoria]], vamos a calcular la distribución muestral de la media ($\mu$):
$E[\overline{x}] = E[\frac{1}{n} \sum x_i] = \frac{1}{n} \sum E[x_i] = \frac{1}{n} \sum \mu = \mu \implies E[\overline{x}] = \mu$.

Así, la varianza de $\overline{x}$ será:
$Var[\overline{x}] = \frac{1}{n^2} \sum Var[x_i] = \frac{\sigma^2}{n} \implies Var[\overline{x}] = \sigma^2/n$.

Así, vemos que la distribución exacta de $\overline{x}$ para pequeñas muestras depende de la población. Además, asintóticamente, la distribución de $\overline{x}$ será normal en virtud del [[Teorema Central del Límite]]. Se suele dar para $n \ge 30$.

--- 
### Referencias

[[Inferencia estadística]]