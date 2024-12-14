### Contenido principal

```ad-Formal
Una vez que saturamos o ramificamos un nodo, volvemos a la lista de nodos vivos y seleccionamos uno de ellos para explorarlo. La selección de este nodo también pude realizarse siguiendo distintos ctiterios:
- **Depth-First Search (DFS):** Búsqueda en profundidad. Se estudia el último nodo incluido en la lista (uno de los dos últimos).
- **Breadth-First Search (BFS):** Búsqueda en amplitud. Se selecciona aquel nodo vivo con la mejor cota proporcionada por la relajación lineal: la menor en caso de minimizar o la mayor en caso de maximizar.

```

```ad-note
**DFS vs BFS.**

La técnica DFS es computacionalmente muy eficiente. Cada nodo a explorar es hijo del nodo explorado en la iteración anterior. De esta forma, solo añadimos una nueva restricción sobre el problema, y podemos reoptimizar la solución mediante el algoritmo Dual-Simplex. No obstante, al modificar de forma tan ligera el problema, la nueva cota no distará mucho de la anterior, por lo que el avance del algoritmo Branch & Bound será más bien lenta. En cambio, la estrategia BFS busca explorar primero aquellos nodos donde es más probable encontrar la solución óptima. Esta estrategia suele producir árboles de exploración con menos nodos, pero tiene la desventaja de que necesita mucha memoria ya que hay que almacenar la información de muchos nodos.
```

**Tema:** [[Métodos de PLE#2. Algoritmo de Branch & Bound.]]

**Definiciones referenciadas:** [[Algoritmo de Branch & Bound]], [[Relajación lineal]], [[Nodo vivo]], [Algoritmo Dual-Simplex](Criterio de factibilidad Dual-Simplex)


---
### Anki
