
---
mathLink: $|A| \ge |V| - 1.$
---
### Contenido Principal

**Fecha:** 2024-04-09, 08:10

```ad-theorem
Si $G = (V,A)$ es un [[Grafo conexo]], entonces $|A| \ge |V| -1$.
```

```ad-proof
Procederemos por inducción sobre $n = |V|$.

$n = 1$.
Sólo hay un vértice y ninguna arista. El único grafo con un vértice es conexo y verifica que $|A| = 0 = |V| - 1$.

$n \implies n+1$.
Sea un vértice $v_0$ y $k$ su grado ([[Grado de un vértice]]). Si quitamos de $G$ el vértice $v_0$ y las aristas asociadas, entonces como mucho pueden quedar $k$ componentes conexas ([[Componente conexa]]), $G_i = (V_i, A_i)$, para $i = 1, \dots, l \le k$. Aplicando la hipótesis de inducción a cada componente conexa, tenemos que $|A_i| \ge |V_i| - 1$. Si ahora sumamos, se obtiene:
$$\sum_{i = 1}^l |A_i| \ge \sum_{i = 1}^l (|V_i| - 1) = \left ( \sum_{i = 1}^l |V_i| \right ) - l.$$
Si ahora tenemos en cuenta el vértice que habiamos quitado y sus $k$ aristas, entonces
$$|A| = k + \sum_{i = 1}^l |A_i| \ge \left ( \sum_{i = 1}^l |V_i| \right ) + (k-l) = |V| - 1 + (k-l) \ge |V| -1.$$
```

**Tema:** [[Teoría elemental de grafos#2. Subgrafos, matriz de adyacencia y grafos conexos]]
**Demostrado por:**
**Consecuencias:**

---
### Anki
