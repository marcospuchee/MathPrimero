### Lema

Sean $f: V \rightarrow V'$ lineal, $B$ base de $V$ y $B'$ base de $V'$. Si $M_{B,B'} (f) v_B = A v_B$ para alguna matriz $A$ y $\forall v \in V$, entonces $A = M_{B, B'} (f)$.

---
### Demostración

Sea $B = \{v_1, \dots, v_n\}$. Entonces, $(v_i)_B = (0, \dots, 0, 1, 0, \dots, 0)^T$ ($1$ en la posición $i$). Así, $A(v_i)_B = i$-ésima columna de $A$. De igual forma, $M_{B,B'} (f)(v_i)B = i$-ésima columna de $M_{B, B'} (f)$. Por tanto, deducimos que la $i$-ésima columna de $A$ es igual a la $i$-ésima columna de $M_{B,B'} (f), \forall i \in \{1, \dots, n\}$.

---
### Referencias

[[Aplicación lineal]]
[[Matriz asociada a una aplicación lineal]]
[[Coordenadas]]