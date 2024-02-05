### Lema

Sea $B = \{v_1, \dots, v_n\}$, una base de un $k$-ev. Sea $\{u_1, \dots, u_m\} \subseteq V$ un conjunto de vectores linealmente independiente, entonces podemos sustituir $m$ vectores de $B$ por $\{u_1, \dots, u_m\}$ y obtener una nueva base de $V$. En particular $m \le n$.

Aunque se pueda hacer la sustitución, esta no se puede realizar de cualquier forma.

---
### Demostración

Razonamos por inducción sobre $m$. Supongamos $m=1$. Queremos ver que podemos sustituir un $v_i$ por $u_i$ y obtener una base de $V$. Como $B$ es base, $\exists \lambda_1, \dots, \lambda_n \in K$ tal que $u_1 = \lambda_1 v_1 + \dots + \lambda_n v_n$. Además, como $\{u_1\}$ es linealmente independiente $\implies$ $u_1 \not = 0 \implies \exists i$ tal que $\lambda_i \not = 0$.
Sin pérdida de generalidad, podemos suponer que $\lambda_1 \not = 0$. Entonces $\lambda_i^{-1} u_1 = v_1 + \lambda_i^{-1} \lambda_2 v_2 + \dots + \lambda_i^{-1} \lambda_n v_n$, luego $v_1 = \lambda_i^{-1} u_1 - \lambda_i^{-1} \lambda_2 v_2 - \dots - \lambda_i^{-1} \lambda_n v_n$. Tenemos $v_1$ como combinación lineal de $\{u_1, v_2, \dots, v_n\}$. Vamos a ver que $\{u_1, v_2, \dots, v_n\}$ es base.

¿Es $\{u_1, v_2, \dots, v_n\}$ linealmente independiente ([[Independencia lineal]])? Supongamos que $\mu_1 u_1 + \mu_2 v_2 + \dots + \mu_n v_n = 0$. Queremos ver que $\mu_1 = \dots = \mu_n = 0$. Tenemos $\mu_1 (\lambda_1 v_1 + \dots + \lambda_n v_n) + \mu_2 v_2 + \dots + \mu_n v_n = 0$, esto es, $\mu_1 \lambda_1 v_1 + (\mu_1 \lambda_2 + \mu_2)v_2 + \dots + (\mu_1 \lambda_n + \mu_n) v_n = 0$. Lo que nos lleva a:
$$ \begin{cases}   \mu_1 \lambda_1 = 0\\   \mu_1 \lambda_2 + \mu_2 = 0\\   \mu_1 \lambda_n + \mu_n = 0   \end{cases} $$
Previamente hemos supuesto que $\lambda_1 \not = 0$, de lo que sigue que $\mu_1 = 0$, de lo que sigue que $\mu_n = 0, \forall n$. Así que ya sabemos que $\{u_1, v_2, \dots, v_n\}$ es linealmente independiente. Sólo queda saber que es sistema generador (POR DEMOSTRAR).

Visto que se cumple para $m = 1$, vamos a asumir que se cumpla para $m>1$ y el resultado es cierto cuando el conjunto linealmente independiente tiene cardinal $<m$. Sin pérdida de generalidad, podemos suponer que $\{u_1, \dots, u_{m-1}, v_{m+1}, \dots, v_n\}$ es base de $V$. Queremos ver que en esta base podemos añadir $u_m$ a cambio de un $v$ y obtener una nueva base. Tenemos que: $u_m = \lambda_1 u_1 + \dots + \lambda_{m-1} u_{m-1} + \lambda_m v_m + \dots + \lambda_n v_n$ para algunos $\lambda_i \in K$. Además, $\exists i$ tal que $\lambda_i \not = 0$ (en caso contrario, $u_m$ es combinación lineal de $\{u_1, \dots, u_m\}$ lo cual es absurdo dado que $\{u_1, \dots, u_m\}$ es linealmente independiente). Sin pérdida de generalidad podemos suponer que $\lambda_m \not = 0$.

Se tiene que $\{u_1, \dots, u_m, v_{m+1}, \dots, v_n\}$ es base de $V$ (POR DEMOSTRAR).

---
### Referencias
[[Base]]
[[Espacio vectorial]]
[[Independencia lineal]]
[[Sistema generador]]
