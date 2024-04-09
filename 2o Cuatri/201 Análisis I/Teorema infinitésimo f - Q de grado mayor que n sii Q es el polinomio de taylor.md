
---
mathLink: $\lim_{x \to a} \frac{f(x) - Q(x)}{(x-a)^n} = 0 \iff Q$ polinomio de Taylor
---
### Contenido Principal

**Fecha:** 2024-03-27, 13:58

```ad-theorem
Sea $f$ una función definida en el intervalo abierto $I$, $n-1$ veces derivable en $I$ de manera que $f^{(n-1)}$ es derivable en $a \in I$. Sea $Q$ un polinomio tal que $\partial Q \le n$. Las siguientes afirmaciones equivalen.
1. $$\lim_{x \to a} \frac{f(x) - Q(x)}{(x-a)^n} = 0.$$
2. $Q$ es el [[Polinomio de Taylor]] de $f$ en el punto $a$ de orden $n$.
```


```ad-proof
**$2 \implies 1$**.
Es consecuencia inmediata de [[Orden del infinitésimo f - polinomio de Taylor]].

**$1 \implies 2$**.
Sea $P$ el [[Polinomio de Taylor]] de $f$ en el punto $a$ de orden $n$. Tendremos que:
$$\frac{P(x) - Q(x)}{(x-a)^n} = \frac{P(x) - f(x)}{(x-a)^n} + \frac{f(x) - Q(x)}{(x-a)^n}.$$
Según la hipótesis y la proposición [[Orden del infinitésimo f - polinomio de Taylor]],
$$\lim_{x \to a} \frac{P(x) - Q(x)}{(x-a)^n} = 0.$$
Para acabar la prueba basta aplicar [[Lema no existe polinomio de orden menor que m infinitésimo de orden mayor que m]].
```


**Tema:** [[Funciones derivables#7. El polinomio de Taylor]]
**Demostrado por:** [[Orden del infinitésimo f - polinomio de Taylor]], [[Lema no existe polinomio de orden menor que m infinitésimo de orden mayor que m]]
**Consecuencias:**

---
### Anki
