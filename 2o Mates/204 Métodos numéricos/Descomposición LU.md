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