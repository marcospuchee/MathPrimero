
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-22, 19:02

```ad-proposition
$R[a,b]$ (conjunto de [[Integral de Riemann]]) es [[espacio vectorial]] y la aplicación $R[a,b] \to \mathbb R$ con $f \to \int_a^b f(x) \, dx$ es lineal. Es decir,
1. $f,g \in R[a,b] \implies f+g \in R[a,b] \land \int_a^b (f+g)(x) \, dx = \int_a^b f(x) \, dx + \int_a^b g(x) \, dx$.
2. Dados $f \in R[a,b]$ y $\alpha \in \mathbb R$, entonces $\alpha f \in R[a,b] \land \int_a^b (\alpha f)(x) \, dx = \alpha \int_a^b f(x) \, dx$.

```

```ad-note
title: Notación
Dada $h: [a,b] \to \mathbb R$ acotada, $P = \{a = x_0, x_1, \dots, x_n = b \}$ [[partición de un intervalo]] $[a,b]$.
$$m_j(h) = \inf \{h(x): x \in [x_{j-1}, x_j] \}, \quad M_j = \sup \{h(x): x \in [x_{j-1}, x_j] \}.$$
```

```ad-proof
$(i)$.
Sea $P = \{x_0, \dots, x_n \}$ partición, entonces tenemos que dado $x \in [x_{j-1}, x_j]$:
$$m_j(f) \le f(x) \le M_j(f), \quad m_j(g) \le g(x) \le M_j(g),$$
de donde se deduce:
$$
\begin{eqnarray}
&\implies& m_j(f) + m_j(g) \le f(x) + g(x) \le M_j(f) + M_j(g) \implies \\
&\implies& m_j(f) + m_j(g) \le m_j(f+g) \le M_j(f+g) \le M_j(f) + M_j(g) \implies \\
&\implies& \tag{*} L(f, P) + L(g, P) \le L(f+g, P) \le U(f+g, P) \le U(f,P) + U(g, P)
\end{eqnarray}
$$
Fijamos $\varepsilon > 0$. Por el [[criterio de integrabilidad]],
1. $f \in R[a,b] \implies \exists Q_1 \in \mathcal P[a,b] : U(f, Q_1) - L(f, Q_1) < \frac{\varepsilon}{2}$.
2. $g \in R[a,b] \implies \exists Q_2 \in \mathcal P[a,b] : U(g, Q_2) - L(g, Q_2) < \frac{\varepsilon}{2}$.

Tomamos $P_\varepsilon = Q_1 \cup Q_2$ partición de $[a,b]$, entonces tenemos que
$$U(f, P_\varepsilon) - L(f, P_\varepsilon) < \frac{\varepsilon}{2}, \quad U(g, P_\varepsilon) - L(g P_\varepsilon) < \frac{\varepsilon}{2}$$

Por esto último y $(*)$, obtenemos la siguiente cadena de resultados:
$$\begin{eqnarray}
(*) &\implies& L(f, P_\varepsilon) + L(g, P_\varepsilon) \le L(f+g, P_\varepsilon) \le U(f+g, P_\varepsilon) \le U(f, P_\varepsilon) + U(g, P_\varepsilon) \\
&\implies& U(f+g, P_\varepsilon) - L(f+g, P_\varepsilon) \le (U(f,P_\varepsilon) - L(f, P_\varepsilon)) + (U(g,P_\varepsilon) - L(g,P_\varepsilon)) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon.
\end{eqnarray}$$
Luego, $f+g \in R[a,b]$. Vamos ahora a ver que $\int_a^b (f+g)(x) \, dx =$ $\int_a^b f(x) \, dx + \int_a^b g(x) \, dx$.
Sabemos que
$$L(f, P_\varepsilon) \le \int_a^b f(x) \, dx \le U(f, P_\varepsilon), \quad L(g, P_\varepsilon) \le \int_a^b g(x) \, dx \le U(g, P_\varepsilon).$$
Luego tenemos que
$$\begin{array}{l}
L(f, P_\varepsilon) + L(g, P_\varepsilon) \le \int_a^b f(x) \, dx + \int_a^b g(x) \, dx \le U(f, P_\varepsilon) + U(g, P_\varepsilon) \\
L(f, P_\varepsilon) + L(g, P_\varepsilon) \le \int_a^b (f+g)(x) \, dx \le U(f, P_\varepsilon) + U(g, P_\varepsilon).
\end{array}$$
De ambos resultados concluimos que
$$\left | \int_a^b f(x) \, dx + \int_a^b g(x) \, dx - \int_a^b (f+g)(x) \, dx \right | \le (U(f, P_\varepsilon) - L(f, P_\varepsilon)) + (U(g, P_\varepsilon) - L(g, P_\varepsilon)) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon.$$
Por tanto, $\forall \varepsilon > 0, \int_a^b f(x) \, dx + \int_a^b g(x) \, dx - \int_a^b (f+g)(x) \, dx = 0$.

$(ii).$
Sea $f \in R[a,b], \alpha < 0, P = \{x_0, \dots, x_n \}$ partición de $[a,b]$. Tenemos que
$$m_j(\alpha f) = \inf \{\alpha f(x) : x \in [x_{j-1}, x_j] \} = \alpha \sup \{f(x): x \in [x_{j-1}, x_j] \} = \alpha M_j(f).$$
Análogamente, $M_j(\alpha f) = \alpha m_j(f)$.
Entonces, 
$$L(\alpha f, P) = \sum_{j=1}^n m_j(\alpha f)(x_j - x_{j-1}) = \alpha \sum_{j=1}^n M_j(f)(x_j - x_{j-1}) = \alpha U(f, P).$$
También, 
$$U(\alpha f, P) = \sum_{j = 1}^n M_j(\alpha f)(x_j - x_{j-1}) = \alpha \sum_{j=1}^n m_j(f) (x_j - x_{j-1}) = \alpha L(f, P).$$
Por tanto, tenemos la siguiente igualdad:
$$
\begin{array}{l}
\underline{\displaystyle \int_a^b} (\alpha f)(x) \, dx = \sup \{L(\alpha f, P) : P \in \mathcal P[a,b] \} = \sup \{\alpha U(f, P) : P \in \mathcal P[a,b] \} \\
= \alpha \inf \{U(f, P) : P \in \mathcal P[a,b] \} = \alpha \overline{\int_a^b} f(x) \, dx = (\textrm{por ser integrable}) \alpha \underline{\int_a^b} f(x) \, dx \\
= \alpha \sup \{L(f, P) : P \in \mathcal P[a,b] \} = \inf \{\alpha L(f, P) : P \in \mathcal P[a,b] \} \\ 
= \inf \{U(\alpha f, P) : P \in \mathcal P[a,b] \} = \overline{\int_a^b} (\alpha f)(x) \,dx
\end{array}
$$
Luego $\alpha f \in R[a,b] \land \int_a^b (\alpha)(x) \, dx = \alpha \int_a^b f(x) \, dx$.
```

