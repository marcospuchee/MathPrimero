
---
mathLink: $\exists \lim_{x \to a}\frac{f(x)- P(x)}{(x-a)n} = 0$.
---
### Contenido Principal

**Fecha:** 2024-03-23, 16:58

```ad-proposition
Sea $f$ una función definida en el intervalo abierto $i$ y $a \in I$. Si $f$ es $n-1$ veces derivable en $I$, $f^{(n-1)}$ es derivable en $a$ y $P$ es el [[Polinomio de Taylor]] de $f$ de orden $n$ centrado en $a$, entonces
$$\exists \lim_{x \to a}\frac{f(x)- P(x)}{(x-a)^n} = 0.$$
```


```ad-proof
Si aplicamos las [[Reglas de L'Hôpital]] $n-1$ veces, tendremos:
$$\lim_{x \to a} \frac{f(x) - P(x)}{(x-a)^n} = \frac{1}{n!} \lim_{x \to a} \frac{f^{(n-1)}(x) - f^{(n-1)}(a) - f^{(n)}(x-a)}{x-a}.$$
Sin embargo, esto es igual a
$$\frac{1}{n!} \lim_{x \to a} \left [ \frac{f^{(n-1)}(x) - f^{(n-1)}(a)}{x-a} - f^{(n)}(a) \right ] = \frac{1}{n!}(f^{(n)}(a) - f^{(n)}(a)) = 0.$$
```

**Tema:** [[Funciones derivables#7. El polinomio de Taylor]]
**Corolarios:** [[Teorema infinitésimo f - Q de grado mayor que n sii Q es el polinomio de taylor]]

---
### Anki

START
Básico
Anverso: Cuál es la proposición que indica el orden del infinitésimo $f - P(x)$, donde $P(x)$ es el polinomio de Taylor?
Reverso: Sea $f$ una función definida en el intervalo abierto $i$ y $a \in I$. Si $f$ es $n-1$ veces derivable en $I$, $f^{(n-1)}$ es derivable en $a$ y $P$ es el [[Polinomio de Taylor]] de $f$ de orden $n$ centrado en $a$, entonces
$$\exists \lim_{x \to a}\frac{f(x)- P(x)}{(x-a)^n} = 0.$$
Tags: proposición/teorema análisisI
<!--ID: 1713093069981-->
END

START
Básico
Anverso: Demostración de que sea $f$ una función definida en el intervalo abierto $i$ y $a \in I$. Si $f$ es $n-1$ veces derivable en $I$, $f^{(n-1)}$ es derivable en $a$ y $P$ es el [[Polinomio de Taylor]] de $f$ de orden $n$ centrado en $a$, entonces
$$\exists \lim_{x \to a}\frac{f(x)- P(x)}{(x-a)^n} = 0.$$
Reverso: Si aplicamos las [[Reglas de L'Hôpital]] $n-1$ veces, tendremos:
$$\lim_{x \to a} \frac{f(x) - P(x)}{(x-a)^n} = \frac{1}{n!} \lim_{x \to a} \frac{f^{(n-1)}(x) - f^{(n-1)}(a) - f^{(n)}(x-a)}{x-a}.$$
Sin embargo, esto es igual a
$$\frac{1}{n!} \lim_{x \to a} \left [ \frac{f^{(n-1)}(x) - f^{(n-1)}(a)}{x-a} - f^{(n)}(a) \right ] = \frac{1}{n!}(f^{(n)}(a) - f^{(n)}(a)) = 0.$$
Tags: demostración análisisI
<!--ID: 1713093069986-->
END