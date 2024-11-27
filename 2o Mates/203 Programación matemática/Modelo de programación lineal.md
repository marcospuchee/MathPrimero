### 1. Introducción al modelo de programación lineal.
- [[Problema de PL en formato estándar]]
- [$v(P)$](Valor de un problema)
- [$x^* {}$](Solución óptima)
- [$v(P) = c^Tx^ * {}$](Valor de un problema es la imagen de la función objetivo de una solución óptima)

### 2. Preliminares de análisis convexo.
##### 1. Conjuntos convexos.
- [[Combinación lineal convexa]]
- [[Conjunto convexo]]
- [[Intersección arbitraria de convexos es convexa]]
- [Conjunto convexo $\iff$ contiene combinaciones lineales convexas de cualquier subconjunto finito](Conjunto convexo sii contiene combinaciones lineales convexas de cualquier subconjunto finito)
- [$\textrm{conv} C$](Envoltura convexa)
- [$C \subset H : H$ convexo $\implies$ $\textrm{conv}C \subset H$](Envoltura convexa de un conjunto es el conjunto convexo mínimo que lo contiene)
- [$\textrm{conv}C = \left \{ \sum_{i = 1}^k \lambda_i x_i \, | \, k \in \mathbb N, x_1, \dots, x_k \in C, \lambda_1, \dots, \lambda_k \ge 0, \sum_{i =1 }^k \lambda_i = 1 \right \}$](Envoltura convexa es el conjunto de las combinaciones lineales convexas formadas por puntos de C)
- [[Polítopo]]
##### 2. Puntos y direcciones extremas.
- [[Punto extremo]]
- [[Dirección]]
- [[Dirección extrema]]
##### 3. Poliedros.
- [[Hiperplano]]
- [[Semiespacio cerrado]]
- [[Semiespacios cerrados son cerrados y convexos]]
- [[Hiperplano es cerrado y convexo]]
- [[Poliedro]]
- [[Poliedro es cerrado y convexo]]
- [[Teorema de representación de poliedros]]

### 3. Identificación analítica de soluciones.
- [$(P)$ tiene una solución óptima $\iff c^T \overline d \ge 0 , \quad \forall \overline d \textrm{ dirección extrema de } \mathcal F$](Teorema fundamental de la programación lineal)
- [[Dirección de descenso ilimitado]]
- [$\overline x \in \mathbb R^n$ punto extremo $\iff$ $ \overline x =(\overline x_B, \overline x_N)$ con $\overline x_B = B^{-1}b \ge 0$ y $\overline x_N = 0$](Teorema de caracterización de puntos extremos)