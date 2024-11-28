
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-17, 11:14

```ad-theorem
Sea $G = (V(G), A)$ un [[grafo]]. 
$G$ es [[grafo euleriano]] $\iff$ el grado de todos los vértices ([[Grado de un vértice]]) es par.
```


```ad-proof
$\rightarrow$.
Si el grafo $G$ es euleriano, es claramente conexo ([[grafo conexo]]) puesto que la existencia de un [[ciclo euleriano]] hace que se puedan conectar cualquier par de vértices por un camino.
Supongamos que el grafo no tiene [[lazo]]s. El grado de todos los vértices debe ser par puesto que en el ciclo euleriano intervienen todas las aristas una sola vez, por lo que la cuenta de ellas en el ciclo para cada vértice dara su grado.Como cada vértice distinto del primero tendrá siempre una arista que le precede y otra que le suceda, todos los vértices distintos del primero tienen grado par.
En cuanto al primero y al último vértice del ciclo, como es el mismo, computarán en suma un número par para las aristas del interior de la secuencia del ciclo y en dos unidades para los extremos, lo cual da una suma par. Por último, si hay lazos, cada uno de ellos suma dos unidades al grado, así que el grado de cada vértice seguirá siendo par.

$\leftarrow$.
Sea $G$ un [[grafo conexo]] tal que todos sus vértices tienen grado par. Tenemos que construir un ciclo euleriano. Notar primero que $G$ no puede ser un árbol, porque en un árbol y asabemos que al menos uno de los vértices es tiene grado $1$. Por tanto, si $G$ no es un árbol, pero sí que es conexo, entonces hay un ciclo, $\Gamma$.
Procederemos por inducción sobre el número de aristas de $G = (V, A)$:
$|A| = 1$ no puede ser porque entonces solo habría dos vértices y necesariamente tendrían grado $1$. Una cosa similar pasa si $|A| = 2$. Luego el caso base es $|A| = 4$, entonces tenemos tres vértices y el ciclo euleriano $\Gamma = A$.
Suponemos ahora que la condición se verifica cuando $|A| \le n$. La demostraremos para $|A| = n+1$ por reducción al absurdo. Suponemos que $\Gamma \neq A$. Consideramos el grafo $G' = (V, A - \Gamma)$. Sean $G_1, G_2, \dots, G_p$ las componentes conexas ([[componente conexa]]) de $G'$. Cogemos una de estas componentes conexas, $G_i = (V_i, A_i)$.
Si $|V_i| = 1$, es porque la componente conexa solo tiene un vértice y ninguna arista. Esto quiere decir que este punto formaba parte del ciclo $\Gamma$ y al final de la demostración veremos que acabará también conectado gracias al ciclo euleriano que construiremos.
Suponemos ahora que $|V_i| > 1$. Todos los vértices de $G_i$ tienen grado par, $G_i$ es conexo, y $|A_i| \le n$. Por la hipótesis de inducción, $G_i$ tiene un ciclo euleriano, $\Gamma_i$ (es decir, que pasa por todos los vértices de $G_i$ y por taodas las aristas $A_i$). Entonces, $\Gamma$ y $\Gamma_i$ tienen que tener una intersección común (porque $G$ es conexo y porque los $G_i$ eran subgrafos conexos maximales). Finalmente, podemos combinar el ciclo $\Gamma$ con todos los ciclos $\Gamma_i$ y obtener un ciclo euleriano, que pasa por todos los vértices de $G$ y por todas sus aristas,  solo una vez, y que vuelve al vértice de donde había salido.
```


**Tema:** [[Teoría elemental de grafos#4. Caminos y ciclos eulerianos.]]
**Demostrado por:**
**Consecuencias:** [[Corolario existe un camino euleriano sii G es conexo y hay sólo dos vértices de grado impar]]

---
### Anki

START
Respuesta anidada
Sea $G = (V(G), A)$ un [[Grafo]]. 
{{c1::$G$ es [[Grafo euleriano]]}} $\iff$ {{c2::el grado de todos los vértices ([[Grado de un vértice]]) es par.}}
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517216-->
END

START
Básico
Anverso: Demostración de que sea $G = (V(G), A)$ un [[Grafo]]. 
$G$ es [[Grafo euleriano]] $\iff$ el grado de todos los vértices ([[Grado de un vértice]]) es par.
Reverso: $\rightarrow$.
Si el grafo $G$ es euleriano, es claramente conexo ([[Grafo conexo]]) puesto que la existencia de un [[Ciclo euleriano]] hace que se puedan conectar cualquier par de vértices por un camino.
Supongamos que el grafo no tiene [[Lazo]]s. El grado de todos los vértices debe ser par puesto que en el ciclo euleriano intervienen todas las aristas una sola vez, por lo que la cuenta de ellas en el ciclo para cada vértice dara su grado.Como cada vértice distinto del primero tendrá siempre una arista que le precede y otra que le suceda, todos los vértices distintos del primero tienen grado par.
En cuanto al primero y al último vértice del ciclo, como es el mismo, computarán en suma un número par para las aristas del interior de la secuencia del ciclo y en dos unidades para los extremos, lo cual da una suma par. Por último, si hay lazos, cada uno de ellos suma dos unidades al grado, así que el grado de cada vértice seguirá siendo par.

$\leftarrow$.
Sea $G$ un [[Grafo conexo]] tal que todos sus vértices tienen grado par. Tenemos que construir un ciclo euleriano. Notar primero que $G$ no puede ser un árbol, porque en un árbol y asabemos que al menos uno de los vértices es tiene grado $1$. Por tanto, si $G$ no es un árbol, pero sí que es conexo, entonces hay un ciclo, $\Gamma$.
Procederemos por inducción sobre el número de aristas de $G = (V, A)$:
$|A| = 1$ no puede ser porque entonces solo habría dos vértices y necesariamente tendrían grado $1$. Una cosa similar pasa si $|A| = 2$. Luego el caso base es $|A| = 4$, entonces tenemos tres vértices y el ciclo euleriano $\Gamma = A$.
Suponemos ahora que la condición se verifica cuando $|A| \le n$. La demostraremos para $|A| = n+1$ por reducción al absurdo. Suponemos que $\Gamma \neq A$. Consideramos el grafo $G' = (V, A - \Gamma)$. Sean $G_1, G_2, \dots, G_p$ las componentes conexas ([[Componente conexo]]) de $G'$. Cogemos una de estas componentes conexas, $G_i = (V_i, A_i)$.
Si $|V_i| = 1$, es porque la componente conexa solo tiene un vértice y ninguna arista. Esto quiere decir que este punto formaba parte del ciclo $\Gamma$ y al final de la demostración veremos que acabará también conectado gracias al ciclo euleriano que construiremos.
Suponemos ahora que $|V_i| > 1$. Todos los vértices de $G_i$ tienen grado par, $G_i$ es conexo, y $|A_i| \le n$. Por la hipótesis de inducción, $G_i$ tiene un ciclo euleriano, $\Gamma_i$ (es decir, que pasa por todos los vértices de $G_i$ y por taodas las aristas $A_i$). Entonces, $\Gamma$ y $\Gamma_i$ tienen que tener una intersección común (porque $G$ es conexo y porque los $G_i$ eran subgrafos conexos maximales). Finalmente, podemos combinar el ciclo $\Gamma$ con todos los ciclos $\Gamma_i$ y obtener un ciclo euleriano, que pasa por todos los vértices de $G$ y por todas sus aristas,  solo una vez, y que vuelve al vértice de donde había salido.
Tags: demostración MatDiscreta
<!--ID: 1718033661453-->
END
