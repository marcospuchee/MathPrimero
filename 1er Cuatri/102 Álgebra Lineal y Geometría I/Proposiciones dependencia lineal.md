### Proposición

1) Si $0 \in \{v_1, \dots, v_n\}$, entonces este es linealmente dependiente.
2) $\{v_1\}$ es linealmente independiente $\iff v_1 \not = 0$.
3) Si $\{v_1, \dots, v_n\}$ es linealmente dependiente, entonces $\{v_1, \dots, v_n, v_{n+1}, \dots, v_{n+r}\}$ es linealmente dependiente.
4) Si $\{v_1, \dots, v_n, v_{n+1}, \dots, v_{n+r}\}$ es linealmente independiente, entonces $\{v_1, \dots, v_n\}$ es linealmente independiente.

---
### Demostración

1) $0 = 0v_1 + 0v_2 + \dots + 0v_n + k0, \forall k \in K$.
2) $0 = 0q, \forall q \in K. qv_1 = 0 \implies q = 0$ (linealmente independiente).
3) $a_1v_1 + \dots + a_nv_n = 0 \implies a_1v_1 + \dots + a_nv_n + 0v_{n+1} + \dots + 0v_{n+r}$.
4) $a_1v_1 + \dots + a_nv_n + \dots + a_rv_r = 0$ con $a_i = 0, \forall i \in K \implies$ $a_1v_1 + \dots + a_nv_n = 0$ si $a_i = 0$.

---
### Referencias
[[Combinación lineal]]
[[Dependencia lineal]]
[[Independencia lineal]]