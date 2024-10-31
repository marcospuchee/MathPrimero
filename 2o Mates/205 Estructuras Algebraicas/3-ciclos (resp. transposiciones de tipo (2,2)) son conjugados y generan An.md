### Contenido Principal

```ad-proposition
Sea $n \ge 5$. Entonces
1. Todos los $3$-ciclos son conjugados en $A_n$ y generan $A_n$, esto es,
$$A_n = \langle (i,j,k) : i,j,k \in \{1, \dots n \} \textrm{ distintos} \rangle.$$
2. Todas las transposiciones de tipo $(2,2)$ son conjugadas en $A_n$ y generan $A_n$, esto es,
$$A_n = \langle (i,j)(k,l) : i,j,k,l \in \{1, \dots, n \} \textrm{ distintos} \rangle.$$
```

^406671

```ad-proof
$(i)$.
Demostramos que todos los $3$-ciclos son conjugados en $A_n$. Esto es, $\forall (a,b,c),(i,j,k) \in S_n$, $\exists \sigma \in A_n$ tal que $^\sigma (a,b,c) = (i,j,k)$.
Es suficiente demostrar que $\forall (a,b,c) \in S_n$, $\exists \sigma \in A_n$ tal que $^\sigma (a,b,c) = (1,2,3)$ ya uqe en este caso, si $(a,b,c),(i,j,k) \in S_n$, entonces $\exists \sigma, \tau \in A_n$ tales que $^\sigma (a,b,c) = (1,2,3) = ^\tau (i,j,k)$. Así, $^{\tau^{-1} \circ \sigma}(a,b,c) = {}^{\tau^{-1}}(1,2,3) = (i,j,k)$, donde $\tau^{-1} \circ \sigma \in A_n$ (por [[teorema del grupo alternado]]).
Sea $(a,b,c) \in S_n$, por [[permutaciones son conjugadas sii tienen el mismo tipo]], $\exists \sigma \in S_n$ tal que $^\sigma (a,b,c) = (1,2,3)$. Dos casos:
1. $\sigma \in A_n$. En este caso, hemos acabado.
2. $\sigma \notin A_n$. Como $n \ge 5$, consideramos $\sigma' = (4,5) \circ \sigma$. Entonces $\sigma' \in A_n$ y,
$$^{\sigma'}(a,b,c) = {}^{(4,5) \circ \sigma}(a,b,c) = {}^{(4,5)}(1,2,3) = (1,2,3),$$
donde la última igualdad se cumple por [[forma de todo conjugado de una permutación]].

Demostramos que los $3$-ciclos generan $A_n$. Esto es, 
$$A_n = \langle (i,j,k) : 1 \le i,j,k \le n \textrm{ distintos} \rangle = \langle (i,j,k) \rangle.$$
$\supseteq$. Por [[todo r-ciclo es una composición de r-1 2-ciclos]], $\forall (i,j,k) \in S-n$, $(i,j,k) \in A_n$. Por [[subgrupo generado es subgrupo]], entonces $A_n \supseteq \langle (i,j,k) \rangle$.
$\subseteq$. Sea $\sigma \in A_n$, demostramos que $\sigma \in \langle (i,j,k) \rangle$. Como $\sigma \in A_n$, $\exists t_1, t_2, \dots, t_{2r} \in S_n$ transposiciones tales que $\sigma = t_1 \circ t_2 \circ \dots \circ t_{2r}$. Es suficiente demostrar que $\forall t_i, t_{i+1}$, se cumple que $t_i \circ t_{i+1} \in A_n$ ya que, en ese caso, $\sigma = (t_1 \circ t_2) \circ \dots \circ (t_{2r-1} \circ t_{2r}) \in \langle (i,j,k) \rangle$. Consideramos los siguientes casos:
1. $(a,b) \circ (a,b) = id = (1,2,3) \circ (1,3,2)$.
2. $(a,b) \circ (a,c) = (a,c,b)$
3. $(a,b) \circ (c,d) = (a,b,c) \circ (b,c,d)$.

$(ii)$.
Sea $(a,b) \circ (c,d)$ con $a,b,c,d$ distintos. Por [[permutaciones son conjugadas sii tienen el mismo tipo]], $\exists \sigma \in S_n$ tal que $^\sigma ((a,b) \circ (c,d)) = (1,2) \circ (3,4)$. Dos casos:
1. $\sigma \in A_n$. Ya habríamos acabado.
2. $\sigma \notin A_n$. Consideramos $\sigma' = (1,2) \circ \sigma$. Entonces $\sigma' \in A_n$ y
$$^{\sigma'}((a,b) \circ (c,d)) = {}^{(1,2) \circ \sigma} ((a,b) \circ (c,d)) = {}^{(1,2)}((1,2) \circ (3,4)) = (1,2) \circ (3,4).$$

Veamos ahora que
$$A_n = \langle (i,j) \circ (k,l) : 1 \le i,j,k,l \le n \textrm{ distintos} \rangle.$$
$\supseteq$. $(i,j) \circ (k,l) \in S_n$, entonces $(i,j) \circ (k,l) \in A_n$ por definición de $A_n$.
$\subseteq$. Sea $\sigma \in A_n$, demostramos que $\sigma \in \langle (i,j) \circ (k,l) \rangle$. Tres casos:
1. $(a,b) \circ (a,b) = id = (a,b) \circ (c,d) \circ(a,b) \circ (c,d)$.
2. $(a,b) \circ (a,c) = (a,b) \circ (d,e) \circ (a,c) \circ (d,e)$.
3. $(a,b) \circ (c,d)$.
```

