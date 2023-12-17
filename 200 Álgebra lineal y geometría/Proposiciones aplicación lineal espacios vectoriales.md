### Proposición

Sea $f: V \rightarrow V'$ lineal, entonces:
1. $f$ es inyectiva ([[Aplicaciones inyectivas, sobreyectivas y biyectivas]]) $\iff Kerf = \{0\}$.
2. Si $U \le V$, entonces $f(U) \le V'$. Si $U' \le V'$, entonces $f^{-1}(U) \le V$.
3. $Kerf \le V$ y $Imf \le V'$.
4. Si $U = <u_1, \dots, u_m>$, entonces $f(U) = <f(u_1), \dots, f(u_m)>$.


---
### Demostración

### 1.
$\rightarrow$. Vemos que $0 \subseteq Kerf$ ya que $f(0) = 0$ ([[Prop 1. AL]]). Vamos a ver que $Kerf \subseteq \{0\}$. Sea $u \in Kerf$, hay que ver que $u = 0$. Como $u \in Kerf, f(u) = 0$. Como $f(0) = 0$ y $f$ es inyectiva, por definición $u=0$.
$\leftarrow$. Hay que ver que si $f(u) = f(v)$ con $u,v \in V$, entonces $u = v$. $f(u) = f(v) \implies f(u) - f(v) = 0$.
Por ser $f$ lineal, $f(u) - f(v) = f(u-v) = 0$. Por hipótesis, $u-v \in Kerf = \{0\} \implies u-v = 0 \implies u=v$.
### 2.
¿$f(U) \le V'$? Hay que ver que si $v_1, v_2 \in f(U), \lambda, \mu \in K$, entonces $\lambda v_1 + \mu v_2 \in f(U)$.
Como $v_1 \in f(U), \exists u_1 \in U$ tal que $f(u_1)=v_1$. Como $v_2 \in f(U), \exists u_2 \in U$ tal que $f(u_2) = v_2$.
Así, $\lambda v_1 + \mu v_2 = \lambda f(u_1) + \mu f(u_2) = f(\lambda u_1 + \mu u_2)$. Como $\lambda u_1 + \mu u_2 \in U, f(\lambda u_1 + \mu u_2) \in f(U)$.
La segunda afirmación queda por demostrar, de manera análoga.
### 3.
Se sigue de (ii). $Kerf = f^{-1}(\{0\})$, $\{0\} \le V'$. Por (ii (la parte por demostrar)), $f^{-1}(\{0\}) \le V$.
$Imf = f(V)$ y $f(V) \le V'$ por (ii).
### 4.
Sabemos que $U = <u_1, \dots, u_m>$ ([[Subespacio generado]]) = $\{\lambda_1 u_1 + \dots \lambda_m u_m | \lambda_i \in K, \forall i\}$. Entonces, $f(U) = \{f(u) | u \in U\} = \{f(\lambda_1 u_1 + \dots + \lambda_ mu_m | \lambda_i \in K, \forall i \}$ $= \{\lambda_1 f(u_1) + \dots + \lambda_m f(u_m) | \lambda_i \in K, \forall i \} = <f(u_1), \dots, f(u_m)>$.



---
### Referencias

[[Aplicación lineal]]
[[Aplicaciones inyectivas, sobreyectivas y biyectivas]]
[[Núcleo]]

https://youtu.be/G1cNClFU4_Y?si=POuwbd2bHoRhRnpx