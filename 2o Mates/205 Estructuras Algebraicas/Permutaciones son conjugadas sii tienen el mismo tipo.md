### Contenido Principal


```ad-theorem
Dos elementos $\sigma, \sigma' \in S_n$ son conjugados ($\exists \tau \in S_n$ tal que $^\tau \sigma = \sigma'$) $\iff$ $\sigma$ y $\sigma'$ tienen el mismo tipo ([[tipo de una permutación]]).
```

^e4fa14

```ad-proof
$\leftarrow$. Sea $\sigma, \sigma' \in S_n$, supongamos que tienen el mismo tipo:
$$\textrm{tipo}(\sigma) = \textrm{tipo}(\sigma') = (l_1, l_2, \dots, l_r)$$
y que dejan $m$ elementos fijos. Podemos escribir:
$$\begin{matrix}
\sigma = (a_1)(a_2) \dots (a_m)(a_{11}, \dots, a_{1l_1}) \dots (a_{r1}, \dots, a_{rl_r}) \\
\sigma' = (b_1)(b_2) \dots (b_m) (b_{11}, \dots, b_{1l_1}) \dots (b_{r1}, \dots, b_{rl_r})
\end{matrix}$$

Notemos que $n = m + l_1 + \dots + l_r$. Por tanto, si tomamos $\tau \in S_n$ con
- $\tau (a_i) = b_i, \, \forall 1 \le i \le n$.
- $\tau (a_{pq}) = b_{pq}$ con $1 \le p \le r$ y $1 \le q \le l$.

se cumple que $^\tau \sigma = \sigma'$.

$\rightarrow$. Corolario de [[forma de todo conjugado de una permutación]].

```

**Tema:** [[Teoría de grupos#10. Conjugación en $S_n$.]]
**Corolario:**

---
### Anki

START
Respuesta anidada
Dos elementos $\sigma, \sigma' \in S_n$ son {{c1::conjugados ($\exists \tau \in S_n$ tal que $^\tau \sigma = \sigma'$)}} $\iff$ $\sigma$ y $\sigma'$ {{c2::tienen el mismo tipo ([[Tipo de una permutación]])}}.
<!--ID: 1727966477285-->
END

START
Básico
Anverso: Demostración de que sos elementos $\sigma, \sigma' \in S_n$ son conjugados ($\exists \tau \in S_n$ tal que $^\tau \sigma = \sigma'$) $\iff$ $\sigma$ y $\sigma'$ tienen el mismo tipo ([[Tipo de una permutación]]).
Reverso: 
$\leftarrow$. Sea $\sigma, \sigma' \in S_n$, supongamos que tienen el mismo tipo:
$$\textrm{tipo}(\sigma) = \textrm{tipo}(\sigma') = (l_1, l_2, \dots, l_r)$$
y que dejan $m$ elementos fijos. Podemos escribir:
$$\begin{matrix}
\sigma = (a_1)(a_2) \dots (a_m)(a_{11}, \dots, a_{1l_1}) \dots (a_{r1}, \dots, a_{rl_r}) \\
\sigma' = (b_1)(b_2) \dots (b_m) (b_{11}, \dots, b_{1l_1}) \dots (b_{r1}, \dots, b_{rl_r})
\end{matrix}$$

Notemos que $n = m + l_1 + \dots + l_r$. Por tanto, si tomamos $\tau \in S_n$ con
- $\tau (a_i) = b_i, \, \forall 1 \le i \le n$.
- $\tau (a_{pq}) = b_{pq}$ con $1 \le p \le r$ y $1 \le q \le l$.

se cumple que $^\tau \sigma = \sigma'$.

$\rightarrow$. Corolario de [[Forma de todo conjugado de una permutación]].
Tags: dem est
<!--ID: 1727966477345-->
END
