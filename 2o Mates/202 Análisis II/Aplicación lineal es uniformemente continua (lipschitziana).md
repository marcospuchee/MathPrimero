### Contenido Principal

```ad-proposition
Sea $T: \mathbb R^n \to \mathbb R^m$ una [[aplicación lineal]]. Entonces $\exists M > 0$ tal que $||T(x)|| \le M||x||$.

Además, $\forall f: \mathbb R^n \to \mathbb R^m$ lineal, $f$ es [[función uniformemente continua]] (es [[función lipschitziana]]).
```

^bad356

```ad-proof
Sea $x = \sum_{i = 1}^n x_i e_i$. Tenemos que, $T(x) = T(\sum_{i = 1}^n x_i e_i) = \sum_{i = 1}^n x_i T(e_i)$. Sin embargo, aplicando la desigualdad triangular y el [[teorema de Cauchy-Schwartz]], obtenemos:
$$||T(x)|| \le \sum_{i = 1}^n |x_i| \, ||T(e_i)|| \le \left ( \sum_{i = 1}^n |x_i|^2 \right )^{1/2} \left ( \sum_{i = 1}^n ||T(e_i)||^2 \right )^{1/2},$$
pero tomando el segundo sumatorio como $M$, obtenemos que eso es igual a $||x||M$, por tanto $||T(x)|| \le M||x||$.

Así, está claro que
$$||T(x) - T(y)|| = ||T(x-y)|| \le M||x-y||.$$
```

**Tema:** [[Funciones de varias variables#3. Continuidad.]]

---
### Anki

START
Básico
Anverso: Toda aplicación lineal es lipschitziana
Reverso: Sea $T: \mathbb R^n \to \mathbb R^m$ una [[aplicación lineal]]. Entonces $\exists M > 0$ tal que $||T(x)|| \le M||x||$.

Además, $\forall f: \mathbb R^n \to \mathbb R^m$ lineal, $f$ es [[función uniformemente continua]] (es [[función lipschitziana]]).
<!--ID: 1728138052323-->
END

START
Básico
Anverso: Demostración de que sea $T: \mathbb R^n \to \mathbb R^m$ una [[aplicación lineal]]. Entonces $\exists M > 0$ tal que $||T(x)|| \le M||x||$.

Además, $\forall f: \mathbb R^n \to \mathbb R^m$ lineal, $f$ es [[función uniformemente continua]] (es [[función lipschitziana]]).
Reverso: Sea $x = \sum_{i = 1}^n x_i e_i$. Tenemos que, $T(x) = T(\sum_{i = 1}^n x_i e_i) = \sum_{i = 1}^n x_i T(e_i)$. Sin embargo, aplicando la desigualdad triangular y el [[teorema de Cauchy-Schwartz]], obtenemos:
$$||T(x)|| \le \sum_{i = 1}^n |x_i| \, ||T(e_i)|| \le \left ( \sum_{i = 1}^n |x_i|^2 \right )^{1/2} \left ( \sum_{i = 1}^n ||T(e_i)||^2 \right )^{1/2},$$
pero tomando el segundo sumatorio como $M$, obtenemos que eso es igual a $||x||M$, por tanto $||T(x)|| \le M||x||$.

Así, está claro que
$$||T(x) - T(y)|| = ||T(x-y)|| \le M||x-y||.$$
Tags: dem anII
<!--ID: 1728138052327-->
END
