### Proposición

Sean $V$ un $k$-[[Espacio vectorial finitamente generado]] y $U \not = \{0\}$ [[Subespacio vectorial]] de $V$. Entonces, $U$ es finitamente generado y $dimU \le dimV$. Además, $dimU = dimV \iff U = V$.

---
### Demostración

Sea $n=dimV$. Sabemos que todo sistema libre de $V$ tiene cardinal $\le n$ ([[Corolario de los cardinales]]). Sea $0 \not = u_1 \in U$. $\{u_1\}$ es sistema libre. Por el [[(POR DEMOSTRAR) Teorema equivalencia entre base, sg minimal y sl maximal]], si $\{u_1\}$ es [[Sistema libre maximal]], de $U$, entonces es [[Base]], y $dimU = 1 \le n$.
Si $\{u_1\}$ no es maximal, entonces $\exists \{u_2\} \in U$ tal que $\{u_1, u_2\}$, que es sistema libre. Si es maximal, entonces $dimU = 2 \le n$. Si no lo es, repetimos el proceso. Como todo sistema libre tiene $\le n$ vectores, en $\le n$ pasos, llegamos a un sistema libre maximal. Esto prueba que $U$ es [[Espacio vectorial finitamente generado]] y $dim U \le dimV$.

#### $dimU = dimV \iff U = V$
$\leftarrow$ es obvio.
$\rightarrow$. Supongamos que $dimU = dimV = n$. Entonces $\exists S \subseteq U$ que es sistema libre maximal de $U$ con $|S| = n$. En particular, $S$ es un sistema libre (visto como subconjunto de $V$). Además $|S| = n =dimV$. Por [[(POR DEMOSTRAR) Prop 4. EV.]], $S$ es base de $V$. Entonces $U = <S> = V$.

---
### Referencias

[[Espacio vectorial]]

19-10-23. Álgebra lineal.