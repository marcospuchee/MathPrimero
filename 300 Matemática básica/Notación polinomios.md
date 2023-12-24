A2023-12-19, 05:53
### Contenido principal

Dado un [[Polinomio]] $p(x)$.
- El coeficiente director de $p(x) \not = 0$ es el término $a_r \not = 0$ tal que $a_k = 0, \forall k > r$.
- En este caso, $r$ es el grado de $p(x)$, que escribiremos como  $\delta (p(x))$ o $\delta(p)$.
- Si $a_r = 1$, decimos que $p(x)$ es mónico.
- Si $a \in K$ cumple que $p(a) = a_0 + a_1a + \dots + a_n a^n = 0$, decimos que $a$ es raíz de $p(x)$.
- Al conjunto de polinomios con coeficientes en $K$ lo denotamos por $K[x]$. Además, $K[x]$ es [[Anillo]] con la suma y el producto de polinomios definidos así: sea $p(x) = \sum_{i = 0}^n a_ix^i$, $q(x) = \sum_{i = 0}^n b_i x^i$, entonces
	- $p(x) + q(x) = \sum_{i = 0}^n (a_i + b_i)x^i$.
	- $p(x)q(x) = \sum^{\delta(p) + \delta(q)}_{i = 0} (\sum_{k + j = i} a_k b_j) x_i$.


--- 
### Referencias

[[Polinomio#1. Polinomios]]