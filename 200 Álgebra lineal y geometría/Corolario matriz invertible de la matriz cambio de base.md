### Corolario

Sean $V$ un $K$-ev y $B, B'$ [[Base]] de $V$. Si $B \rightarrow^P B'$ ([[Matriz cambio de base]]), entonces $B' \rightarrow^{P^{-1}} B$ ([[Matriz invertible]]). En particular, las matrices de cambio de base son invertibles.

---
### Demostración

Para demostrar este corolario, es necesario saber que sean $V$ un $K$-ev y $B$ base de $V$. Entonces la matriz cambio de base de $B$ a $B$ es la identidad: $B \rightarrow^I B$.

Sea $B' \rightarrow^Q B$. Tenemos que $B \rightarrow^P B' \rightarrow^Q B$. Por [[Corolario composición de matriz cambio de base]], $B \rightarrow^{QP} B$, pero por la observación anterior, $B \rightarrow^I B$. Así, $QP = I$. Es decir, $Q = P^{-1}$.

---
### Referencias

[[Aplicación lineal]]