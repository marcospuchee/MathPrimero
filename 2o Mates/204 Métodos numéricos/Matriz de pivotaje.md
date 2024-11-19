### Contenido Principal

```ad-proposition
Sea $A \in \mathbb R^{n \times n}$ y sean $i,j \in \mathbb N$ índices tales que $1 \le i,j \le n$. Entonces la matriz $P_{i,j}$ dada por
$$P_{i,j} := I - (e_i - e_j)(e_i - e_j)^T$$
satisface que $P_{i,j}A$ es la matriz resultante de permutar la fila $i$ con la fila $j$ de $A$.
```

```ad-proof
Comprobamos que
$$\begin{eqnarray}
P_{i,j}A &=& (I - e_ie_i^T - e_i e_j^T + e_i e_j^T + e_j e_i^T)A \\
&=& A - e_i(e_i^T A) - e_j(e_j^TA) + e_i(e_j^TA) + e_j(e_i^TA),
\end{eqnarray}$$
que es, en efecto, el resultado de permutar la fila $i$ con la fila $j$ de $A$.
```

**Tema:** [[Descomposición LU#4. Eliminación gaussiana con pivoteo parcial.]]

---
### Anki
