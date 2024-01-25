### Enunciado Teorema

Sean $V$ un $k$-ev y $U$ un subespacio ([[Subespacio vectorial]]) de $V$, entonces existe $W$ subespacio de $V$ tal que $V= U \bigoplus W$ ([[Suma directa]]).

---
### Demostración

Sea $\{v_1, \dots, v_m\}$ [[Base]] de $U$. La prolongamos a $\{v_1, \dots, v_m, v_{m+1}, \dots, v_n\}$ base de $V$. Definimos $W = <v_{m+1}, \dots, v_n>$. Hay que probar que $V = U \bigoplus W$.
##### ¿Es $V = U+W$?
Sea $v \in V$, hay que ver que $\exists u \in U, w \in W$ tal que $v = u + w$:
$v = \lambda_1 v_1 + \dots + \lambda_m v_m + \lambda_{m+1} v_{m+1} + \dots + \lambda_n v_n$ para algunos $\lambda_i \in K$. Como podemos comprobar, están contenidas una base de $U$ y una combinación lineal de $W$. Por lo tanto $V = U + W$.
##### $U \cap W = \{0\}$
Sea $v \in U \cap W$, hay que ver que $v = 0$. Como $v \in U, v = \lambda_1 v_1 + \dots + \lambda_m v_m$ para algunos $\lambda_i \in K$. Como $v \in W$, $v = \lambda_{m+1} v_{m+1} + \dots + \lambda_n v_n$ para algunos $\lambda_i \in K$. Por tanto, $\lambda_1 v_1 + \dots + \lambda_m v_m = \lambda_{m+1} v_{m+1} + \dots + \lambda_n v_n$. Pasándolo todo a un lado se queda: $\lambda_1 v_1 + \dots + \lambda_m v_m - \lambda_{m+1} v_{m+1} - \dots - \lambda_n v_n = 0$. Como $\{v_1, \dots, v_m, v_{m+1}, \dots, v_n\}$ es base de $V$, entonces es linealmente independiente ([[Independencia lineal]]), por lo que $\lambda_i = 0, \forall i \in \{1, \dots, n\}$. Deducimos que $v = 0$.

---
### Referencias

[[Espacio vectorial]]

23-10-23. Álgebra lineal (práctica).