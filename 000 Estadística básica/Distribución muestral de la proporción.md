### Contenido principal

Observamos en primer lugar que a cada valor de la proporción de individuos, $\hat{\pi}$, le corresponde un determinado número de individuos, $Y$. Lo que estamos afirmando es que $\hat{\pi} = Y/n$.

$Y$ siempre sigue una [[Distribución binomial]] por lo que $P(\hat{p} = r/n) = \binom{n}{r} p^r(1-p)^{n-r}$ con $r = 0,1, \dots, n$.

Sabemos que $Y \sim B(n,p)$, su media y varianza valdrán $\mu_Y = np$ y $\sigma_Y^2 = np(1-p)$ porque sigue una distribución binomial. Por tanto, como $\hat{\pi} = Y/n$, obtenemos que $\mu_{\hat{\pi}} = \frac{np}{n} = p$ y $\sigma_{\hat{\pi}}^2 = \frac{np(1-p)}{n^2} = \frac{p(1-p)}{n}$.

--- 
### Referencias

[[Inferencia estadística]]