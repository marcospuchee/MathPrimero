
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-28, 09:00

```ad-lemma
Dado un [[Grafo]] $G = (V,A)$ con $m$ aristas, es decir $|A| = m$, se tiene:
$$\sum_{v \in V} \textrm{grado}(v) = 2m.$$
[[Grado de un vértice]]
```


```ad-proof
Supongamos que el grafo no tiene ningún [[Lazo]]. Procederemos por inducción sobre el número de vértices, $n$.

$n=1$.
Trivial, pues al no haber lazos, el grado del único vértice es $0$, que coincide con el doble del número de aristas, que es cero.

$n \implies n+1$.
Consideramos dos grafos $G$ y $H$ cuyos conjuntos de vértices son respectivamente $\{v_1, \dots, v_n\}$ y $\{v_1, \dots, v_n\} \cup \{a\}$. Así mismo, el conjunto de aristas de $H$ estará formado por las de $G$ junto con las aristas incidentes con el vértice $a$.
Descomponemos el conjunto $V$ en dos subconjuntos $A$ y $B$, siendo $A$ el conjunto de vértices que tengan una arista incidente con $a$ y $B$ el resto de los vértices de $V$. Es evidente que $A$ y $B$ son disjuntos y que su unión es $V$.
$$\sum_{x \in V(G)} \textrm{grado}_H(x) = \sum_{x \in A} \textrm{grado}_H(x) + \sum_{x \in B} \textrm{grado}_H(x).$$
Si $x \in A$, entonces $\textrm{grado}_H(x) = \textrm{grado}_G(x) + x(a)$, siendo $\textrm{grado}_G(x)$ el grado de $x$ en el grafo $G$ y $x(a)$ el número de aristas incidentes con $x$ y $a$ en el grafo $H$. Si $x \in B$, entonces $\textrm{grado}_H(x) = \textrm{grado}_G(x)$. Se tiene por tanto:
$$\sum_{x \in V(G)} \textrm{grado}_H(x) = \sum_{x \in A}(\textrm{grado}_G(x) + x(a)) + \sum_{x \in B} \textrm{grado}_G(x) = \sum_{x \in A \cup B} \textrm{grado}_G (x) + \sum_{x \in A} x(a).$$
Si hacemos valer la hipótesis de inducción y $A(G)$ es el conjunto de aristas del grafo $G$, $A(H)$ el conjunto de aristas del grafo $H$, el primer sumando es justamente $2|A(G)|$, el segundo sumando es simplemente el grado de $a$, $\textrm{grado}_H(a)$. Por tanto,
$$\sum_{x \in V(G)} \textrm{grado}_H(x) = 2|A(G)| + \textrm{grado}_H(a).$$
Tenemos finalmente:
$$
\begin{eqnarray}
\sum_{x \in V(H)} \textrm{grado}(x) &=& \sum_{x \in V(G)} \textrm{grado}_H(x) + \textrm{grado}_H(a) \\
&=& 2|A(G)| + \textrm{grado}_H(a) + \textrm{grado}_H(a) \\
&=& 2(|A(G)| + \textrm{grado}_H(a)) = 2|A(H)|.
\end{eqnarray}
$$
```

**Tema:** [[Teoría elemental de grafos#1. Noción de grafo. Isomorfismo. Grafos completos]]
**Corolarios:**

---
### Anki
