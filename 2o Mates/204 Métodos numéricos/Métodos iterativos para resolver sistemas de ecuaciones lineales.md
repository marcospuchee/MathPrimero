### 1. Definiciones.
- [$Mx^k = b-Nx^{k-1}$](Método iterativo)
- [Método de Jacobi](Método iterativo)
- [Método de Gauss-Seidel](Método iterativo)
- [[Método iterativo convergente]]
- [$Mx^k = b - Nx^{k-1}$ converge $\implies \lim \limits_ {k \to +\infty} x^k = x^* {}$](Método iterativo converge implica que converja a la solución (sistemas de ecuaciones lineales))
- [[Error]], [$e^k := x^k - x$](Error.md)
- [$e^{k+1} = -M^{-1}Ne^k$](Ecuación del error)
- [[Matriz de iteración]], [$Q := -M^{-1}N$](Matriz de iteración)
### 2. Estudio de la convergencia.
- [[Radio espectral]], [$\rho(A)$](Radio espectral)
- [$Mx^k = b-Nx^{k-1}$ converge a $x^* {}$ $\iff$ $\rho(Q) < 1$](Caracterización convergencia método iterativo sistemas de ecuaciones lineales (radio espectral matriz de iteración))
- [$||Q|| < 1$ para alguna norma matricial subordinada $\implies$ $Mx^k = b-Nx^{k-1}$ converge](Norma matriz de iteración menor que uno implica método convergente)
- [[Método de Jacobi converge en matriz EDDF]]
- [[Método de Gauss-Seidel converge con SDP]]
- [[Método de Gauss-Seidel converge en matriz EDDF]]
