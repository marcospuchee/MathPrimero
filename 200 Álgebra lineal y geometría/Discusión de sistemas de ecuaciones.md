### Contenido principal

Sea $AX = B$ un sistema de ecuaciones lineales, de la forma explicada en [[Forma matricial de un sistema de ecuaciones]], sea $H$ la forma normal ([[Forma normal de una matriz]]) de la matriz ampliada del sistema: $(A|B)$. Pueden pasar dos casos:
1. $H$ tiene un pivote ([[Pivote de una matriz]]) en la última columna. Tenemos una ecuación $0 = 1$, luego SI ([[Posibles soluciones de un sistema de ecuaciones]]).
2. $H$ no tiene un pivote en la última columna. Dos subcasos:
	1. $H$ tiene un pivote en las columnas anteriores. SCD.
	2. $H$ no tiene pivote en alguna de las columnas anteriores. Reordenando las incógnitas si fuese necesario, podemos suponer que $H$ tiene pivotes en las $t$ primeras columnas y no los tiene en ninguna de las siguientes, luego:$$H =
\begin{equation}
	\begin{pmatrix}
		1 && ... && ... && 0 && a_{1,t+1} && ... && a_{1, n} && b_1\\
		0 && 1 && ... && 0 && a_{2,t+1} && ... && a_{2, n} && b_2\\
		0 && 0 && 1 && ... && ... && ... && ... && b_3\\
		... && ... && ... && ... && ... && ... && ... && ...\\
		0 && 0 && ... && 1 && a_{t, t+1} && ... && a_{t,n} && b_t\\
		0 && 0 && 0 && 0 &&0 && 0 && 0&&0
	\end{pmatrix}
\end{equation}
$$ por lo que las soluciones son:

$$
\begin{equation}
	\begin{matrix}
	x_1 = b_1 - a_{1,t+1}\lambda_{t+1} - ... - a_{1,n}\lambda_{n}\\
	...\\
	x_t = b_t - a_{t,t+1}\lambda_{t+1} - ... - a_{t,n}\lambda_{n}\\
	...\\
	x_{t+1} = \lambda_{t+1}\\
	...\\
	x_n = \lambda_n
	\end{matrix}
\end{equation}
$$



--- 
### Referencias
[[Sistemas de ecuaciones lineales]]