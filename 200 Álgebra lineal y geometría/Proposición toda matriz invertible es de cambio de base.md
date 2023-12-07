### Proposición

Sean $V$ un $K$-ev y $B=\{v_1, \dots, v_n\}$ una [[Base]] de $V$. Sea $P \in M_n(K)$ una [[Matriz invertible]]. Entonces:
1) $\exists B'$ base de $V$ tal que $B' \rightarrow^P B$. ([[Matriz cambio de base]])
2) $\exists B''$ base de $V$ tal que $B \rightarrow^P B''$. ([[Matriz cambio de base]])

---
### Demostración

1) Llamamos a las entradas de $P = (P_{i,j})$. Sean $v_1' = P_{1,1} v_1 + \dots + P_{n,1} v_n, \dots, v_n' = P_{1,n} v_1 + \dots + P_{n,n} v_n$. Estamos definiendo los $v_i'$ de forma que sus [[Coordenadas]] en la base $B$ son la $i$-ésima columna de $P, \forall i \in \{1, \dots, n\}$. Si vemos que $B' = \{v_1', \dots, v_n'\}$ es base de $V$, entonces $B' \rightarrow^P B$. Escribimos $v_i', \forall i$ en forma matricial: $$(v_1', \dots, v_n') = (v_1, \dots, v_n) P $$ahora multiplicamos  por la inversa a derecha: $$ (v_1', \dots, v_n')P^{-1} = (v_1, \dots, v_n)  $$cada uno de los vectores $v_1, \dots, v_n$ es una combinación lineal de $\{v_1', \dots, v_n'\}$. Entonces como $\{v_1, \dots, v_n\}$ es base, $V = \langle v_1, \dots, v_n \rangle \subseteq \langle v_1', \dots, v_n' \rangle$, luego $\{v_1', \dots, v_n'\}$ es [[Sistema generador]] de $V$ tal que $|\{v_1', \dots, v_n'\}| \le n = dimV$, luego ??, por [[(POR DEMOSTRAR) Prop 4. EV.]] $\{v_1', \dots, v_n'\}$ es base de $V$.
2) Por la primera afirmación, $\exists B''$ base de $V$ tal que $B'' \rightarrow^{P^{-1}} B$. Por el [[Corolario matriz invertible de la matriz cambio de base]], $B \rightarrow^{(P^{-1})^{-1}} \rightarrow B''$. Finalmente, $(P^{-1})^{-1} = P$. Por tanto, $B \rightarrow^P B''$.

---
### Referencias

[[Aplicación lineal]]