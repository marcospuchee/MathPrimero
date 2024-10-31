### Contenido Principal

```ad-proposition
$\forall k: 1 \le k \le n-1$,
$$\prod_{j = k+1}^n (I + \alpha_{j,k}e_j e_k^T) = I + v^{(k)} e_k^T,$$
donde $v^{(k)} = \sum_{j = k+1}^n \alpha_{j,k} e_j$.
```

```ad-note
title: Explicación
Notemos que
$$v^{(k)} = (0, \dots, 0, \alpha_{k+1, k}, \alpha_{k+2, k}, \dots, \alpha_{n,k})^T.$$
Y, por tanto, $I + v^{(k)}e_k^T$ es la matriz identidad, pero debajo de la identidad en la columna $k$ está la columna $v^{(k)}$.
```

```ad-proof
Vamos a proceder por inducción sobre $m$.

Fijado $m \in \mathbb N$, $k+1 \le m \le n-1$. Tenemos que
$$\prod_{j = k+1}^m (I + \alpha_{j,k} e_j e_k^T) = I + \left ( \sum_{j = k+1}^m \alpha_{j,k} e_j \right ) e_k^T.$$

Para $m = k+1$, ¿ $I + \alpha_{k+1, k} e_{k+1} e_k^T = I + \alpha_{k+1, k} e_{k+1} e_k^T$ ? Obvio.

Supongamos que se cumple para $m$. Veámoslo para $m+1$.
$$\prod_{j = k+1}^{m+1} (I + \alpha_{j,k} e_j e_k^T) = \left [ \prod_{j = k+1}^m (I + \alpha_{j,k} e_j e_k^T) \right ] (I + \alpha_{m+1,k} e_{m+1} e_k^T) = $$
por hipótesis de inducción,
$$\begin{eqnarray}

&=& \left [ I + \left ( \sum_{j = k+1}^m \alpha_{j,k} e_j \right ) e_k^T \right ] (I + \alpha_{m+1, k} e_{m+1} e_k^T) \\ 
&=& I + \alpha_{m+1, k} e_{m+1} e_k^T + \sum_{j = k+1}^m \alpha_{j,k} e_j e_k^T + \left [ \left ( \sum_{j = k+1}^m \alpha_{j,k} e_j \right ) e_k^T \right ] \alpha_{m+1, k} e_{m+1} e_k^T \\
&=& I + \sum_{j = k+1}^{m+1} \alpha_{j,k} e_j e_k^T.

\end{eqnarray}$$
```

**Tema:** [[Descomposición LU#2. La eliminación gaussiana como descomposición matricial.]]

---
### Anki

START
Básico
Anverso: Proposición valor de la matriz $L$ de la descomposición $LU$.
Reverso: $\forall k: 1 \le k \le n-1$,
$$\prod_{j = k+1}^n (I + \alpha_{j,k}e_j e_k^T) = I + v^{(k)} e_k^T,$$
donde $v^{(k)} = \sum_{j = k+1}^n \alpha_{j,k} e_j$.

Notemos que
$$v^{(k)} = (0, \dots, 0, \alpha_{k+1, k}, \alpha_{k+2, k}, \dots, \alpha_{n,k})^T.$$
Y, por tanto, $I + v^{(k)}e_k^T$ es la matriz identidad, pero debajo de la identidad en la columna $k$ está la columna $v^{(k)}$.
Tags:
<!--ID: 1727083427944-->
END

START
Básico
Anverso: Demostración de que $\forall k: 1 \le k \le n-1$,
$$\prod_{j = k+1}^n (I + \alpha_{j,k}e_j e_k^T) = I + v^{(k)} e_k^T,$$
donde $v^{(k)} = \sum_{j = k+1}^n \alpha_{j,k} e_j$.
Reverso: Vamos a proceder por inducción sobre $m$.

Fijado $m \in \mathbb N$, $k+1 \le m \le n-1$. Tenemos que
$$\prod_{j = k+1}^m (I + \alpha_{j,k} e_j e_k^T) = I + \left ( \sum_{j = k+1}^m \alpha_{j,k} e_j \right ) e_k^T.$$

Para $m = k+1$, ¿ $I + \alpha_{k+1, k} e_{k+1} e_k^T = I + \alpha_{k+1, k} e_{k+1} e_k^T$ ? Obvio.

Supongamos que se cumple para $m$. Veámoslo para $m+1$.
$$\prod_{j = k+1}^{m+1} (I + \alpha_{j,k} e_j e_k^T) = \left [ \prod_{j = k+1}^m (I + \alpha_{j,k} e_j e_k^T) \right ] (I + \alpha_{m+1,k} e_{m+1} e_k^T) = $$
por hipótesis de inducción,
$$\begin{eqnarray}

&=& \left [ I + \left ( \sum_{j = k+1}^m \alpha_{j,k} e_j \right ) e_k^T \right ] (I + \alpha_{m+1, k} e_{m+1} e_k^T) \\ 
&=& I + \alpha_{m+1, k} e_{m+1} e_k^T + \sum_{j = k+1}^m \alpha_{j,k} e_j e_k^T + \left [ \left ( \sum_{j = k+1}^m \alpha_{j,k} e_j \right ) e_k^T \right ] \alpha_{m+1, k} e_{m+1} e_k^T \\
&=& I + \sum_{j = k+1}^{m+1} \alpha_{j,k} e_j e_k^T.

\end{eqnarray}$$

Tags: met
<!--ID: 1727083427946-->
END
