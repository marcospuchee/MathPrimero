### Contenido Principal

```ad-theorem
Sea $n \ge 5$. Entonces $A_n$ es simple ([[grupo simple]]).
```

^a5b10d

```ad-proof
Sea $N \unlhd A_n$. Suponemos $N \neq \{id \}$. Demostramos $N = A_n$. 

Sea $\sigma \textrm{\\}\{id\}$ una permutación con soporte minimal. Esto es, $\nexists \tau \in N \textrm{\\} \{id\}$ tal que $|\textrm{supp}(\tau)| < |\textrm{supp}(\sigma)|$. Supongamos sin pérdida de generalidad que $\textrm{supp}(\sigma) = \{1,2, \dots, k\}$. Distinguiremos casos sobre $k$:
1. $k = 1$. Por tanto $\textrm{supp}(\sigma) = \{1\}$, lo es una contradicción. Luego $\sigma = id$, que es contradicción también.
2. $k = 2$. $\textrm{supp}(\sigma) = \{1,2\}$. Por tanto, $\sigma = (1,2)$. Pero $(1,2) \notin A_n$, lo cual es una contradicción.
3. $k = 3$. $\textrm{supp}(\sigma) = \{1,2,3 \}$. Por tanto, es un $3$-ciclo. Sea $(a,b,c) \in S_n$, por [[3-ciclos (resp. transposiciones de tipo (2,2)) son conjugados y generan An]], $\exists \tau \in A_n$ tal que $(a,b,c) = {}^\tau \sigma \in N$ (porque $N \unlhd A_n$). Es decir, $N$ contiene todos los $3$-ciclos. Por el mismo resultado, $A_n = \langle (i,j,k) \rangle \le N \unlhd A_n$. Luego $N = A_n$.
4. Entonces $\sigma$ es un $4$-ciclo o una permutación de tipo $(2,2)$. Como los $4$-ciclos son impares, el único caso a considerar es $\sigma$ es de tipo $(2,2)$. Se demuestra igual que el tercer caso.
5. $k \ge 5$ y la descomposición en ciclos disjuntos de $\sigma$ contiene al menos un $r$-ciclo para $r \ge 3$. Suponemos sin pérdida de generalidad que $\sigma(1) = 2$, $\sigma(2) = 3$. Consideramos
$$\tau = (3,4,5) \circ \sigma \circ (3,5,4) \circ \sigma^{-1} \in N.$$
Entonces:
	- Si $i > k$, $\tau(i) = i \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(2) = 2 \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(3) = 4 \implies \tau \neq id$.
Lo cual es una contradicción con la minimalidad de $\sigma$.
6. $k \ge 5$ y $\sigma$ se expresa como composición de transposiciones de disjuntos: $\sigma \circ (1,2) \circ (3,4) \circ (5,6) \circ \dots$. Considerando $\tau = (3,4,5) \circ \sigma \circ (3,5,4) \circ \sigma^{-1} \in N$.
	- Si $i > k, \tau(i) = i \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(1) = 1, \tau(2) = 2 \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(6) = 5 \implies \tau \neq id$.
```

**Tema:** [[Teoría de grupos#14. Simplicidad de $A_n$.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Teorema de la simplicidad de $A_n$
Reverso: Sea $n \ge 5$. Entonces $A_n$ es simple ([[grupo simple]]).
Tags: est
<!--ID: 1730228001534-->
END

START
Básico
Anverso: Demostración de que sea $n \ge 5$. Entonces $A_n$ es simple ([[grupo simple]]).
Reverso: Sea $N \unlhd A_n$. Suponemos $N \neq \{id \}$. Demostramos $N = A_n$. 

Sea $\sigma \textrm{\\}\{id\}$ una permutación con soporte minimal. Esto es, $\nexists \tau \in N \textrm{\\} \{id\}$ tal que $|\textrm{supp}(\tau)| < |\textrm{supp}(\sigma)|$. Supongamos sin pérdida de generalidad que $\textrm{supp}(\sigma) = \{1,2, \dots, k\}$. Distinguiremos casos sobre $k$:
1. $k = 1$. Por tanto $\textrm{supp}(\sigma) = \{1\}$, lo es una contradicción. Luego $\sigma = id$, que es contradicción también.
2. $k = 2$. $\textrm{supp}(\sigma) = \{1,2\}$. Por tanto, $\sigma = (1,2)$. Pero $(1,2) \notin A_n$, lo cual es una contradicción.
3. $k = 3$. $\textrm{supp}(\sigma) = \{1,2,3 \}$. Por tanto, es un $3$-ciclo. Sea $(a,b,c) \in S_n$, por [[3-ciclos (resp. transposiciones de tipo (2,2)) son conjugados y generan An]], $\exists \tau \in A_n$ tal que $(a,b,c) = {}^\tau \sigma \in N$ (porque $N \unlhd A_n$). Es decir, $N$ contiene todos los $3$-ciclos. Por el mismo resultado, $A_n = \langle (i,j,k) \rangle \le N \unlhd A_n$. Luego $N = A_n$.
4. Entonces $\sigma$ es un $4$-ciclo o una permutación de tipo $(2,2)$. Como los $4$-ciclos son impares, el único caso a considerar es $\sigma$ es de tipo $(2,2)$. Se demuestra igual que el tercer caso.
5. $k \ge 5$ y la descomposición en ciclos disjuntos de $\sigma$ contiene al menos un $r$-ciclo para $r \ge 3$. Suponemos sin pérdida de generalidad que $\sigma(1) = 2$, $\sigma(2) = 3$. Consideramos
$$\tau = (3,4,5) \circ \sigma \circ (3,5,4) \circ \sigma^{-1} \in N.$$
Entonces:
	- Si $i > k$, $\tau(i) = i \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(2) = 2 \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(3) = 4 \implies \tau \neq id$.
Lo cual es una contradicción con la minimalidad de $\sigma$.
6. $k \ge 5$ y $\sigma$ se expresa como composición de transposiciones de disjuntos: $\sigma \circ (1,2) \circ (3,4) \circ (5,6) \circ \dots$. Considerando $\tau = (3,4,5) \circ \sigma \circ (3,5,4) \circ \sigma^{-1} \in N$.
	- Si $i > k, \tau(i) = i \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(1) = 1, \tau(2) = 2 \implies \textrm{supp}(\tau) \subseteq \textrm{supp}(\sigma)$.
	- $\tau(6) = 5 \implies \tau \neq id$.
Tags: dem est
<!--ID: 1730368366085-->
END

