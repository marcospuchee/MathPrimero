
---
mathLink: $V = U \bigoplus U^\perp$
---
### Contenido Principal

**Fecha:** 2024-03-01, 19:26

Sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ un [[Subespacio regular]]. Entonces,

```ad-theorem
$$V = U \bigoplus U^\perp.$$
[[Subespacio ortogonal a un subespacio]]
```


```ad-proof
Sea $\{u_1, \dots, u_m\}$ [[Base]] de $U$. Por el lema de prolongación, sea $u_{m+1}, \dots, u_n \in V$ tales que $B = \{u_1, \dots, u_m, u_{m+1}, \dots, u_n\}$ es base de $V$.

Sea $v \in V$, y denotamos $[v]_B = (x_1, \dots, x_n) \in \mathbb K^n$. Tenemos:
$v \in U^\perp \iff F(u,v) = 0 \quad \forall u \in U \iff$ (por [[Subespacio ortogonal a subespacio generado]]) $F(u_i, v) = 0 \quad \forall i = 1, \dots, n \iff$ $0 = F(u_i, x_1 u_1 + \dots + x_n u_n) = \sum_{j = 1}^n x_j F(u_i, u_j), \forall i = 1, \dots, n$ $\iff A(x_1 \dots x_n)^t = 0$, donde $A = (a_{ij}) \in M_{m \times n}(\mathbb K)$ con $a_{ij} = F(v_i, v_j), 1 \le i \le m, 1 \le j \le n$. 

Luego $v \in U^\perp \iff A(x_1 \dots x_n)^t = 0$. Por tanto, $V \ge U^\perp = \{v \in V: A[v]_B = 0 \} = \{v \in V: [v]_B \in Ker(f_A) \}$, donde $f_A: \mathbb K^n \to \mathbb K^m$ con $y \to Ay$.

Así, $\dim U^\perp = \dim Ker(f_A) = \dim f_A - \dim Imf_A = n - \dim f_A(\mathbb K^n)$, que esto a su vez es $n - rg(f_A)$ (por [[Rango de una aplicación lineal]]) $= n - rg(A)$ ([[Rango de una aplicación lineal]]) , donde $A$ es la [[Matriz asociada a una aplicación lineal]] a $f_A$ con respecto a las bases canónicas de $\mathbb K^n, \mathbb K^m$.

Sin embargo, $A$ está formada por las primeras $m$ filas de la [[Matriz coordenada de F]] con respecto a $B$. Sea $G = F \restriction_{U \times U}: U \times U \to \mathbb K^n$. La matriz coordenada de $G$ con respecto a la base $\{u_1, \dots, u_n \}$ de $U$ es $M = (G(u_i, u_j)) \in M_{m \times n} (\mathbb K)$, pero como $G(u_i, u_j) = F(u_i, u_j), \forall i,j \in \{1, \dots, m\}$, $M$ está formada por las primeras $m$ columnas de $A$.

$U$ es regular $\iff G$ es regular ([[Forma bilineal invertible]]) $\iff M$ es regular $\iff rg(M) = m$. Luego tenemos $rg(A) \ge m \implies rg(A) = m$. Deducimos que $\dim U^\perp = n-m = n- \dim U$ $\implies \dim U + \dim U^\perp = n = \dim V$. Pero $U$ es regular $\implies U \cap U^\perp = 0 \iff U + U^\perp = U \bigoplus U^\perp$.

Así, $\dim U \bigoplus U^\perp = \dim U + \dim U^\perp = n \implies V = U \bigoplus U^\perp$.

```


**Tema:** [[Formas bilineales]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Sea $U \le V$, qué es $U \bigoplus U^\perp$?
Reverso: Sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ un [[Subespacio regular]]. Entonces,
$$V = U \bigoplus U^\perp.$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709571902563-->
END

START
Básico
Anverso: Demostración de que sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ un [[Subespacio regular]]. Entonces,
$$V = U \bigoplus U^\perp.$$
Reverso: Sea $\{u_1, \dots, u_m\}$ [[Base]] de $U$. Por el lema de prolongación, sea $u_{m+1}, \dots, u_n \in V$ tales que $B = \{u_1, \dots, u_m, u_{m+1}, \dots, u_n\}$ es base de $V$.

Sea $v \in V$, y denotamos $[v]_B = (x_1, \dots, x_n) \in \mathbb K^n$. Tenemos:
$v \in U^\perp \iff F(u,v) = 0 \quad \forall u \in U \iff$ (por [[Subespacio ortogonal a subespacio generado]]) $F(u_i, v) = 0 \quad \forall i = 1, \dots, n \iff$ $0 = F(u_i, x_1 u_1 + \dots + x_n u_n) = \sum_{j = 1}^n x_j F(u_i, u_j), \forall i = 1, \dots, n$ $\iff A(x_1 \dots x_n)^t = 0$, donde $A = (a_{ij}) \in M_{m \times n}(\mathbb K)$ con $a_{ij} = F(v_i, v_j), 1 \le i \le m, 1 \le j \le n$. 

Luego $v \in U^\perp \iff A(x_1 \dots x_n)^t = 0$. Por tanto, $V \ge U^\perp = \{v \in V: A[v]_B = 0 \} = \{v \in V: [v]_B \in Ker(f_A) \}$, donde $f_A: \mathbb K^n \to \mathbb K^m$ con $y \to Ay$.

Así, $\dim U^\perp = \dim Ker(f_A) = \dim f_A - \dim Imf_A = n - \dim f_A(\mathbb K^n)$, que esto a su vez es $n - rg(f_A)$ (por [[Rango de una aplicación lineal]]) $= n - rg(A)$ ([[Rango de una aplicación lineal]]) , donde $A$ es la [[Matriz coordenada]] a $f_A$ con respecto a las bases canónicas de $\mathbb K^n, \mathbb K^m$.

Sin embargo, $A$ está formada por las primeras $m$ filas de la [[Matriz coordenada de F]] con respecto a $B$. Sea $G = F \restriction_{U \times U}: U \times U \to \mathbb K^n$. La matriz coordenada de $G$ con respecto a la base $\{u_1, \dots, u_n \}$ de $U$ es $M = (G(u_i, u_j)) \in M_{m \times n} (\mathbb K)$, pero como $G(u_i, u_j) = F(u_i, u_j), \forall i,j \in \{1, \dots, m\}$, $M$ está formada por las primeras $m$ columnas de $A$.

$U$ es regular $\iff G$ es regular ([[Forma bilineal invertible]]) $\iff M$ es regular $\iff rg(M) = m$. Luego tenemos $rg(A) \ge m \implies rg(A) = m$. Deducimos que $\dim U^\perp = n-m = n- \dim U$ $\implies \dim U + \dim U^\perp = n = \dim V$. Pero $U$ es regular $\implies U \cap U^\perp = 0 \iff U + U^\perp = U \bigoplus U^\perp$.

Así, $\dim U \bigoplus U^\perp = \dim U + \dim U^\perp = n \implies V = U \bigoplus U^\perp$.

Tags: demostración ÁlgebraI
<!--ID: 1709571902572-->
END