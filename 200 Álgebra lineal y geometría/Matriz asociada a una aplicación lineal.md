### Contenido principal

Sean $V$ y $V'$ dos $k$-ev, $B = \{v_1, \dots, v_n\}$ una base de $V$, $B' = \{v_1', \dots, v_m'\}$ una base de $V'$, $f: V \rightarrow V'$ lineal. Se llama matriz asociada a $f$ en las bases $B$ y $B'$ a la que tiene como columna j-ésima las coordenadas de $f(v_j)$ en la base $B'$. La denotamos $M_{B,B'} (f)$.
Es decir,
$$M_{B,B'} (f) = (f(v_1)_{B'}, \dots, f(v_n)_{B'})$$ Otra forma de escribirlo:
$f(v_1) = \lambda_{1,1} v_1' + \dots + \lambda_{1,m} v_m'$
$\vdots$
$f(v_n) = \lambda_{n,1} v_1' + \dots + \lambda_{n,m} v_m'$
Entonces,
$$
M_{B,B'} (f) =
\begin{equation}
	\begin{pmatrix}
		\lambda_{1,1} && \vdots && \lambda_{n,1} \\
		\vdots && \vdots && \vdots \\
		\lambda_{1,m} && \vdots && \lambda_{n,m}
	\end{pmatrix}
\end{equation}
$$
Observamos que $M_{B,B'} (f) \in M_{m \times n} (K)$. La dimensión de la matriz es $dimV' \times dimV$.

--- 
### Referencias

[[Aplicación lineal]]