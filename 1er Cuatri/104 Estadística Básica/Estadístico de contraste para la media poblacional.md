### Contenido principal

Supongamos que en el contraste que estamos estudiando, $H_0 : \mu = \mu_0$ ([[Elementos de un contraste de hipótesis]]). Como suponemos esta hipótesis cierta, la media muestral $\overline{x}$ proviene de una [[Distribución normal]] con media $\mu_0$ y varianza $\sigma$ desconocida:
$$
\begin{equation}
\frac{\overline{X_n} - \mu_0}{s_n/\sqrt{n}} \sim t_{n-1}
\end{equation}
$$

Por tanto, el [[Estadístico de contraste]] es:
$$
\begin{equation}
t_0 = \frac{\overline x - \mu_0}{s_n / \sqrt n}
\end{equation}
$$

y debemos de ubicar $t_0$ en la distribución $t$ de Student con $n-1$ grados de libertad:
- Si $t_0$ está cerca del centro de la distribución, los datos son compatibles con la hipótesis nula.
- Si $t_0$ está en una de las colas de la distribución, los datos no son compatibles con $H_0$ y proporcionan evidencia a favor que $H_A$ sea verdadera.

--- 
### Referencias

[[Inferencia estadística]]
[[Contraste de hipótesis]]