
---
mathLink: $F(x,y) = [x]_B^t · A · [y]_B$
---
### Contenido Principal

**Fecha:** 2024-02-22, 16:17

Sea $F$ [[Forma bilineal]] sobre $V$, $\dim V = n$. Sea $B$ base de $V$. Entonces, 

```ad-lemma
La [[Matriz coordenada de F]] con respecto a la base $B$ es la única matriz $A \in M_n(\mathbb K)$ tal que:
$$\forall x,y \in V, \quad F(x,y) = [x]_B^t · A · [y]_B$$
```


```ad-proof
**Existencia:**
Si $x,y \in V$, tenemos que $x = x_1 v_1, \dots x_n v_n, y = y_1 v_1, \dots, y_n v_n$ con $x_i, y_i \in \mathbb K$ únicos. Luego, sabemos que $F(x,y) = F(x_1 v_1 + \dots + x_n v_n, y_1 v_1 + \dots + y_n v_n) =$ (por ser bilineal) $x_1 F(v_1, y_1v_1 + \dots + y_n v_n) + x_2 F(v_2, y_1 v_1 + \dots + y_n v_n) + \dots + x_n F(v_n, y_1 v_1 + \dots + y_n v_n)$ $= \sum_{i = 1}^n x_i F(v_i, \sum_{j = 1}^n y_j v_j) =$ $\sum_{i = 1}^n x_i \sum_{j = 1}^n y_j F(v_i, v_j) =$ $\sum_{i = 1, j = 1}^n x_i y_j F(v_i, v_j) =$ $(x_1, \dots, x_n)(\sum_{j = 1}^n F(v_1, v_j)y_j, \dots, \sum_{j= 1}^n F(v_n, v_j)y_j)^t =$ $(x_1, \dots, x_n)(F(v_i, v_j))(y_1, \dots, y_n)^t =$ $[x]_B^t (F(v_i, v_j)) [y]_B$

**Unicidad:**
Sea $A \in M_n(\mathbb K)$ tal que $\forall x, y \in V, F(x,y) = [x]_B^t · A · [y]_B$. Escribimos $B = \{ v_1, \dots, v_n \}$. Si particularizamos la condición $F(x,y) = [x]_B^t · A · [y]_B$ para los vectores de $B$, obtenemos, $\forall i, j \in \{1, \dots n\}$ :
$$F(v_i, v_j) = [v_i]^t_B · A · [v_j]_B = (0 , \dots, 0,1,0, \dots, 0) A (0 , \dots, 0,1,0, \dots, 0)^t$$
en las posiciones $i$ y $j$ respectivamente. Esto es lo mismo que
$$(0, \dots, 0, 1, 0, \dots, 0)(a_{1j}, a_{2j, \dots a_{nj}})^t = a_{ij}$$ 
Por tanto, $A$ es la [[Matriz coordenada de F]] con respecto a $B$.
```



**Tema:** [[Formas bilineales]]
**Corolarios:** [[Matriz coordenada de F simétrica sii F simétrica]]

---
### Anki

START
Básico
Anverso: Cómo se calcula una forma bilineal a partir de una matriz coordenada?
Reverso: Sea $F$ [[Forma bilineal]] sobre $V$, $\dim V = n$. Sea $B$ base de $V$. Entonces, la [[Matriz coordenada de F]] con respecto a la base $B$ es la única matriz $A \in M_n(\mathbb K)$ tal que:
$$\forall x,y \in V, \quad F(x,y) = [x]_B^t · A · [y]_B$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1708973800419-->
END

START
Básico
Anverso: Demostración de que sea $F$ [[Forma bilineal]] sobre $V$, $\dim V = n$. Sea $B$ base de $V$. Entonces, la [[Matriz coordenada de F]] con respecto a la base $B$ es la única matriz $A \in M_n(\mathbb K)$ tal que:
$$\forall x,y \in V, \quad F(x,y) = [x]_B^t · A · [y]_B$$
Reverso: **Existencia:**
Si $x,y \in V$, tenemos que $x = x_1 v_1, \dots x_n v_n, y = y_1 v_1, \dots, y_n v_n$ con $x_i, y_i \in \mathbb K$ únicos. Luego, sabemos que $F(x,y) = F(x_1 v_1 + \dots + x_n v_n, y_1 v_1 + \dots + y_n v_n) =$ (por ser bilineal) $x_1 F(v_1, y_1v_1 + \dots + y_n v_n) + x_2 F(v_2, y_1 v_1 + \dots + y_n v_n) + \dots + x_n F(v_n, y_1 v_1 + \dots + y_n v_n)$ $= \sum_{i = 1}^n x_i F(v_i, \sum_{j = 1}^n y_j v_j) =$ $\sum_{i = 1}^n x_i \sum_{j = 1}^n y_j F(v_i, v_j) =$ $\sum_{i = 1, j = 1}^n x_i y_j F(v_i, v_j) =$ $(x_1, \dots, x_n)(\sum_{j = 1}^n F(v_1, v_j)y_j, \dots, \sum_{j= 1}^n F(v_n, v_j)y_j)^t =$ $(x_1, \dots, x_n)(F(v_i, v_j))(y_1, \dots, y_n)^t =$ $[x]_B^t (F(v_i, v_j)) [y]_B$

**Unicidad:**
Sea $A \in M_n(\mathbb K)$ tal que $\forall x, y \in V, F(x,y) = [x]_B^t · A · [y]_B$. Escribimos $B = \{ v_1, \dots, v_n \}$. Si particularizamos la condición $F(x,y) = [x]_B^t · A · [y]_B$ para los vectores de $B$, obtenemos, $\forall i, j \in \{1, \dots n\}$ :
$$F(v_i, v_j) = [v_i]^t_B · A · [v_j]_B = (0 , \dots, 0,1,0, \dots, 0) A (0 , \dots, 0,1,0, \dots, 0)^t$$
en las posiciones $i$ y $j$ respectivamente. Esto es lo mismo que
$$(0, \dots, 0, 1, 0, \dots, 0)(a_{1j}, a_{2j, \dots a_{nj}})^t = a_{ij}$$ 
Por tanto, $A$ es la [[Matriz coordenada de F]] con respecto a $B$.
Tags: demostración ÁlgebraI
<!--ID: 1708973800425-->
END