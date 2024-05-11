
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-16, 08:35

```ad-proposition
Todo [[árbol]] que cumpla $|V| > 1$ tiene al menos dos hojas ([[Hoja del árbol]]).
```

```ad-proof
Como el número de vértices es finito, existirá un [[camino]] de longitud máxima. Sea este camino $v_0 v_1 v_2 \dots v_n$, entonces afirmamos que si $v_0$y $v_n$ no tuvieran grado $1$ ([[Grado de un vértice]]), llegaríamos a una contradicción.
En efecto, si el grado de $v_0$ fuera mayoyr de $1$, entonces existiría otra arista diferente de $v_0 v_1$ adyacente con $v_0$. Si el vértice adyacente con esta nueva arista estuviera en la secuencia, entonces habría un [[ciclo]], sino  podríamos ampliar la secuencia con dicho vértice y hacer el camino más largo. En mabos casos llegamos a una contradicción.
El mismo razonamiento vale para $v_n$.
```

**Tema:** [[Teoría elemental de grafos#3. Estructuras tipo árbol]]
**Corolarios:** [[Teorema definiciones equivalentes de árbol]]

---
### Anki
