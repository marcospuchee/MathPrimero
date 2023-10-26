### Proposición

Sean $V$ un $k$-ev y $S = \{v_1, \dots, v_n\} \subseteq V$, entonces $S$ es base de $V$ $\iff$ todo vector de $V$ se puede expresar de forma única como [[combinación lineal]] de vectores de $S$.
 
---
### Demostración

##### Demostración a la derecha.
Partimos de que $S$ es base de $V$. $S$ base de $V \implies S$ sistema generador de $V$ ([[Sistema generador de un espacio vectorial]]), por lo que todo vector de $V$ es c.l. de vectores de $S$. Sólo queda probar la unicidad.
Sea $v \in V$, supongamos por reducción al absurdo que $v = \lambda_1 v_1 + \dots + \lambda_n v_n = \mu_1 v_1 + \dots + \mu_n v_n$. Queremos ver que $\lambda_i = \mu_i, \forall i$. Tenemos que: $\lambda_1 v_1 + \dots + \lambda_n v_n = \mu_1 v_1 + \dots + \mu_n v_n \implies (\lambda_1 - \mu_1)v_1 + \dots + (\lambda_n - \mu_n)v_n = 0$. Sin embargo, por ser $S$ base de $V$, es linealmente independiente ([[Independencia lineal]]), y por tanto $\lambda_i - \mu_i = 0 \implies \lambda_i = \mu_i, \forall i$.

##### Demostración a la izquierda.
Tenemos que $S$ es sistema generador. Hay que ver que también sea linealmente independiente. Es decir, hay que ver que si (1) $\lambda_1 v_1 + \dots + \lambda_n v_n = 0$, entonces $\lambda_1 = \dots = \lambda_n = 0$, o bien (2) $0v_1 + \dots + 0v_n = 0$. Por la hipótesis, sólo hay una expresión de $0$ como combinación lineal de vectores de $S$, lo que quiere decir que $\lambda_i = 0, \forall i$.


---
### Referencias
[[Espacio vectorial]]
[[Base]]

11-10-23 Álgebra