
---
mathLink: $\dim V^\perp = \dim V - rg(F)$
---
### Contenido Principal

**Fecha:** 2024-02-23, 17:06

Sea $V \neq 0$, y sea $F$ una [[Forma bilineal simétrica]] sobre $V$. Entonces,

```ad-theorem
$$\dim V^\perp = \dim V - rg(F)$$

[[Subespacio ortogonal a un subespacio]], [[Rango de una forma bilineal]].
```


```ad-proof
Sea $B = \{v_1, \dots, v_n\}$ base de $V$, y $A = (a_{ij}) \in M_n (\mathbb K)$ la [[Matriz coordenada de F]] con respecto la base $B$ (es decir, $a_{ij} = F(v_i, v_j), \forall i,j$).
Sea $v \in V$ cualquiera. Podemos escribir $v = x_1 v_1 + \dots + x_n v_n$, con $x_i \in \mathbb K, \forall i = 1, \dots, n$. Notemos que:
$$v \in V^\perp \iff F(w, v) = 0 \quad \forall w \in V \iff F(v_i, v)=0 \quad \forall i = 1, \dots, n$$
por [[Subespacio ortogonal a subespacio generado]]. Que, a la vez, esto se cumple
$$
\begin{eqnarray}
&\iff& F(v_i, x_1v_1 + \dots + x_n v_n) = 0, \forall i = 1, \dots, n \\
&\iff& \sum_{j=1}^n x_j F(v_i, v_j) = 0, \forall i = 1, \dots, n \\
&\iff& A (x_1 \dots x_n)^t = 0.
\end{eqnarray}
$$
Por tanto, $V^\perp = \{v \in V : A[v]_B = 0 \}$. Consideramos $f: \mathbb K^n \to \mathbb K^n$ con $y \to Ay$, que es una [[Aplicación lineal]]. Tenemos: $V^\perp = \{v \in V: f([v]_B) = 0\} = \{v \in V: [v]_B \in Kerf \}$ ([[Núcleo]]). Ahora, $A$ es la matriz coordenada de $F$ con respecto a la base canónica de $\mathbb K^n$. Por tanto, $\dim Kerf =$ (por [[Teorema suma de dimensiones de núcleo e imagen]]) $\dim V - \dim Imf =$ (por [[Rango de una aplicación lineal]]) $n - rg(f) =$ (por [[Coincidencia rango de una aplicación lineal con el rango de columnas de cualquier matriz asociada]]) $n - rg(A)$. Luego $\dim V^\perp = \dim V - rg(A)$.
```


**Tema:** [[Formas bilineales]]
**Demostrado por:** [[Subespacio ortogonal a subespacio generado]]
**Consecuencias:** [[Corolario F es regular sii su subespacio ortogonal es el 0]]

---
### Anki

START
Básico
Anverso: A qué es igual $\dim V^\perp$?
Reverso: Sea $V \neq 0$, y sea $F$ una [[Forma bilineal simétrica]] sobre $V$. Entonces,
$$\dim V^\perp = \dim V - rg(F)$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709571902544-->
END

START
Básico
Anverso: Demostración de que sea $V \neq 0$, y sea $F$ una [[Forma bilineal simétrica]] sobre $V$. Entonces,
$$\dim V^\perp = \dim V - rg(F)$$
Reverso: Sea $B = \{v_1, \dots, v_n\}$ base de $V$, y $A = (a_{ij}) \in M_n (\mathbb K)$ la [[Matriz coordenada de F]] con respecto la base $B$ (es decir, $a_{ij} = F(v_i, v_j), \forall i,j$).
Sea $v \in V$ cualquiera. Podemos escribir $v = x_1 v_1 + \dots + x_n v_n$, con $x_i \in \mathbb K, \forall i = 1, \dots, n$. Notemos que:
$$v \in V^\perp \iff F(w, v) = 0 \quad \forall w \in V \iff F(v_i, v)=0 \quad \forall i = 1, \dots, n$$
por [[Subespacio ortogonal a subespacio generado]]. Que, a la vez, esto se cumple
$$
\begin{eqnarray}
&\iff& F(v_i, x_1v_1 + \dots + x_n v_n) = 0, \forall i = 1, \dots, n \\
&\iff& \sum_{j=1}^n x_j F(v_i, v_j) = 0, \forall i = 1, \dots, n \\
&\iff& A (x_1 \dots x_n)^t = 0.
\end{eqnarray}
$$
Por tanto, $V^\perp = \{v \in V : A[v]_B = 0 \}$. Consideramos $f: \mathbb K^n \to \mathbb K^n$ con $y \to Ay$, que es una [[Aplicación lineal]]. Tenemos: $V^\perp = \{v \in V: f([v]_B) = 0\} = \{v \in V: [v]_B \in Kerf \}$ ([[Núcleo]]). Ahora, $A$ es la matriz coordenada de $F$ con respecto a la base canónica de $\mathbb K^n$. Por tanto, $\dim Kerf =$ (por [[Teorema suma de dimensiones de núcleo e imagen]]) $\dim V - \dim Imf =$ (por [[Rango de una aplicación lineal]]) $n - rg(f) =$ (por [[Coincidencia rango de una aplicación lineal con el rango de columnas de cualquier matriz asociada]]) $n - rg(A)$. Luego $\dim V^\perp = \dim V - rg(A)$.
Tags: demostración ÁlgebraI
<!--ID: 1709571902553-->
END
