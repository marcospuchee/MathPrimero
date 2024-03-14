
---
mathLink: $B, B'$ bases ortogonales, entonces $sig(B) = sig(B')$
---
### Contenido Principal

**Fecha:** 2024-03-07, 18:48

```ad-theorem
Sea $V$ un $\mathbb R$-espacio vectorial de dimensión $\dim V = n$, sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sean $B, B'$ dos bases ortogonales ([[Conjunto F-ortogonal]]) de $V$. Entonces,
$$sig(B) = sig(B').$$
([[Signatura]])
```


```ad-proof
Supongamos que $B = \{v_1, \dots, v_n\}$, con $F(v_i, v_i) > 0, \forall 1 \le i \le s$ y $F(v_i, v_i) \le 0, \forall s+1 \le 1 \le n$. Supongamos también que $B' = \{u_1, \dots, u_n\}$, con $F(u_j, u_j) > 0, \forall 1 \le j \le t$, y $F(u_j, u_j) \le 0, \forall t+1 \le j \le n$. Queremos ver que $s = t$.

Sean $X = \langle v_1, \dots, v_s \rangle \le V, Y = \langle u_{t+1}, \dots, u_n \rangle \le V$. Veamos que $X \cap Y = 0$. Para ello, tomamos $v \in X \cap Y$. Tenemos:
$$v = \alpha_1 v_1 + \dots \alpha_s v_s = \beta_{t+1} u_{t+1} + \dots + \beta_n u_n, \quad \alpha_i, \beta_j \in \mathbb R.$$
Notemos que:
$$
\begin{eqnarray}
F(v,v) &=& F(\alpha_1 v_1 + \dots \alpha_s v_s, \alpha_1 v_1 + \dots \alpha_s v_s) \\
&=& \sum_{i,k = 1}^s \alpha_i \alpha_k F(v_i, v_k) \\
&=& \sum_{i = 1}^s \alpha_i^2 F(v_i, v_i) \ge 0,
\end{eqnarray}
$$
por ser bilineal y ortogonal. Por otro lado, 
$$F(v,v) = F(\beta_{t+1} u_{t+1} + \dots + \beta_n u_n, \beta_{t+1} u_{t+1} + \dots + \beta_n u_n) = \sum_{j = t+1}^n (\beta_j)^2 F(u_j, u_j) \le 0.$$
Por lo que acabamos de ver que $F(v,v) = 0$ y $\alpha_i = 0 = \beta_j, \forall i,j$, luego $v = 0$. Así, $X \cap Y = 0$. Por tanto, $X \bigoplus Y \le V$. Tenemos:
$$ n \ge \dim X \bigoplus Y = \dim X + \dim Y = s + (n-t) \implies t \ge s$$
Un razonamiento análogo sirve para probar $s \ge t$, y por tanto, $s = t$.
```


**Tema:** [[Formas bilineales]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que establece la igualdad entre la signatura de dos bases $F$-ortogonales?
Reverso: Sea $V$ un $\mathbb R$-espacio vectorial de dimensión $\dim V = n$, sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sean $B, B'$ dos bases ortogonales ([[Conjunto F-ortogonal]]) de $V$. Entonces,
$$sig(B) = sig(B').$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709836068037-->
END

START
Básico
Anverso: Demostración de que sea $V$ un $\mathbb R$-espacio vectorial de dimensión $\dim V = n$, sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sean $B, B'$ dos bases ortogonales ([[Conjunto F-ortogonal]]) de $V$. Entonces,
$$sig(B) = sig(B').$$
Reverso: Supongamos que $B = \{v_1, \dots, v_n\}$, con $F(v_i, v_i) > 0, \forall 1 \le i \le s$ y $F(v_i, v_i) \le 0, \forall s+1 \le 1 \le n$. Supongamos también que $B' = \{u_1, \dots, u_n\}$, con $F(u_j, u_j) > 0, \forall 1 \le j \le t$, y $F(u_j, u_j) \le 0, \forall t+1 \le j \le n$. Queremos ver que $s = t$.

Sean $X = \langle v_1, \dots, v_s \rangle \le V, Y = \langle u_{t+1}, \dots, u_n \rangle \le V$. Veamos que $X \cap Y = 0$. Para ello, tomamos $v \in X \cap Y$. Tenemos:
$$v = \alpha_1 v_1 + \dots \alpha_s v_s = \beta_{t+1} u_{t+1} + \dots + \beta_n u_n, \quad \alpha_i, \beta_j \in \mathbb R.$$
Notemos que:
$$
\begin{eqnarray}
F(v,v) &=& F(\alpha_1 v_1 + \dots \alpha_s v_s, \alpha_1 v_1 + \dots \alpha_s v_s) \\
&=& \sum_{i,k = 1}^s \alpha_i \alpha_k F(v_i, v_k) \\
&=& \sum_{i = 1}^s \alpha_i^2 F(v_i, v_i) \ge 0,
\end{eqnarray}
$$
por ser bilineal y ortogonal. Por otro lado, 
$$F(v,v) = F(\beta_{t+1} u_{t+1} + \dots + \beta_n u_n, \beta_{t+1} u_{t+1} + \dots + \beta_n u_n) = \sum_{j = t+1}^n (\beta_j)^2 F(u_j, u_j) \le 0.$$
Por lo que acabamos de ver que $F(v,v) = 0$ y $\alpha_i = 0 = \beta_j, \forall i,j$, luego $v = 0$. Así, $X \cap Y = 0$. Por tanto, $X \bigoplus Y \le V$. Tenemos:
$$ n \ge \dim X \bigoplus Y = \dim X + \dim Y = s + (n-t) \implies t \ge s$$
Un razonamiento análogo sirve para probar $s \ge t$, y por tanto, $s = t$.
Tags: demostración ÁlgebraI
<!--ID: 1709836068042-->
END