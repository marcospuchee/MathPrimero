
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-06, 19:39

Sea $f \in End(V)$ ([[Endomorfismo]]), y sea $A$ la matriz coordenadas de $f$ ([[Matriz asociada a una aplicación lineal]]) con respecto a una base (cualquiera) $B$ de $V$. Entonces,

```ad-theorem
$f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff A$ es diagonalizable ([[Matriz diagonalizable]]).
```


```ad-proof
$\rightarrow$. 
Supongamos que $f$ es diagonalizable. Sea $B'$ una base de $V$ formada por vectores propios de $f$. Escribimos $B' = \{v_1, \dots, v_n\} (n = dimV)$. Tenemos que $f(v_i) = \lambda_i v_i$, para cierto $\lambda_i \in K, \forall i = 1, \dots, n$. Por tanto, $\forall i, [f(v_i)]_{B'} = [\lambda_i v_i]_{B'}$ $= \lambda_i [v_i]_{B'} = \lambda_i (0, \dots, 0,1,0, \dots, 0)$ con un $1$ en la $i$-ésima posición. Así, la matriz coordenadas de $f$ en $B'$ es $D = diag(\lambda_1, \lambda_2, \dots, \lambda_n$), es decir, la matriz diagonal con $\lambda_1, \dots, \lambda_n$ en la diagonal. Concluimos que $A$ y $D$ son semejantes (por [[Matrices asociadas a endomorfismos son semejantes]]) , y por tanto $A$ es diagonalizable. De hecho, $D = P^{-1}AP$, donde $P$ es la [[Matriz cambio de base]] de $B'$ a $B$.

$\leftarrow$.
Supongamos que $A$ es diagonalizable. Sea $P \in GL_n (K)$ tal que $P^{-1}AP$ es diagonal. Queremos hallar $B'$ base de $V$ tal que la matriz coordenadas de $f$ en $B'$ sea $P^{-1}AP$. Es suficiente hallar $B'$ tal que $P$ sea la matriz cambio de base de $B'$ a $B$. Escribimos $P = (p_{ij})$ y $B = \{u_1, \dots, u_n\}$. Consideramos:
- $v_1 = p_{11} u_1 + p_{21} u_2 + \dots + p_{n1} u_n$.
- $\dots$
- $v_j = p_{1j} u_1 + p_{2j} u_2 \dots + p_{nj} v_n$.

Por construcción, $[v_j]_B = (p_{1j}, \dots, p_{nj})$ (columna $j$-ésima de $P, \forall j = 1, \dots, n$). Dado que $P$ es invertible, sabemos que $rg_c(P) = m$, y por tanto $B'$ es linealmente independiente ([[Independencia lineal]]), y en consecuencia, $B'$ base de $V$ ([[(POR DEMOSTRAR) Prop 4. EV.]]). Deducimos que $P$ es la matriz cambio de base de $B'$ a $B$, y por tanto, $D = P^{-1}AP$ es la matriz coordenadas de $f$ con respecto a $B'$. Si $D = diag(d_1, d_2, \dots, d_n)$, entonces $\forall j, [f(v_j)]_{B'} = (0, \dots, 0, d_j, 0, \dots, 0)$ (con $d_j$ en la $j$-ésima posición) $\iff f(v_j) = d_j v_j$. Luego $B'$ es la base de $V$ formada por vectores propios de $f$.
```


**Tema:** [[Diagonalización]]
**Demostrado por:** [[Matrices asociadas a endomorfismos son semejantes]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué relación existe entre que una matriz $A$ sea diagonalizable con que $f$ sea un endomorfismo diagonalizable?
Reverso: Sea $f \in End(V)$ ([[Endomorfismo]]), y sea $A$ la matriz coordenadas de $f$ ([[Matriz asociada a una aplicación lineal]]) con respecto a una base (cualquiera) $B$ de $V$. Entonces, $f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff A$ es diagonalizable ([[Matriz diagonalizable]]).
Tags: proposición/teorema
<!--ID: 1707247432334-->
END

START
Básico
Anverso: Demostración de que sea $f \in End(V)$ ([[Endomorfismo]]), y sea $A$ la matriz coordenadas de $f$ ([[Matriz asociada a una aplicación lineal]]) con respecto a una base (cualquiera) $B$ de $V$. Entonces, $f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff A$ es diagonalizable ([[Matriz diagonalizable]]).
Reverso: $\rightarrow$. 
Supongamos que $f$ es diagonalizable. Sea $B'$ una base de $V$ formada por vectores propios de $f$. Escribimos $B' = \{v_1, \dots, v_n\} (n = dimV)$. Tenemos que $f(v_i) = \lambda_i v_i$, para cierto $\lambda_i \in K, \forall i = 1, \dots, n$. Por tanto, $\forall i, [f(v_i)]_{B'} = [\lambda_i v_i]_{B'}$ $= \lambda_i [v_i]_{B'} = \lambda_i (0, \dots, 0,1,0, \dots, 0)$ con un $1$ en la $i$-ésima posición. Así, la matriz coordenadas de $f$ en $B'$ es $D = diag(\lambda_1, \lambda_2, \dots, \lambda_n$), es decir, la matriz diagonal con $\lambda_1, \dots, \lambda_n$ en la diagonal. Concluimos que $A$ y $D$ son semejantes (por [[Matrices asociadas a endomorfismos son semejantes]]) , y por tanto $A$ es diagonalizable. De hecho, $D = P^{-1}AP$, donde $P$ es la [[Matriz cambio de base]] de $B'$ a $B$.

$\leftarrow$.
Supongamos que $A$ es diagonalizable. Sea $P \in GL_n (K)$ tal que $P^{-1}AP$ es diagonal. Queremos hallar $B'$ base de $V$ tal que la matriz coordenadas de $f$ en $B'$ sea $P^{-1}AP$. Es suficiente hallar $B'$ tal que $P$ sea la matriz cambio de base de $B'$ a $B$. Escribimos $P = (p_{ij})$ y $B = \{u_1, \dots, u_n\}$. Consideramos:
- $v_1 = p_{11} u_1 + p_{21} u_2 + \dots + p_{n1} u_n$.
- $\dots$
- $v_j = p_{1j} u_1 + p_{2j} u_2 \dots + p_{nj} v_n$.

Por construcción, $[v_j]_B = (p_{1j}, \dots, p_{nj})$ (columna $j$-ésima de $P, \forall j = 1, \dots, n$). Dado que $P$ es invertible, sabemos que $rg_c(P) = m$, y por tanto $B'$ es linealmente independiente ([[Independencia lineal]]), y en consecuencia, $B'$ base de $V$ ([[(POR DEMOSTRAR) Prop 4. EV.]]). Deducimos que $P$ es la matriz cambio de base de $B'$ a $B$, y por tanto, $D = P^{-1}AP$ es la matriz coordenadas de $f$ con respecto a $B'$. Si $D = diag(d_1, d_2, \dots, d_n)$, entonces $\forall j, [f(v_j)]_{B'} = (0, \dots, 0, d_j, 0, \dots, 0)$ (con $d_j$ en la $j$-ésima posición) $\iff f(v_j) = d_j v_j$. Luego $B'$ es la base de $V$ formada por vectores propios de $f$.
Tags: demostración
<!--ID: 1707247432349-->
END
