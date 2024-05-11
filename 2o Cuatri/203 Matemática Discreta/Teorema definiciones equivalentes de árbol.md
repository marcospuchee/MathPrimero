
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-16, 08:40

```ad-theorem
Para todo [[grafo]] $G = (V(G), A)$ son equivalentes:
1. $G$ es un [[árbol]].
2. Dados dos vértices $u,v \in V(G)$, existe exactamente un sólo [[camino]] que conecta $u$ con $v$.
3. $G$ es un [[grafo conexo]], y si suprimimos una arista cualquiera, deja de serlo.
4. $G$ no tiene [[ciclo]]s y si añadimos una arista, el nuevo grafo obtendio tiene un ciclo.
5. $G = (V(G), A)$ es conexo y $|A| = |V(G)| - 1$.
```

```ad-proof
$1 \implies 2$.
$G$ es un árbol, por tanto es conexo. Dados $u,v \in V(G)$, existe al menos un camino qeu los une. Supongamos que entre los vértices $u$ y $v$ exisen dos caminos. Denotemos por $x$ el vértice donde estos caminos divergen por primera vez y $w$ el vértice donde estos caminos convergen nuevamente. Por tanto los dos caminos diferentes entre los vértices $xx$ y $w$ forman un ciclo, lo cual contradice la definición de árbol.
$2 \implies 1$.
Supongamos que $\forall u,v \in V(G)$, existe un único camino que los une. Entonces $G$ es conexo y sin ciclos, pues de existir un ciclo, existirían dos vértices conectados por dos caminos.

$1 \implies 3$. 
Supongamos primero que tenemos un grafo $G$ conexo y sin ciclos. Queremos probar que se desconecta al quitar una arista cualquiera. Dada una arista $e$ de $G$, formamos el grafo $G - \{e\}$ eliminándola. Si $G - \{e\}$ fuera conexo, podríamos conectar en $G - \{e\}$ los vértices de la arista $e$, y añadiendo la arista $e$ tendríamos un ciclo en $G$: contradicción. Así, $G-\{e\}$ no es conexo (sea cual sea la arista $e$ elegida).
$3 \implies 1$.
Por hipótesis, $G$ es conexo y se desconecta si quitamos cualquier arista. Si tuviera un ciclo, entonces al suprimir una arista de dicho ciclo, obtendríamos un grafo que sería conexo, lo que supone una contradicción con la hipótesis.

$1 \implies 4$.
Como $G$ es conexo, dos vértices cualesquiera se pueden conectar por un camino en $G$. Al añadir una arista entre estos vértices, esta arista junto con el camino mencionado forma un ciclo.
$4 \implies 1$.
En el otro sentido, sea $G$  un grafo sin ciclos para el que añadir una arista supone la formación de un ciclo. Supongamos que $G$ no es conexo. Entonces existen al menos dos vértices $u$ y $v$ que no son conectados. Al agregar la arista $\{uv\}$ aparece un ciclo, lo cual implica la existencia de un camino entre $u$ y $v$. Contradicción. $G$ es conexo por tanto es un árbol.

$1 \implies 5$.
Haremos la demostración por inducción sobre $|V|$. Si $|V| = 1$, no puede tener arista, y por tanto $|A| = 0$. Suponiendo cierto $n-1$, veamos que también es cierto $n$. Sabemos que todo árbol tiene al menos una hoja ([[Proposición número de hojas de un árbol]]). Si eliminamos esta hoja del grafo, lo que queda, el grafo $G' = (V', A')$, sigue siendo conexo sin ciclos. Por tanto, un árbol, con un vértice y una arista menos. Aplicando la hipótesis de inducción, tenemos que
$$|A'| = |V'| -1 = (n-1)-1 = n-2.$$
Entonces, $|A| = |A'|+1 = (n-2)+1 = n-1$.
$5 \implies 1$.
Si un grafo conexo con $|A| = |V(G)| -1$ tuviera un ciclo, entonces podríamos quitarle una arista (del ciclo mismo) y el subgrafo seguirá siendo conexo. Pero tendríamos un grafo conexo con dos aristas menos que la cantidad de vértices, y esto contradice la hipótesis.
```


**Tema:** [[Teoría elemental de grafos#3. Estructuras tipo árbol]]
**Demostrado por:** [[Proposición número de hojas de un árbol]]
**Consecuencias:** [[Teorema G es un árbol sii no tiene ciclos y tiene una arista menos que el número de vértices]]

---
### Anki
