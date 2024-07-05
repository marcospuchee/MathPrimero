
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-16, 09:09

```ad-theorem
Hay $n^{n-2}$ árboles etiquetados ([[Árbol etiquetado]]) de $n$ vértices diferentes.
```


```ad-proof
Para poder enumerar todos los árboles con una cantidad de vértices determinada, lo que hizo Cayley fue asignar a cada árbol etiquetado un código de números naturales de manera biunívoca.
Sea $G$ un [[árbol]] con $n$ vértices etiquetados con los números $\{0, 1, 2, \dots, n-1 \}$, y las correspondientes $n-1$ aristas. El algoritmo que describimos a continuación asocia a cada árbol etiquetado una lista ordenada de $n-2$ números (entre $0$ y $n-1$) que nombraremos como $(a_1, \dots, a_{n-2})$.
1. Localizamos el vértice de grado $1$ con menor etiqueta, que llamamos $b_1$, y apuntamos quién es su único vecino, $a_1$.
2. Borramos entonces $b_1$ y su arista.
3. Localizamos el vértice de grado $1$ con menor eitqueta, $b_2$, apuntamos quién es su vecino $a_2$, y borramos $b_2$ y su arista.
4. Y así, sucesivamente, hasta quedarnos con sólo un vértice.

Lo que hemos ido anotando forma una lista $(a_1, \dots, a_{n-2})$, llamada **código de Prüfer** del árbol $G$.

La reconstrucción del árbol a partir de su código de Prüfer es la siguiente, partiendo de la lista $a = (a_1, \dots, a_{n-2})$ y el conjunto de etiquetas $V = \{0,1,2, \dots, n-1 \}$:
1. Declaramos que $b_1$ es el menor elemento de $V$ que no está en la lista $a$, y formamos la arista $\{a_1, b_1\}$.
2. Eliminamos ahora el símbolo $b_1$ de $V$ y recortamos la lista $a$ quitándole su primer elemento.
3. Repetimos el proceso para obtener $b_2$ (el menor elemento de $V - \{b_1 \}$ que no esté en la lista recortada en el paso anterior, y formar la arista $\{a_2, b_2 \}$).
4. Y así sucesivamente.

Puesto que cada código de Prüfer genera un árbol etiquetado diferente y a la inversa, es decir, todo árbol etiquetado tiene un único código de Prüfer, habrá tanto árboles etiquetados como código de Prüfer diferentes para cada numero de vértices $n$. Cada código está formado por $n-2$ números elegidos entre las cifras $\{0,1,2, \dots, n-1 \}$. Luego el cómputo es: $VR(n,n-2) = n^{n-2}$ ([[Variaciones con repetición]]).
```


**Tema:** [[Teoría elemental de grafos#3. Estructuras tipo árbol]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Cayley?
Reverso: Hay $n^{n-2}$ árboles etiquetados ([[Árbol etiquetado]]) de $n$ vértices diferentes.
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517225-->
END

START
Básico
Anverso: Demostración de que hay $n^{n-2}$ árboles etiquetados ([[Árbol etiquetado]]) de $n$ vértices diferentes.
Reverso: Para poder enumerar todos los árboles con una cantidad de vértices determinada, lo que hizo Cayley fue asignar a cada árbol etiquetado un código de números naturales de manera biunívoca.
Sea $G$ un [[Árbol]] con $n$ vértices etiquetados con los números $\{0, 1, 2, \dots, n-1 \}$, y las correspondientes $n-1$ aristas. El algoritmo que describimos a continuación asocia a cada árbol etiquetado una lista ordenada de $n-2$ números (entre $0$ y $n-1$) que nombraremos como $(a_1, \dots, a_{n-2})$.
1. Localizamos el vértice de grado $1$ con menor etiqueta, que llamamos $b_1$, y apuntamos quién es su único vecino, $a_1$.
2. Borramos entonces $b_1$ y su arista.
3. Localizamos el vértice de grado $1$ con menor eitqueta, $b_2$, apuntamos quién es su vecino $a_2$, y borramos $b_2$ y su arista.
4. Y así, sucesivamente, hasta quedarnos con sólo un vértice.

Lo que hemos ido anotando forma una lista $(a_1, \dots, a_{n-2})$, llamada **código de Prüfer** del árbol $G$.

La reconstrucción del árbol a partir de su código de Prüfer es la siguiente, partiendo de la lista $a = (a_1, \dots, a_{n-2})$ y el conjunto de etiquetas $V = \{0,1,2, \dots, n-1 \}$:
1. Declaramos que $b_1$ es el menor elemento de $V$ que no está en la lista $a$, y formamos la arista $\{a_1, b_1\}$.
2. Eliminamos ahora el símbolo $b_1$ de $V$ y recortamos la lista $a$ quitándole su primer elemento.
3. Repetimos el proceso para obtener $b_2$ (el menor elemento de $V - \{b_1 \}$ que no esté en la lista recortada en el paso anterior, y formar la arista $\{a_2, b_2 \}$).
4. Y así sucesivamente.

Puesto que cada código de Prüfer genera un árbol etiquetado diferente y a la inversa, es decir, todo árbol etiquetado tiene un único código de Prüfer, habrá tanto árboles etiquetados como código de Prüfer diferentes para cada numero de vértices $n$. Cada código está formado por $n-2$ números elegidos entre las cifras $\{0,1,2, \dots, n-1 \}$. Luego el cómputo es: $VR(n,n-2) = n^{n-2}$ ([[Variaciones con repetición]]).
Tags: demostración MatDiscreta
<!--ID: 1717176517227-->
END