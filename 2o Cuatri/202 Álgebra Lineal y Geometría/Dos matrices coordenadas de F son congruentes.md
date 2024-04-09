
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-22, 16:37

Sean $B, B'$ dos bases de $V$ y sea $P \in GL_n (\mathbb K)$ la [[Matriz cambio de base]] entre $B'$ y $B$. Sean $A, A' \in M_n (\mathbb K)$ las matrices coordenadas de $F$ ([[Matriz coordenada de F]]) con respecto a las bases $B, B'$ respectivamente. Entonces,

```ad-proposition
$A$ y $A'$ son [[Matrices congruentes]].
```


```ad-proof
Tenemos que $F(x,y) = [x]_B^t · A · [y]_B$ por [[Lema cálculo forma bilineal a partir de matriz coordenada]], que es igual a $(P[x]_{B'})^t · A · (P[y]_{B'})$ por [[Corolario producto cambio de base por coordenadas de una base]], que, por propiedad de la transpuesta, devuelve:
$$([x]_{B'})^t · P^t · A · P · [y]_{B'}$$
Así, $A' = P^t AP$ luego son congruentes.
```



**Tema:** [[Formas bilineales]]
**Corolarios:** [[Toda matriz simétrica es congruente a una matriz diagonal]], [[Criterio de Sylvester]]

---
### Anki

START
Básico
Anverso: Qué relación guardan dos matrices coordenadas de $F$ respecto a bases distintas?
Reverso: Sean $B, B'$ dos bases de $V$ y sea $P \in GL_n (\mathbb K)$ la [[Matriz cambio de base]] entre $B'$ y $B$. Sean $A, A' \in M_n (\mathbb K)$ las matrices coordenadas de $F$ ([[Matriz coordenada de F]]) con respecto a las bases $B, B'$ respectivamente. Entonces, $A$ y $A'$ son [[Matrices congruentes]].
Tags: proposición/teorema ÁlgebraI
<!--ID: 1708973800483-->
END

START
Básico
Anverso: Demostración de que sean $B, B'$ dos bases de $V$ y sea $P \in GL_n (\mathbb K)$ la [[Matriz cambio de base]] entre $B'$ y $B$. Sean $A, A' \in M_n (\mathbb K)$ las matrices coordenadas de $F$ ([[Matriz coordenada de F]]) con respecto a las bases $B, B'$ respectivamente. Entonces, $A$ y $A'$ son [[Matrices congruentes]].
Reverso: Tenemos que $F(x,y) = [x]_B^t · A · [y]_B$ por [[Lema cálculo forma bilineal a partir de matriz coordenada]], que es igual a $(P[x]_{B'})^t · A · (P[y]_{B'})$ por [[Corolario producto cambio de base por coordenadas de una base]], que, por propiedad de la transpuesta, devuelve:
$$([x]_{B'})^t · P^t · A · P · [y]_{B'}$$
Así, $A' = P^t AP$ luego son congruentes.
Tags: demostración ÁlgebraI
<!--ID: 1708973800494-->
END