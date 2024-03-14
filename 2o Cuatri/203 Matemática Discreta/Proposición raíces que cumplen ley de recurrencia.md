
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-02, 22:33

```ad-proposition
Si $x$ es una raíz de [[Multiplicidad algebraica]] $l > 1$, entonces las sucesiones $x^n, nx^n, x^nx^n, \dots, n^{l-1}x^n$ cumplen la [[Ley de recurrencia]].
```


```ad-proof
Para cada $n > k$, formamos el polinomio:
$$p_n(x) = x_n p(x)$$
donde $p(x)$ es el [[Polinomio característico asociado al espacio vectorial de las sucesiones definidas por una misma ley de recurrencia]]. Luego,
$$p_n(x) = x^n (x^k - (\lambda_0 + \lambda_1 x + \dots + \lambda_{k-1} x^{k-1})).$$

Sea $x_0$ raíz del polinomio característico, luego también es raíz de $p_n(x)$, por ser producto. Denotamos $l$ la multiplicidad algebraica de $x_0$. Nos damos cuenta de que, sea $q(x) = (x-x_0)^2 p(x)$. Luego,
$$q'(x) = 2(x-x_0) p(x) + (x-x_0)^2 p'(x), \quad q'(x_0) = 0.$$
Así, deducimos que $x_0$ es raíz de multiplicidad $l-i$ de $p_n^{(i)}(x)$.

Construimos los polinomios siguientes:
$$
\begin{eqnarray}
q^1_n(x) &=&  x p_n'(x) = (x^{n+k}-\lambda_0 x^n - \dots - \lambda_{k-1} x^{n+k-1})'x = (n+k)x^{n+k} - \lambda_0 n x^n - \dots - \lambda_{k-1}(n+k-1)x^{n+k-1}, \\
q^2_n (x) &=& x {q^1_n}' (x) = (n+k)^2x^{n+k}- \lambda_0 n^2x^n - \dots - \lambda_{k-1}(n+k-1)^2 x^{n+k-1} \\
\dots \\
q^i_n(x) &=& x {q_n^{i-1}}' (x) = (n+k)^i x^{n+k} - \lambda_0 n^i x^n - \dots - \lambda_{k-1}(n+k-1)^i x^{n+k-1}
\end{eqnarray}
$$
con $1 \le i \le l-1$. Luego $x_0$ será raíz de $q^i_n(x)$ con multiplicidad $l-1 \implies q^i_n(x_0) = 0$. Lo que implica que
$$
\begin{array}
((n+k)^i x_0^{n+k} - \lambda_0 n^i x^n_0 - \dots - \lambda_{k-1} (n+k-1) x_0^{n+k-1} = 0 \implies \\
(n+k)^i x_0^{n+k} = \lambda_0 n^i x_0^n + \dots + \lambda_{k-1} (n+k-1) x_0^{n+k-1}
\end{array}
$$
Así, por analogía con la ley de recurrencia ($a_{n+k} = \lambda_0 a_n + \dots + \lambda_{k-1}) a_{n+k-1}$), tenemos que $a_n = n^i x_0^n$ es la solución de la ley de recurrencia.
```

**Tema:** [[Ecuaciones de recurrencia#2. Solución de las leyes de recurrencia lineales y homogéneas]]
**Corolarios:** [[Teorema solución ley de recurrencia]]

---
### Anki
