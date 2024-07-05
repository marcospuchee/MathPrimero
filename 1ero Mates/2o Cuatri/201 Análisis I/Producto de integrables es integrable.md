
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 19:15

```ad-proposition
Sean $f,g \in R[a,b]$ /[[integral de Riemann]] $\implies fg \in R[a,b]$.
```


```ad-proof
**Caso 1. $f = g$.**
¿$f^2 \in R[a,b]$? Como $f^2 = |f|^2$ y $|f|$ es integrable, podemos suponer $f \ge 0$.
Sea $P = \{a = x_0, x_1, \dots, x_n = b \}$ [[partición de un intervalo]] $[a,b]$. Tenemos:
$$\begin{array}{l}
\sup \{f^2(x) : x \in [x_{j-1}, x_j] \} = (\sup \{f(x): x \in [x_{j-1}, x_j] \} )^2 = M_j^2 \\
\inf \{f^2(x): x \in [x_{j-1}, x_j] \} = (\inf \{f(x): x \in [x_{j-1}, x_j] \} )^2 = m_j^2,
\end{array}$$
por suponer que $f \ge 0$.
Luego,
$$U(f^2, P) - L(f^2, P) = \sum_{j = 1}^n (x_j - x_{j-1})(M_j^2 - m_j^2) = \sum_{j = 1}^n (x_j - x_{j-1})(M_j - m_J)(M_j + m_j).$$
Al ser $f$ integrable, $f$ es acotada. Es decir, $\exists K \ge 0$ tal que $|f(x)| \le K, \forall x \in [a,b]$. Entonces $m_j + M_j \le 2K$. Es decir,
$$\sum_{j = 1}^n (x_j - x_{j-1})(M_j - m_j)(M_j + m_j) \le 2K \sum_{j = 1}^n (x_j - x_{j-1})(M_j - m_j).$$
Por tanto, $U(f^2, P) - L(f^2, P) \le 2K (U(f, P) - L(f, P))$.
Dado $\varepsilon > 0, \exists P_\varepsilon \in [a,b]$ tal que $U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon/2K$. Entonces, 
$$U(f^2, P_\varepsilon) - L(f^2, P_\varepsilon) \le 2K (U(f, P_\varepsilon) - L(f, P_\varepsilon)) < \varepsilon \implies f^2 \in R[a,b].$$

**Caso general.**
$f,g \in R[a,b]$. ¿$fg \in R[a,b]$? Tenemos que:
$$(f+g)^2 = f^2 + g^2 +2fg \implies fg = \frac{1}{2} \left ( (f+g)^2 - f^2 - g^2 \right ).$$
Como $f,g \in R[a,b]$, entonces $(f+g)2, f^2, g^2 \in R[a,b]$. Luego $f,g$ integrable.
```

**Tema:** [[Integración de funciones de una variable real]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la proposición que garantiza que el producto de funciones integrables es integrable
Reverso: Sean $f,g \in R[a,b]$ /[[Integral de Riemann]] $\implies fg \in R[a,b]$.
Tags: proposición/teorema análisisI
<!--ID: 1714669443723-->
END

START
Básico
Anverso: Demostración de que sean $f,g \in R[a,b]$ /[[Integral de Riemann]] $\implies fg \in R[a,b]$.
Reverso: **Caso 1. $f = g$.**
¿$f^2 \in R[a,b]$? Como $f^2 = |f|^2$ y $|f|$ es integrable, podemos suponer $f \ge 0$.
Sea $P = \{a = x_0, x_1, \dots, x_n = b \}$ [[Partición de un intervalo]] $[a,b]$. Tenemos:
$$\begin{array}{l}
\sup \{f^2(x) : x \in [x_{j-1}, x_j] \} = (\sup \{f(x): x \in [x_{j-1}, x_j] \} )^2 = M_j^2 \\
\inf \{f^2(x): x \in [x_{j-1}, x_j] \} = (\inf \{f(x): x \in [x_{j-1}, x_j] \} )^2 = m_j^2,
\end{array}$$
por suponer que $f \ge 0$.
Luego,
$$U(f^2, P) - L(f^2, P) = \sum_{j = 1}^n (x_j - x_{j-1})(M_j^2 - m_j^2) = \sum_{j = 1}^n (x_j - x_{j-1})(M_j - m_J)(M_j + m_j).$$
Al ser $f$ integrable, $f$ es acotada. Es decir, $\exists K \ge 0$ tal que $|f(x)| \le K, \forall x \in [a,b]$. Entonces $m_j + M_j \le 2K$. Es decir,
$$\sum_{j = 1}^n (x_j - x_{j-1})(M_j - m_j)(M_j + m_j) \le 2K \sum_{j = 1}^n (x_j - x_{j-1})(M_j - m_j).$$
Por tanto, $U(f^2, P) - L(f^2, P) \le 2K (U(f, P) - L(f, P))$.
Dado $\varepsilon > 0, \exists P_\varepsilon \in [a,b]$ tal que $U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon/2K$. Entonces, 
$$U(f^2, P_\varepsilon) - L(f^2, P_\varepsilon) \le 2K (U(f, P_\varepsilon) - L(f, P_\varepsilon)) < \varepsilon \implies f^2 \in R[a,b].$$

**Caso general.**
$f,g \in R[a,b]$. ¿$fg \in R[a,b]$? Tenemos que:
$$(f+g)^2 = f^2 + g^2 +2fg \implies fg = \frac{1}{2} \left ( (f+g)^2 - f^2 - g^2 \right ).$$
Como $f,g \in R[a,b]$, entonces $(f+g)2, f^2, g^2 \in R[a,b]$. Luego $f,g$ integrable.
Tags: demostración análisisI
<!--ID: 1714669443727-->
END