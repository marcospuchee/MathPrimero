
---
mathLink: $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ tiene estructura de espacio vectorial y $\dim S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} = k$
---
### Contenido principal

**Fecha:** 2024-02-22, 17:01

Sea $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ el conjunto de todas las sucesiones definidas por una misma [[Ley de recurrencia lineal y homogénea]] con los coeficientes $\lambda_0, \lambda_1, \dots, \lambda_{k-1}$.

```ad-proposition
title: Formal definition
$S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ tiene estructura de [[Espacio vectorial]] real de dimensión $k$, con las operaciones habituales para la suma de sucesiones y el producto de una sucesión por un número ([[Operaciones con sucesiones]]).
```

```ad-proof
Sean $a_n, b_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$, luego tenemos que $a_{n+k} = \lambda_{k-1} a_{n+k-1} + \dots + \lambda_1 a_{n+1} + \lambda_0 a_n$ y $b_{n+k} = \lambda_{k-1} b_{n+k-1} + \dots + \lambda_1 b_{n+1} + \lambda_0 b_n$. Sumamos $a_{n+k} + b_{n+k}$, lo que nos devuelve:
$$\lambda_{k-1}(a_{n+k-1} + b_{n+k-1}) + \dots + \lambda_1 (a_{n+1} + b_{n+1}) + \lambda_0 (a_n + b_n)$$
luego $a_n + b_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$.

Ahora probamos con la multiplicación por un escalar. Sea $a_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ y $\alpha \in \mathbb R$. Tenemos que $a_{n+k} = \lambda_{k-1} a_{n+k-1} + \dots + \lambda_1 a_{n+1} + \lambda_0 a_n$, lo que implica que:
$$\alpha a_{n+k} = \lambda_{k-1}(\alpha a_{n+k-1}) + \dots + \lambda_0 (\alpha a_n)$$
luego $\alpha a_{n+k} \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$. Por tanto, $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ es un [[Subespacio vectorial]] del espacio vectorial de todas las sucesiones.

Para comprobar que $\dim S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} = k$, construimos un [[Endomorfismo]] con $\mathbb R^k$. Sea $\phi: S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} \to \mathbb R^k$ lineal, con $\phi (a_n) \to (a_0, a_1, \dots, a_{k-1})$ donde $(a_0, a_1, \dots, a_{k-1})$ son los primeros $k$ términos (puesto que toda sucesión definida por una ley de recurrencia de orden $k$ está determinada por los $k$ primeros términos).
- Inyectiva. Veamos que $Ker \phi = \{0\}$ (por (i) de [[Proposiciones aplicación lineal espacios vectoriales]]). Suponemos que $\phi (a_n) = 0$, pero $\phi (a_n) = 0 \iff (a_0, a_1, \dots, a_{k-1}) = 0_k \iff a_i = 0, \forall i = 0, \dots, k-1$. Por lo que $a_k = \lambda_{k-1} a_{k-1} + \dots + \lambda_0 a_0 = 0$, deducimos que $a_{k+1} = 0$, y $a_{k+2}$ y... sucesivamente. Luego $a_n = 0$ y $Ker \phi = \{0\}$.
- Sobreyectiva. Sea $(x_0, x_1, \dots, x_{k-1}) \in \mathbb R^k$. Sea la sucesión $a_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ cuyos $k$ primeros términos son $(x_0, x_1, \dots, x_{k-1})$. Así, $\phi (a_n) = (x_0, \dots, x_{k-1})$.
```

**Tema:** [[Ecuaciones de recurrencia#1. Sucesiones definidas por ecuaciones de recurrencia]]
**Corolarios:** [[El polinomio característico de una ley de recurrencia tiene k raíces simples]]

---
### Anki

START
Básico
Anverso: Demuestra que sea $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ el conjunto de todas las sucesiones definidas por una misma [[Ley de recurrencia lineal y homogénea]] con los coeficientes $\lambda_0, \lambda_1, \dots, \lambda_{k-1}$. $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ tiene estructura de [[Espacio vectorial]] real de dimensión $k$, con las operaciones habituales para la suma de sucesiones y el producto de una sucesión por un número ([[Operaciones con sucesiones]]).
Reverso: Sean $a_n, b_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$, luego tenemos que $a_{n+k} = \lambda_{k-1} a_{n+k-1} + \dots + \lambda_1 a_{n+1} + \lambda_0 a_n$ y $b_{n+k} = \lambda_{k-1} b_{n+k-1} + \dots + \lambda_1 b_{n+1} + \lambda_0 b_n$. Sumamos $a_{n+k} + b_{n+k}$, lo que nos devuelve:
$$\lambda_{k-1}(a_{n+k-1} + b_{n+k-1}) + \dots + \lambda_1 (a_{n+1} + b_{n+1}) + \lambda_0 (a_n + b_n)$$
luego $a_n + b_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$.

Ahora probamos con la multiplicación por un escalar. Sea $a_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ y $\alpha \in \mathbb R$. Tenemos que $a_{n+k} = \lambda_{k-1} a_{n+k-1} + \dots + \lambda_1 a_{n+1} + \lambda_0 a_n$, lo que implica que:
$$\alpha a_{n+k} = \lambda_{k-1}(\alpha a_{n+k-1}) + \dots + \lambda_0 (\alpha a_n)$$
luego $\alpha a_{n+k} \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$. Por tanto, $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ es un [[Subespacio vectorial]] del espacio vectorial de todas las sucesiones.

Para comprobar que $\dim S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} = k$, construimos un [[Endomorfismo]] con $\mathbb R^k$. Sea $\phi: S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} \to \mathbb R^k$ lineal, con $\phi (a_n) \to (a_0, a_1, \dots, a_{k-1})$ donde $(a_0, a_1, \dots, a_{k-1})$ son los primeros $k$ términos (puesto que toda sucesión definida por una ley de recurrencia de orden $k$ está determinada por los $k$ primeros términos).
- Inyectiva. Veamos que $Ker \phi = \{0\}$ (por (i) de [[Proposiciones aplicación lineal espacios vectoriales]]). Suponemos que $\phi (a_n) = 0$, pero $\phi (a_n) = 0 \iff (a_0, a_1, \dots, a_{k-1}) = 0_k \iff a_i = 0, \forall i = 0, \dots, k-1$. Por lo que $a_k = \lambda_{k-1} a_{k-1} + \dots + \lambda_0 a_0 = 0$, deducimos que $a_{k+1} = 0$, y $a_{k+2}$ y... sucesivamente. Luego $a_n = 0$ y $Ker \phi = \{0\}$.
- Sobreyectiva. Sea $(x_0, x_1, \dots, x_{k-1}) \in \mathbb R^k$. Sea la sucesión $a_n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ cuyos $k$ primeros términos son $(x_0, x_1, \dots, x_{k-1})$. Así, $\phi (a_n) = (x_0, \dots, x_{k-1})$.
Tags: demostración  MatDiscreta
<!--ID: 1708973800608-->
END
