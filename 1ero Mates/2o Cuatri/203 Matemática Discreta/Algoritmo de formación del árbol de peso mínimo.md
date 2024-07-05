
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-23, 09:11

```ad-theorem
Sea un [[grafo]] $G$ con $n$ vértices y sea $a_1, a_2, \dots, a_{n-1}$ una sucesión de $n-1$ aristas de manera que para cada $i = 1, \dots, n-1$, la arista $a_i$ es la arista de menor peso que se pueda tomar sin formar [[ciclo]]s.

Entonces el grafo $T$ formado por $V(T) = V(G)$ y $A(T) = \{a_1, a_2, \dots, a_{n-1} \}$ es un [[árbol generador de peso mínimo]].
```


```ad-proof
Veamos primero que $T$ es [[árbol]]. Como por construcción no tiene ciclos y el número de aristas es una unidad menor del número de vértices, por el [[teorema G es un árbol sii no tiene ciclos y tiene una arista menos que el número de vértices]], entonces es árbol.

Veamos ahora que es de peso mínimo. Para ello, sea $T'$ otro [[árbol generador]] de $G$. Tenemos que demostrar que el peso de $T$ es menor o igual que el de $T'$.

En la sucesión de aristas de $T'$ (las podemos ordenar como queramos puesto que es un conjunto finito), sea $e$ la primera arista de $T$ que no está en $T'$. Si añadimos esta arista a $T'$ se formará un ciclo puesto que esto era una de las caracterizaciones de un árbol ([[teorema definiciones equivalentes de árbol]]). Sea $C$ dicho ciclo. En él debe existir una arista que no está en $T$, de lo contrario en $T$ aparecería un ciclo. Sea $f$ dicha arista del ciclo $C$, que tendrá un peso mayor o igual que el de $e$, ya que no puede ser ninguna de las anteriores a $e$, de ser así se habría formado un ciclo en el grafo $T$. Formemos ahora el grafo $T+e-f$, es decir, el grafo formado cambiando en $T$ la arista $f$ por la $e$. El grafo $T' + e-f$ es un árbol porque no tiene ciclos y tiene $n-1$ aristas. POr la hipótesis del enunciado, el peso de la arista $e$ es menor o igualq ue el peso de la arista $f$. Por tanto, el peso de $T'+e-f$ es menor o igual que el peso de $T'$. Repitiendo el proceso un número finito de veces llegamos al grafo $T$, puesto que en cada paso el grafo que queda es de menor peso que el anterior. Y la demostración queda finalizada.
```

**Tema:** [[Teoría elemental de grafos#6. Árboles generadores.]]
**Demostrado por:** [[Teorema definiciones equivalentes de árbol]], [[Teorema G es un árbol sii no tiene ciclos y tiene una arista menos que el número de vértices]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Algoritmo de formación del árbol de peso mínimo.
Reverso: Sea un [[Grafo]] $G$ con $n$ vértices y sea $a_1, a_2, \dots, a_{n-1}$ una sucesión de $n-1$ aristas de manera que para cada $i = 1, \dots, n-1$, la arista $a_i$ es la arista de menor peso que se pueda tomar sin formar [[Ciclo]]s. Entonces el grafo $T$ formado por $V(T) = V(G)$ y $A(T) = \{a_1, a_2, \dots, a_{n-1} \}$ es un [[Árbol generador de peso mínimo]].

Veamos primero que $T$ es [[Árbol]]. Como por construcción no tiene ciclos y el número de aristas es una unidad menor del número de vértices, por el [[Teorema G es un árbol sii no tiene ciclos y tiene una arista menos que el número de vértices]], entonces es árbol.

Veamos ahora que es de peso mínimo. Para ello, sea $T'$ otro [[Árbol generador]] de $G$. Tenemos que demostrar que el peso de $T$ es menor o igual que el de $T'$.

En la sucesión de aristas de $T'$ (las podemos ordenar como queramos puesto que es un conjunto finito), sea $e$ la primera arista de $T$ que no está en $T'$. Si añadimos esta arista a $T'$ se formará un ciclo puesto que esto era una de las caracterizaciones de un árbol ([[Teorema definiciones equivalentes de árbol]]). Sea $C$ dicho ciclo. En él debe existir una arista que no está en $T$, de lo contrario en $T$ aparecería un ciclo. Sea $f$ dicha arista del ciclo $C$, que tendrá un peso mayor o igual que el de $e$, ya que no puede ser ninguna de las anteriores a $e$, de ser así se habría formado un ciclo en el grafo $T$. Formemos ahora el grafo $T+e-f$, es decir, el grafo formado cambiando en $T$ la arista $f$ por la $e$. El grafo $T' + e-f$ es un árbol porque no tiene ciclos y tiene $n-1$ aristas. POr la hipótesis del enunciado, el peso de la arista $e$ es menor o igualq ue el peso de la arista $f$. Por tanto, el peso de $T'+e-f$ es menor o igual que el peso de $T'$. Repitiendo el proceso un número finito de veces llegamos al grafo $T$, puesto que en cada paso el grafo que queda es de menor peso que el anterior. Y la demostración queda finalizada.
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517427-->
END