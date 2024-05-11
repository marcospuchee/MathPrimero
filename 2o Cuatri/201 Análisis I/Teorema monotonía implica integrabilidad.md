
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 16:51

```ad-theorem
Sea $f: [a,b] \to \mathbb R$ una [[función monótona]], entonces $f \in \mathcal R([a,b])$ ([[integral de Riemann]]).
```


```ad-proof
Supondremos que $f: [a,b] \to \mathbb R$ es monótona creciente ($x<y \implies f(x) \le f(y)$). Para cada $n \in \mathbb N$, sea $P_n = \{x_0, x_1, \dots, x_n\}$ de modo que $x_j - x_{j-1} = \frac{b-a}{n}$. Tomamos

$$\begin{eqnarray} m_j &=& \inf \{f(x): x \in [x_{j-1}, x_j] \} = f(x_{j-1}) \\
M_j &=& \sup \{f(x): x \in [x_{j-1}, x_j] \} = f(x_j), \end{eqnarray} $$
por ser monótona.

Entonces, con la definición de [[suma superior de Riemann]] y [[suma inferior de Riemann]], desarrollamos:
$$
\begin{eqnarray} 
U(f, P_n) - L(f,P_n) &=& \sum_{j = 1}^n (M_j - m_j)(x_j - x_{j-1}) = \sum_{j = 1}^n (f(x_j) - f(x_{j-1}))(x_j - x_{j-1}) = \\
&=& \sum_{j = 1}^n (f(x_j) - f(x_{j-1}))(\frac{b-a}{n}) = \frac{b-a}{n} \sum_{j = 1}^n (f(x_j) - f(x_{j-1})) = \\
&=& \frac{b-a}{n}(f(x_n) - f(x_0)) = \frac{b-a}{n}(f(b)- f(a)).
\end{eqnarray}
$$
Dado $\varepsilon > 0, \exists n \in \mathbb N$ tal que: 
$$\frac{b-a}{n} (f(b) - f(a)) < \varepsilon \implies U(f, P_n) - L(f, P_n) < \varepsilon.$$
Por el [[criterio de integrabilidad]], $f \in R[a,b]$.
```

**Tema:** [[Integración de funciones de una variable real#1. Integral de Riemann]]
**Demostrado por:** [[Criterio de integrabilidad]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué relación existe entre que una función sea monótona e integrable?
Reverso: Sea $f: [a,b] \to \mathbb R$ una [[función monótona]], entonces $f \in \mathcal R([a,b])$ ([[integral de Riemann]]).
Tags: proposición/teorema análisisI
<!--ID: 1714669443678-->
END

START
Básico
Anverso: Demostración de que sea $f: [a,b] \to \mathbb R$ una [[función monótona]], entonces $f \in \mathcal R([a,b])$ ([[integral de Riemann]]).
Reverso: 
Tags: demostración análisisI
<!--ID: 1714669443688-->
END
