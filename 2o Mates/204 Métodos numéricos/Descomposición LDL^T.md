### Contenido Principal

```ad-proposition
Si $A$ es simétrica e invertible, y $A = LU$, entonces $A = LDL^T$ con $D = \textrm{diag}(u_{11}, \dots, u_{nn})$.
```

```ad-proof
$A$ invertible $\implies$ $D$ invertible. $M = U^TD^{-1}$ es triangular inferior con $1$ en la diagonal y además $LDM^T = LU = A$. Como $A$ es simétrica, $A = A^T = MDL^T$. $L' = M$ es triangular inferior con $1$ en la diagonal, $U' = DL^T$ es triangular superior, y por unicidad de la descomposición $LU$ tenemos que $L = L' = M \iff U = DL^T$.
```

**Tema:** [[Descomposición LU#3. Matrices especiales y propiedades de la descomposición LU.]]

---
### Anki

START
Básico
Anverso: Condiciones suficientes para descomposición $A = LDL^t$.
Reverso: Si $A$ es simétrica e invertible, y $A = LU$, entonces $A = LDL^T$ con $D = \textrm{diag}(u_{11}, \dots, u_{nn})$.
Tags: met
<!--ID: 1735044171464-->
END

START
Básico
Anverso: Demostración de que si $A$ es simétrica e invertible, y $A = LU$, entonces $A = LDL^T$ con $D = \textrm{diag}(u_{11}, \dots, u_{nn})$. 
Reverso: $A$ invertible $\implies$ $D$ invertible. $M = U^TD^{-1}$ es triangular inferior con $1$ en la diagonal y además $LDM^T = LU = A$. Como $A$ es simétrica, $A = A^T = MDL^T$. $L' = M$ es triangular inferior con $1$ en la diagonal, $U' = DL^T$ es triangular superior, y por unicidad de la descomposición $LU$ tenemos que $L = L' = M \iff U = DL^T$.
Tags: dem met
<!--ID: 1735044171466-->
END

