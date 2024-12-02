### Contenido principal

Sea $A \in \mathbb R^{n \times n}$ diagonalizable con $|\lambda_1| \ge |\lambda_2| \ge \dots |\lambda_{n-1}| > |\lambda_n|$, y $\lambda_i \neq 0$, $\forall i$. Como $A$ es invertible, y los valores propios de $A^{-1}$ son $\lambda_i^{-1}$, tenemos que:
$$|\lambda_n^{-1}| > |\lambda_{n-1}^{-1}| \ge \dots \ge |\lambda_2^{-1}| \ge |\lambda_1^{-1}|.
$$
Por tanto, podemos calcular $\lambda_n$ aplicando el método de la Potencia a $A^{-1}$:

```ad-Algorithm
1. Tomamos $x^{(0)} := x \in \mathbb R^n, \, ||x||_2 = 1$ arbitrario.
2. Construimos $p^{(k+1)} := A^{-1}x^{(k)} \quad \equiv \quad Ap^{(k+1)} = x^{(k)}, \, k = 0,1,2, \dots$
3. Definimos
$$q_k := (x^{(k)})^T p^{(k+1)}, \quad x^{(k+1)} := \frac{p^{(k+1)}}{||p^{(k+1)||_2}}.$$

Se deduce que $\frac{1}{q_k} \approx |\lambda_n|$.

*Hay que valorar si conviene o no calcular $A^{-1}$.*
```


**Tema:** [[Métodos para valores y vectores propios#3. Método de la potencia.]]

---
### Anki
