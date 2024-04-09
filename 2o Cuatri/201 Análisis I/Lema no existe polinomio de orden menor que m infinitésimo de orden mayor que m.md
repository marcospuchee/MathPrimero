
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-23, 17:07

```ad-lemma
Sea $P$ un [[Polinomio]] real de variable real de grado $\partial P \le m$, y $a \in \mathbb R$, si
$$\lim_{x \to a} \frac{P(x)}{(x-a)^m} = 0,$$
entonces $P$ es el polinomio idénticamente nulo; $P \equiv 0$.
```

```ad-proof
Por reducción al absurdo, supondremos que $P$ no es idénticamente nulo.
- Caso 1: $\partial P = m$. Tendremos que $P(x) = \sum_{k = 0}^m a_k (x-a)^k = \sum_{k = l}^m a_k (x-a)^k$ con $a_m \neq 0$ y $0 \le l \le m, a_l \neq 0$. Por tanto,
$$\frac{P(x)}{(x-a)^l} = \sum_{k = l}^m a_k (x-a)^{k-l} = \sum_{j = 0}^{m-l} a_{j+l} (x-a)^j.$$
Entonces
$$\lim_{x \to a} \frac{P(x)}{(x-a)^l} = a_l \neq 0.$$
Si $l < m$, tendremos
$$\lim_{x \to a} \frac{P(x)}{(x-a)^m} = \lim_{x \to a} \frac{1}{(x-a)^{m-l}} \frac{P(x)}{(x-a)^l} = \infty,$$
una contradicción que muestra que $l = m$. Entonces
$$P(x) = a_m (x-a)^m,$$
por tanto
$$\lim_{x \to a} \frac{P(x)}{(x-a)^m} = a_m,$$
nuestra hipótesis nos dice que el último límite es cero, por tanto $a_m = 0$. Una contradicción.

- Caso 2: $\partial P < m$. Si $\partial P = n$, sea
$$ \widetilde{P}(x) := (x-a)^{m-n} P(x),$$
como suponemos que $P$ no es idénticamente nulo, tendremos que $\widetilde P$ tampoco lo es y $\partial \widetilde P = m$. Además,
$$\lim_{x \to a} \frac{\widetilde P(x)}{(x-a)^m} = \lim_{x \to a} (x-a)^{m-n} \frac{P(x)}{(x-a)^m} = 0.$$
```

**Tema:** [[Funciones derivables#7. El polinomio de Taylor]]
**Corolarios:** [[Teorema infinitésimo f - Q de grado mayor que n sii Q es el polinomio de taylor]]

---
### Anki
