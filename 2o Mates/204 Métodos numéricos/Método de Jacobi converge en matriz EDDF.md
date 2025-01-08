### Contenido Principal

```ad-proposition
Sea $A$ una matriz EDDF, entonces el método de Jacobi aplicado a sistemas $Ax = b$ converge.
```

```ad-proof
Sabemos que $\forall i \in \{1, \dots, n \}$, se cumple que $|a_{ii}| > \sum_{j = 1, i \neq j}^n |a_{ij}|$, veamos que $||Q||_\infty < 1$.

Por las propiedades de las matrices diagonales, sabemos que $$M^{-1} = \textrm{diag}(\frac{1}{a_{11}}, \dots, \frac{1}{a_{nn}}).$$

Por tanto, $$Q(i,j) = -[M^{-1}N](i,j) = - [M^{-1}(i,:)N(:,j)] = -M^{-1}(i,i)N(i,j),$$ luego si $i = j$, $Q(i,j) = 0$, pero si $i \neq j$, $Q(i,j) = -\frac{1}{A(i,i)} \cdot A(i,j)$.

Por definición, $||Q||_\infty = \max_{1 \le i \le n} ||Q(i,:)||_1$. Sin embargo, fijado $i \in \{1, \dots, n\}$, entonces
$$||Q(i,:)||_1 = \sum_{j = 1}^n |Q(i,j)| = \sum_{j = 1, j \neq j}^n \left | \frac{A(i,j)}{A(i,i)} \right | = \frac{1}{|A(i,i)|} \sum_{j = 1, j \neq i}^n |A(i,j)| < 1.$$
```

**Tema:** [[Métodos iterativos para resolver sistemas de ecuaciones lineales#2. Estudio de la convergencia.]]

**Definiciones referenciadas:** [Matriz EDDF](Matrices diagonalmente dominantes), [Método de Jacobi](Método iterativo), [$Q := -M^{-1}N$](Matriz de iteración), [[Método iterativo convergente]]
**Resultados referenciados:** [$||Q|| < 1$ para alguna norma matricial subordinada $\implies$ $Mx^k = b-Nx^{k-1}$ converge](Norma matriz de iteración menor que uno implica método convergente), [$||A||_ \infty = \max \limits_ {1 \le i \le m} ||A(i,:)||_ 1 = \max \limits_ {1 \le i \le m} \sum_ {j = 1}^n |a_ {ij}|$](Cálculo norma matricial subordinada infinito)

---
### Anki
