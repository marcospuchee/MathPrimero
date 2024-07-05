
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-16, 10:16

```ad-theorem
$(E, V, +)$ [[espacio afín euclídeo]]. Sean $U_P, W_Q \subseteq E$ [[variedad afín]]. Entonces,
$$d(U_P, W_Q) = d(P, (W+U)_Q).$$
```


```ad-proof
Sean $X \in U_P, Y \in W_Q$ cualesquiera. Tenemos $\vec{XY} = \vec{XP} + \vec{PQ} + \vec{QY}$. Ahora:
$$
\begin{eqnarray}
P + \vec{XY} &=& P + (\vec{XP} + \vec{PQ} + \vec{QY}) = (P + \vec{PQ}) + (\vec{XP} + \vec{QY}) \\
&=& Q + (\vec{XP} + \vec{QY}).
\end{eqnarray}
$$
Cabe destacar que $\vec{XP} \in U$ y $\vec{QY} \in W$. Denotamos $Z = Q + (\vec{XP} + \vec{QY})$, tenemos que $Z \in (W+U)_Q$, que por notación, $(W+U)_Q = L$. Sin embargo, $P + \vec{XY} = Z \in L$, luego $\vec{XY} = \vec{PZ}$. En particular, $d(X, Y) = d(P, Z)$. Por tanto,
$$\{d(X, Y): X \in U_P, Y \in W_Q \} \subseteq \{d(P, Z) : Z \in (W+U)_Q \} \implies d(P, (W+U)_Q) \le d(U_P, W_Q).$$

Por otro lado, sea $R = P_L(P)$ ([[proyección ortogonal de un punto sobre una variedad afín]]) (donde $L = (U+W)_Q$). Entonces, por [[lema distancia punto-variedad igual a distancia punto-proyección ortogonal sobre la variedad afín]], $d(P, L) = d(P, R)$.
Tenemos $R \in L$, y por tanto $\vec{QR} \in U+W$, y podemos escribir $\vec{QR} = u+w$ donde $u \in U, w \in W$. Consideramos $X = P-u \in U_P$, $Y = Q+w \in W_Q$. Ahora, como $R = Q+(u+w) = (Q+w)+u = Y+u$, entonces
$$\vec{PR} = \vec{PX} + \vec{XY} + \vec{YR} = -u + \vec{XY} + u = \vec{XY}.$$
Por tanto $d(P, R) = d(X, Y)$, de modo que:
$$d(P, R) \in \{d(X', Y') : X' \in U_P, Y' \in W_Q \} \implies d(U_P, W_Q) \le d(P, R) = d(P, L).$$
Por tanto, $d(U_P, W_Q) = d(P, L)$.
```


**Tema:** [[Espacios afines euclídeos]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cómo se puede transformar una distancia entre variedades para que sea una distancia punto-variedad?
Reverso: $(E, V, +)$ [[Espacio afín euclídeo]]. Sean $U_P, W_Q \subseteq E$ [[Variedad afín]]. Entonces,
$$d(U_P, W_Q) = d(P, (W+U)_Q).$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1715864620162-->
END

START
Básico
Anverso: Demostración de que sea $(E, V, +)$ [[Espacio afín euclídeo]]. Sean $U_P, W_Q \subseteq E$ [[Variedad afín]]. Entonces,
$$d(U_P, W_Q) = d(P, (W+U)_Q).$$
Reverso: Sean $X \in U_P, Y \in W_Q$ cualesquiera. Tenemos $\vec{XY} = \vec{XP} + \vec{PQ} + \vec{QY}$. Ahora:
$$
\begin{eqnarray}
P + \vec{XY} &=& P + (\vec{XP} + \vec{PQ} + \vec{QY}) = (P + \vec{PQ}) + (\vec{XP} + \vec{QY}) \\
&=& Q + (\vec{XP} + \vec{QY}).
\end{eqnarray}
$$
Cabe destacar que $\vec{XP} \in U$ y $\vec{QY} \in W$. Denotamos $Z = Q + (\vec{XP} + \vec{QY})$, tenemos que $Z \in (W+U)_Q$, que por notación, $(W+U)_Q = L$. Sin embargo, $P + \vec{XY} = Z \in L$, luego $\vec{XY} = \vec{PZ}$. En particular, $d(X, Y) = d(P, Z)$. Por tanto,
$$\{d(X, Y): X \in U_P, Y \in W_Q \} \subseteq \{d(P, Z) : Z \in (W+U)_Q \} \implies d(P, (W+U)_Q) \le d(U_P, W_Q).$$

Por otro lado, sea $R = P_L(P)$ ([[Proyección ortogonal de un punto sobre una variedad afín]]) (donde $L = (U+W)_Q$). Entonces, por [[Lema distancia punto-variedad igual a distancia punto-proyección ortogonal sobre la variedad afín]], $d(P, L) = d(P, R)$.
Tenemos $R \in L$, y por tanto $\vec{QR} \in U+W$, y podemos escribir $\vec{QR} = u+w$ donde $u \in U, w \in W$. Consideramos $X = P-u \in U_P$, $Y = Q+w \in W_Q$. Ahora, como $R = Q+(u+w) = (Q+w)+u = Y+u$, entonces
$$\vec{PR} = \vec{PX} + \vec{XY} + \vec{YR} = -u + \vec{XY} + u = \vec{XY}.$$
Por tanto $d(P, R) = d(X, Y)$, de modo que:
$$d(P, R) \in \{d(X', Y') : X' \in U_P, Y' \in W_Q \} \implies d(U_P, W_Q) \le d(P, R) = d(P, L).$$
Por tanto, $d(U_P, W_Q) = d(P, L)$.
Tags: demostración ÁlgebraI
<!--ID: 1715864620168-->
END