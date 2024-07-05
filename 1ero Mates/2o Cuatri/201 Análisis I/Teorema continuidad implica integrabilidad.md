
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 17:02

```ad-theorem
Sea $f: [a,b] \to \mathbb R$ continua ([[Función continua en un conjunto]]), entonces $f \in \mathcal R([a,b])$ ([[integral de Riemann]]).
```


```ad-proof
Por ser continua, por el [[teorema de Heine (1872)]], $f$ es [[función uniformemente continua]]. Esto es, dado $\varepsilon > 0, \exists \delta > 0$ tal que si $x, y \in [a,b] \land |x-y| \le \delta$, entonces $|f(x) - f(y)| < \frac{\varepsilon}{b-a}$.

Tomamos $n \in \mathbb N$ tal que $\frac{b-a}{n} < \delta$. Sea $P_n = \{x_0, x_1, \dots, x_n \}$ partición de $[a,b]$ ([[partición de un intervalo]]) tal que $x_j - x_{j-1} = \frac{b-a}{n}$. Tomamos:
$$M_j = \sup \{f(x) : x \in [x_{j-1}, x_j] \}; \quad m_j = \inf \{f(x) : x \in [x_{j-1}, x_j] \}.$$
Por el [[teorema de Weierstrass]], $f$ es [[función acotada]], es decir, $\exists u_j, v_j \in [x_{j-1}, x_j]$ tales que $f(u_j) \le f(x) \le f(v_j)$, $\forall x \in [x_{j-1}, x_j]$. Por tanto,
$$M_j = f(v_j), m_j = f(u_j) \implies M_j - m_j = f(v_i) - f(u_j) < \frac{\varepsilon}{b-a}.$$
Entonces,
$$U(f, P_n) - L(f,P_n) = \sum_{j = 1}^n (M_J - m_j)(x_j - x_{j-1}) < \frac{\varepsilon}{b-a} \sum_{j = 1}^n (x_j - x_{j-1}) = \varepsilon,$$
([[suma superior de Riemann]], [[suma inferior de Riemann]]) ya que $\sum_{j = 1}^n (x_j - x_{j-1}) = x_n - x_0 = b-a$.

Por tanto, por el [[criterio de integrabilidad]], $f \in \mathcal R ([a,b])$.
```

**Tema:** [[Integración de funciones de una variable real#1. Integral de Riemann]]
**Demostrado por:** [[Criterio de integrabilidad]], [[Teorema de Weierstrass]], [[Teorema de Heine (1872)]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué relación existe entre que una función sea continua e integrable?
Reverso: Sea $f: [a,b] \to \mathbb R$ continua ([[Función continua en un conjunto]]), entonces $f \in \mathcal R([a,b])$ ([[Integral de Riemann]]).
Tags: proposición/teorema análisisI
<!--ID: 1714669443700-->
END

START
Básico
Anverso: Demostración de que sea $f: [a,b] \to \mathbb R$ continua ([[Función continua en un conjunto]]), entonces $f \in \mathcal R([a,b])$ ([[Integral de Riemann]]).
Reverso: Por ser continua, por el [[Teorema de Heine (1872)]], $f$ es [[Función uniformemente continua]]. Esto es, dado $\varepsilon > 0, \exists \delta > 0$ tal que si $x, y \in [a,b] \land |x-y| \le \delta$, entonces $|f(x) - f(y)| < \frac{\varepsilon}{b-a}$.

Tomamos $n \in \mathbb N$ tal que $\frac{b-a}{n} < \delta$. Sea $P_n = \{x_0, x_1, \dots, x_n \}$ partición de $[a,b]$ ([[Partición de un intervalo]]) tal que $x_j - x_{j-1} = \frac{b-a}{n}$. Tomamos:
$$M_j = \sup \{f(x) : x \in [x_{j-1}, x_j] \}; \quad m_j = \inf \{f(x) : x \in [x_{j-1}, x_j] \}.$$
Por el [[Teorema de Weierstrass]], $f$ es [[Función acotada]], es decir, $\exists u_j, v_j \in [x_{j-1}, x_j]$ tales que $f(u_j) \le f(x) \le f(v_j)$, $\forall x \in [x_{j-1}, x_j]$. Por tanto,
$$M_j = f(v_j), m_j = f(u_j) \implies M_j - m_j = f(v_i) - f(u_j) < \frac{\varepsilon}{b-a}.$$
Entonces,
$$U(f, P_n) - L(f,P_n) = \sum_{j = 1}^n (M_J - m_j)(x_j - x_{j-1}) < \frac{\varepsilon}{b-a} \sum_{j = 1}^n (x_j - x_{j-1}) = \varepsilon,$$
([[Suma superior de Riemann]], [[Suma inferior de Riemann]]) ya que $\sum_{j = 1}^n (x_j - x_{j-1}) = x_n - x_0 = b-a$.

Por tanto, por el [[Criterio de integrabilidad]], $f \in \mathcal R ([a,b])$.
Tags: demostración análisisI
<!--ID: 1714669443709-->
END