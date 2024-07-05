
---
mathLink: $0 \not = E_f (\lambda) \le V$
---
### Contenido Principal

**Fecha:** 2024-02-02, 19:48
Sea $f \in End(V)$ ([[Endomorfismo]]), $\lambda \in K$ [[Valor propio de un endomorfismo]] $f$, entonces

```ad-lemma
$0 \not = E_f (\lambda) \le V$

En particular, $dim(E_f (\lambda) \ge 1)$
```


```ad-proof
Notemos que $0 \in E_f (\lambda)$, de modo que $E_f (\lambda) \not = \emptyset$. Ahora, dados $u, v \in E_f (\lambda), \alpha, \beta \in K$, tenemos:
$$f(\alpha u + \beta v) = \alpha f(u) + \beta f(v) = \alpha (\lambda u) + \beta (\lambda v) = \lambda(\alpha u + \beta v)$$
Así, por definición de [[Subespacio vectorial]], $E_f (\lambda) \le V$.

Además, por definición de valor propio de $f$, tenemos que $\exists v \in V - \{0\}$ tal que $f(v) = \lambda v$. Así, $v \in E_f (\lambda)$ y deducimos que $E_f (\lambda) \not = 0$ (es decir, no es el subespacio del cero). En particular, $dim(E_f (\lambda)) \ge 1$.
``` 

**Tema:** [[Diagonalización]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Demostración de que sea $f \in End(V)$ ([[Endomorfismo]]), $\lambda \in K$ [[Valor propio de un endomorfismo]] $f$, entonces $0 \not = E_f (\lambda) \le V$

En particular, $dim(E_f (\lambda) \ge 1)$
Reverso: Notemos que $0 \in E_f (\lambda)$, de modo que $E_f (\lambda) \not = \emptyset$. Ahora, dados $u, v \in E_f (\lambda), \alpha, \beta \in K$, tenemos:
$$f(\alpha u + \beta v) = \alpha f(u) + \beta f(v) = \alpha (\lambda u) + \beta (\lambda v) = \lambda(\alpha u + \beta v)$$
Así, por definición de [[Subespacio vectorial]], $E_f (\lambda) \le V$.

Además, por definición de valor propio de $f$, tenemos que $\exists v \in V - \{0\}$ tal que $f(v) = \lambda v$. Así, $v \in E_f (\lambda)$ y deducimos que $E_f (\lambda) \not = 0$ (es decir, no es el subespacio del cero). En particular, $dim(E_f (\lambda)) \ge 1$.
Tags: demostración
<!--ID: 1707247432422-->
END