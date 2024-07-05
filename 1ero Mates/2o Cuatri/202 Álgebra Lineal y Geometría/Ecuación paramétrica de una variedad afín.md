### Contenido principal

**Fecha:** 2024-04-25, 16:58

```ad-formal
title: Formal definition
Sean $(A, V, +)$ [[espacio afín]], donde $V$ es un $\mathbb K$-espacio vectorial de dimensión $\dim V = n$, $L = W_P \subseteq A$ [[variedad afín]], $\mathcal R = \{O, B\}$ un [[sistema de referencia cartesiano]] en $A$. Supongamos que $\{w_1, \dots, w_k\}$ es una base de $W$ ($k = \dim L$). Escribimos $B = \{v_1, \dots, v_n \}$. Tenemos:
$$w_j = \alpha_{1j} v_1 + \alpha_{2j} v_2 + \dots + \alpha_{nj} v_n, \quad \forall j \in \{1, \dots, k\},$$
con $\alpha_{ij}, \dots, \alpha_{nj} \in \mathbb K$ únicos. Luego $[w_j]_B = (\alpha_{1j}, \dots, \alpha_{nj}) \in \mathbb K^n$. Sea $X \in A$, tenemos:
$$
\begin{eqnarray}
X \in L &\iff& [\vec{PX}]_B = [\lambda_1 w_1 + \dots + \lambda_k w_k]_B = \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B \\ &\iff& [\vec{PX}]_B = [X]_{\mathcal R} - [P]_{\mathcal R} = \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B \\
&\iff& (x_1, \dots, x_n)^t = (p_1, \dots, p_n)^t + \lambda_1 (\alpha_{11}, \dots, \alpha_{n1})^t + \dots + \lambda_k (\alpha_{1k}, \dots, \alpha_{nk})^t,
\end{eqnarray}
$$
para ciertos $\lambda_1, \dots, \lambda_k \in \mathbb K$.

Luego esta es la ecuación paramétrica de $L$:
$$X \in L \iff [X]_{\mathcal R} = [P]_{\mathcal R } + \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B.$$

```

**Tema:** [[Espacios afines]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Definición y desarrollo de la ecuación paramétrica de una variedad afín
Reverso: Sean $(A, V, +)$ [[Espacio afín]], donde $V$ es un $\mathbb K$-espacio vectorial de dimensión $\dim V = n$, $L = W_P \subseteq A$ [[Variedad afín]], $\mathcal R = \{O, B\}$ un [[Sistema de referencia cartesiano]] en $A$. Supongamos que $\{w_1, \dots, w_k\}$ es una base de $W$ ($k = \dim L$). Escribimos $B = \{v_1, \dots, v_n \}$. Tenemos:
$$w_j = \alpha_{1j} v_1 + \alpha_{2j} v_2 + \dots + \alpha_{nj} v_n, \quad \forall j \in \{1, \dots, k\},$$
con $\alpha_{ij}, \dots, \alpha_{nj} \in \mathbb K$ únicos. Luego $[w_j]_B = (\alpha_{1j}, \dots, \alpha_{nj}) \in \mathbb K^n$. Sea $X \in A$, tenemos:
$$
\begin{eqnarray}
X \in L &\iff& [\vec{PX}]_B = [\lambda_1 w_1 + \dots + \lambda_k w_k]_B = \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B \\ &\iff& [\vec{PX}]_B = [X]_{\mathcal R} - [P]_{\mathcal R} = \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B \\
&\iff& (x_1, \dots, x_n)^t = (p_1, \dots, p_n)^t + \lambda_1 (\alpha_{11}, \dots, \alpha_{n1})^t + \dots + \lambda_k (\alpha_{1k}, \dots, \alpha_{nk})^t,
\end{eqnarray}
$$
para ciertos $\lambda_1, \dots, \lambda_k \in \mathbb K$.

Luego esta es la ecuación paramétrica de $L$:
$$X \in L \iff [X]_{\mathcal R} = [P]_{\mathcal R } + \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B.$$
Tags: definición ÁlgebraI
<!--ID: 1714060760624-->
END