### Proposición

Sea $f: V \rightarrow V'$ lineal, entonces:
1. Sea $\{v_1, \dots, v_n\}$ un [[Sistema generador]] de $V$, $f$ es sobreyectiva $\iff \{f(v_1), \dots, f(v_n)\}$ es sistema generador de $V'$.
2. Sea $\{v_1, \dots, v_n\}$ una [[Base]] de $V$, entonces $f$ es inyectiva $\iff \{f(v_1), \dots, f(v_n)\}$ es linealmente independiente ([[Independencia lineal]]).
3. Sea $\{v_1, \dots, v_n\}$ una base de $V$, entonces $f$ es biyectiva $\iff \{f(v_1), \dots, f(v_n) \}$ es base de $V'$.

---
### Demostración

### iii)
$\rightarrow$. Aplicando i) y ii), lo demostramos.
$\leftarrow$. Aplicando i) y ii), lo demostramos.
### i)
$\rightarrow$. Sea $v' \in V'$, hay que ver que $v'$ es combinación lineal de $\{f(v_1), \dots, f(v_n) \}$. Como $f$ es sobreyectiva, $\exists v \in V$ tal que $f(v) = v'$ . Como $\{v_1, \dots v_n\}$ es sistema generador de $V$, $\exists \lambda_1, \dots, \lambda_n \in K$ tal que $v = \lambda_1 v_1 + \dots \lambda_n v_n$. Así, $v' = f(v) = f(\lambda_1 v_1 + \dots + \lambda_n v_n) =$ $\lambda_1 f(v_1) + \dots + \lambda_n v_n$.
$\leftarrow$. Queremos ver que si $v' \in V', \exists v \in V$ tal que $f(v) = v'$. Como $\{f(v_1), \dots, f(v_n) \}$ es sistema generador de $V'$, $v' = \lambda_1 f(v_1) + \dots + \lambda_n f(v_n)$ para algunos $\lambda_i \in K$. Así, tenemos que $v' = \lambda_1 f(v_1) + \dots + \lambda_n f(v_n) = f(\lambda_1 v_1 + \dots + \lambda_n v_n)$. Sea $v = \lambda_1 v_1 + \dots + \lambda_n v_n$, entonces ya lo tenemos demostrado.
### ii)
$\rightarrow$. Queremos ver que si $\lambda_1 f(v_1) + \dots + \lambda_n f(v_n) = 0$ entonces $\lambda_i = 0, \forall i$. Tenemos que $0 = \lambda_1 f(v_1) + \dots + \lambda_n f(v_n) = f(\lambda_1 v_1 + \dots + \lambda_n v_n)$. $\lambda_1 v_1 + \dots + \lambda_n v_n \in Kerf$, como $f$ inyectiva ([[Proposiciones aplicación lineal espacios vectoriales]]), $Kerf = \{0\}$, así, $\lambda_1 v_1 + \dots + \lambda_n v_n = 0$. Dado que $\{v_1, \dots, v_n\}$ base, entonces es linealmente independiente, por lo que $\lambda_i = 0, \forall i$.
$\leftarrow$. Queremos ver que $Kerf = \{0\}$. Sea $v \in Kerf$, queremos ver que $v = 0$. Como $\{v_1, \dots, v_n\}$ es sistema generador de $V$, $v= \lambda_1 v_1 + \dots + \lambda_n v_n$ para algunos $\lambda_i \in K$. Como $v \in Kerf$, $f(v) = 0 = f(\lambda_1 v_1 + \dots + \lambda_n v_n) = \lambda_1 f(v_1) + \dots + \lambda_n f(v_n)$. Como $\{f(v_1), \dots, f(v_n)\}$ es linealmente independiente, $\lambda_i = 0, \forall i$. Tomando la definición de $v = \lambda_1 v_1 + \dots + \lambda_n v_n$, tenemos que $\lambda_i = 0, \forall i$, por lo que $v = 0$.

---
### Referencias

[[Aplicaciones inyectivas, sobreyectivas y biyectivas]]
[[Aplicación lineal]]