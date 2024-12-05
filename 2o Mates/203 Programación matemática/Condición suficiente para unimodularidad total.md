### Contenido Principal

```ad-theorem
Sea $A \in \{0, \pm 1\}^{m \times n}$ una matriz que verifica las siguientes condiciones:
- En cada columna de $A$ hay, como mucho, dos elementos no nulos.
- Las filas de $A$ pueden dividirse en dos conjuntos $I_1$ y $I_2$ tales que:
	- Si una columna tiene dos elementos no nulos del mismo signo, entonces uno pertenece a una fila de $I_1$ y el otro a una de $I_2$.
	- Si una columna tiene dos elementos no nulos de signo distinto, los dos pertenecen a filas de $I_1$ o los dos pertenecen a filas de $I_2$.

Entonces $A$ es totalmente unimodular.
```

```ad-proof
*No la preguntará en el examen.*

Haremos la prueba por inducción sobre el tamaño de las submatrices cuadradas no-singulares de $A$. Claramente, las submatrices de orden $1$ no nulas tienen elementos (determinantes) $\pm 1$. Supongamos que la hipótesis es cierta para todas las submatrices cuadradas de orden $k$ y sea $C$ una submatriz cuadrada no-singular de orden $k+1$. Claramente, $C$ no puede tener una columna de ceros. Distinguiremos dos casos:
- Si $C$ tiene una columna con un solo elemento nulo, desarrollando su determinante por esta columna éste se reduce (salvo signo) al determinante de una submatriz cuadrada que es unimodular por hipótesis de inducción. Por tanto $|C| = \pm 1$.
- Si, por contra, todas las columnas de $C$ tienen dos elementos no nulos, entonces
$$\sum_{i \in I_1} c_{ij} - \sum_{i \in I_2} c_{ij} = 0, \quad \forall j = 1, \dots, k+1.$$

Por tanto, las filas de $C$ son linealmente dependientes y $C$ es singular.
```

**Tema:** [[Programación lineal entera#2. Combinatoria poliédrica.]]

**Definiciones referenciadas:** [[Matriz totalmente unimodular]]
**Resultados referenciados:** -.

---
### Anki

START
Básico
Anverso: Condiición suficiente para unimodularidad total
Reverso: Sea $A \in \{0, \pm 1\}^{m \times n}$ una matriz que verifica las siguientes condiciones:
- En cada columna de $A$ hay, como mucho, dos elementos no nulos.
- Las filas de $A$ pueden dividirse en dos conjuntos $I_1$ y $I_2$ tales que:
	- Si una columna tiene dos elementos no nulos del mismo signo, entonces uno pertenece a una fila de $I_1$ y el otro a una de $I_2$.
	- Si una columna tiene dos elementos no nulos de signo distinto, los dos perteneces a filas de $I_1$ o los dos pertenecen a filas de $I_2$.

Entonces $A$ es totalmente unimodular.
Tags: prm
<!--ID: 1733328768635-->
END
