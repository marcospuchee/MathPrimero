
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-27, 14:08

```ad-theorem
Sea $I$ un intervalo abierto $f: I \to \mathbb R$ una función $n+1$ veces derivable en $I$ y $a, x \in I$, entonces $\exists \xi \in ]a,x[$ tal que:
$$f(x) = \sum_{k = 0}^n \frac{f^{(k)}(a)}{k!} (x-a)^k + \frac{f^{(n+1)}(\xi)}{(n+1)!}(x-a)^{n+1}.$$
```


```ad-proof
Sean
$$
R(x) := f(x) - \sum_{k = 0}^n \frac{f^{(k)}(a)}{k!}(x-a)^k, \quad S(x) := \frac{(x-a)^{n+1}}{(n+1)!}, \quad x \in I.
$$
([[Resto de Taylor]])

Por la propiedad que cumple el [[Polinomio de Taylor]], tenemos que
$$R(a) = R'(a) = \dots = R^{(n)}(a) = 0, \quad R^{(n+1)}(x) = f^{(n+1)}(x), \quad x \in I^o.$$
Además, tenemos que
$$S(a) = S'(a) = \dots = S^{(n)}(a) = 0,\quad S^{(n+1)}(x) = 1, \quad x \in I^o.$$

Supondremos por ejemplo que $a < x$. Si aplicamos el [[Teorema del valor medio de Cauchy (1821)]], en primer lugar para las funciones $R$ y $S$, después para $R'$ y $S'$, y sucesivamente para $R^{(k)}, S^{(k)}$, con $0 \le k \le n$, llegamos a:
$$
\begin{eqnarray}
\frac{R(x)}{S(x)} &=& \frac{R(x) - R(a)}{S(x) - S(a)} = \frac{R'(\xi_1)}{S'(\xi_1)} = \frac{R'(\xi_1) - R'(a)}{S'(\xi_1) - S'(a)} = \frac{R''(\xi_2)}{S''(\xi_2)} = \frac{R''(\xi_2) - R''(a)}{S''(\xi_2) - S''(a)} = \dots \\
&=& \frac{R^{(n)}(\xi_n) - R^{(n)}(a)}{S^{(n)}(\xi_n) - S^{(n)}(a)} = \frac{R^{(n+1)}(\xi_{n+1})}{S^{(n+1)}(\xi_{n+1})} = f^{(n+1)}(\xi_{n+1})
\end{eqnarray}
$$

donde 
$$a < \xi_{n+1} < \xi_n < \dots < \xi_1 < x.$$
Por tanto,
$$R(x) = S(x)f^{(n+1)}(\xi_{n+1}),$$
que es lo que queríamos demostrar.
```


**Tema:** [[Funciones derivables#7. El polinomio de Taylor]]
**Demostrado por:** [[Teorema del valor medio de Cauchy (1821)]]
**Consecuencias:** [[Proposición existencia límite del infinitésimo f - polinomio de Taylor de grado n+1]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Lagrange (1797)?
Reverso: Sea $I$ un intervalo abierto $f: I \to \mathbb R$ una función $n+1$ veces derivable en $I$ y $a, x \in I$, entonces $\exists \xi \in ]a,x[$ tal que:
$$f(x) = \sum_{k = 0}^n \frac{f^{(k)}(a)}{k!} (x-a)^k + \frac{f^{(n+1)}(\xi)}{(n+1)!}(x-a)^{n+1}.$$
Tags: proposición/teorema análisisI
<!--ID: 1713093069918-->
END

START
Básico
Anverso: Demostración del teorema de Lagrange (1797)
Reverso: Sean
$$
R(x) := f(x) - \sum_{k = 0}^n \frac{f^{(k)}(a)}{k!}(x-a)^k, \quad S(x) := \frac{(x-a)^{n+1}}{(n+1)!}, \quad x \in I.
$$
([[Resto de Taylor]])

Por la propiedad que cumple el [[Polinomio de Taylor]], tenemos que
$$R(a) = R'(a) = \dots = R^{(n)}(a) = 0, \quad R^{(n+1)}(x) = f^{(n+1)}(x), \quad x \in I^o.$$
Además, tenemos que
$$S(a) = S'(a) = \dots = S^{(n)}(a) = 0,\quad S^{(n+1)}(x) = 1, \quad x \in I^o.$$

Supondremos por ejemplo que $a < x$. Si aplicamos el [[Teorema del valor medio de Cauchy (1821)]], en primer lugar para las funciones $R$ y $S$, después para $R'$ y $S'$, y sucesivamente para $R^{(k)}, S^{(k)}$, con $0 \le k \le n$, llegamos a:
$$
\begin{eqnarray}
\frac{R(x)}{S(x)} &=& \frac{R(x) - R(a)}{S(x) - S(a)} = \frac{R'(\xi_1)}{S'(\xi_1)} = \frac{R'(\xi_1) - R'(a)}{S'(\xi_1) - S'(a)} = \frac{R''(\xi_2)}{S''(\xi_2)} = \frac{R''(\xi_2) - R''(a)}{S''(\xi_2) - S''(a)} = \dots \\
&=& \frac{R^{(n)}(\xi_n) - R^{(n)}(a)}{S^{(n)}(\xi_n) - S^{(n)}(a)} = \frac{R^{(n+1)}(\xi_{n+1})}{S^{(n+1)}(\xi_{n+1})} = f^{(n+1)}(\xi_{n+1})
\end{eqnarray}
$$

donde 
$$a < \xi_{n+1} < \xi_n < \dots < \xi_1 < x.$$
Por tanto,
$$R(x) = S(x)f^{(n+1)}(\xi_{n+1}),$$
que es lo que queríamos demostrar.
Tags: demostración análisisI
<!--ID: 1713093069920-->
END