**Tema:** [[Teoría de grupos#14. Simplicidad de $A_n$.]]

---
### Anki

START
Básico
Anverso: Conjugación $3$-ciclos y transposiciones de tipo $(2,2)$, y su generado
Reverso: Sea $n \ge 5$. Entonces
1. Todos los $3$-ciclos son conjugados en $A_n$ y generan $A_n$, esto es,
$$A_n = \langle (i,j,k) : i,j,k \in \{1, \dots n \} \textrm{ distintos} \rangle.$$
2. Todas las transposiciones de tipo $(2,2)$ son conjugadas en $A_n$ y generan $A_n$, esto es,
$$A_n = \langle (i,j)(k,l) : i,j,k,l \in \{1, \dots, n \} \textrm{ distintos} \rangle.$$
Tags: est
<!--ID: 1730228001548-->
END

START
Básico
Anverso: Demostración de que sea $n \ge 5$. Entonces
1. Todos los $3$-ciclos son conjugados en $A_n$ y generan $A_n$, esto es,
$$A_n = \langle (i,j,k) : i,j,k \in \{1, \dots n \} \textrm{ distintos} \rangle.$$
2. Todas las transposiciones de tipo $(2,2)$ son conjugadas en $A_n$ y generan $A_n$, esto es,
$$A_n = \langle (i,j)(k,l) : i,j,k,l \in \{1, \dots, n \} \textrm{ distintos} \rangle.$$
Reverso: $(i)$.
Demostramos que todos los $3$-ciclos son conjugados en $A_n$. Esto es, $\forall (a,b,c),(i,j,k) \in S_n$, $\exists \sigma \in A_n$ tal que $^\sigma (a,b,c) = (i,j,k)$.
Es suficiente demostrar que $\forall (a,b,c) \in S_n$, $\exists \sigma \in A_n$ tal que $^\sigma (a,b,c) = (1,2,3)$ ya uqe en este caso, si $(a,b,c),(i,j,k) \in S_n$, entonces $\exists \sigma, \tau \in A_n$ tales que $^\sigma (a,b,c) = (1,2,3) = ^\tau (i,j,k)$. Así, $^{\tau^{-1} \circ \sigma}(a,b,c) = {}^{\tau^{-1}}(1,2,3) = (i,j,k)$, donde $\tau^{-1} \circ \sigma \in A_n$ (por [[teorema del grupo alternado]]).
Sea $(a,b,c) \in S_n$, por [[permutaciones son conjugadas sii tienen el mismo tipo]], $\exists \sigma \in S_n$ tal que $^\sigma (a,b,c) = (1,2,3)$. Dos casos:
1. $\sigma \in A_n$. En este caso, hemos acabado.
2. $\sigma \notin A_n$. Como $n \ge 5$, consideramos $\sigma' = (4,5) \circ \sigma$. Entonces $\sigma' \in A_n$ y,
$$^{\sigma'}(a,b,c) = {}^{(4,5) \circ \sigma}(a,b,c) = {}^{(4,5)}(1,2,3) = (1,2,3),$$
donde la última igualdad se cumple por [[forma de todo conjugado de una permutación]].

Demostramos que los $3$-ciclos generan $A_n$. Esto es, 
$$A_n = \langle (i,j,k) : 1 \le i,j,k \le n \textrm{ distintos} \rangle = \langle (i,j,k) \rangle.$$
$\supseteq$. Por [[todo r-ciclo es una composición de r-1 2-ciclos]], $\forall (i,j,k) \in S-n$, $(i,j,k) \in A_n$. Por [[subgrupo generado es subgrupo]], entonces $A_n \supseteq \langle (i,j,k) \rangle$.
$\subseteq$. Sea $\sigma \in A_n$, demostramos que $\sigma \in \langle (i,j,k) \rangle$. Como $\sigma \in A_n$, $\exists t_1, t_2, \dots, t_{2r} \in S_n$ transposiciones tales que $\sigma = t_1 \circ t_2 \circ \dots \circ t_{2r}$. Es suficiente demostrar que $\forall t_i, t_{i+1}$, se cumple que $t_i \circ t_{i+1} \in A_n$ ya que, en ese caso, $\sigma = (t_1 \circ t_2) \circ \dots \circ (t_{2r-1} \circ t_{2r}) \in \langle (i,j,k) \rangle$. Consideramos los siguientes casos:
1. $(a,b) \circ (a,b) = id = (1,2,3) \circ (1,3,2)$.
2. $(a,b) \circ (a,c) = (a,c,b)$
3. $(a,b) \circ (c,d) = (a,b,c) \circ (b,c,d)$.

$(ii)$.
Sea $(a,b) \circ (c,d)$ con $a,b,c,d$ distintos. Por [[permutaciones son conjugadas sii tienen el mismo tipo]], $\exists \sigma \in S_n$ tal que $^\sigma ((a,b) \circ (c,d)) = (1,2) \circ (3,4)$. Dos casos:
1. $\sigma \in A_n$. Ya habríamos acabado.
2. $\sigma \notin A_n$. Consideramos $\sigma' = (1,2) \circ \sigma$. Entonces $\sigma' \in A_n$ y
$$^{\sigma'}((a,b) \circ (c,d)) = {}^{(1,2) \circ \sigma} ((a,b) \circ (c,d)) = {}^{(1,2)}((1,2) \circ (3,4)) = (1,2) \circ (3,4).$$

Veamos ahora que
$$A_n = \langle (i,j) \circ (k,l) : 1 \le i,j,k,l \le n \textrm{ distintos} \rangle.$$
$\supseteq$. $(i,j) \circ (k,l) \in S_n$, entonces $(i,j) \circ (k,l) \in A_n$ por definición de $A_n$.
$\subseteq$. Sea $\sigma \in A_n$, demostramos que $\sigma \in \langle (i,j) \circ (k,l) \rangle$. Tres casos:
1. $(a,b) \circ (a,b) = id = (a,b) \circ (c,d) \circ(a,b) \circ (c,d)$.
2. $(a,b) \circ (a,c) = (a,b) \circ (d,e) \circ (a,c) \circ (d,e)$.
3. $(a,b) \circ (c,d)$.
Tags: dem est
<!--ID: 1730228001550-->
END