**Tema:** [[Integración de funciones de una variable real#1. Integral de Riemann]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que garantiza la linealidad de la aplicación integral y que conjunto de las funciones integrables Riemann sea espacio vectorial?
Reverso: $R[a,b]$ (conjunto de [[Integral de Riemann]]) es [[espacio vectorial]] y la aplicación $R[a,b] \to \mathbb R$ con $f \to \int_a^b f(x) \, dx$ es lineal. Es decir,
1. $f,g \in R[a,b] \implies f+g \in R[a,b] \land \int_a^b (f+g)(x) \, dx = \int_a^b f(x) \, dx + \int_a^b g(x) \, dx$.
2. Dados $f \in R[a,b]$ y $\alpha \in \mathbb R$, entonces $\alpha f \in R[a,b] \land \int_a^b (\alpha f)(x) \, dx = \alpha \int_a^b f(x) \, dx$.
Tags: proposición/teorema análisisI
<!--ID: 1714669443768-->
END

START
Básico
Anverso: Demostración de que $R[a,b]$ (conjunto de [[Integral de Riemann]]) es [[espacio vectorial]] y la aplicación $R[a,b] \to \mathbb R$ con $f \to \int_a^b f(x) \, dx$ es lineal. Es decir,
1. $f,g \in R[a,b] \implies f+g \in R[a,b] \land \int_a^b (f+g)(x) \, dx = \int_a^b f(x) \, dx + \int_a^b g(x) \, dx$.
2. Dados $f \in R[a,b]$ y $\alpha \in \mathbb R$, entonces $\alpha f \in R[a,b] \land \int_a^b (\alpha f)(x) \, dx = \alpha \int_a^b f(x) \, dx$.
Reverso: $(i)$.
Sea $P = \{x_0, \dots, x_n \}$ partición, entonces tenemos que dado $x \in [x_{j-1}, x_j]$:
$$m_j(f) \le f(x) \le M_j(f), \quad m_j(g) \le g(x) \le M_j(g),$$
de donde se deduce:
$$
\begin{eqnarray}
&\implies& m_j(f) + m_j(g) \le f(x) + g(x) \le M_j(f) + M_j(g) \implies \\
&\implies& m_j(f) + m_j(g) \le m_j(f+g) \le M_j(f+g) \le M_j(f) + M_j(g) \implies \\
&\implies& \tag{*} L(f, P) + L(g, P) \le L(f+g, P) \le U(f+g, P) \le U(f,P) + U(g, P)
\end{eqnarray}
$$
Fijamos $\varepsilon > 0$. Por el [[criterio de integrabilidad]],
1. $f \in R[a,b] \implies \exists Q_1 \in \mathcal P[a,b] : U(f, Q_1) - L(f, Q_1) < \frac{\varepsilon}{2}$.
2. $g \in R[a,b] \implies \exists Q_2 \in \mathcal P[a,b] : U(g, Q_2) - L(g, Q_2) < \frac{\varepsilon}{2}$.

Tomamos $P_\varepsilon = Q_1 \cup Q_2$ partición de $[a,b]$, entonces tenemos que
$$U(f, P_\varepsilon) - L(f, P_\varepsilon) < \frac{\varepsilon}{2}, \quad U(g, P_\varepsilon) - L(g P_\varepsilon) < \frac{\varepsilon}{2}$$

Por esto último y $(*)$, obtenemos la siguiente cadena de resultados:
$$\begin{eqnarray}
(*) &\implies& L(f, P_\varepsilon) + L(g, P_\varepsilon) \le L(f+g, P_\varepsilon) \le U(f+g, P_\varepsilon) \le U(f, P_\varepsilon) + U(g, P_\varepsilon) \\
&\implies& U(f+g, P_\varepsilon) - L(f+g, P_\varepsilon) \le (U(f,P_\varepsilon) - L(f, P_\varepsilon)) + (U(g,P_\varepsilon) - L(g,P_\varepsilon)) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon.
\end{eqnarray}$$
Luego, $f+g \in R[a,b]$. Vamos ahora a ver que $\int_a^b (f+g)(x) \, dx =$ $\int_a^b f(x) \, dx + \int_a^b g(x) \, dx$.
Sabemos que
$$L(f, P_\varepsilon) \le \int_a^b f(x) \, dx \le U(f, P_\varepsilon), \quad L(g, P_\varepsilon) \le \int_a^b g(x) \, dx \le U(g, P_\varepsilon).$$
Luego tenemos que
$$\begin{array}{l}
L(f, P_\varepsilon) + L(g, P_\varepsilon) \le \int_a^b f(x) \, dx + \int_a^b g(x) \, dx \le U(f, P_\varepsilon) + U(g, P_\varepsilon) \\
L(f, P_\varepsilon) + L(g, P_\varepsilon) \le \int_a^b (f+g)(x) \, dx \le U(f, P_\varepsilon) + U(g, P_\varepsilon).
\end{array}$$
De ambos resultados concluimos que
$$\left | \int_a^b f(x) \, dx + \int_a^b g(x) \, dx - \int_a^b (f+g)(x) \, dx \right | \le (U(f, P_\varepsilon) - L(f, P_\varepsilon)) + (U(g, P_\varepsilon) - L(g, P_\varepsilon)) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon.$$
Por tanto, $\forall \varepsilon > 0, \int_a^b f(x) \, dx + \int_a^b g(x) \, dx - \int_a^b (f+g)(x) \, dx = 0$.

$(ii).$
Sea $f \in R[a,b], \alpha < 0, P = \{x_0, \dots, x_n \}$ partición de $[a,b]$. Tenemos que
$$m_j(\alpha f) = \inf \{\alpha f(x) : x \in [x_{j-1}, x_j] \} = \alpha \sup \{f(x): x \in [x_{j-1}, x_j] \} = \alpha M_j(f).$$
Análogamente, $M_j(\alpha f) = \alpha m_j(f)$.
Entonces, 
$$L(\alpha f, P) = \sum_{j=1}^n m_j(\alpha f)(x_j - x_{j-1}) = \alpha \sum_{j=1}^n M_j(f)(x_j - x_{j-1}) = \alpha U(f, P).$$
También, 
$$U(\alpha f, P) = \sum_{j = 1}^n M_j(\alpha f)(x_j - x_{j-1}) = \alpha \sum_{j=1}^n m_j(f) (x_j - x_{j-1}) = \alpha L(f, P).$$
Por tanto, tenemos la siguiente igualdad:
$$
\begin{array}{l}
\underline{\displaystyle \int_a^b} (\alpha f)(x) \, dx = \sup \{L(\alpha f, P) : P \in \mathcal P[a,b] \} = \sup \{\alpha U(f, P) : P \in \mathcal P[a,b] \} \\
= \alpha \inf \{U(f, P) : P \in \mathcal P[a,b] \} = \alpha \overline{\int_a^b} f(x) \, dx = (\textrm{por ser integrable}) \alpha \underline{\int_a^b} f(x) \, dx \\
= \alpha \sup \{L(f, P) : P \in \mathcal P[a,b] \} = \inf \{\alpha L(f, P) : P \in \mathcal P[a,b] \} \\ 
= \inf \{U(\alpha f, P) : P \in \mathcal P[a,b] \} = \overline{\int_a^b} (\alpha f)(x) \,dx
\end{array}
$$
Luego $\alpha f \in R[a,b] \land \int_a^b (\alpha)(x) \, dx = \alpha \int_a^b f(x) \, dx$.
Tags: demostración análisisI
<!--ID: 1714669443773-->
END