
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-20, 20:10

```ad-lemma
Sea $F$ un [[Producto escalar]] sobre $V$ y sea $B$ base de $V$. Entonces la matriz coordenada $A$ de $F$ ([[Matriz coordenada de F]]) respecto a $B$, satisface: $\det(A) > 0$.

```


```ad-proof
Sea $B' = \{v_1, \dots, v_n\}$ base ortogonal ([[Conjunto F-ortogonal]]) de $V$. Sabemos que $F(v_i, v_i) > 0, \forall i = 1, \dots, n$. La matriz coordenada de $F$ respecto a $B'$ es: $D = Diag(F(v_1, v_1), \dots, F(v_n, v_n)) \in M_n(\mathbb R)$.
Tenemos que $\det(D) = \prod_{i = 1}^n F(v_i, v_i) > 0$. Por otro lado, $A = P^t D P$, donde $P \in GL_n(\mathbb R)$ es [[Matriz cambio de base]] de $B$ a $B'$. Tomamos $\det(A) = \det(P^tDP)$ $= \det(P^t) · \det(D) · \det(P) = \det(P)^2 · \det(D) > 0$.
```

**Tema:** [[Espacios vectoriales euclídeos]]
**Corolarios:** [[Criterio de Sylvester]]

---
### Anki

START
Básico
Anverso: Qué valor tiene el determinante de una matriz asociada a un producto escalar?
Reverso: Sea $F$ un [[Producto escalar]] sobre $V$ y sea $B$ base de $V$. Entonces la matriz coordenada $A$ de $F$ ([[Matriz coordenada de F]]) respecto a $B$, satisface: $\det(A) > 0$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1712235233648-->
END

START
Básico
Anverso: Demostración de que sea $F$ un [[Producto escalar]] sobre $V$ y sea $B$ base de $V$. Entonces la matriz coordenada $A$ de $F$ ([[Matriz coordenada de F]]) respecto a $B$, satisface: $\det(A) > 0$.
Reverso: Sea $B' = \{v_1, \dots, v_n\}$ base ortogonal ([[Conjunto F-ortogonal]]) de $V$. Sabemos que $F(v_i, v_i) > 0, \forall i = 1, \dots, n$. La matriz coordenada de $F$ respecto a $B'$ es: $D = Diag(F(v_1, v_1), \dots, F(v_n, v_n)) \in M_n(\mathbb R)$.
Tenemos que $\det(D) = \prod_{i = 1}^n F(v_i, v_i) > 0$. Por otro lado, $A = P^t D P$, donde $P \in GL_n(\mathbb R)$ es [[Matriz cambio de base]] de $B$ a $B'$. Tomamos $\det(A) = \det(P^tDP)$ $= \det(P^t) · \det(D) · \det(P) = \det(P)^2 · \det(D) > 0$.
Tags: demostración ÁlgebraI
<!--ID: 1712235233659-->
END