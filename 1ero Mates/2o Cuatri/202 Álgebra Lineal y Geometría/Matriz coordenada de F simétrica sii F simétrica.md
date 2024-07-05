
---
mathLink: $F$ simétrica $\iff A$ simétrica
---
### Contenido Principal

**Fecha:** 2024-02-23, 16:28

Sea $F$ una [[Forma bilineal]] sobre $V$, y sea $A$ la [[Matriz coordenada de F]] con respecto a una [[Base]] $B$ cualquiera de $V$. Entonces,

```ad-lemma
$F$ es simétrica ([[Forma bilineal simétrica]]) $\iff A$ es simétrica ($A = A^t$).
```

```ad-proof
Escribimos $B = \{v_1, \dots, v_n\}$. Tenemos $A = (a_{ij}) \in M_n(\mathbb K)$, donde $a_{ij} = F(v_i, v_j), \forall i,j \in \{1, \dots, n\}$.

$\rightarrow$.
Supongamos que $F$ es simétrica, entonces $F(x,y) = F(y,x), \forall x,y \in V$. En particular, $\forall i,j \in \{1, \dots, n\}$, tenemos que $a_{ij} = F(v_i, v_j) = F(v_j, V_i) = a_{ji}$. Por tanto, $A$ es simétrica ($A = A^t$).

$\leftarrow$.
Supongamos que $A$ es simétrica, es decir $A^t = A$. Sean $x,y \in V$ arbitrarios. Entonces, por [[Lema cálculo forma bilineal a partir de matriz coordenada]], sabemos que:
$$
\begin{eqnarray}
F(x,y) = [x]^t_B · A [y]_B &=& ([x]_B^t · A · [y]_B)^t \\
&=& [y]_B^t A^t ([x]_B^t)^t \\
&=& [y]_B^t · A^t · [x]_B \\
&=& [y]_B^t · A · [x]_B = F(y,x).
\end{eqnarray}
$$
Luego $F$ es simétrica.
```



**Tema:** [[Formas bilineales]]
**Corolarios:** [[Toda matriz simétrica es congruente a una matriz diagonal]]

---
### Anki

START
Respuesta anidada
Sea $F$ una [[Forma bilineal]] sobre $V$, y sea $A$ la [[Matriz coordenada de F]] con respecto a una [[Base]] $B$ cualquiera de $V$. Entonces,
{{c1::$F$ es simétrica ([[Forma bilineal simétrica]])}} $\iff$ {{c2::$A$ es simétrica ($A = A^t$).}}
Tags: proposición/teorema ÁlgebraI
<!--ID: 1708973800432-->
END

START
Básico
Anverso: Demostración de que sea $F$ una [[Forma bilineal]] sobre $V$, y sea $A$ la [[Matriz coordenada de F]] con respecto a una [[Base]] $B$ cualquiera de $V$. Entonces,
$F$ es simétrica ([[Forma bilineal simétrica]]) $\iff A$ es simétrica ($A = A^t$).
Reverso: Escribimos $B = \{v_1, \dots, v_n\}$. Tenemos $A = (a_{ij}) \in M_n(\mathbb K)$, donde $a_{ij} = F(v_i, v_j), \forall i,j \in \{1, \dots, n\}$.

$\rightarrow$.
Supongamos que $F$ es simétrica, entonces $F(x,y) = F(y,x), \forall x,y \in V$. En particular, $\forall i,j \in \{1, \dots, n\}$, tenemos que $a_{ij} = F(v_i, v_j) = F(v_j, V_i) = a_{ji}$. Por tanto, $A$ es simétrica ($A = A^t$).

$\leftarrow$.
Supongamos que $A$ es simétrica, es decir $A^t = A$. Sean $x,y \in V$ arbitrarios. Entonces, por [[Lema cálculo forma bilineal a partir de matriz coordenada]], sabemos que:
$$
\begin{eqnarray}
F(x,y) = [x]^t_B · A [y]_B &=& ([x]_B^t · A · [y]_B)^t \\
&=& [y]_B^t A^t ([x]_B^t)^t \\
&=& [y]_B^t · A^t · [x]_B \\
&=& [y]_B^t · A · [x]_B = F(y,x).
\end{eqnarray}
$$
Luego $F$ es simétrica.
Tags: demostración ÁlgebraI
<!--ID: 1708973800438-->
END
