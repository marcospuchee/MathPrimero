
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-05, 10:45

```ad-theorem
Un grafo $G =(V, A)$ es [[grafo bipartito]] $\iff$ no tiene ningún [[ciclo]] de longitud impar.
```


```ad-proof
$\rightarrow$.
Si $G$ es bipartito con $V = D \cup I$, dado un ciclo $v_0, v_1, \dots, v_{k-1}, v_k (= v_0)$, de longitud $k$, podemos suponer que $v_0 \in D$ entonces necesariamente $v_1 \in I, v_2 \in D, \dots$ Como $v_k = v_0 \in D$, $v_{k-1} \in I$ y por tanto $k-1$ ha de ser impar, luego $k$ es par.

$\leftarrow$. Podemos suponer que $G$ es [[grafo conexo]] (sino, trabajaríamos con cada una de sus [[componente conexa]]). Elegimos un vértice $v_0 \in V$ cualquiera. Para cada vértice $v \in V$, sea $p_v$ cualquier camino minimal que una $v_0$ con $v$. Y denotamos $d_v$ su longitud. Notar que todos los caminos minimales que unen dos vértices tienen la misma longitud.
Definimos ahora
$$D = \{v \in V: d_v \textrm{ es par } \}, \quad I = \{v \in V : d_v \textrm{ es impar } \}.$$
Obviamente, $V = D \cup I$ es una partición ([[partición de un conjunto]]) de $V$. Vamos a comprobar, por reducción al absurdo, que el grafo $G = (D \cup I, A)$ es bipartito.
Si el grafo $G = (D \cup I, A)$ no fuerea bipartito es porque existirían dos vértices $u,v$ que, o bien están los dos en $D$, o bien están los dos en $I$, y que están unidos por una única arista $\{u,v \}$.
Consideremos el camino cerrado definido por la unión de $p_u$, $\{u,v\}$ y $p_v$ (de $v_0$ a $u$, de $u$ a $v$, y de $v$ a $v_0$). La longitud total de este camino cerrado es $d_u + 1 + d_v$, que es un número impar, tanto si $u,v \in D$, como si $u,v \in I$. De este camino cerrado siempre se puede sacar un ciclo (sin repeticiones de vértices, sacado del inicial y final) de longitud impar (en efecto, si el camino se descompondrá en ciclos de longitud par, entonces la longitud del camino, que es la suma de las longitudes de los ciclos en que se descompone, sería par), lo cual contradice la hipótesis. Por tanto, el grafo $G = (D \cup I, A)$ es bipartito.
```

**Tema:** [[Teoría elemental de grafos#7. Grafo bipartito. El Teorema del matrimonio.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Condición suficiente y necesaria para que un grafo sea bipartito
Reverso: Un grafo $G =(V, A)$ es [[Grafo bipartito]] $\iff$ no tiene ningún [[Ciclo]] de longitud impar.
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517358-->
END

START
Básico
Anverso: Demostración de que un grafo $G =(V, A)$ es [[Grafo bipartito]] $\iff$ no tiene ningún [[Ciclo]] de longitud impar.
Reverso: $\rightarrow$.
Si $G$ es bipartito con $V = D \cup I$, dado un ciclo $v_0, v_1, \dots, v_{k-1}, v_k (= v_0)$, de longitud $k$, podemos suponer que $v_0 \in D$ entonces necesariamente $v_1 \in I, v_2 \in D, \dots$ Como $v_k = v_0 \in D$, $v_{k-1} \in I$ y por tanto $k-1$ ha de ser impar, luego $k$ es par.

$\leftarrow$. Podemos suponer que $G$ es [[Grafo conexo]] (sino, trabajaríamos con cada una de sus [[Componente conexa]]). Elegimos un vértice $v_0 \in V$ cualquiera. Para cada vértice $v \in V$, sea $p_v$ cualquier camino minimal que una $v_0$ con $v$. Y denotamos $d_v$ su longitud. Notar que todos los caminos minimales que unen dos vértices tienen la misma longitud.
Definimos ahora
$$D = \{v \in V: d_v \textrm{ es par } \}, \quad I = \{v \in V : d_v \textrm{ es impar } \}.$$
Obviamente, $V = D \cup I$ es una partición ([[Partición de un conjunto]]) de $V$. Vamos a comprobar, por reducción al absurdo, que el grafo $G = (D \cup I, A)$ es bipartito.
Si el grafo $G = (D \cup I, A)$ no fuerea bipartito es porque existirían dos vértices $u,v$ que, o bien están los dos en $D$, o bien están los dos en $I$, y que están unidos por una única arista $\{u,v \}$.
Consideremos el camino cerrado definido por la unión de $p_u$, $\{u,v\}$ y $p_v$ (de $v_0$ a $u$, de $u$ a $v$, y de $v$ a $v_0$). La longitud total de este camino cerrado es $d_u + 1 + d_v$, que es un número impar, tanto si $u,v \in D$, como si $u,v \in I$. De este camino cerrado siempre se puede sacar un ciclo (sin repeticiones de vértices, sacado del inicial y final) de longitud impar (en efecto, si el camino se descompondrá en ciclos de longitud par, entonces la longitud del camino, que es la suma de las longitudes de los ciclos en que se descompone, sería par), lo cual contradice la hipótesis. Por tanto, el grafo $G = (D \cup I, A)$ es bipartito.
Tags: demostración MatDiscreta
<!--ID: 1717176517360-->
END
