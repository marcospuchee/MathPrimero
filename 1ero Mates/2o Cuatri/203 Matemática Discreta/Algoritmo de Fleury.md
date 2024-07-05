
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 17:29

```ad-theorem
Dado un [[grafo]] $G = (V, A)$. A través del procedimiento de la demostración, encontramos ciclos eulerianos ([[ciclo euleriano]]) y caminos eulerianos ([[camino euleriano]]).
```


```ad-proof
1. Verificar que $G$ es [[grafo conexo]] con todos los vértices de grado par o bien, excepto dos de ellos, todos tienen grado par ([[grado de un vértice]]).
2. Empezamos eligiendo un vértice del grafo (de grado impar si los hay).
3. Vamos recorriendo el grafo, eligiendo aristas que no se hayan recorrido. Siempre tenemos que elegir, si es posible, una arista tal que la supresión de esta no desconecte el grafo. Si no es posible es porque solo queda una arista, con lo cual, añadiremos esta última arista al camino.
4. A continuación, pasamos al otro vértice y eliminamos la arista elegida.
5. Y así sucesivamente, hasta la última arista.
```


**Tema:** [[Teoría elemental de grafos#4. Caminos y ciclos eulerianos.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el algoritmo de Fleury?
Reverso: Dado un [[Grafo]] $G = (V, A)$. A través del procedimiento de la demostración, encontramos ciclos eulerianos ([[Ciclo euleriano]]) y caminos eulerianos ([[Camino euleriano]]).
1. Verificar que $G$ es [[Grafo conexo]] con todos los vértices de grado par o bien, excepto dos de ellos, todos tienen grado par ([[Grado de un vértice]]).
2. Empezamos eligiendo un vértice del grafo (de grado impar si los hay).
3. Vamos recorriendo el grafo, eligiendo aristas que no se hayan recorrido. Siempre tenemos que elegir, si es posible, una arista tal que la supresión de esta no desconecte el grafo. Si no es posible es porque solo queda una arista, con lo cual, añadiremos esta última arista al camino.
4. A continuación, pasamos al otro vértice y eliminamos la arista elegida.
5. Y así sucesivamente, hasta la última arista.
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517437-->
END
