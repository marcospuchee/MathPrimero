### Contenido principal

Si conocemos $\sigma$, entonces [[Intervalo de confianza para la media de una población Normal (varianza conocida)]].

Cuando no la conocemos, entonces la sustituimos por su [[Estimador]], $s_n$. Sin embargo, este resultado ya no se basa en:
$$
\begin{equation}
\frac{\overline{X_n} - \mu}{\sigma / \sqrt{n}} \sim N(0,1)
\end{equation}
$$
sino que al sustituir se queda:
$$
\begin{equation}
\frac{\overline{X_n} - \mu}{s_n/\sqrt{n}} \sim t_{n-1}
\end{equation}
$$
donde $t_{n-1}$ es una variable aleatoria $t$ de Student con $n-1$ grados de libertad. Por tanto, se nos queda que:
$$
\begin{equation}
1 - \alpha = P(\overline{X_n} - t_{\alpha, n-1} \frac{s_n}{\sqrt{n}} \le \mu \le \overline{X_n}+ t_{\alpha, n-1} \frac{s_n}{\sqrt{n}})
\end{equation}
$$
y
$$
\begin{equation}
IC_\alpha = [\overline{X_n} \pm t_{1-\alpha, n-1} s_n / \sqrt{n}]
\end{equation}
$$



--- 
### Referencias

[[Distribución normal]]
[[Inferencia estadística]]
[[Intervalo de confianza]]