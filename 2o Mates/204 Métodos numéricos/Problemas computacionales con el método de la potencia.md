### Contenido principal

Recordemos que en el método de la potencia, calculamos $y^{(k)} \approx \lambda_1^k \alpha_1 v_1$. Sin embargo, aunque $y^{(k)}$ es *esencialmente* un vector propio de $A$, su cálculo tiene problemas de:
- Overflow (cálculo con números grandes) si $|\lambda_1| > 1$.
- Underflow (cálculo con números pequeños) si $|\lambda_1| < 1$.

La solución es normalizar el vector.

```ad-Algorithm
1. Tomamos $x^{(0)} := x \in \mathbb R^n \textrm{\\} \{0\}$ con $||x||_2 = 1$ arbitrario.
2. Construimos $p^{(k+1)} := Ax^{(k)}, \, \, k = 0,1,2, \dots$.
3. Definimos
$$q_k := (x^{(k)})^T p^{(k+1)}, \quad x^{(k+1)} := \frac{p^{(k+1)}}{||p^{(k+1)}||_2}.$$
```

**Tema:** [[Métodos para valores y vectores propios#3. Método de la potencia.]]

**Resultados referenciados:** [[Método de la potencia]]

---
### Anki
