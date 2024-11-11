### Contenido Principal

```ad-proposition
Sea $X \neq \emptyset$.
1. Sea $(a_1, a_2, \dots, a_r)$ ([[r-ciclo]]) $\in S_X$. Entonces, $\forall 1 \le i \le r-1$,
$$(a_1, a_2, \dots, a_r)^i (a_1) = a_{i+1}.$$
En particular $o(a_1, a_2, \dots, a_r) = r$ ([[orden de un elemento de un grupo]]).
2. Sea $\sigma \in S_X$ con descomposición en ciclos disjuntos ([[teorema de la descomposición en ciclos]])
$$\sigma = c_1 \circ c_2 \circ \dots \circ c_r.$$
Entonces $o(\sigma) = \textrm{mcm}(o(c_1), o(c_2), \dots, o(c_r))$.
```

^4e5f25

```ad-proof
1. Denotamos $c = (a_1, a_2, \dots, a_r)$. Demostramos que $\forall 1 \le i \le r-1$, $c^i (a_1) = a_{i+1}$. Inducción sobre $i$.
Si $i = 1$. Trivial: $c(a_1) = a_2$.
Supongamos el resultado para $i-1$, veámoslo para $i$:
$$c^i(a_1) = c(c^{i-1}(a_1)) = c(a_i) = a_{i+1}.$$
En particular, para $1 \le i \le r-1$, $c^i \neq \textrm{id} \implies o(c) \ge r$. Demostramos que $o(c) = r$: $c^r(a_1) = c(c^{r-1}(a_1)) = c(a_r) = a_1$. ¿ $c^r(a_i) = a_i$ ? 
$c^r(a_i) = (a_i, a_{i+1}, \dots, a_{i-1})^r(a_i) = a_i \implies o(c) = r$.

2. (Esta demostración se puede generalizar a $n$) Denotamos $n = o(c_1 \circ c_2)$, $n_1 = o(c_1)$ y $n_2 = o(c_2)$. Sea $\textrm{mcm}(n_1, n_2) = k$. Es decir, $\exists k_1 \in \mathbb Z$ tal que $k = k_1 n_1$, y $\exists k_2 \in \mathbb Z$ tal que $k = k_2 n_2$. Tenemos que:
$$(c_1 \circ c_2)^k = c_1^k \circ c_2^k = c_1^{k_1 n_1} \circ c_2^{k_2 n_2} = (c_1^{n_1})^{k_1} \circ (c_2^{n_2})^{k_2} = id,$$
luego $n | k$.
$\textrm{id} = (c_1 \circ c_2)^n = c_1^n \circ c_2^n$, de lo que se deduce que $c_1^n = c_2^{-n}$, y $c_2^n = c_1^{-n}$. Notemos que si $c_1, c_2$ son [[permutaciones disjuntas]], entonces $c_1^n, c_2^n$ también lo son. Veamos que $c_1^n = c_2^{-n} \implies c_1^n = \textrm{id}$. Como son disjuntas, $x \in \textrm{supp}(c_1^n)$ $\implies$ $x \notin \textrm{supp}(c_2^{-n})$. Sin embargo, $c_1^n(x) = c_2^{-n}(x) = x$, luego $c_2^n = c_1^{-n}$, y $c_2^n = \textrm{id}$. Como $n_1 | n$ y $n_1 | n$, entonces $\textrm{mcm}(n_1, n_2) = k|n$.

```

