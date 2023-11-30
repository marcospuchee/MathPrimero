### Corolario

Sea $f: V \rightarrow V'$ lineal.
1. Si $f$ es inyectiva, entonces $dimV \le dimV'$
2. Si $f$ es sobreyectiva, entonces $dimV \ge dimV'$.

---
### Demostración

1. Sea $f': V \rightarrow f(V)$ con $v \rightarrow f(v)$. Como $f$ es lineal e inyectiva, $f'$ es lineal, inyectiva, y además se cumple que es sobreyectiva. Por el [[Corolario clasificación de los espacios vectoriales finitamente generados]], $dimV = dimf(V)$. Sabemos que si $f$ es lineal, $f(V)$ es un subespacio de $V'$, por tanto $dimf(V) \le dimV'$ ([[Teorema suma de dimensiones de núcleo e imagen]] ?).
2. Sea $B$ una base de $V$. Como $f$ es sobreyectiva, por (i) de [[Proposición sg, sl y base con aplicaciones lineales]], $f(B)$ es [[Sistema generador de un espacio vectorial]] de $V'$. Por tanto $dimV = |B| \ge |f(B)| \ge dimV'$ según [[Corolario de los cardinales]].

---
### Referencias

[[Aplicación lineal]]