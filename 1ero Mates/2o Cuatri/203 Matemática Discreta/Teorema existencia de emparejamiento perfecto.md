
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-05, 11:03

```ad-theorem
Sea $G = (D \cup I, A)$ un [[grafo bipartito]] y $|D| = |I|$. El grafo $G$ tiene un [[emparejamiento perfecto]] $\iff$ para cada $S \subset D$ el conjunto
$$N(S) = \{b \in I: b \textrm{ es vecino de } s \textrm{ para algún } s \in S \}$$
tiene al menos tantos elementos como $S$, es decir, $|N(S)| \ge |S|$.
```


```ad-proof
$\rightarrow$.
Sea $S = \{d_1, d_2, \dots, d_k \} \subset D$. Si hay un emparejamiento perfecto, entonces cada elemento $d_i$ tendrá su pareja $e_i \in I$. Esto implica que $e_i \in N(s), \forall i \in \{1,2,\dots,k \}$. Por tanto
$$|N(S)| \ge k = |S|.$$

$\leftarrow$. Inducción sobre el número de aristas de $G$, $|A| = m$.
$m = 1$. Si sólo tenemos una arista, es fácil comprobar que $D$ e $I$ son conjuntos de un elemento cada uno y que el grafo $G$ es el [[grafo completo]] $K_2$ que tiene un emparejamiento perfecto obvio.
$m-1 \implies m$. Suponemos que todo grafo bipartito con un número de aristas menor o igual a $m$ tiene un emparejamiento perfecto. Vamos a demostrar lo mismo para un grafo con $|A| = m+1$. Dividiremos la demostración en dos casos.

**1. Suponemos que $\forall S \subset D$, con $0 < |S| < |D|$, tenemos que $|N(S)| \ge |S| + 1$**.
Cogemos una arista cualquiera de $G$, $\{x,y\}$. Consideremos ahora el [[subgrafo inducido]] por el subconjunto $(D - \{x\}) \cup (I - \{y\})$ denotado por $G'$. Es también un grafo bipartito y al menos tiene una arista menos de las que tenía $G$. Comprobamos que verifica la condición del enunciado: sea $S \subset D - \{x\}$, entonces
$$N^{G'}(S) = \left \{ \begin{array}{l l} N^G(S) & \textrm{si } y \notin N^G(S), \\ N^G(S) - \{y\} & \textrm{si } y \in N^G(S). \end{array} \right .$$
En ambos casos, como estamos suponiendo que $|N^G(S)| \ge |S| + 1$, tenemos que $|N^{G'}(S)| \ge |S|$. Podemos, por tanto, aplicar la hipótesis de inducción al subgrafo $G'$ y deducir que tiene un emparejamiento perfecto. Si a este emparejamiento perfecto le añadimos la arista que habíamos quitado, $\{x,y\}$, tendremos el emparejamiento perfecto del grafo inicial $G$.

**2. Suponemos que existe un $S \subset D$, con $0 < |S| < |D|$, tal que $|N(S)| = |S|$.**
A este caso, primero aplicamos la hipótesis de inducción al grafo bipartito inducido por $S$ y $N(S)$. Esto nos dará un primer emparejamiento perfecto que solo empareja vértices de $S$ con vértices de $N(S)$.
Sean ahora, $D' = D-S$ y $I' = I-N(S)$, y consideremos el subgrafo inducido por $D' \cup I'$ denotado por $G'$. Es también un grafo bipartito y tiene menos aristas de las que tenía $G$. Comprobamos que verifica la condición del enunciado: por reducción al absurdo, si $\exists S' \subset D'$ tal que $|N^{G'}(S')| < |S'|$, entonces
$$N^G(S \cup S') = |N^G(S)| + |N^G(S' \cap I')| = |N^G(S)| + |N^{G'}(S')| < |S| + |S'| = |S \cup S'|,$$
lo cual es una contradicción.
Si aplicamos a $G'$ la hipótesis de inducción, tendremos otro emparejamiento perfecto que solo empareja vértices de $D - S$ con vértices de $I-N(S)$. Uniendo los dos emparejamientos obtenemos el emparejamiento deseado.

```


