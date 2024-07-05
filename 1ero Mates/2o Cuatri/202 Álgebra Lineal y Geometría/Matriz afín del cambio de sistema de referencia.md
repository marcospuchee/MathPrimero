
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-22, 18:19

```ad-proposition
Dado un [[espacio afín]] $(A, V, +)$ (donde $V$ es un $\mathbb K$-espacio vectorial con $\dim V = n$). Sean $\mathcal R = \{O , B\}, \mathcal R' = \{O', B'\}$ dos sistemas cartesianos ([[Sistema de referencia cartesiano]]). 

Sea $P \in A$ tal que $[P]_{\mathcal R} = X \in \mathbb K^n$ y $[P]_{\mathcal R'} = X' \in \mathbb K^n$; podemos reescribir [[ecuación cambio de sistema de referencia]] como
$$\begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = M \begin{pmatrix} 1 \\ \hline X \end{pmatrix}.$$
donde $M$ es la matriz afín al cambio de sistema de referencia de $\mathcal R$ a $\mathcal R'$.
```

```ad-proof
Tomamos
$$M = \begin{pmatrix}
1  & \begin{array}{|ccc} 0 \dots 0 \end{array} \\
\hline \begin{array}{c|} b_1 \\ \vdots \\ b_n \end{array} & A
\end{pmatrix} \in M_{n+1}(\mathbb K)$$
donde $Y = (b_1 \dots b_n)^t = [O]_{B'} \in \mathbb K^N$. Veamos que la ecuación 
$$X' = [O]_{\mathcal R'} + AX,$$
se puede reescribir como
$$\begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = M \begin{pmatrix} 1 \\ \hline X \end{pmatrix}.$$

Tenemos:
$$M \begin{pmatrix} 1 \\ \hline X \end{pmatrix} = \begin{pmatrix} \begin{array}{c|} 1 \end{array} & 0 \\
\hline \begin{array}{c|} Y \end{array} & A \end{pmatrix} \begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = \begin{pmatrix} 1 \\
b_1 + \sum_{j = 1}^n a_{1j} x_j \\ \dots \\ b_n + \sum_{j = 1}^n a_{nj} x_j \end{pmatrix} = \begin{pmatrix} 1 \\ \hline Y + AX \end{pmatrix} = \begin{pmatrix} 1 \\ \hline X' \end{pmatrix}$$
La matriz $M$ se denomina la matriz afín del cambio de sistema de referencia de $\mathcal R$ a $\mathcal R'$.
```

**Tema:** [[Espacios afines]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la matriz afín del cambio de sistema de referencia?
Reverso: Dado un [[Espacio afín]] $(A, V, +)$ (donde $V$ es un $\mathbb K$-espacio vectorial con $\dim V = n$). Sean $\mathcal R = \{O , B\}, \mathcal R' = \{O', B'\}$ dos sistemas cartesianos ([[Sistema de referencia cartesiano]]). 

Sea $P \in A$ tal que $[P]_{\mathcal R} = X \in \mathbb K^n$ y $[P]_{\mathcal R'} = X' \in \mathbb K^n$; podemos reescribir [[Ecuación cambio de sistema de referencia]] como
$$\begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = M \begin{pmatrix} 1 \\ \hline X \end{pmatrix}.$$
donde $M$ es la matriz afín al cambio de sistema de referencia de $\mathcal R$ a $\mathcal R'$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060760987-->
END

START
Básico
Anverso: Demostración de que dado un [[Espacio afín]] $(A, V, +)$ (donde $V$ es un $\mathbb K$-espacio vectorial con $\dim V = n$). Sean $\mathcal R = \{O , B\}, \mathcal R' = \{O', B'\}$ dos sistemas cartesianos ([[Sistema de referencia cartesiano]]). 

Sea $P \in A$ tal que $[P]_{\mathcal R} = X \in \mathbb K^n$ y $[P]_{\mathcal R'} = X' \in \mathbb K^n$; podemos reescribir [[Ecuación cambio de sistema de referencia]] como
$$\begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = M \begin{pmatrix} 1 \\ \hline X \end{pmatrix}.$$
donde $M$ es la matriz afín al cambio de sistema de referencia de $\mathcal R$ a $\mathcal R'$.
Reverso: Tomamos
$$M = \begin{pmatrix}
1  & \begin{array}{|ccc} 0 \dots 0 \end{array} \\
\hline \begin{array}{c|} b_1 \\ \vdots \\ b_n \end{array} & A
\end{pmatrix} \in M_{n+1}(\mathbb K)$$
donde $Y = (b_1 \dots b_n)^t = [O]_{B'} \in \mathbb K^N$. Veamos que la ecuación 
$$X' = [O]_{\mathcal R'} + AX,$$
se puede reescribir como
$$\begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = M \begin{pmatrix} 1 \\ \hline X \end{pmatrix}.$$

Tenemos:
$$M \begin{pmatrix} 1 \\ \hline X \end{pmatrix} = \begin{pmatrix} \begin{array}{c|} 1 \end{array} & 0 \\
\hline \begin{array}{c|} Y \end{array} & A \end{pmatrix} \begin{pmatrix} 1 \\ \hline X' \end{pmatrix} = \begin{pmatrix} 1 \\
b_1 + \sum_{j = 1}^n a_{1j} x_j \\ \dots \\ b_n + \sum_{j = 1}^n a_{nj} x_j \end{pmatrix} = \begin{pmatrix} 1 \\ \hline Y + AX \end{pmatrix} = \begin{pmatrix} 1 \\ \hline X' \end{pmatrix}$$
La matriz $M$ se denomina la matriz afín del cambio de sistema de referencia de $\mathcal R$ a $\mathcal R'$.
Tags: demostración ÁlgebraI
<!--ID: 1714060761011-->
END