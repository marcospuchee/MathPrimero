### Contenido Principal

```ad-proposition
Sea $X \neq \emptyset$, y $\sigma, \tau \in S_X$. Si las permutaciones ([[permutación]]) $\sigma$ y $\tau$ son [[permutaciones disjuntas]], entonces
$$\sigma \circ \tau = \tau \circ \sigma.$$
```

^e53775

```ad-proof
Sea $x \in X$. Hay dos casos:
1. $x \notin \textrm{supp}(\sigma) \land x \notin \textrm{supp}(\tau)$ ([[soporte de una permutación]]). Entonces $\sigma \circ \tau (x) = x = \tau \circ \sigma(x)$.
2. $x \in \textrm{supp}(\sigma)$. Como son disjuntas, $x \notin \textrm{supp}(\tau)$. 
Notemos que $x \in \textrm{supp}(\sigma) \implies \sigma (x) \in \textrm{supp}(\sigma)$: supongamos que $\sigma (x) \notin \textrm{supp}(\sigma)$. Entonces, $\sigma(\sigma(x)) = \sigma(x)$. Como $\sigma$ es biyectiva, entonces $\sigma (x) = x$, lo cual es una contradicción. Luego $\sigma(x) \in \textrm{supp}(\sigma)$.
Por tanto, $\sigma \circ \tau (x) = \sigma(\tau(x)) = \sigma(x) = \tau(\sigma(x)) = \tau \circ \sigma(x)$.
3. $x \in \textrm{supp}(\tau)$. Análogo al caso anterior.

```

**Tema:** [[Teoría de grupos#3. Estructura de ciclos.]]

---
### Anki

START
Básico
Anverso: Demostración de que sea $X \neq \emptyset$, y $\sigma, \tau \in S_X$. Si las permutaciones ([[permutación]]) $\sigma$ y $\tau$ son [[permutaciones disjuntas]], entonces
$$\sigma \circ \tau = \tau \circ \sigma.$$
Reverso: Sea $x \in X$. Hay dos casos:
1. $x \notin \textrm{supp}(\sigma) \land x \notin \textrm{supp}(\tau)$ ([[soporte de una permutación]]). Entonces $\sigma \circ \tau (x) = x = \tau \circ \sigma(x)$.
2. $x \in \textrm{supp}(\sigma)$. Como son disjuntas, $x \notin \textrm{supp}(\tau)$. 
Notemos que $x \in \textrm{supp}(\sigma) \implies \sigma (x) \in \textrm{supp}(\sigma)$: supongamos que $\sigma (x) \notin \textrm{supp}(\sigma)$. Entonces, $\sigma(\sigma(x)) = \sigma(x)$. Como $\sigma$ es biyectiva, entonces $\sigma (x) = x$, lo cual es una contradicción. Luego $\sigma(x) \in \textrm{supp}(\sigma)$.
Por tanto, $\sigma \circ \tau (x) = \sigma(\tau(x)) = \sigma(x) = \tau(\sigma(x)) = \tau \circ \sigma(x)$.
3. $x \in \textrm{supp}(\tau)$. Análogo al caso anterior.
Tags: dem est
<!--ID: 1727083427914-->
END

START
Respuesta anidada
Sea $X \neq \emptyset$, y $\sigma, \tau \in S_X$. Si las permutaciones ([[permutación]]) $\sigma$ y $\tau$ son {{c1::[[permutaciones disjuntas]]}}, entonces
{{c2::$$\sigma \circ \tau = \tau \circ \sigma.$$}}
Tags:
<!--ID: 1727083427916-->
END