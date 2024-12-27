### Contenido Principal

```ad-proposition
Sea $M_k = I + v^{(k)}e_k^T \in \mathbb R^{n \times n}$, con $v^{(k)} = \sum_{j = k+1}^n \alpha_{j,k} e_j$ con $1 \le k \le n-1$ ([[proposición producto de matrices elementales de tipo III]]). Se cumple que $M_k^{-1} = I - v^{(k)}e_k^T$ y que
$$M_1^{-1}M_2^{-1} \dots M_{n-1}^{-1} = I - \sum_{j = 1}^{n-1} v^{(j)} e_j^T.$$
```

```ad-note
Por tanto, en ya tenemos la descomposición LU:
$$\begin{matrix}
U:=M_{n-1} \dots M_2 M_1 A = \left ( \prod_{j = 1}^{n-1} M_{n-j} \right ) A \\
L := \prod_{j = 1}^{n-1} M_j^{-1}
\end{matrix}$$
Pero con estos últimos resultados, les podemos dar forma a ambas matrices.
```

```ad-proof
Veamos primero que $M_k^{-1} = I - v^{(k)}e_k^T$.
$$M_kM_k^{-1} = (I+v^{(k)}e_k^T)(I-v^{(k)}e_k^T) = I - (v^{(k)}e_k^T)^2 = I - v^{(k)}(e_k^T v^{(k)})e_k^T = I.$$

Para demostrar lo otro, procederemos por inducción sobre $n$.
**Caso base: $n=2$.**
$$\sum_{j = 1}^{2-1} M_j^{-1} = I - \sum_{j = 1}^{2-1}v^{(j)}e_j^T \implies M_1^{-1} = I-v^{(1)}e_1^T.$$

**Hipótesis de inducción.** Sea $k \in \mathbb N$, supongamos que
$$\prod_{j =1}^{k-1} M_j^{-1} = I - \sum_{j = 1}^{k-1} v^{(j)}e_j^T.$$
Queremos probarlo para $k+1$:
$$\begin{eqnarray}
\prod_{j = 1}^k M_j^{-1} &=& \left ( \prod_{j = 1}^{k-1} M_j^{-1} \right ) M_k^{-1} = \left (I- \sum_{j = 1}^{k-1} v^{(j)} e_j^T \right)\left ( I - v^{(k)} e_k^T \right ) \\
&=& I - v^{(k)}e_k^T - \sum_{j = 1}^{k-1} v^{(j)} e_j^T + \left ( \sum_{j = 1}^{k-1} v^{(j)} e_j^T \right ) v^{(k)} e_k^T \\
&=& I - \sum_{j = 1}^k v^{(j)} e_j^T + \sum_{j = 1}^{k-1} v^{(j)} (e_j^T v^{(k)}) e_k^T \\
&=& I - \sum_{j = 1}^k v^{(j)}e_j^T
\end{eqnarray}$$
```

**Tema:** [[Descomposición LU#2. La eliminación gaussiana como descomposición matricial.]]

---
### Anki

START
Básico
Anverso: Definición y obtención de la matriz $L$ en la descomposición $LU$:
Reverso: Sea $M_k = I + v^{(k)}e_k^T \in \mathbb R^{n \times n}$, con $v^{(k)} = \sum_{j = k+1}^n \alpha_{j,k} e_j$ con $1 \le k \le n-1$ . Se cumple que $M_k^{-1} = I - v^{(k)}e_k^T$ y que
$$L:=M_1^{-1}M_2^{-1} \dots M_{n-1}^{-1} = I - \sum_{j = 1}^{n-1} v^{(j)} e_j^T.$$
Tags: met
<!--ID: 1735044171373-->
END

START
Básico
Anverso: Demostración de que sea $M_k = I + v^{(k)}e_k^T \in \mathbb R^{n \times n}$, con $v^{(k)} = \sum_{j = k+1}^n \alpha_{j,k} e_j$ con $1 \le k \le n-1$. Se cumple que $M_k^{-1} = I - v^{(k)}e_k^T$ y que
$$M_1^{-1}M_2^{-1} \dots M_{n-1}^{-1} = I - \sum_{j = 1}^{n-1} v^{(j)} e_j^T.$$
Reverso: Veamos primero que $M_k^{-1} = I - v^{(k)}e_k^T$.
$$M_kM_k^{-1} = (I+v^{(k)}e_k^T)(I-v^{(k)}e_k^T) = I - (v^{(k)}e_k^T)^2 = I - v^{(k)}(e_k^T v^{(k)})e_k^T = I.$$

Para demostrar lo otro, procederemos por inducción sobre $n$.
**Caso base: $n=2$.**
$$\sum_{j = 1}^{2-1} M_j^{-1} = I - \sum_{j = 1}^{2-1}v^{(j)}e_j^T \implies M_1^{-1} = I-v^{(1)}e_1^T.$$

**Hipótesis de inducción.** Sea $k \in \mathbb N$, supongamos que
$$\prod_{j =1}^{k-1} M_j^{-1} = I - \sum_{j = 1}^{k-1} v^{(j)}e_j^T.$$
Queremos probarlo para $k+1$:
$$\begin{eqnarray}
\prod_{j = 1}^k M_j^{-1} &=& \left ( \prod_{j = 1}^{k-1} M_j^{-1} \right ) M_k^{-1} = \left (I- \sum_{j = 1}^{k-1} v^{(j)} e_j^T \right)\left ( I - v^{(k)} e_k^T \right ) \\
&=& I - v^{(k)}e_k^T - \sum_{j = 1}^{k-1} v^{(j)} e_j^T + \left ( \sum_{j = 1}^{k-1} v^{(j)} e_j^T \right ) v^{(k)} e_k^T \\
&=& I - \sum_{j = 1}^k v^{(j)} e_j^T + \sum_{j = 1}^{k-1} v^{(j)} (e_j^T v^{(k)}) e_k^T \\
&=& I - \sum_{j = 1}^k v^{(j)}e_j^T
\end{eqnarray}$$
Tags: dem met
<!--ID: 1735044171375-->
END

START
Básico
Anverso: Definición de la matriz $U$ en la descomposición $LU$.
Reverso: $U:=M_{n-1} \dots M_2 M_1 A = \left ( \prod_{j = 1}^{n-1} M_{n-j} \right ) A$.
Tags: met
<!--ID: 1735044171377-->
END
