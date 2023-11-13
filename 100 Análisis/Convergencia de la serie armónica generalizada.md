### Contenido principal

$\sum_{n=1}^{+\infty} \frac{1}{n^p}$ es la serie armónica generalizada. Como $\frac{1}{n^p} \ge 0, \forall n \in \mathbb{N}, \frac{1}{n^p} \ge \frac{1}{(n+1)^p}, \forall n \in \mathbb{N}$. Por el [[Criterio de Condensación de Cauchy]], $\sum_{n=1}^{+\infty} \frac{1}{n^p}$ converge $\iff \sum_{n=1}^{+\infty} \frac{2^n}{2^{np}}$ converge.

$\sum_{n=1}^{+\infty} \frac{2^n}{2^{np}} = \sum_{n=1}^{+\infty} \frac{1}{2^{n(p-1)}}$. 
- Si $p > 1, p-1>0$. Por tanto, $\frac{1}{2^{p-1}} < \frac{1}{2^0} = 1$. Así, se trata de una serie geométrica de razón $\frac{1}{2^{p-1}} < 1$, por lo que converge a 0.
- Si $p < 1 , \frac{1}{2^{n(p-1)}}= 2^{(1-p)n}$, que diverge.
- Si $p=1, \sum_{n=1}^{+\infty} \frac{1}{n^p} = \sum_{n=1}^{+\infty} \frac{1}{n}$, que es la serie armónica y diverge.

--- 
### Referencias

[[Serie numérica]]