**Tema:** [[Teoría elemental de grafos#7. Grafo bipartito. El Teorema del matrimonio.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Teorema condición suficiente y necesaria para que un grafo bipartito tenga un emparejamiento perfecto
Reverso: Sea $G = (D \cup I, A)$ un [[Grafo bipartito]] y $|D| = |I|$. El grafo $G$ tiene un [[Emparejamiento perfecto]] $\iff$ para cada $S \subset D$ el conjunto
$$N(S) = \{b \in I: b \textrm{ es vecino de } s \textrm{ para algún } s \in S \}$$
tiene al menos tantos elementos como $S$, es decir, $|N(S)| \ge |S|$.
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517220-->
END

START
Básico
Anverso: Demostración de que sea $G = (D \cup I, A)$ un [[Grafo bipartito]] y $|D| = |I|$. El grafo $G$ tiene un [[Emparejamiento perfecto]] $\iff$ para cada $S \subset D$ el conjunto
$$N(S) = \{b \in I: b \textrm{ es vecino de } s \textrm{ para algún } s \in S \}$$
tiene al menos tantos elementos como $S$, es decir, $|N(S)| \ge |S|$.
Reverso: $\rightarrow$.
Sea $S = \{d_1, d_2, \dots, d_k \} \subset D$. Si hay un emparejamiento perfecto, entonces cada elemento $d_i$ tendrá su pareja $e_i \in I$. Esto implica que $e_i \in N(s), \forall i \in \{1,2,\dots,k \}$. Por tanto
$$|N(S)| \ge k = |S|.$$

$\leftarrow$. Inducción sobre el número de aristas de $G$, $|A| = m$.
$m = 1$. Si sólo tenemos una arista, es fácil comprobar que $D$ e $I$ son conjuntos de un elemento cada uno y que el grafo $G$ es el [[Grafo completo]] $K_2$ que tiene un emparejamiento perfecto obvio.
$m-1 \implies m$. Suponemos que todo grafo bipartito con un número de aristas menor o igual a $m$ tiene un emparejamiento perfecto. Vamos a demostrar lo mismo para un grafo con $|A| = m+1$. Dividiremos la demostración en dos casos.

**1. Suponemos que $\forall S \subset D$, con $0 < |S| < |D|$, tenemos que $|N(S)| \ge |S| + 1$**.
Cogemos una arista cualquiera de $G$, $\{x,y\}$. Consideremos ahora el [[Subgrafo inducido]] por el subconjunto $(D - \{x\}) \cup (I - \{y\})$ denotado por $G'$. Es también un grafo bipartito y al menos tiene una arista menos de las que tenía $G$. Comprobamos que verifica la condición del enunciado: sea $S \subset D - \{x\}$, entonces
$$N^{G'}(S) = \left \{ \begin{array}{l l} N^G(S) & \textrm{si } y \notin N^G(S), \\ N^G(S) - \{y\} & \textrm{si } y \in N^G(S). \end{array} \right .$$
En ambos casos, como estamos suponiendo que $|N^G(S)| \ge |S| + 1$, tenemos que $|N^{G'}(S)| \ge |S|$. Podemos, por tanto, aplicar la hipótesis de inducción al subgrafo $G'$ y deducir que tiene un emparejamiento perfecto. Si a este emparejamiento perfecto le añadimos la arista que habíamos quitado, $\{x,y\}$, tendremos el emparejamiento perfecto del grafo inicial $G$.

**2. Suponemos que existe un $S \subset D$, con $0 < |S| < |D|$, tal que $|N(S)| = |S|$.**
A este caso, primero aplicamos la hipótesis de inducción al grafo bipartito inducido por $S$ y $N(S)$. Esto nos dará un primer emparejamiento perfecto que solo empareja vértices de $S$ con vértices de $N(S)$.
Sean ahora, $D' = D-S$ y $I' = I-N(S)$, y consideremos el subgrafo inducido por $D' \cup I'$ denotado por $G'$. Es también un grafo bipartito y tiene menos aristas de las que tenía $G$. Comprobamos que verifica la condición del enunciado: por reducción al absurdo, si $\exists S' \subset D'$ tal que $|N^{G'}(S')| < |S'|$, entonces
$$N^G(S \cup S') = |N^G(S)| + |N^G(S' \cap Y')| = |N^G(S)| + |N^{G'}(S')| < |S| + |S'| = |S \cup S'|,$$
lo cual es una contradicción.
Si aplicamos a $G'$ la hipótesis de inducción, tendremos otro emparejamiento perfecto que solo empareja vértices de $D - S$ con vértices de $I-N(S)$. Uniendo los dos emparejamientos obtenemos el emparejamiento deseado.

Tags: demostración MatDiscreta
<!--ID: 1717176517222-->
END