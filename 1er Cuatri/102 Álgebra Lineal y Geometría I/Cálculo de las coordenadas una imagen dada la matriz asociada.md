### Proposición

Sean $f: V \rightarrow V'$ lineal, $B$ base de $V$ y $B'$ [[Base]] de $V'$, entonces:
$$ f(v)_{B'} = M_{B,B'} (f) v_B, \forall v \in V$$

---
### Demostración

Sea $B = \{v_1, \dots, v_n\}, B' = \{v_1', \dots, v_m'\}$. Sea $v \in V$, sabemos que $\exists ! \lambda_1, \dots, \lambda_n \in K$ tal que $v = \lambda_1 v_1 + \dots + \lambda_n v_n$. Así, $v_B = (\lambda_1, \dots, \lambda_n)$ ([[Coordenadas]]) en columna.

Sea $M_{B, B'}(f) = (\lambda_{i,j}) \in M_{m \times n} (k)$ una [[Matriz asociada a una aplicación lineal]]. Tenemos que $f(v) = f(\lambda_1 v_1 + \dots + \lambda_n v_n)$. Como $f$ es lineal, tenemos que esto es $\lambda_1 f(v_1) + \dots + \lambda_n f(v_n)$. Utilizamos la matriz asociada: $\lambda_1 (\lambda_{1,1} v_1' + \dots + \lambda_{m,1} v_m') + \dots + \lambda_n (\lambda_{1,n} v_1' + \dots + \lambda_{m,n} v_m')$. Esto es $(\lambda_1 \lambda_{1,1} + \dots + \lambda_n \lambda_{1,n}) v_1' + \dots + (\lambda_1 \lambda_{m,1} + \dots + \lambda_n \lambda_{m,n}) v_m'$. Es decir:
$$
f(v)_{B'} = 
\begin{equation}
\begin{pmatrix}
\lambda_1 \lambda_{1,1} + \dots + \lambda_n \lambda_{1,n}\\
\vdots\\
\lambda_1 \lambda_{m,1} + \dots + \lambda_n \lambda_{m,1}
\end{pmatrix}
\end{equation}
$$
Si realizamos la multiplicación de las matrices de la derecha, da eso. (COMPROBAR).

---
### Referencias

[[Aplicación lineal]]