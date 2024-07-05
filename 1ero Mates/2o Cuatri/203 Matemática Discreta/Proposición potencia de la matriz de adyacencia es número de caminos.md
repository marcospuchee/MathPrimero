
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-09, 07:53

```ad-proposition
Sea $G = (V,A)$ un [[Grafo]] con conjunto de vértices $\{v_1, v_2, \dots, v_n\}$ y sea $A_G$ su [[Matriz de adyacencia]]. Sea $(A_G)^k$ la potencia $k$-ésima de la matriz de adyacencia. Sea $a_{ij}^{(k)}$ la entrada $i,j$ de la matriz $(A_G)^k$. 

Entonces el número de [[Camino]]s (pueden repetir vértices y aristas) de longitud $k$ entre los vértices $v_i$ y $v_j$ es la entrada $a_{ij}$ de la matriz $A^k_G$.
```


```ad-proof
Procederemos por inducción sobre el exponente $k$ en $A_G^k$.

$k=1$. La proposición se reudce a la propia definición de la matriz de adyacencia y por lo tanto este caso es trivial.

$k-1 \implies k$. Tomemos dos vértices cualesquiera $v_i$ y $v_j$ (que pueden coincidir) de $V$. Un camino de longitud $k$ que una $v_i$ con $v_j$ será de la forma:
$$v_i x_1 x_2 x_3 \dots x_{k-1} v_j.$$
Esto se puede descomponer en $v_i x_1$ y $x_1 x_2 x_3 \dots x_{k-1} v_j$. El primer camino de longitud $1$ se corresponde con una arista adyacente con $v_i$ y el segundo de longitud $k-1$ es un camino que une un vértice conectado con $v_i$ con el vértice $v_j$. Teniendo en cuenta esto, si llamamos $H_{i,j}(k)$ al número de caminos de longitud $k$ que conectan $v_i$ con $v_j$, se tendrá:
$$H_{i,j}(k) = \sum_{v \in V} (\textrm{n. de aristas adyacentes a } v_i \textrm{ y } v) \times (\textrm{n. de caminos de longitud } k-1 \textrm{ que conectan } v \textrm{ y } v_j).$$
Dado un vértice cualquiera, $v_k$, el número de aristas adyacentes a $v_i$ y $v_k$ es precisamente el elemento de matriz $(A_G)_{i,k}$, por lo que la suma anterior se puede expresar así:
$$H_{i,j}(k) = \sum_{l = 1}^n (A_G)_{i,l} \times (\textrm{n. de caminos de longitud } k-1 \textrm{ que conectan } v_l \textrm{ y } v_j).$$
Pero por la hipótesis de inducción, el segundo factor es $(A_G^{k-1})_{i,k}$. Por lo que
$$H_{i,j}(k) = \sum_{l = 1}^n (A_G)_{i,l} · (A_G^{k-1})_{i,k} = (A_G^k)_{i,k}.$$
```


**Tema:** [[Teoría elemental de grafos#2. Subgrafos, matriz de adyacencia y grafos conexos]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $G = (V,A)$ un [[Grafo]] con conjunto de vértices $\{v_1, v_2, \dots, v_n\}$ y sea $A_G$ su [[Matriz de adyacencia]]. Sea $(A_G)^k$ la potencia $k$-ésima de la matriz de adyacencia. Sea $a_{ij}^{(k)}$ la entrada $i,j$ de la matriz $(A_G)^k$. 

Entonces {{c1::el número de [[Camino]]s (pueden repetir vértices y aristas) de longitud $k$ entre los vértices $v_i$ y $v_j$}} es la entrada $a_{ij}$ de la matriz $A^k_G$.
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517276-->
END

START
Básico
Anverso: Demostración de que sea $G = (V,A)$ un [[Grafo]] con conjunto de vértices $\{v_1, v_2, \dots, v_n\}$ y sea $A_G$ su [[Matriz de adyacencia]]. Sea $(A_G)^k$ la potencia $k$-ésima de la matriz de adyacencia. Sea $a_{ij}^{(k)}$ la entrada $i,j$ de la matriz $(A_G)^k$. 

Entonces el número de [[Camino]]s (pueden repetir vértices y aristas) de longitud $k$ entre los vértices $v_i$ y $v_j$ es la entrada $a_{ij}$ de la matriz $A^k_G$.
Reverso: Procederemos por inducción sobre el exponente $k$ en $A_G^k$.

$k=1$. La proposición se reudce a la propia definición de la matriz de adyacencia y por lo tanto este caso es trivial.

$k-1 \implies k$. Tomemos dos vértices cualesquiera $v_i$ y $v_j$ (que pueden coincidir) de $V$. Un camino de longitud $k$ que una $v_i$ con $v_j$ será de la forma:
$$v_i x_1 x_2 x_3 \dots x_{k-1} v_j.$$
Esto se puede descomponer en $v_i x_1$ y $x_1 x_2 x_3 \dots x_{k-1} v_j$. El primer camino de longitud $1$ se corresponde con una arista adyacente con $v_i$ y el segundo de longitud $k-1$ es un camino que une un vértice conectado con $v_i$ con el vértice $v_j$. Teniendo en cuenta esto, si llamamos $H_{i,j}(k)$ al número de caminos de longitud $k$ que conectan $v_i$ con $v_j$, se tendrá:
$$H_{i,j}(k) = \sum_{v \in V} (\textrm{n. de aristas adyacentes a } v_i \textrm{ y } v) \times (\textrm{n. de caminos de longitud } k-1 \textrm{ que conectan } v \textrm{ y } v_j).$$
Dado un vértice cualquiera, $v_k$, el número de aristas adyacentes a $v_i$ y $v_k$ es precisamente el elemento de matriz $(A_G)_{i,k}$, por lo que la suma anterior se puede expresar así:
$$H_{i,j}(k) = \sum_{l = 1}^n (A_G)_{i,l} \times (\textrm{n. de caminos de longitud } k-1 \textrm{ que conectan } v_l \textrm{ y } v_j).$$
Pero por la hipótesis de inducción, el segundo factor es $(A_G^{k-1})_{i,k}$. Por lo que
$$H_{i,j}(k) = \sum_{l = 1}^n (A_G)_{i,l} · (A_G^{k-1})_{i,k} = (A_G^k)_{i,k}.$$
Tags: demostración MatDiscreta
<!--ID: 1717176517279-->
END
