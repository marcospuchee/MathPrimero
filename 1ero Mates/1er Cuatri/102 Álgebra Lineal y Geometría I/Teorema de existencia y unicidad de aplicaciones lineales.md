### Enunciado Teorema

Sean $V, V'$ dos $k$-ev. Sean $B = \{v_1, \dots v_n\}$ una base de $V$ y $v_1', \dots, v_n' \in V'$. Entonces existe una única $f: V \rightarrow V'$ lineal tal que $f(v_i) = v_i', \forall i$.

---
### Demostración

##### Unicidad
Vamos a empezar viendo que como mucho hay una aplicación lineal que cumple las condiciones del teorema. Supongamos que $f: V \rightarrow V'$ lineal tal que $f(v_i) = v_i', \forall i$. Sea $v \in V$, sabemos que $\exists ! \lambda_1, \dots, \lambda_n \in K$ tales que $v = \lambda_1 v_1 + \dots + \lambda_n v_n$. Entonces $f(v) = f(\lambda_1 v_1 + \dots + \lambda_n v_n) = \lambda_1 f(v_1) + \dots + \lambda_n f(v_n)$, esto es lo mismo que $\lambda_1 v_1' + \dots + \lambda_n v_n'$. Hemos visto que si $f: V \rightarrow V'$ lineal y $f(v_i) = v_i', \forall i$, entonces $f: V \rightarrow V'$ con $v \rightarrow \lambda_1 v_1' + \dots + \lambda_n v_n'$ y
$$
\begin{equation}
	v_B=
	\begin{pmatrix}
		\lambda_1 \\
		\vdots \\
		\lambda_n
	\end{pmatrix}
\end{equation}
$$
es las coordenadas de $v$ en la [[Base]] $b$

##### Existencia
Veamos ahora que $f: V \rightarrow V'$ con $v \rightarrow \lambda_1 v_1' + \dots + \lambda_n v_n'$ y las [[Coordenadas]] de $v_B = (\lambda_1, \dots, \lambda_n)$. Hay que ver que:
1. ¿$f$ lineal? Sean $v_B = (\lambda_1, \dots, \lambda_n), v_B' = (\lambda_1', \dots, \lambda_n')$. Entonces, vamos a ver cuánto es $f(\lambda v + \mu v')$. $\lambda v + \mu v' =$ $\lambda(\lambda_1 v_1 + \dots + \lambda_n v_n) + \mu (\lambda_1' v_1 + \dots + \lambda_n' v_n) =$ $(\lambda \lambda_1 + \mu \lambda_1')v_1 + \dots + (\lambda \lambda_n + \mu \lambda_n') v_n$. Es decir, $(\lambda v + \mu v')_B = (\lambda \lambda_1 + \mu \lambda_1', \dots, \lambda \lambda_n + \mu \lambda_n')$. Por tanto, $f(\lambda \lambda_1 + \mu \lambda_1') v_1' + \dots + (\lambda \lambda_n + \mu \lambda_n')v_n'$, ya que la aplicación manda las coordenadas a las $v_i'$. Por otra parte, queremos ver cuánto es $\lambda f(v) + \mu f(v') =$ $\lambda(\lambda_1 v_1' + \dots + \lambda_n v_n') + \mu(\lambda_1' v_1' + \dots + \lambda_n' v_n') =$ $(\lambda \lambda_1 + \mu \lambda_1')v_1' + \dots + (\lambda \lambda_n + \mu \lambda_n') v_n'$. Hemos llegado a lo mismo que teníamos arriba, con lo cual, $f$ es lineal.
2. ¿$f(v_i) = v_i', \forall i \in \{1, \dots, n\}$? Hay que observar las coordenadas de $v_i$. $v_{i_B} = \{0, \dots, 1, \dots, 0\}$. El $1$ coincide con la posición $i$. Por la definición de $f$, $v_i$ es multiplicar las coordenadas por su respectivo $v_i'$, por tanto, $f(v_i) = v_i'$.


---
### Referencias

[[Aplicación lineal]]