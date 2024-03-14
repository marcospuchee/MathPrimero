
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-04, 16:50

```ad-cor
Sea $A \in M_n(\mathbb K)$ simétrica. $A$ es congruente ([[Matrices congruentes]]) a una matriz diagonal.
```


```ad-proof
Considera $F = F_A: \mathbb K^n \times \mathbb K^n \to \mathbb K$ con $(x,y) \to x^t A y$ la [[Forma bilineal]] definida sobre $V = \mathbb K^n$ tal que $A$ es la [[Matriz coordenada de F]] con respecto a la base canónica de $V$. Como $A$ es simétrica, entonces $F$ es simétrica ([[Matriz coordenada de F simétrica sii F simétrica]]). Por [[Teorema existencia base F-ortogonal]], $\exists B = \{v_1, \dots, v_n\}$ base de $V$ $F$-ortogonal ([[Conjunto F-ortogonal]]). Es decir, $F(v_i, v_j) = 0, \forall i \neq j$. La matriz coordenada de $F$ con respecto a $B$ es:
$$ M = 
\begin{pmatrix}
F(v_1, v_1) & 0 & \dots & 0 \\
0 & F(v_2, v_2) & \dots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \dots & F(v_n, v_n)
\end{pmatrix}.
$$
Como $A$ y $M$ son matrices coordenadas de $F$ con respecto a dos bases distintas, entonces $A$ y $M$ son congruentes ([[Dos matrices coordenadas de F son congruentes]]).
```

**Tema:** [[Formas bilineales]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: A qué es congruente una matriz simétrica?
Reverso: Sea $A \in M_n(\mathbb K)$ simétrica. $A$ es congruente ([[Matrices congruentes]]) a una matriz diagonal.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709571902482-->
END

START
Básico
Anverso: Demostración de que sea $A \in M_n(\mathbb K)$ simétrica. $A$ es congruente ([[Matrices congruentes]]) a una matriz diagonal.
Reverso: Considera $F = F_A: \mathbb K^n \times \mathbb K^n \to \mathbb K$ con $(x,y) \to x^t A y$ la [[Forma bilineal]] definida sobre $V = \mathbb K^n$ tal que $A$ es la [[Matriz coordenada de F]] con respecto a la base canónica de $V$. Como $A$ es simétrica, entonces $F$ es simétrica ([[Matriz coordenada de F simétrica sii F simétrica]]). Por [[Teorema existencia base F-ortogonal]], $\exists B = \{v_1, \dots, v_n\}$ base de $V$ $F$-ortogonal ([[Conjunto F-ortogonal]]). Es decir, $F(v_i, v_j) = 0, \forall i \neq j$. La matriz coordenada de $F$ con respecto a $B$ es:
$$ M = 
\begin{pmatrix}
F(v_1, v_1) & 0 & \dots & 0 \\
0 & F(v_2, v_2) & \dots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \dots & F(v_n, v_n)
\end{pmatrix}.
$$
Como $A$ y $M$ son matrices coordenadas de $F$ con respecto a dos bases distintas, entonces $A$ y $M$ son congruentes ([[Dos matrices coordenadas de F son congruentes]]).
Tags: demostración ÁlgebraI
<!--ID: 1709571902492-->
END