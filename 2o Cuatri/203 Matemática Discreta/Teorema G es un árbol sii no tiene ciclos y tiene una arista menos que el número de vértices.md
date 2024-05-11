
---
mathLink: $G$ árbol $\iff G$ no tiene ciclos y $|A| = |V|-1$.
---
### Contenido Principal

**Fecha:** 2024-04-16, 08:57

```ad-theorem
Sea $G = (V, A)$ un [[grafo]] con $|V| = n$. Son equivalentes:
1. $G$ es un [[árbol]].
2. $G$ no tiene [[ciclo]]s y $|A| = n-1$.
```


```ad-proof
Gracias a [[Teorema definiciones equivalentes de árbol]], sabemos que $i) \implies ii)$.

$ii \implies i$.
Por reducción al absurdo, suponemos que $G$ no tiene ciclos y que $|A| = n-1$, pero que no es conexo. Dividimos el grafo en sus componentes conexas ([[Componente conexa]]), $G_i = (V_i, A_i)$, para $i = 1, \dots, k$ con $k>1$.
Cada componente conexa no tiene ciclos, porque si existiera un ciclo en alguna de ellas, entonces el mismo ciclo lo sería de $G$. Obviamente, cada componente conexa es conexa. Por lo tanto, cada componente conexa es un árbol, y eso implica que $|A_i| = |V_i| -1$, $\forall i = 1, \dots, k$. Por tanto,
$$|A| = \sum_{i = 1}^k |A_i| = \sum_{i = 1}^k(|V-i| -1) = \left ( \sum_{i = 1}^k |V_i| \right ) - k = n-k < n-1,$$
lo que contradice la hipótesis $|A| = n-1$.
```

**Tema:** [[Teoría elemental de grafos#3. Estructuras tipo árbol]]
**Demostrado por:**
**Consecuencias:**

---
### Anki
