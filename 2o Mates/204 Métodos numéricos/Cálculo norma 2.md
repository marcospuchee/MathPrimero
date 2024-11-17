### Contenido Principal

```ad-proposition
Dada una matriz $A \in \mathbb R^{n \times n}$ cualquiera,
$$||A||_2 = \sqrt{\rho(A^TA)}$$
```

```ad-proof
Dado que $A^TA$ es simétrica, sabemos que $\exists Q \in \mathbb R^{n \times n}$ ortogonal y $\exists D$ diagonal tal que $Q^T(A^TA)Q=D$. Dado que $Q$ es ortogonal, $Q^{-1} = Q^T$. Por tanto,
$$Q^T(A^TA)Q = D \implies A^TA = QDQ^T.$$

Dividimos la prueba en las siguientes dos desigualdades:

- $||A||_2 \le \sqrt{\rho(A^TA)}$.
Por definición, $||A||_2 = \sup \limits_{x \in \mathbb R^n \textrm{\\} \{0\}} \frac{||Ax||_2}{||x||_2}$. Será suficiente comprobar que $\frac{||Ax||_2}{||x||_2} \le \sqrt{\rho(A^TA)}$, $\forall x \in \mathbb R^n \textrm{\\} \{0\}$. Dado que $Ax$ es un vector, nos damos cuenta de que
$$\begin{eqnarray}||Ax||_2^2 &=& (Ax)^T(Ax) = x^T (A^T A) x = x^T (QDQ^T) x = (x^TQ)D(Q^Tx) \\ &=& (Q^Tx)^T D (Q^Tx).
\end{eqnarray}$$
Sea $y:= Q^Tx \in \mathbb R^{n \times 1}$, entonces, por ser $D$ diagonal,
$$y^T D y = \sum_{i = 1}^n d_i y_i^2; 0 \le d_i = D(i,i).$$
Por tanto,
$$0 \le d_i \le \max \limits_{1 \le j \le n} |d_j| = \rho(A^T A),$$
lo que implica que
$$\sum_{i = 1}^n d_i y_i^2 \le \sum_{i = 1}^n \rho(A^TA)y_i^2 = \rho(A^TA) \sum_{i = 1}^n y_i^2 = \rho(A^TA) \, ||y||_2^2, = \rho(A^TA) \, ||Q^Tx||^2_2,$$
deshaciendo el cambio de variable $y = Q^Tx$, y por un resultado del seminario 4,
$$\rho(A^TA) \, ||Q^Tx||_2^2 = \rho(A^TA) ||x||_2^2.$$
Por tanto, $||Ax||_2^2 \le \rho(A^TA) ||x||_2^2$ $\implies$ $\frac{||Ax||^2_2}{||x||_2^2} \le \rho(A^TA)$.

- $||A||_2 \ge \sqrt{\rho(A^TA)}$.
Bastará con encontrar $y \in \mathbb R^n \textrm{\\} \{0\}$ tal que
$$\frac{||Ay||_2^2}{||y||_2^2} = \rho(A^TA),$$
dado que entonces, $\sup \limits_{x \in \mathbb R^n \textrm{\\} \{0\}} \frac{||Ax||_2^2}{||x||_2^2} \ge \frac{||Ay||_2^2}{||y||_2^2} = \rho(A^TA)$. Sea $k:= \textrm{argmax}_{1 \le i \le n} \{|d_i| \}$. Tomamos $d_k$, entonces $\lambda_k = \rho(A^TA)$ y tomamos $q_k := Q(:,k)$ el vector propio asociado a $\lambda_k$. Que $q_k$ sea vector propio implica que $(A^TA)q_k = d_k q_k$. Entonces,
$$\begin{eqnarray}
||Aq_k||^2_2 &=& (Aq_k)^T(Aq_k) = q_k^T ((A^T A) q_k)  = q_k^T(d_k q_k) = d_k q_k^T q_k \\ &=& \rho(A^TA)||q_k||_2^2 = \rho(A^TA)
\end{eqnarray}$$
dado que $||q_k||_2^2 = 1$ porque $Q$ es ortogonal, y toda columna de una matriz ortogonal forma parte de una base ortonormal.

Luego hemos demostrado lo que queríamos.
```

**Tema:** [[Sistemas lineales y su solución numérica#1. Normas de vectores y de matrices.]]

**Definiciones referenciadas:** [$|| A ||_ 2$](Norma matricial subordinada a una norma vectorial), [$\rho(A^TA)$](Radio espectral), [[Matriz ortogonal]]
**Resultados referenciados:** [$A \in \mathbb R^{n \times n}$ simétrica $\implies$ $\exists Q$ ortogonal $: QAQ^T = D$ diagonal](Matriz real simétrica es diagonalizable por matrices ortogonales), [$0 \le d_i = D(i,i)$](Matriz real simétrica definida positiva implica que sus valores propios son estrictamente positivos)

---
### Anki
