
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-15, 17:30

```ad-theorem
Sea $V$ un [[Espacio vectorial euclídeo]]. La aplicación $g: V \to \mathbb R$ con $x \to g(x) = ||x||$ ([[Norma de un vector]]) satisface las siguientes propiedades:
1. $g(x) \ge 0, \forall x \in V$ y $g(x) = 0$ sii $x = 0$.
2. $\forall \lambda \in \mathbb R, \forall x \in V, \quad g(\lambda x) = |\lambda|g(x)$.
3. $\forall x,y \in V, \quad g(x+y) \le g(x) + g(y)$ (desigualdad triangular de Minkowski).

Podemos llamar norma a toda aplicación que cumpla estas propiedades, luego puede existir una norma al margen de un [[producto escalar]].
```

```ad-proof
Las propiedades $(i), (ii)$ se deducen directamente de la definición de la norma:

$(i)$. Sea $x \in V$. Por la definición de producto escalar, sabemos que $x · x \ge 0$, y además $x·x = 0$ sii $x = 0$. Entonces $g(x) = ||x|| = \sqrt{x · x} \ge 0$ y $g(x) = 0$ sii $x = 0$.

$(ii).$ $\forall \lambda \in \mathbb R, \forall x \in V$, se cumple que
$$g(\lambda x) = ||\lambda x|| = \sqrt{(\lambda x) · (\lambda x)} = \sqrt{\lambda^2(x · x)} = (\sqrt{\lambda^2})\sqrt{x·x} = |\lambda| · ||x||.$$

$(iii)$. Tenemos:
$$||x+y||^2 = (x+y)·(x+y) = x·x + 2x · y + y·y = ||x||^2 + 2(x·y) + ||y||^2.$$
Sin embargo, $||x||^2 + 2(x·y) + ||y||^2 < ||x||^2 + 2|x·y| + ||y||^2$, y por el [[Teorema de Cauchy-Schwartz]], tenemos que
$$ ||x||^2 + 2|x·y| + ||y||^2 \le ||x||^2 + 2||x|| · ||y|| + ||y||^2 = (||x||+ ||y||)^2.$$
Por tanto, $||x+y|| \le ||x|| + ||y||$, es decir: $g(x+y) \le g(x) + g(y)$.
```

**Tema:** [[Espacios vectoriales euclídeos]]
**Demostrado por:** [[Teorema de Cauchy-Schwartz]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Propiedades de toda norma (al margen de un vector)
Reverso: Sea $V$ un [[Espacio vectorial euclídeo]]. La aplicación $g: V \to \mathbb R$ con $x \to g(x) = ||x||$ ([[Norma de un vector]]) satisface las siguientes propiedades:
1. $g(x) \ge 0, \forall x \in V$ y $g(x) = 0$ sii $x = 0$.
2. $\forall \lambda \in \mathbb R, \forall x \in V, \quad g(\lambda x) = |\lambda|g(x)$.
3. $\forall x,y \in V, \quad g(x+y) \le g(x) + g(y)$ (desigualdad triangular de Minkowski).

Podemos llamar norma a toda aplicación que cumpla estas propiedades, luego puede existir una norma al margen de un [[producto escalar]].
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060760848-->
END

START
Básico
Anverso: Demostración de que sea $V$ un [[Espacio vectorial euclídeo]]. La aplicación $g: V \to \mathbb R$ con $x \to g(x) = ||x||$ ([[Norma de un vector]]) satisface las siguientes propiedades:
1. $g(x) \ge 0, \forall x \in V$ y $g(x) = 0$ sii $x = 0$.
2. $\forall \lambda \in \mathbb R, \forall x \in V, \quad g(\lambda x) = |\lambda|g(x)$.
3. $\forall x,y \in V, \quad g(x+y) \le g(x) + g(y)$ (desigualdad triangular de Minkowski).

Podemos llamar norma a toda aplicación que cumpla estas propiedades, luego puede existir una norma al margen de un [[producto escalar]].
Reverso: Las propiedades $(i), (ii)$ se deducen directamente de la definición de la norma:

$(i)$. Sea $x \in V$. Por la definición de producto escalar, sabemos que $x · x \ge 0$, y además $x·x = 0$ sii $x = 0$. Entonces $g(x) = ||x|| = \sqrt{x · x} \ge 0$ y $g(x) = 0$ sii $x = 0$.

$(ii).$ $\forall \lambda \in \mathbb R, \forall x \in V$, se cumple que
$$g(\lambda x) = ||\lambda x|| = \sqrt{(\lambda x) · (\lambda x)} = \sqrt{\lambda^2(x · x)} = (\sqrt{\lambda^2})\sqrt{x·x} = |\lambda| · ||x||.$$

$(iii)$. Tenemos:
$$||x+y||^2 = (x+y)·(x+y) = x·x + 2x · y + y·y = ||x||^2 + 2(x·y) + ||y||^2.$$
Sin embargo, $||x||^2 + 2(x·y) + ||y||^2 < ||x||^2 + 2|x·y| + ||y||^2$, y por el [[Teorema de Cauchy-Schwartz]], tenemos que
$$ ||x||^2 + 2|x·y| + ||y||^2 \le ||x||^2 + 2||x|| · ||y|| + ||y||^2 = (||x||+ ||y||)^2.$$
Por tanto, $||x+y|| \le ||x|| + ||y||$, es decir: $g(x+y) \le g(x) + g(y)$.
Tags: demostración ÁlgebraI
<!--ID: 1714060760865-->
END

