
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-30, 21:27

Sea $f \in End(V), A, C \in M_n (K)$ matrices coordenadas de $f$ ([[Matriz asociada a una aplicación lineal]]) respecto a $B, B'$ bases de $V$ respectivamente, entonces,
```ad-proposition
$A$ y $C$ son semejantes.

```


```ad-proof
Sea $B = \{v_1, \dots, v_n\}$ [[Base]] de $V$. Sea $A \in M_n (K)$ la matriz coordenada de $f$ con respecto a la base $B$, es decir, $[f(v_j)]_B \in K^n$ ([[Coordenadas]]) es la columna j-ésima de $A, \forall j \in \{1, \dots, n\}$.
Sabemos por [[Cálculo de las coordenadas una imagen dada la matriz asociada]] que $\forall v \in V, [f(v)]_B = A[v]_B$.
Consideremos $B'$ una base de $V$, y sea $C$ la matriz coordenada de $f$ con respecto a $B'$. Sea $P$ la [[Matriz cambio de base]] de $B$ a $B'$, tenemos que $[f(v)]_{B'} = C[v]_{B'}$.

Por otro lador, $[v]_{B'} = P[v]_B, \forall v \in V$. Por tanto, $P[f(v)]_B = CP[v]_B \implies [f(v)]_B = P^{-1}CP [v]_B$.

Así, hemos llegado a que $A = P^{-1}CP$, luego $A$ y $C$ son matrices semejantes ([[Semejanza de matrices]]).

```


**Tema:** [[Diagonalización]]
**Consecuencias:** [[Dos matrices coordenadas de f respecto a bases distintas poseen el mismo polinomio característico]], [[Teorema relación matriz diagonalizable endomorfismo diagonalizable]]

---
### Anki

START
Respuesta anidada
Sean $f \in End(V), A, C \in M_n (K)$ matrices coordenadas de $f$ ([[Matriz asociada a una aplicación lineal]]) respecto a $B, B'$ bases de $V$ respectivamente, entonces, {{c1::$A$ y $C$ son semejantes.}}
Tags: proposición/teorema
<!--ID: 1706723823967-->
END

START
Básico
Anverso: Demostración de que sean $f \in End(V), A, C \in M_n (K)$ matrices coordenadas de $f$ ([[Matriz asociada a una aplicación lineal]]) respecto a $B, B'$ bases de $V$ respectivamente, entonces, $A$ y $C$ son semejantes.
Reverso: Sea $B = \{v_1, \dots, v_n\} [[Base]] de $V$. Sea $A \in M_n (K)$ la matriz coordenada de $f$ con respecto a la base $B$, es decir, $[f(v_j)]_B \in K^n$ ([[Coordenadas]]) es la columna j-ésima de $A, \forall j \in \{1, \dots, n\}$.
Sabemos por [[Cálculo de las coordenadas una imagen dada la matriz asociada]] que $\forall v \in V, [f(v)]_B = A[v]_B$.
Consideremos $B'$ una base de $V$, y sea $C$ la matriz coordenada de $f$ con respecto a $B'$. Sea $P$ la [[Matriz cambio de base]] de $B$ a $B'$, tenemos que $[f(v)]_{B'} = C[v]_{B'}$.

Por otro lador, $[v]_{B'} = P[v]_B, \forall v \in V$. Por tanto, $P[f(v)]_B = CP[v]_B \implies [f(v)]_B = P^{-1}CP [v]_B$.

Así, hemos llegado a que $A = P^{-1}CP$, luego $A$ y $C$ son matrices semejantes ([[Semejanza de matrices]]).
Tags: demostración
<!--ID: 1706723823972-->
END
