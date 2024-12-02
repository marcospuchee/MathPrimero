## Tema 1: Descomposición $LU$.
**Referencia:** [[Descomposición LU]]

### 1. Métodos directos y sistemas triangulares.
- [[Sustitución regresiva]]
- [[Sustitución progresiva]]
- [[Algoritmo matricial óptimo]]
- [[(por demostrar) Sustitución progresiva y regresiva son óptimos]]
### 2. La eliminación gaussiana como descomposición matricial.
- [$A = LU$](Descomposición matricial LU)
- [$L_{m,k} := I + \alpha_{m,k} e_m e_k^T$](Obtención de matriz elemental de tipo III)
- [$\prod_{m = k+1}^n L_ {m,k} = I + v^{(k)} e_k^T =: M_k$](Proposición producto de matrices elementales de tipo III)
- [$M_1^{-1}M_2^{-1} \dots M_{n-1}^{-1} = I - \sum_{j = 1}^{n-1} v^{(j)} e_j^T$](Producto de inversas de matrices elementales de tipo III)
- [$U:=M_{n-1} \dots M_2 M_1 A$](Producto de inversas de matrices elementales de tipo III)
- [$L := \prod_{j = 1}^{n-1} M_j^{-1}$](Producto de inversas de matrices elementales de tipo III)
### 3. Matrices especiales y propiedades de la descomposición LU.
- [[Propiedades de las matrices triangulares]]
- [[Propiedades de la descomposición LU]]
- [Matriz DDC](Matrices diagonalmente dominantes), [Matriz DDF](Matrices diagonalmente dominantes), [Matriz EDDC](Matrices diagonalmente dominantes), [Matriz EDDF](Matrices diagonalmente dominantes)
- [$A \in \mathbb R^{n \times n}$ EDD $\implies$ $A(i,i) \neq 0$, $\forall i$](Matriz EDDC o EDDF implica todo elemento en la diagonal es no nulo)
- [$A \in GL_n(\mathbb R)$ $\implies$ $A = LU$ es única](Matriz regular que admite descomposición LU impica que la descomposición es única)
- [$A \in \mathbb R^{n \times n}$ EDDC $\implies$ $\exists A = LU$](EDDC tiene factorización LU)
- [[Matriz simétrica implica que sus matrices de trabajo también lo son]]
- [$A \in \mathbb R^{n \times n}$ definida positiva $\implies$ $A(i,i) > 0$, $\forall i$](Matriz definida positiva tiene diagonal estrictamente positiva)
- [$A \in \mathbb R^{n \times n}$ simétrica definida positiva $\implies \exists A = LU$](Matriz simétrica y definida positiva tiene factorización LU)
- [$A = LDL^T$](Descomposición LDL^T)
- [[Descomposición de Choleski]], [$A = GG^T$](Descomposición de Choleski)
### 4. Eliminación gaussiana con pivoteo parcial.
- [$P_{i,j}$](Matriz de pivotaje)
- [$M_{n-1} P_{n-1} \dots M_1 P_1 = M_{n-1}^{(n-1)} M_{n-2}^{(n-1)} \dots M_1^{(n-1)} P_{n-1} \dots P_1$](Conmutación de M y P)
- [$PA = LU$](Descomposición PA = LU)
- [$A \in GL_n(\mathbb R) \implies \exists j : A(1, j) \neq 0$](Matriz invertible tiene elemento distinto de cero en la primera columna)
- [$A \in GL_n(\mathbb R) \implies$ se puede hacer el primer paso de eliminación gaussiana con pivoteo parcial](Matriz invertible siempre se puede hacer el primer paso de EG con pivoteo parcial)
---
## Tema 2: Sistemas lineales y su solución numérica
**Referencia:** [[Sistemas lineales y su solución numérica]]
### 1. Normas de vectores y de matrices.
- [[Norma matricial]], [$|| \cdot ||$](Norma matricial)
- [$||\cdot||_ \alpha$](Norma matricial)
- [[Norma matricial subordinada a una norma vectorial]], [$|| A ||_ \alpha$](Norma matricial subordinada a una norma vectorial)
- [$||A||_ \alpha = \sup \limits_ {x \neq 0} \frac{||Ax||_ \alpha}{||x||_ \alpha} = \max \limits_ {x \neq 0} \frac{||Ax||_ \alpha}{||x||_ \alpha} = \max \limits_ {||x||_ \alpha = 1} ||Ax||_ \alpha$](Norma matricial subordinada a una norma vectorial)
- [$D = \textrm{diag}(d_1, \dots, d_n) \in \mathbb R^{n \times n} \implies ||D||_ 2 = \max \limits_ {1 \le i \le n} |d_i|$](Norma matricial subordinada a una norma vectorial)
- [$Q \in \mathbb R^{n \times n}$ ortogonal $\implies$ $||Q||_ 2 = 1$](Norma matricial subordinada a una norma vectorial)
- [$||Ax||_ \alpha \le ||A||_ \alpha ||x||_ \alpha$, $\forall x \in \mathbb R^n$](Propiedades de la norma matricial subordinada)
- [$||AB|| \le ||A|| \, ||B||$](Propiedades de la norma matricial subordinada)
- [$||A||_ 1 = \max \limits_ {1 \le j \le n} ||A(:,j)||_ 1 = \max \limits_ {1 \le j \le n} \sum_ {i = 1}^n |a_ {ij}|$](Cálculo norma matricial subordinada 1)
- [$||A||_ \infty = \max \limits_ {1 \le i \le m} ||A(i,:)||_ 1 = \max \limits_ {1 \le i \le m} \sum_ {j = 1}^n |a_ {ij}|$](Cálculo norma matricial subordinada infinito)
- [Valor propio](Valor propio de una matriz), [Vector propio](Valor propio de una matriz)
- [$\lambda \in K$ valor propio de $A$ $\iff \det(A - \lambda I_n) = 0$](Teorema obtención valores propios)
- [[Radio espectral]], [$\rho(A)$](Radio espectral)
- [$A \in \mathbb R^{n \times n}$ simétrica $\implies$ sus valores propios son reales](Matriz real simétrica implica que sus valores propios son reales)
- [$A \in \mathbb R^{n \times n}$ SDP $\implies$ $\lambda > 0$, $\forall \lambda$ valor propio de $A$](Matriz real simétrica definida positiva implica que sus valores propios son estrictamente positivos)
- [[Matriz diagonalizable]]
- [$A \in \mathbb R^{n \times n}$ simétrica $\implies$ $\exists Q$ ortogonal $: QAQ^T = D$ diagonal](Matriz real simétrica es diagonalizable por matrices ortogonales)
- [$||A||_ 2 = \sqrt{\rho(A^TA)}$](Cálculo norma 2)
### 2. Solución numérica perturbada de los sistemas lineales.
- [$\hat A \hat x = \hat b$](Sistema perturbado)
- [Error relativo](Errores absoluto y relativo de una aproximación), [$\frac{||x- \hat x||}{||x||}$](Errores absoluto y relativo de una aproximación) 
- [$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}$](Teorema de las cotas del error relativo en la perturbación de los términos independientes)
- [$\kappa(A)$](Número de condición de una matriz respecto de una norma)
- [$\frac{1}{\kappa(A)} \le \frac{e_r}{r_r} \le \kappa(A)$](Número de condición de una matriz respecto de una norma)
- [$||(I - B)^{-1}|| \le \frac{1}{1 - ||B||}$](Cota norma inversa matriz perturbada en función de la inversa de la matriz normal)
- [$||(A+E)^{-1}|| \le \frac{||A^{-1}||}{1-p}$](Cota norma inversa matriz perturbada en función de la inversa de la matriz normal)
- [$\frac{||x- \hat x||}{||x||} \le \frac{\kappa(A)}{1-p} \left ( \frac{||\hat A - A||}{||A||} + \frac{||b- \hat b||}{||b||} \right )$](Teorema cota error relativo en un sistema completamente perturbado)
---
## Tema 3. Métodos para valores y vectores propios.
**Referencia:** [[Métodos para valores y vectores propios]]
### 1. Definición.
- [[Valor propio de una matriz]]
- [$\lambda \in K$ valor propio de $A$ $\iff$ $\det(A-\lambda I) = 0$](Teorema obtención valores propios)
- [$A \in \mathbb R^{n \times n}$ simétrica $\implies$ valores propios reales](Matriz real simétrica implica que sus valores propios son reales) 
- [$A \in \mathbb R^{n \times n}$ SDP $\implies$ valores propios estrictamente positivos](Matriz real simétrica definida positiva implica que sus valores propios son estrictamente positivos)
### 2. Discos de Gershgorin.
- [[Discos de Gershgorin]]
- [[Valores propios están contenidos en la unión de sus discos de Gershgorin]]
- [[Teorema distribución valores propios en componentes conexas de discos de Gershgorin]]
### 3. Método de la potencia.
- [[Cociente de Rayleigh]]
- [[Fundamentos teóricos del método de la potencia]]
- [[Método de la potencia]]
- [[Problemas computacionales con el método de la potencia]]
- [[Método de la potencia inversa]]
