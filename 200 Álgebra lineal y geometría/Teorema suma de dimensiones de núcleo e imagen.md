### Enunciado Teorema

Sea $f: V \rightarrow V'$ lineal. Entonces $dimV = dim(Kerf) + dim(Imf)$.

---
### Demostración

Sea $\{v_1, \dots, v_m\}$ [[base]] de $Kerf$ ([[Núcleo]]). Como es un conjunto linealmente independiente ([[Independencia lineal]]) de $V$, podemos prolongarlo a base de $V$: $\{v_1, \dots, v_m, v_{m+1}, \dots, v_n\}$ base de $V$. Hay que ver que $\{f(v_{m+1}), \dots, f(v_n) \}$ es base de $Imf$, así tendremos que $dim(Imf) = n-m = dimV - dim(Kerf)$, y la fórmula del enunciado se cumple.

Veamos que $\{f(v_{m+1}), \dots, f(v_n) \}$ es linealmente independiente. Supongamos que $\lambda_{m+1} f(v_{m+1}) + \dots + \lambda_n f(v_n) = 0$ con $\lambda_i \in K, \forall i$. Hay que ver que $\lambda_{m+1} = \dots = \lambda_n = 0$. Tenemos $\lambda_{m+1} f(v_{m+1}) + \dots + \lambda_n f(v_n) = 0 \implies f(\lambda_{m+1}v_{m+1} + \dots + \lambda_n v_n) = 0$ por ser $f$ lineal. Como da $0$, $\lambda_{m+1} v_{m+1} + \dots + \lambda_n v_n \in Kerf = <v_1, \dots v_m> \implies \lambda_{m+1} v_{m+1} + \dots \lambda_n v_n = \lambda_1 v_1 + \dots \lambda_m v_n$. Si lo pasamos todo a un lado, $\lambda_1 v_1 + \dots + \lambda_m v_m - \lambda_{m+1} - v_{m+1} - \dots - \lambda_n v_n = 0$. Esto es una combinación lineal de vectores de la base de $V$, por lo que es linealmente independiente. Así, $\lambda_i = 0, \forall i$, en particular $\lambda_{m+1} = \dots = \lambda_n = 0$.

Veamos que $\{f(v_{m+1}), \dots, f(v_n) \}$ es [[Sistema generador de un espacio vectorial]] de $Imf$. Sea $v' \in Imf$, queremos ver que $v' \in <f(v_{m+1}), \dots, f(v_n)>$. Como $v' \in Imf, \exists v \in V$ tal que $f(v) = v'$. Entonces, dado que $v \in V$ se puede escribir como combinación lineal de su base: $v' = f(v) = f(\mu_1 v_1 + \dots + \mu_m v_m + \mu_{m+1} + v_{m+1} + \dots + \mu_n v_n) =$ $\mu_1 f(v_1) + \dots + \mu_m f(v_m) + \mu_{m+1} f(v_{m+1}) + \dots + \mu_n f(v_n)$, por ser $f$ lineal ([[Prop 1. AL]]). Como $v_1, \dots, v_m \in Kerf, f(v_1), \dots, f(v_m) = 0$. Por tanto, $v' = \mu_{m+1} f(v_{m+1}) + \dots + \mu_n f(v_n)$. Así, tenemos que $v' = <f(v_{m+1}), \dots, f(v_n)>$.


---
### Referencias

[[Aplicación lineal]]
[[Dimensión de un espacio vectorial]]

https://www.youtube.com/watch?v=PNXU10GDZgc&list=PLxt0Hgnl0gCWiRspcpvoyC3ReYfXDEApd&index=11&ab_channel=alexmoqui