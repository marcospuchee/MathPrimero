
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-23, 08:55

```ad-theorem
Sea $G = (V, A)$ un [[grafo hamiltoniano]] y sea $S$ un conjunto no vacío de vértices de $G$. Sea $G(V- S)$ el subgrafo inducido por el conjunto de vértices que no están en $S$, y si $c(G(V- S))$ es el número de componentes conexas ([[componente conexa]]) de $G(V-S)$, entonces:
$$c(G(V-S)) \le |S|.$$
```


```ad-proof
Sea $\Gamma$ un ciclo hamiltoniano en $G$ y sea el grafo $\widetilde G = (V, \Gamma)$. Si eliminamos $|S|$ vértices de $G$ está claro que no podemos partir el ciclo en más de $|S|$ trozos por lo que
$$c(\widetilde G(V-S)) \le |S|.$$
Pero por otro lado
$$c(G(V-S)) \le c(\widetilde G(V - S)),$$
ya que en $G(V- S)$ como mínimo hay tantas aristas como en $\Gamma - S$ y los mismos vértices. Por tanto el número de sus componentes conexas no puede superar al de $\Gamma - S$. Y el resultado está demostrado.
```

**Tema:** [[Teoría elemental de grafos#5. Caminos y ciclos hamiltonianos.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Teorema de la condición necesaria para que un grafo sea hamiltoniano
Reverso: Sea $G = (V, A)$ un [[Grafo hamiltoniano]] y sea $S$ un conjunto no vacío de vértices de $G$. Sea $G(V- S)$ el subgrafo inducido por el conjunto de vértices que no están en $S$, y si $c(G(V- S))$ es el número de componentes conexas ([[Componente conexo]]) de $G(V-S)$, entonces:
$$c(G(V-S)) \le |S|.$$
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517255-->
END

START
Básico
Anverso: Demostración de que sea $G = (V, A)$ un [[Grafo hamiltoniano]] y sea $S$ un conjunto no vacío de vértices de $G$. Sea $G(V- S)$ el subgrafo inducido por el conjunto de vértices que no están en $S$, y si $c(G(V- S))$ es el número de componentes conexas ([[Componente conexo]]) de $G(V-S)$, entonces:
$$c(G(V-S)) \le |S|.$$
Reverso: Sea $\Gamma$ un ciclo hamiltoniano en $G$ y sea el grafo $\widetilde G = (V, \Gamma)$. Si eliminamos $|S|$ vértices de $G$ está claro que no podemos partir el ciclo en más de $|S|$ trozos por lo que
$$c(\widetilde G(V-S)) \le |S|.$$
Pero por otro lado
$$c(G(V-S)) \le c(\widetilde G(V - S)),$$
ya que en $G(V- S)$ como mínimo hay tantas aristas como en $\Gamma - S$ y los mismos vértices. Por tanto el número de sus componentes conexas no puede superar al de $\Gamma - S$. Y el resultado está demostrado.
Tags: demostración MatDiscreta
<!--ID: 1717176517257-->
END
