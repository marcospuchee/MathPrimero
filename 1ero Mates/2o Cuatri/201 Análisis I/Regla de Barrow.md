
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 19:37

```ad-theorem
Suponemos que $f \in R[a,b]$ ([[integral de Riemann]]) y admite [[función primitiva]] $F: [a,b] \to \mathbb R$. Entonces:
$$\int_a^b f(x) \, dx = F(b) - F(a).$$
```


```ad-proof
Fijamos $\varepsilon > 0$ y tomamos $P = \{a = x_0, x_1, \dots, x_n = b \}$ ([[partición de un intervalo]]) tal que $U(f, P) - L(f, P) < \varepsilon$.
Sabemos que $L(f, P) \le \int_a^b f(x) \, dx \le U(f, P)$. Sea $x_{j-1} \le c_j \le x_j, \forall j = 1, \dots, n$. Luego podemos encadenar las siguientes implicaciones
$$\begin{array}{l}
\implies m_j \le f(c_j) \le M_j \implies m_j(x_j - x_{j-1}) \le f(c_j)(x_j - x_{j-1}) \le M_j (x_j - x_{j-1}) \\
\implies\sum_{j = 1} m_j (x_j - x_{j-1}) \le \sum_{j = 1}^n f(c_j)(x_j - x_{j-1}) \le \sum_{j = 1}^n (x_j - x_{j-1}) M_j \\
\implies L(f, P) \le \sum_{j = 1}^n (x_j - x_{j-1})f(c_j) \le U(f, P).
\end{array}$$
Luego $F: [x_{j-1}, x_j] \to \mathbb R$ es continua en $[x_{j-1}, x_j]$ y derivable en $]x_{j-1}, x_j[$. Por lo que, aplicando el [[teorema del valor medio de Cauchy (1821)]], tenemos:
$\exists \xi_j \in ]x_{j-1}, x_j[$ tal que $F(x_j) - F(x_{j-1}) = (x_j - x_{j-1}) F'(\xi_j) =$ $(x_j - x_{j-1}) f(\xi_j)$.
Si tomamos $c_j = \xi_j$, se queda:
$$L(f, P) \le \sum_{j = 1}^n (F(x_j) - F(x_{j-1})) \le U(f, P),$$
pero la serie es telescópica, luego su resultado es: $F(x_n) - F(x_0) = F(b) - F(a)$. Por tanto, nos queda que:
$$\left | \int_a^b f(x) \, dx - (F(b) - F(a)) \right | \le U(f, P) - L(f, P) < \varepsilon, \quad \forall \varepsilon > 0$$
Luego
$$\int_a^b f(x) \, dx = F(b) - F(a).$$
```


**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:**
**Consecuencias:** [[Proposición integración por partes]]

---
### Anki

START
Básico
Anverso: Cuál es la regla de Barrow?
Reverso: Suponemos que $f \in R[a,b]$ ([[Integral de Riemann]]) y admite [[Función primitiva]] $F: [a,b] \to \mathbb R$. Entonces:
$$\int_a^b f(x) \, dx = F(b) - F(a).$$
Tags: proposición/teorema análisisI
<!--ID: 1714669443732-->
END

START
Básico
Anverso: Demostración de la regla de Barrow
Reverso: Fijamos $\varepsilon > 0$ y tomamos $P = \{a = x_0, x_1, \dots, x_n = b \}$ ([[Partición de un intervalo]]) tal que $U(f, P) - L(f, P) < \varepsilon$.
Sabemos que $L(f, P) \le \int_a^b f(x) \, dx \le U(f, P)$. Sea $x_{j-1} \le c_j \le x_j, \forall j = 1, \dots, n$. Luego podemos encadenar las siguientes implicaciones
$$\begin{array}{l}
\implies m_j \le f(c_j) \le M_j \implies m_j(x_j - x_{j-1}) \le f(c_j)(x_j - x_{j-1}) \le M_j (x_j - x_{j-1}) \\
\implies\sum_{j = 1} m_j (x_j - x_{j-1}) \le \sum_{j = 1}^n f(c_j)(x_j - x_{j-1}) \le \sum_{j = 1}^n (x_j - x_{j-1}) M_j \\
\implies L(f, P) \le \sum_{j = 1}^n (x_j - x_{j-1})f(c_j) \le U(f, P).
\end{array}$$
Luego $F: [x_{j-1}, x_j] \to \mathbb R$ es continua en $[x_{j-1}, x_j]$ y derivable en $]x_{j-1}, x_j[$. Por lo que, aplicando el [[Teorema del valor medio de Cauchy (1821)]], tenemos:
$\exists \xi_j \in ]x_{j-1}, x_j[$ tal que $F(x_j) - F(x_{j-1}) = (x_j - x_{j-1}) F'(\xi_j) =$ $(x_j - x_{j-1}) f(\xi_j)$.
Si tomamos $c_j = \xi_j$, se queda:
$$L(f, P) \le \sum_{j = 1}^n (F(x_j) - F(x_{j-1})) \le U(f, P),$$
pero la serie es telescópica, luego su resultado es: $F(x_n) - F(x_0) = F(b) - F(a)$. Por tanto, nos queda que:
$$\left | \int_a^b f(x) \, dx - (F(b) - F(a)) \right | \le U(f, P) - L(f, P) < \varepsilon, \quad \forall \varepsilon > 0$$
Luego
$$\int_a^b f(x) \, dx = F(b) - F(a).$$
Tags: demostración análisisI
<!--ID: 1714669443736-->
END