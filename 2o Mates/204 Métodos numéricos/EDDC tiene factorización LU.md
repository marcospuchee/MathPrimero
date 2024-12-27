### Contenido Principal

```ad-theorem
$A \in \mathbb R^{n \times n}$ EDDC ([[matrices diagonalmente dominantes]]) $\implies$ $A$ tiene factorización $LU$.
```

```ad-proof
Vamos a proceder por inducción sobre $n$.

**Caso base: $n = 1$**. 
$A = (a_{11})$ con $a_11 \neq 0$, entonces $A = LU$ con $L = (1)$ y $U = (a_{11})$. 

**Hipótesis de inducción.**
Supongamos que $\forall B \in \mathbb R^{(n-1)\times (n-1)}$ EDDC tiene descomposición LU. Veámoslo para $n$. Sea $A \in \mathbb R^{n \times n}$. Hemos visto que $a_{11} \neq 0$, por lo que podemos aplicar el primer paso de la eliminación gaussiana:
$$ \left ( \begin{array}{c | c} 1 & 0_{n-1}^T \\ \hline - \frac{A(2:n,1)}{A(1,1)} & I_{n-1} \end{array} \right ) \left ( \begin{array}{c | c} A(1,1) & A(1, 2:n) \\ \hline A(2:n,1) & A(2:n, 2:n) \end{array} \right ) = \left ( \begin{array}{c | c} A(1,1) & A(1, 2:n) \\ \hline 0_{n-1} & B \end{array} \right ),$$
donde $B := A(2:n, 2:n) - \frac{A(2:n,1) A(1, 2:n)}{A(1,1)}$. Sean $i,j$, $1 \le i,j \le n$, se cumple que
$$\begin{eqnarray}
B(i,j) &=& A(i+1, j+1) - \frac{1}{A(1,1)} \left [ A(2:n, 1) A(1, 2:n) \right ](i,j) \\ &=& A(i+1, j+1) - \frac{1}{A(1,1)} A(i+1, 1) A(1, j+1).
\end{eqnarray}$$
Sea $j \in \{1, \dots, n\}$ fijo. probaremos que $\sum_{i = 1, j \neq i}^{n-1} |B(i,j)| < |B(j,j)|$. Tenemos que
$$(*) \quad \sum_{i = 1, i \neq j}^{n-1} |B(i,j)| \le \sum_{i = 1, i \neq j}^{n-1} |A(i+1, j+1)| + \frac{|A(1,j+1)}{|A(1,1)|} \sum_{i = 1, j \neq 1}^{n-1} |A(i+1, 1)|.$$
Sin embargo,
$$\sum_{i = 1, i \neq j}^{n-1} |A(i+1, j+1)| = \sum_{i = 1, i \neq j+1}^n |A(i, j+1)| - |A(1, j+1)|< |A(j+1, j+1)| - |A(1,j+1)|.$$
Aplicando esta desigualdad a $(*)$, nos queda que
$$\begin{eqnarray}
(*) &<& |A(j+1, j+1)| - |A(1,j+1)| + \frac{|A(1,j+1)|}{|A(1,1)|} \sum_{i = 1, j \neq i}^n |A(i,1)| \\
&<& |A(j+1, j+1)| - |A(1,j+1)| + \frac{|A(1,j+1)|}{|A(1,1)|} \sum_{i = 1, j \neq i}^n |A(i,1)|
\end{eqnarray}$$
```

**Tema:** [[Descomposición LU#3. Matrices especiales y propiedades de la descomposición LU.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Relación matriz dominante con factorización LU
Reverso: $A \in \mathbb R^{n \times n}$ EDDC $\implies$ $A$ tiene factorización $LU$.
Tags: met
<!--ID: 1735044171451-->
END

START
Básico
Anverso: Demostración de que $A \in \mathbb R^{n \times n}$ EDDC $\implies$ $A$ tiene factorización $LU$.
Reverso: Vamos a proceder por inducción sobre $n$.

**Caso base: $n = 1$**. 
$A = (a_{11})$ con $a_11 \neq 0$, entonces $A = LU$ con $L = (1)$ y $U = (a_{11})$. 

**Hipótesis de inducción.**
Supongamos que $\forall B \in \mathbb R^{(n-1)\times (n-1)}$ EDDC tiene descomposición LU. Veámoslo para $n$. Sea $A \in \mathbb R^{n \times n}$. Hemos visto que $a_{11} \neq 0$, por lo que podemos aplicar el primer paso de la eliminación gaussiana:
$$ \left ( \begin{array}{c | c} 1 & 0_{n-1}^T \\ \hline - \frac{A(2:n,1)}{A(1,1)} & I_{n-1} \end{array} \right ) \left ( \begin{array}{c | c} A(1,1) & A(1, 2:n) \\ \hline A(2:n,1) & A(2:n, 2:n) \end{array} \right ) = \left ( \begin{array}{c | c} A(1,1) & A(1, 2:n) \\ \hline 0_{n-1} & B \end{array} \right ),$$
donde $B := A(2:n, 2:n) - \frac{A(2:n,1) A(1, 2:n)}{A(1,1)}$. Sean $i,j$, $1 \le i,j \le n$, se cumple que
$$\begin{eqnarray}
B(i,j) &=& A(i+1, j+1) - \frac{1}{A(1,1)} \left [ A(2:n, 1) A(1, 2:n) \right ](i,j) \\ &=& A(i+1, j+1) - \frac{1}{A(1,1)} A(i+1, 1) A(1, j+1).
\end{eqnarray}$$
Sea $j \in \{1, \dots, n\}$ fijo. probaremos que $\sum_{i = 1, j \neq i}^{n-1} |B(i,j)| < |B(j,j)|$. Tenemos que
$$(*) \quad \sum_{i = 1, i \neq j}^{n-1} |B(i,j)| \le \sum_{i = 1, i \neq j}^{n-1} |A(i+1, j+1)| + \frac{|A(1,j+1)}{|A(1,1)|} \sum_{i = 1, j \neq 1}^{n-1} |A(i+1, 1)|.$$
Sin embargo,
$$\sum_{i = 1, i \neq j}^{n-1} |A(i+1, j+1)| = \sum_{i = 1, i \neq j+1}^n |A(i, j+1)| - |A(1, j+1)|< |A(j+1, j+1)| - |A(1,j+1)|.$$
Aplicando esta desigualdad a $(*)$, nos queda que
$$\begin{eqnarray}
(*) &<& |A(j+1, j+1)| - |A(1,j+1)| + \frac{|A(1,j+1)|}{|A(1,1)|} \sum_{i = 1, j \neq i}^n |A(i,1)| \\
&<& |A(j+1, j+1)| - |A(1,j+1)| + \frac{|A(1,j+1)|}{|A(1,1)|} \sum_{i = 1, j \neq i}^n |A(i,1)|
\end{eqnarray}$$
Tags: dem met
<!--ID: 1735044171454-->
END

