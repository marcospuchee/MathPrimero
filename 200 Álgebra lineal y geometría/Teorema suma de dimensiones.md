### Enunciado Teorema

Sea $V$ un $k$-ev. Sean $U, W$ subespacios ([[Subespacio vectorial]]) de $V$, entonces $dim(U+W) = dimU + dimW - dim(U \cap W)$ ([[Dimensión de un espacio vectorial]])

---
### Demostración

Sea $\{u_1, \dots, u_t\}$ base de $U \cap W$. La prolongamos a $\{u_1, \dots, u_t, u_{t+1}, \dots, u_r\}$ [[base]] de $U$ y también a $\{u_1, \dots, u_t, w_{t+1}, \dots, w_s\}$ base de $W$. De esto extraemos que $t = dimU\cap W, r = dimU, s = dimW$. Hay que probar que: $B_u \cup B_W = \{u_1, \dots, u_t, u_{t+1}, \dots, u_r, w_{t+1}, \dots, w_s\}$ es base de $U+W$, lo que implica que $dimU+W = |B_U \cup B_W| = r+s-t$.
##### ¿$B_U \cup B_W$ es linealmente independiente?
Supongamos que $\lambda_1 u_1 + \dots + \lambda_t u_t + \dots + \lambda_r u_r + \mu_{t+1} w_{t+1} + \dots + \mu_s w_s = 0$ para algunos $\lambda_i, \mu_j \in K$. Queremos ver que $0 = \lambda_i = \mu_j, \forall i,j$. Tenemos que $\lambda_1 u_1 + \dots + \lambda_r u_r = -\mu_{t+1} w_{t+1} - \dots - \mu_s w_s$. Como todo esto pertenece a $U \cap W$, podemos afirmar que cualquiera de sus partes (en este caso la derecha) se puede escribir como [[combinación lineal]] del sistema generador ([[Sistema generador de un espacio vectorial]]) de $U \cap W$:
$-\mu_{t+1} w_{t+1} - \dots - \mu_s w_s = \alpha_1 u_1  \dots + \alpha_t u_t$ para algunos $\alpha_i \in K$. Entonces, $\alpha_{t+1}  w_{t+1} + \dots + \alpha_t u_t + \mu_{t+1} w_{t+1} + \dots + \mu_s w_s = 0$, lo que nos lleva a una combinación lineal de vectores de la base de $W$. Por tanto, $\alpha_1 = \dots = \alpha_t = \mu_{t+1} = \dots = \mu_s = 0$.
Ahora que $\mu_i = 0, \forall i, \lambda_1 u_1 + \dots + \lambda_r u_r = 0 \implies \lambda_1 = \dots = \lambda_r = 0$. Por tanto, $B_U \cup B_W$ es linealmente independiente, lo que implica que es una base de $U+W$.

##### ¿$B_U \cup B_W$ es sistema generador de $U+W$?
Sea $x \in U+W$, entonces $x=u+w$ para algunos $u \in U, w \in W$. 
Como $u \in U$, $u = \lambda_1 u_1 + \dots + \lambda_t u_t + \lambda_{t+1} u_{t+1} + \dots + \lambda_r u_r$ para algunos $\lambda_i \in K$. 
Como $w \in W, w = \mu_1 u_1 + \dots + \mu_t u_t + \mu_{t+1} w_{t+1} + \dots + \mu_s w_s$ para algunos $\mu_i \in K$.
Entonces, $x = u+w = (\lambda_1 + \mu_1)u_1 + \dots + (\lambda_t + \mu_t) u_t + \lambda_{t+1}u_{t+1} + \dots + \lambda_r u_r + \mu_{r+1} w_{r+1} + \dots + \mu_s w_s$, que es combinación lineal de $B_U \cup B_W$. Por lo tanto, $B_U \cup B_W$ es sistema generador ([[Sistema generador de un espacio vectorial]]) de $U+W$.

---
### Referencias

[[Espacio vectorial]]

19-10-23 Álgebra lineal.
23-10-23 Álgebra lineal (Práctica).