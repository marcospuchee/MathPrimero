### Contenido principal

Sea $X \sim N(\mu, \sigma^2)$, hemos visto que la media muestral tiene una distribución de probabilidad $\overline{X_n} \sim N(\mu, \sigma^2/n)$ ([[Distribución muestral de la media]]). Sea $Z \sim N(0,1)$ la forma tipificada ([[Fórmula de tipificación]]) de $\overline{X_n}$, buscamos un valor $z_{\alpha/2}$ tal que $P(|Z| \le z_{\alpha/2}) = 1-\alpha$, donde $Z = \frac{\overline{X_n} - \mu}{\sigma / \sqrt{n}}$, por la [[Fórmula de tipificación]]. Así desarrollamos la fórmula y nos queda que:
$$
\begin{equation}
P(|\frac{\overline{X_n} - \mu}{\sigma / \sqrt{n}}| \le z_{\alpha/2}) = P(\overline{X_n} - z_{\alpha}\frac{\sigma}{\sqrt{n}} \le \mu \le \overline{X_n} + z_{\alpha/2} \frac{\sigma}{\sqrt{n}})
\end{equation}
$$
$\alpha =$ [[Nivel de significación]] (porcentaje que se queda fuera de un cierto valor).

Así, el intervalo de confianza será $IC_\alpha = [\overline{X} \pm z_{\alpha/2} \sigma / \sqrt{n}]$ y lo llamamos intervalo de confianza al $\alpha\%$ para la media.

Cuando desconocemos $\alpha$ (que es lo normal), tenemos la siguiente fórmula: [[Intervalo de confianza para la media de una población Normal (varianza desconocida)]]

--- 
### Referencias

[[Distribución normal]]
[[Intervalo de confianza]]
[[Inferencia estadística]]