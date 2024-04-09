
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-27, 14:39

```ad-theorem
Sean $\epsilon > 0, a \in \mathbb R$ y $f$ una función infinitamente derivable en $]a- \varepsilon, a + \varepsilon[$. Si $\exists B > 0$, y $C > 0$ tales que $\forall n \in \mathbb N$
$$\sup_{x \in ]a-\varepsilon, a + \varepsilon[} |f^{(n)}(x)| \le (n!)B^nC,$$
entonces
$$f(x) = \sum_{n = 0}^{+\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n, \quad |x-a| < 1/B.$$
[[Desarrollo de Taylor]], [[Polinomio de Taylor]]
```


```ad-proof

Basta demostrar que el [[Resto de Taylor]] converge a cero. Recordando la expresión de Lagrange del resto ([[Teorema de Lagrange (1797)]]), resulta que si $|x-a| < 1/B$, entonces
$$\frac{|f^{(n+1)}(\xi)|}{(n+1)!} |x-a|^{n+1} \le C(B|x-a|)^{n+1}.$$
La última expresión tiende a cero porque $B|x-a| < 1$.
```


**Tema:** [[Funciones derivables#7. El polinomio de Taylor]]
**Demostrado por:** [[Teorema de Lagrange (1797)]]
**Consecuencias:**

---
### Anki
