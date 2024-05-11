
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-22, 18:52

```ad-lemma
Sea $(A, V, +)$ [[espacio afín]].
1. Sean $P, Q \in A \land W \le V$. $Q \in W_P$ ([[variedad afín]]) $\iff W_P = W_Q$.
2. $U \le W \le V \land P \in A \implies U_p \subseteq W_p$.
3. Sean $W_P, W_Q \subseteq A$ variedades afines tales que $U_P \subseteq W_Q \implies U \le V$.
4. Sea $L \subseteq A$ variedad afín. Entonces $W = \{\vec{PQ}: P, Q \in L \} =$ es subespacio director de $L$, es decir, $L = W_p$ para algún $P \in L$.
```


```ad-proof
$(i).$
$\rightarrow$. Sup. $Q \in W_p$. Sea $X \in W_p$, ¿$X \in W_Q$? Tenemos $\vec{QX} = \vec{QP} + \vec{PX} \in W \implies$ $W_p \subseteq W_Q$. Análogamente, $W_Q \subseteq W_P$.
$\leftarrow$. Sup. $W_P = W_Q$, entonces $Q \in W_Q = W_P$.

$(ii).$
Sup. $U \le W \le V \land P \in A$. Sea $X \in U_P \implies \vec{PX} \in U \le W \implies$ $X \in W_P$.

$(iii).$
Notemos que $P \in U_P \subseteq W_Q$. Por $(i)$, tenemos que $W_P = W_Q$. Sea $u \in U$. Tenemos $P + u \in U_P \subseteq W_Q = W_P$. Por tanto, $R = P+u = P+w$ para algún $w \in W$. Luego $u = \vec{PR} = w \in W$. Así, $U \le W$.

$(iv).$
Podemos escribir $L = (W')_P$, donde $W' \le V$ y $P \in L$. Veamos que $W' = W$.
$\subseteq$. Sea $w' \in W'$. Entonces $Q = P + w' \in L \implies w' = \vec{PQ} \in W$. Así, $W' \subseteq W$.
$\supseteq$. Sea $w \in W$, es decir, $w = \vec{QR}$ donde $Q, R \in L$. Tenemos:
$$\vec{QR} = \vec{QP} + \vec{PR} = - \vec{PQ} + \vec{PR}.$$
Sin embargo, $-\vec{PQ} \in W'$ y $\vec{PR} \in W'$, por tanto, $\vec{QR} \in W'$. Así, $W \subseteq W'.$
```

**Tema:** [[Espacios afines]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Propiedades que cumplen las variedades afines
Reverso:Sea $(A, V, +)$ [[espacio afín]].
1. Sean $P, Q \in A \land W \le V$. $Q \in W_P$ ([[variedad afín]]) $\iff W_P = W_Q$.
2. $U \le W \le V \land P \in A \implies U_p \subseteq W_p$.
3. Sean $W_P, W_Q \subseteq A$ variedades afines tales que $U_P \subseteq W_Q \implies U \le V$.
4. Sea $L \subseteq A$ variedad afín. Entonces $W = \{\vec{PQ}: P, Q \in L \} =$ es subespacio director de $L$, es decir, $L = W_p$ para algún $P \in L$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060760815-->
END

START
Básico
Anverso: Demostración de que sea $(A, V, +)$ [[espacio afín]].
1. Sean $P, Q \in A \land W \le V$. $Q \in W_P$ ([[variedad afín]]) $\iff W_P = W_Q$.
2. $U \le W \le V \land P \in A \implies U_p \subseteq W_p$.
3. Sean $W_P, W_Q \subseteq A$ variedades afines tales que $U_P \subseteq W_Q \implies U \le V$.
4. Sea $L \subseteq A$ variedad afín. Entonces $W = \{\vec{PQ}: P, Q \in L \} =$ es subespacio director de $L$, es decir, $L = W_p$ para algún $P \in L$.
Reverso: $(i).$
$\rightarrow$. Sup. $Q \in W_p$. Sea $X \in W_p$, ¿$X \in W_Q$? Tenemos $\vec{QX} = \vec{QP} + \vec{PX} \in W \implies$ $W_p \subseteq W_Q$. Análogamente, $W_Q \subseteq W_P$.
$\leftarrow$. Sup. $W_P = W_Q$, entonces $Q \in W_Q = W_P$.

$(ii).$
Sup. $U \le W \le V \land P \in A$. Sea $X \in U_P \implies \vec{PX} \in U \le W \implies$ $X \in W_P$.

$(iii).$
Notemos que $P \in U_P \subseteq W_Q$. Por $(i)$, tenemos que $W_P = W_Q$. Sea $u \in U$. Tenemos $P + u \in U_P \subseteq W_Q = W_P$. Por tanto, $R = P+u = P+w$ para algún $w \in W$. Luego $u = \vec{PR} = w \in W$. Así, $U \le W$.

$(iv).$
Podemos escribir $L = (W')_P$, donde $W' \le V$ y $P \in L$. Veamos que $W' = W$.
$\subseteq$. Sea $w' \in W'$. Entonces $Q = P + w' \in L \implies w' = \vec{PQ} \in W$. Así, $W' \subseteq W$.
$\supseteq$. Sea $w \in W$, es decir, $w = \vec{QR}$ donde $Q, R \in L$. Tenemos:
$$\vec{QR} = \vec{QP} + \vec{PR} = - \vec{PQ} + \vec{PR}.$$
Sin embargo, $-\vec{PQ} \in W'$ y $\vec{PR} \in W'$, por tanto, $\vec{QR} \in W'$. Así, $W \subseteq W'.$
Tags: demostración ÁlgebraI
<!--ID: 1714060760826-->
END
