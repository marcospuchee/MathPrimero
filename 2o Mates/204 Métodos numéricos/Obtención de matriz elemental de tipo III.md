### Contenido principal

Algoritmo para econtrar la matriz $L_{m,k}$, que añade $0$ en la fila $m$, columna $k$ de $A$ (es decir, la matriz elemental de tipo $III$). Para ello, vamos a realizar las operaciones: multiplicar la fila $k$ por el número $\alpha_{m,k}$, sumar el resultado a la fila $m$ y sustituir la fila $m$ de la matriz dada por el resultado de esta operación.

```ad-Algorithm
1. $e^T_mA = A(m, :)$ es la fila $m$ de la matriz $A$, $e_k^T A = A(k,:)$ es la fila $k$ de la matriz $A$. Multiplicar la fila $k$ por el número $\alpha_{m,k}$, y sumar el resultado a la fila $m$ se escribe como $\alpha_{m,k}e_k^T A + e_m^TA$.
2. La matriz que tiene en la fila $m$ la correspondiente fila de la matriz $A$, y cero en el resto de elementos es $e_m(e_m^T A)$. La matriz con las mismas filas que $A$, excepto la fila $m$, que es nula, es: $A - e_m(e_m^T A)$. La matriz que tiene en la fila $m$ el vector fila $(\alpha_{m,k}e_k^TA + e_m^TA)$ y cero en el resto de elementos es: $e_m(\alpha_{m,k}e_k^T A + e_m^T A)$.
3. La matriz deseada es finalmente:
$$\begin{matrix}
A - e_m(e_m^TA) + e_m(\alpha_{m,k} e_k^T A + e_m^T A) \\
= A-e_m(e_m^TA) + e_m(\alpha_{m,k} e_k^T A) + e_m(e_m^TA) \\
= (I + \alpha_{m,k}e_m e_k^T)A
\end{matrix}.$$

Así, la matriz de la transformación elemental se escribe
$$L_{m,k} = I + \alpha_{m,k} e_m e_k^T.$$
```

**Tema:** [[Descomposición LU#2. La eliminación gaussiana como descomposición matricial.]]

**Definiciones referenciadas:** [[Matriz elemental de tipo III]]

---
### Anki

START
Básico
Anverso: Algoritmo para econtrar la matriz $L_{m,k}$, que añade $0$ en la fila $m$, columna $k$ de $A$ (es decir, la [[matriz elemental de tipo III]])
Reverso: Para ello, vamos a realizar las operaciones: multiplicar la fila $k$ por el número $\alpha_{m,k}$, sumar el resultado a la fila $m$ y sustituir la fila $m$ de la matriz dada por el resultado de esta operación.
1. $e^T_mA = A(m, :)$ es la fila $m$ de la matriz $A$, $e_k^T A = A(k,:)$ es la fila $k$ de la matriz $A$. Multiplicar la fila $k$ por el número $\alpha_{m,k}$, y sumar el resultado a la fila $m$ se escribe como $\alpha_{m,k}e_k^T A + e_m^TA$.
2. La matriz que tiene en la fila $m$ la correspondiente fila de la matriz $A$, y cero en el resto de elementos es $e_m(e_m^T A)$. La matriz con las mismas filas que $A$, excepto la fila $m$, que es nula, es: $A - e_m(e_m^T A)$. La matriz que tiene en la fila $m$ el vector fila $(\alpha_{m,k}e_k^TA + e_m^TA)$ y cero en el resto de elementos es: $e_m(\alpha_{m,k}e_k^T A + e_m^T A)$.
3. La matriz deseada es finalmente:
$$\begin{matrix}
A - e_m(e_m^TA) + e_m(\alpha_{m,k} e_k^T A + e_m^T A) \\
= A-e_m(e_m^TA) + e_m(\alpha_{m,k} e_k^T A) + e_m(e_m^TA) \\
= (I + \alpha_{m,k}e_m e_k^T)A
\end{matrix}.$$

Así, la matriz de la transformación elemental se escribe
$$L_{m,k} = I + \alpha_{m,k} e_m e_k^T.$$
Tags:
<!--ID: 1727083427948-->
END