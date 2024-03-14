
---
mathLink: $A \in M_n(\mathbb C)$ simétrica es congruente a $Diag(1, \dots, 1, 0, \dots, 0)$
---
### Contenido Principal

**Fecha:** 2024-03-04, 16:58

```ad-theorem
Sea $A \in M_n(\mathbb C)$ simétrica. entonces, $A$ es congruente a la matriz
$$M =
\begin{pmatrix}
I_r & 0 \\
0 & 0
\end{pmatrix} = Diag(1, \dots, 1, 0, \dots, 0)
$$
([[Matrices congruentes]]) donde $I_r$ es la matriz identidad con $r$ unos, es decir, $rg A = r$.

En particular, $A, A' \in M_n (\mathbb C)$ son congruentes $\iff rg(A) = rg(A')$.
```


```ad-proof
Consideramos $F = F_A : \mathbb C^n \times \mathbb C^n \to \mathbb C$ con $(x,y) \to x^t A y$. 

Sea $B = \{v_1, \dots, v_n\}$ base $F$-ortogonal ([[Conjunto F-ortogonal]]) de $V = \mathbb C^n$ (por [[Teorema existencia base F-ortogonal]]). Podemos suponer, reordenando los vectores de $B$, si es necesario, que $F(v_i, v_i) \neq 0, \forall 1 \le i \le t$ y que $F(v_i, v_i) = 0, \forall t+1 \le i \le n$.

Luego, si $1 \le i \le t$, tenemos $a_i = F(v_i, v_i) \neq 0, a_i \in \mathbb C$. Consideramos $b_i \in \mathbb C - \{0\}$ tal que $(b_i)^2 = a_i$. Sea $B' = \{\frac{1}{b_1}v_1, \frac{1}{b_2} v_2, \dots, \frac{1}{b_t} v_t, v_{t+1}, \dots, v_n \}$. Notemos que $B'$ es base de $V$. $B'$ es base $F$-ortogonal. Tenemos:
$$F(\frac{1}{b_i} v_i, \frac{1}{b_i} v_i) = (\frac{1}{b_i})^2 F(v_i, v_i) = \frac{1}{a_i} F(v_i, v_i) = \frac{a_i}{a_i} = 1, \quad 1 \le i \le t.$$
Por tanto, la [[Matriz coordenada de F]] con respecto a $B'$ es:
$$M = \begin{pmatrix} I_t & 0 \\ 0 & 0 \end{pmatrix}.$$
En particular, $t = rg(M)$, pero $M$ y $A$ son congruentes, luego $t = rg(A) = rg(M)$.

Falta demostrar que $A, A' \in M_n(\mathbb C)$ simétricas con $rg(A) = rg(A') = r$ son congruentes. Por lo visto anteriormente, $A, A'$ son congruentes a $M$. Por tanto, como [[La relación de congruencia es de equivalencia]], entonces $A, A'$ son coongruentes entre sí.
```


**Tema:** [[Formas bilineales]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: A qué es congruente una matriz compleja simétrica?
Reverso: Sea $A \in M_n(\mathbb C)$ simétrica. entonces, $A$ es congruente a la matriz
$$M =
\begin{pmatrix}
I_r & 0 \\
0 & 0
\end{pmatrix} = Diag(1, \dots, 1, 0, \dots, 0)
$$
([[Matrices congruentes]]) donde $I_r$ es la matriz identidad con $r$ unos, es decir, $rg A = r$.

En particular, $A, A' \in M_n (\mathbb C)$ son congruentes $\iff rg(A) = rg(A')$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709571902503-->
END

START
Básico
Anverso: Demostración de que sea $A \in M_n(\mathbb C)$ simétrica. entonces, $A$ es congruente a la matriz
$$M =
\begin{pmatrix}
I_r & 0 \\
0 & 0
\end{pmatrix} = Diag(1, \dots, 1, 0, \dots, 0)
$$
([[Matrices congruentes]]) donde $I_r$ es la matriz identidad con $r$ unos, es decir, $rg A = r$.

En particular, $A, A' \in M_n (\mathbb C)$ son congruentes $\iff rg(A) = rg(A')$.
Reverso: Consideramos $F = F_A : \mathbb C^n \times \mathbb C^n \to \mathbb C$ con $(x,y) \to x^t A y$. 

Sea $B = \{v_1, \dots, v_n\}$ base $F$-ortogonal ([[Conjunto F-ortogonal]]) de $V = \mathbb C^n$ (por [[Teorema existencia base F-ortogonal]]). Podemos suponer, reordenando los vectores de $B$, si es necesario, que $F(v_i, v_i) \neq 0, \forall 1 \le i \le t$ y que $F(v_i, v_i) = 0, \forall t+1 \le i \le n$.

Luego, si $1 \le i \le t$, tenemos $a_i = F(v_i, v_i) \neq 0, a_i \in \mathbb C$. Consideramos $b_i \in \mathbb C - \{0\}$ tal que $(b_i)^2 = a_i$. Sea $B' = \{\frac{1}{b_1}v_1, \frac{1}{b_2} v_2, \dots, \frac{1}{b_t} v_t, v_{t+1}, \dots, v_n \}$. Notemos que $B'$ es base de $V$. $B'$ es base $F$-ortogonal. Tenemos:
$$F(\frac{1}{b_i} v_i, \frac{1}{b_i} v_i) = (\frac{1}{b_i})^2 F(v_i, v_i) = \frac{1}{a_i} F(v_i, v_i) = \frac{a_i}{a_i} = 1, \quad 1 \le i \le t.$$
Por tanto, la [[Matriz coordenada de F]] con respecto a $B'$ es:
$$M = \begin{pmatrix} I_t & 0 \\ 0 & 0 \end{pmatrix}.$$
En particular, $t = rg(M)$, pero $M$ y $A$ son congruentes, luego $t = rg(A) = rg(M)$.

Falta demostrar que $A, A' \in M_n(\mathbb C)$ simétricas con $rg(A) = rg(A') = r$ son congruentes. Por lo visto anteriormente, $A, A'$ son congruentes a $M$. Por tanto, como [[La relación de congruencia es de equivalencia]], entonces $A, A'$ son coongruentes entre sí.
Tags: demostración ÁlgebraI
<!--ID: 1709571902512-->
END