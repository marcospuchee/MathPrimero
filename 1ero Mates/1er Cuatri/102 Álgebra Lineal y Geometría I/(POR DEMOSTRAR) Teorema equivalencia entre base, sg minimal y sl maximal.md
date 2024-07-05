### Enunciado Teorema

Sean $V$ un $k$-ev f.g ([[Espacio vectorial finitamente generado]]) y $S \subseteq V$. Son equivalentes:
1) $S$ es base. [[Base]]
2) $S$ es [[Sistema generador minimal]]
3) $S$ es [[Sistema libre maximal]]

---
### Demostración

##### S base $\implies$ $S$ sistema generador minimal
Sea $S = \{v_1, \dots, v_n\}$ un base, $S$ es sistema generador. Por tanto, hay que ver que ningún subconjunto propio de $S$ sea sistema generador. Sin pérdida de generalidad, basta ver que $\{v_1, \dots, v_{n-1}\}$ no es sistema generador. Supongamos por reducción al absurdo que $\{v_1, \dots, v_{n-1}\}$ es sistema generador. Entonces, $v_n = \lambda_1 v_1 + \dots + \lambda_{n-1} v_{n-1}$ para algunos $\lambda_1, \dots, \lambda_{n-1} \in K$. Esto implica que $\lambda_1 v_1 + \dots + \lambda_{n-1} v_{n-1} - v_n = 0$, así tendríamos que $S$ es linealmente dependiente (contradicción).

##### Acabar la demostración.


---
### Referencias
[[Espacio vectorial]]