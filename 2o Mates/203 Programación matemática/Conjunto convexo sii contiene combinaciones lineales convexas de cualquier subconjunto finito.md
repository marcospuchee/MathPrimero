### Contenido Principal

```ad-proposition
Un conjunto $C \subseteq \mathbb R^n$ es [[conjunto convexo]] $\iff$ $C$ contiene las [[combinación lineal convexa]] de cualquier subconjunto finito de puntos de $C$.
```

```ad-proof
$\rightarrow$. Inducción.
Es obvio que $C$ contiene las combinaciones lineales convexas de un elemento. Supongamos que el resultado se cumple para las combinaciones lineales convexas de $k$ elementos, para un cierto $k \in \mathbb N$, y sean $x_1, \dots, x_{k+1} \in C$ y $\lambda_1, \dots, \lambda_{k+1} \ge 0$ con $\sum_{i = 1}^{k+1} \lambda_i  =1$. Observemos que:
$$\sum_{i = 1}^{k+1} \lambda_i x_i = \sum_{i = 1}^k \lambda_i x_i + \lambda_{k+1}x_{k+1} = \left ( \sum_{i = 1}^k \lambda_i \right ) \sum_{i = 1}^k \frac{\lambda_i}{\sum_{i = 1}^k \lambda_i}x_i + \lambda_{k+1}x_{k+1}.$$
Por hipótesis de inducción se cumple que
$$\hat x := \sum_{i = 1}^k \frac{\lambda_i}{\sum_{i  =1}^k \lambda_i} x_i \in C.$$
Por tanto, al ser $C$ convexo
$$\sum_{i = 1}^{k+1} \lambda_i x_i = (1-\lambda_{k+1})\hat x + \lambda_{k+1} x_{k+1} \in C.$$

$\leftarrow$. Si $C$ contiene las combinaciones lineales convexas de cualquier número finito de puntos contendrá, en particular, las de dos puntos.
```

**Tema:** [[Modelo de programación lineal#1. Preliminares de Análisis Convexo]]

---
### Anki

START
Básico
Anverso: Demostración de un conjunto $C \subseteq \mathbb R^n$ es [[conjunto convexo]] $\iff$ $C$ contiene las [[combinación lineal convexa]] de cualquier subconjunto finito de puntos de $C$.
Reverso: $\rightarrow$. Inducción.
Es obvio que $C$ contiene las combinaciones lineales convexas de un elemento. Supongamos que el resultado se cumple para las combinaciones lineales convexas de $k$ elementos, para un cierto $k \in \mathbb N$, y sean $x_1, \dots, x_{k+1} \in C$ y $\lambda_1, \dots, \lambda_{k+1} \ge 0$ con $\sum_{i = 1}^{k+1} \lambda_i  =1$. Observemos que:
$$\sum_{i = 1}^{k+1} \lambda_i x_i = \sum_{i = 1}^k \lambda_i x_i + \lambda_{k+1}x_{k+1} = \left ( \sum_{i = 1}^k \lambda_i \right ) \sum_{i = 1}^k \frac{\lambda_i}{\sum_{i = 1}^k \lambda_i}x_i + \lambda_{k+1}x_{k+1}.$$
Por hipótesis de inducción se cumple que
$$\hat x := \sum_{i = 1}^k \frac{\lambda_i}{\sum_{i  =1}^k \lambda_i} x_i \in C.$$
Por tanto, al ser $C$ convexo
$$\sum_{i = 1}^{k+1} \lambda_i x_i = (1-\lambda_{k+1})\hat x + \lambda_{k+1} x_{k+1} \in C.$$

$\leftarrow$. Si $C$ contiene las combinaciones lineales convexas de cualquier número finito de puntos contendrá, en particular, las de dos puntos.
Tags: dem prm
<!--ID: 1727083428010-->
END

START
Respuesta anidada
Un conjunto $C \subseteq \mathbb R^n$ {{c1::es [[conjunto convexo]]}} $\iff$ {{c2::$C$ contiene las [[combinación lineal convexa]] de cualquier subconjunto finito de puntos de $C$.}}
Tags:
<!--ID: 1727083428012-->
END
