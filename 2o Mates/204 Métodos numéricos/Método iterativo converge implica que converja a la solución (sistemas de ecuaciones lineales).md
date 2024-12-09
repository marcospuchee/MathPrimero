### Contenido Principal

```ad-proposition
Dado un sistema de ecuaciones lineal: $$Ax = b, \quad A \in \mathbb R^{n \times n}, \, b \in \mathbb R^n,$$ definimos el método iterativo $Mx^k = b-Nx^{k-1}$, donde $A = M+N$ con $M$ fácilmente invertible.

Entonces, $\{x^k \}^\infty_{k = 0}$ converge $\implies$ $\lim \limits_{k \to +\infty} x^k = x^*$, donde $x^*$ es la solución al sistema de ecuaciones.
```

```ad-proof
Sea $y := \lim \limits_{k \to +\infty} x^k$, $y \in \mathbb R^n$. Se tiene que $Mx^k = b-Nx^{k-1}$, $\forall k > 0$. Por tanto, tomando límites, $$\lim_{k \to +\infty} Mx^k = \lim_{k \to +\infty}[b - Nx^{k-1}],$$ y por la continuidad de las aplicaciones lineales:
$$\begin{eqnarray} M \left [\lim \limits_{k \to + \infty} x^k \right ] &=& b - \lim \limits_{k \to +\infty} Nx^{k-1} \\ M \left [\lim \limits_{k \to +\infty} x^k \right ] &=& b - N \left [ \lim \limits_{k \to +\infty} x^{k-1} \right ] \\ My &=& b-Ny \\ (M+N)y &=& b \\ Ay &=& b.  \end{eqnarray}$$ Por tanto, $y$ es solución de $Ax = b$, pero $Ax = b$ tiene solución única, luego $y = x^*$.
```

**Tema:** [[Métodos iterativos para resolver sistemas de ecuaciones lineales#1. Definición]]

**Definiciones referenciadas:** [Método iterativo (sistemas de ecuaciones lineales)](Método iterativo)
**Resultados referenciados:** [[Aplicación lineal es uniformemente continua (lipschitziana)]]

---
### Anki
