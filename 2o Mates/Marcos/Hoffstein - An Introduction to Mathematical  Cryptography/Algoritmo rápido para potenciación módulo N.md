### Contenido principal

Supongamos que queremos elevar $g^A \pmod N$.

```ad-Algorithm
1. Calcular la expansión binaria de $A$ como
$$A = A_0 + A_1 \cdot 2 + A_2 \cdot 2^2 + \dots + A_r \cdot 2^r, \quad A_0, \dots, A_r \in \{0,1\},$$
podemos asumir que $A_r = 1$.

2. Computamos las potencias $g^{2^i} \pmod N$ para $0 \le i \le r$:
$$\begin{matrix*}[l c]
a_0 \equiv g & \pmod N \\
a_1 \equiv a_0^2 \equiv g^2 & \pmod N \\
a_2 \equiv a_1^2 \equiv g^{2^2} & \pmod N \\
a_3 \equiv a_2^2 \equiv g^{2^3} & \pmod N \\
\quad \vdots \quad \vdots & \vdots \\
a_r \equiv a_{r-1}^2 \equiv g^{2^r} & \pmod N
\end{matrix*}.$$
Cada término es el cuadrado del anterior, luego esto requiere $r$ multiplicaciones.
3. Computamos $g^A \pmod N$ utilizando la fórmula
$$\begin{eqnarray} g^A &=& g^{A_0 + A_1 \cdot 2 + A_2 \cdot 2^2 + A_3 \cdot 2^3 + \dots + A_r \cdot 2^r} \\
&=& g^{A_0} \cdot (g^2)^{A_1} \cdot (g^{2^2})^{A_2} \cdot (g^{2^3})^{A_3} \dots (g^{2^r})^{A_r} \\
&\equiv& a_0^{A_0} \cdot a_1^{A_1} \cdot a_2^{A_2} \dots a_r^{A_r} \pmod N,
\end{eqnarray}$$
donde los valores $a_0, a_1, \dots, a_r$ están calculados en el paso 2. Luego el producto de estos es solamente el producto de aquellos tales que $A_i = 1$. Es decir, como mucho, $r$ operaciones.
```

**Running time:** toma como mucho $2r$ multiplicaciones módulo $N$ para computar $g^A$. Como $A \ge 2^r$ toma, como mucho, $2log_2(A)$ multiplicaciones módulo $N$ para computar $g^A$.

**Tema:** [[An Introduction to Cryptography#2. Aritmética modular.]]

---
### Anki
