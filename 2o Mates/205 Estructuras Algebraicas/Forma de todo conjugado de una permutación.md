### Contenido Principal

```ad-proposition
Sean $\sigma, \tau \in S_n$. Supongamos que $\sigma = (a_{11}, \dots, a_{1l_1})\dots (a_{r1}, \dots, a_{rl_r})$. Entonces,
$$^\tau \sigma = (\tau(a_{11}), \dots, \tau(a_{1l_1})) \circ \dots \circ (\tau(a_{r1}), \dots, \tau(a_{rl_r})).$$
```

^90f93f

```ad-proof
En el caso particular de que $\sigma$ sea un $r$-ciclo, $\sigma = (a_1, \dots, a_r)$. Queremos ver que $^\tau \sigma = (\tau(a_1), \dots, \tau(a_r))$. Por notación, vamos a llamar a $^\tau \sigma = \tau \sigma \tau^{-1}$ y a $(\tau(a_1), \dots, \tau(a_r)) = g$.

Vamos a comprobar que $\forall 1 \le i \le n$, se cumple que $\tau \sigma \tau^{-1}(i) = g(i)$. Distinguimos casos:
1. $i \in \{\tau(a_1), \dots, \tau(a_{r-1}) \}$. Es decir, $i = \tau (a_j)$ para $1 \le j \le r-1$. 
Por un lado, $g(i) = g(\tau(a_j)) = \tau(a_{j+1})$. 
Por otro lado, $\tau \sigma \tau^{-1}(i) = \tau \sigma \tau^{-1} (\tau (a_j)) = \tau \sigma (a_j) = \tau(a_{j+1})$.

2. $i = \tau(a_r)$. Entonces, $g(i) = g(\tau (a_r)) = \tau(a_1)$, y $\tau \sigma \tau^{-1} (i) = \tau \sigma \tau^{-1}(\tau(a_r)) = \tau \sigma (a_r) = \tau(a_1)$.

3. $i \notin \{\tau (a_1), \dots, \tau(a_r) \} \equiv \tau^{-1}(i) \notin \{a_1, \dots, a_r \}$. Entonces, $g(i) = i$, y $\tau \sigma \tau^{-1}(i) = \tau \tau^{-1}(i) = i$.


En el caso general,
$$\begin{eqnarray}
^\tau \sigma &=& \tau(a_{11}, \dots, a_{1l_1}) \circ \dots \circ (a_{r1}, \dots, a_{rl_r}) \tau^{-1} \\
&=& \tau(a_{11}, \dots, a_{1l_1})\tau^{-1} \tau (a_{21}, \dots, a_{2l_2})\tau^{-1} \dots \\
&=& (\tau(a_{11}), \dots, \tau(a_{1l1})) \dots (\tau(a_{r1}), \dots, \tau(a_{rl_r}))
\end{eqnarray}$$
y podemos aplicar el resultado particular.
```

**Tema:** [[Teoría de grupos#10. Conjugación en $S_n$.]]

---
### Anki

START
Básico
Anverso: Qué forma tiene todo conjugado de una permutación?
Reverso: Sean $\sigma, \tau \in S_n$. Supongamos que $\sigma = (a_{11}, \dots, a_{1l_1})\dots (a_{r1}, \dots, a_{rl_r})$. Entonces,
$$^\tau \sigma = (\tau(a_{11}), \dots, \tau(a_{1l_1})) \circ \dots \circ (\tau(a_{r1}), \dots, \tau(a_{rl_r})).$$
<!--ID: 1727966477863-->
END

START
Básico
Anverso: Demostración de que sean $\sigma, \tau \in S_n$. Supongamos que $\sigma = (a_{11}, \dots, a_{1l_1})\dots (a_{r1}, \dots, a_{rl_r})$. Entonces,
$$^\tau \sigma = (\tau(a_{11}), \dots, \tau(a_{1l_1})) \circ \dots \circ (\tau(a_{r1}), \dots, \tau(a_{rl_r})).$$
Reverso: En el caso particular de que $\sigma$ sea un $r$-ciclo, $\sigma = (a_1, \dots, a_r)$. Queremos ver que $^\tau \sigma = (\tau(a_1), \dots, \tau(a_r))$. Por notación, vamos a llamar a $^\tau \sigma = \tau \sigma \tau^{-1}$ y a $(\tau(a_1), \dots, \tau(a_r)) = g$.

Vamos a comprobar que $\forall 1 \le i \le n$, se cumple que $\tau \sigma \tau^{-1}(i) = g(i)$. Distinguimos casos:
1. $i \in \{\tau(a_1), \dots, \tau(a_{r-1}) \}$. Es decir, $i = \tau (a_j)$ para $1 \le j \le r-1$. 
Por un lado, $g(i) = g(\tau(a_j)) = \tau(a_{j+1})$. 
Por otro lado, $\tau \sigma \tau^{-1}(i) = \tau \sigma \tau^{-1} (\tau (a_j)) = \tau \sigma (a_j) = \tau(a_{j+1})$.

2. $i = \tau(a_r)$. Entonces, $g(i) = g(\tau (a_r)) = \tau(a_1)$, y $\tau \sigma \tau^{-1} (i) = \tau \sigma \tau^{-1}(\tau(a_r)) = \tau \sigma (a_r) = \tau(a_1)$.

3. $i \notin \{\tau (a_1), \dots, \tau(a_r) \} \equiv \tau^{-1}(i) \notin \{a_1, \dots, a_r \}$. Entonces, $g(i) = i$, y $\tau \sigma \tau^{-1}(i) = \tau \tau^{-1}(i) = i$.


En el caso general,
$$\begin{eqnarray}
^\tau \sigma &=& \tau(a_{11}, \dots, a_{1l_1}) \circ \dots \circ (a_{r1}, \dots, a_{rl_r}) \tau^{-1} \\
&=& \tau(a_{11}, \dots, a_{1l_1})\tau^{-1} \tau (a_{21}, \dots, a_{2l_2})\tau^{-1} \dots \\
&=& (\tau(a_{11}), \dots, \tau(a_{1l1})) \dots (\tau(a_{r1}), \dots, \tau(a_{rl_r}))
\end{eqnarray}$$
y podemos aplicar el resultado particular.
Tags: dem est
<!--ID: 1727966477916-->
END