**Tema:** [[Teoría de grupos#4. Exponenciales y orden de un elemento.]]

---
### Anki

START
Básico
Anverso: Cuál es el orden de un $r$-ciclo
Reverso: Sea $(a_1, a_2, \dots, a_r)$ ([[r-ciclo]]) $\in S_X$. Entonces, $\forall 1 \le i \le r-1$,
$$(a_1, a_2, \dots, a_r)^i (a_1) = a_{i+1}.$$
En particular $o(a_1, a_2, \dots, a_r) = r$ ([[Orden de un elemento de un grupo]]).
<!--ID: 1727339263740-->
END

START
Básico
Anverso: Demostración de que sea $(a_1, a_2, \dots, a_r)$ ([[r-ciclo]]) $\in S_X$. Entonces, $\forall 1 \le i \le r-1$,
$$(a_1, a_2, \dots, a_r)^i (a_1) = a_{i+1}.$$
En particular $o(a_1, a_2, \dots, a_r) = r$ ([[Orden de un elemento de un grupo]]).
Reverso: Denotamos $c = (a_1, a_2, \dots, a_r)$. Demostramos que $\forall 1 \le i \le r-1$, $c^i (a_1) = a_{i+1}$. Inducción sobre $i$.
Si $i = 1$. Trivial: $c(a_1) = a_2$.
Supongamos el resultado para $i-1$, veámoslo para $i$:
$$c^i(a_1) = c(c^{i-1}(a_1)) = c(a_i) = a_{i+1}.$$
En particular, para $1 \le i \le r-1$, $c^i \neq \textrm{id} \implies o(c) \ge r$. Demostramos que $o(c) = r$: $c^r(a_1) = c(c^{r-1}(a_1)) = c(a_r) = a_1$. ¿ $c^r(a_i) = a_i$ ? 
$c^r(a_i) = (a_i, a_{i+1}, \dots, a_{i-1})^r(a_i) = a_i \implies o(c) = r$.
Tags: dem est
<!--ID: 1727339263742-->
END

START
Básico
Anverso: Cuál es el orden de una permutación a partir de su descomposición en ciclos?
Reverso: Sea $\sigma \in S_X$ con descomposición en ciclos disjuntos ([[teorema de la descomposición en ciclos]])
$$\sigma = c_1 \circ c_2 \circ \dots \circ c_r.$$
Entonces $o(\sigma) = \textrm{mcm}(o(c_1), o(c_2), \dots, o(c_r))$.
<!--ID: 1727339263744-->
END

START
Básico
Anverso: Demostración de que sea $\sigma \in S_X$ con descomposición en ciclos disjuntos ([[teorema de la descomposición en ciclos]])
$$\sigma = c_1 \circ c_2 \circ \dots \circ c_r.$$
Entonces $o(\sigma) = \textrm{mcm}(o(c_1), o(c_2), \dots, o(c_r))$.
Reverso: (Esta demostración se puede generalizar a $n$) 
Denotamos $n = o(c_1 \circ c_2)$, $n_1 = o(c_1)$ y $n_2 = o(c_2)$. Sea $\textrm{mcm}(n_1, n_2) = k$. Es decir, $\exists k_1 \in \mathbb Z$ tal que $k = k_1 n_1$, y $\exists k_2 \in \mathbb Z$ tal que $k = k_2 n_2$. Tenemos que:
$$(c_1 \circ c_2)^k = c_1^k \circ c_2^k = c_1^{k_1 n_1} \circ c_2^{k_2 n_2} = (c_1^{n_1})^{k_1} \circ (c_2^{n_2})^{k_2} = id,$$
luego $n | k$.
$\textrm{id} = (c_1 \circ c_2)^n = c_1^n \circ c_2^n$, de lo que se deduce que $c_1^n = c_2^{-n}$, y $c_2^n = c_1^{-n}$. Notemos que si $c_1, c_2$ son [[permutaciones disjuntas]], entonces $c_1^n, c_2^n$ también lo son. Veamos que $c_1^n = c_2^{-n} \implies c_1^n = \textrm{id}$. Como son disjuntas, $x \in \textrm{supp}(c_1^n)$ $\implies$ $x \notin \textrm{supp}(c_2^{-n})$. Sin embargo, $c_1^n(x) = c_2^{-n}(x) = x$, luego $c_2^n = c_1^{-n}$, y $c_2^n = \textrm{id}$. Como $n_1 | n$ y $n_1 | n$, entonces $\textrm{mcm}(n_1, n_2) = k|n$.
Tags: dem est
<!--ID: 1727339263746-->
END