### Contenido Principal

```ad-proposition
Sea $A \in \mathbb R^{n \times n}$ EDDF entonces Gauss-Seidel aplicado a cualquier sistema con $A$ como matriz de coeficientes es convergente.
```

```ad-proof
Probamos que $\rho(Q_{GS}) < 1$. Sea $\lambda \in \mathbb C$ valor propio de $Q_{GS}$, veamos que $|\lambda|<1$. Como $Q_{GS} = -M^{-1}N$, entonces $\exists x \in \mathbb C^n \textrm{\\} \{0\}$ tal que $$Q_{GS}x = \lambda x \iff -M^{-1}N x = \lambda x \iff -Nx = \lambda Mx \iff (\lambda M+N)x = 0,$$ lo que implica uqe $\lambdaM+N$ no es invertible.
```

**Tema:**

**Definiciones referenciadas:** [Método de Gauss-Seidel](Método iterativo), [Matriz EDDF](Matrices diagonalmente dominantes), [$Q := -M^{-1}N$](Matriz de iteración), [[Método iterativo convergente]], [$\rho(A)$](Radio espectral)
**Resultados referenciados:**

---
### Anki
