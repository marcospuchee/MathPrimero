
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-24, 10:05

Sean $a,b \in \mathbb R, a<b, c \in ]a,b[$ y $f: ]a,b[ \to \mathbb R$.

```ad-proposition
Las siguientes afirmaciones equivalen:
1. La función $f$ es derivable en $c$ ([[Función derivable en un punto]]).
2. $\exists r \in \mathbb R$ y una función $H : ]a,b[ \to \mathbb R$ continua en c ([[Función continua en un punto]]), tales que $H(c) = 0$ y
$$f(x) = f(c) + r(x-c) + H(x)(x-c), \quad x \in ]a,b[.$$
Si se verifica 1 o 2, tendremos que $r = f'(c)$.
```


```ad-proof
**(i) $\implies$ (ii).**
Sea
$$ H(x) = \left \{ \begin{array}{c l}
\displaystyle \frac{f(x) - f(c)}{x-c} - f'(c), & x \in ]a,b[ - \{c\}; \\
0, & x = c.
\end{array} \right .
$$
Puesto que $f$ es derivable en $c$, entonces $\exists \lim_{x \to c} H(x) = 0 = H(c)$, por tanto $H$ es continua en $c$.

**(ii) $\implies$ (i).**
De la definición de [[Función derivable en un punto]], deducimos que si $x \in ]a,b[ - \{c\}$,
$$H(x) = \frac{f(x)-f(c)}{x-c} - f'(c).$$
Puesto que $H$ es continua en $c$, [[Función continua en un punto que es punto de acumulación]] nos dice que $\lim_{x \to c} H(x) = H(c) = 0$, así
$$\lim_{x \to c} \frac{f(x) - f(c)}{x-c} - f'(c) = \lim_{x \to c} \left ( \frac{f(x) - f(c)}{x-c} - f'(c) \right ) = \lim_{x \to c} H(x) = H(c) = 0.$$

```

**Tema:** [[Funciones derivables#1. Derivabilidad y continuidad]]
**Corolarios:** [[Toda función derivable en un punto es continua en ese punto]], [[Regla de la cadena]], [[Teorema de la función inversa]]

---
### Anki

START
Básico
Anverso: Qué dice la formulación de Weierstrass (1861)?
Reverso: Sean $a,b \in \mathbb R, a<b, c \in ]a,b[$ y $f: ]a,b[ \to \mathbb R$. Las siguientes afirmaciones equivalen:
1. La función $f$ es derivable en $c$ ([[Función derivable en un punto]]).
2. $\exists r \in \mathbb R$ y una función $H : ]a,b[ \to \mathbb R$ continua en c ([[Función continua en un punto]]), tales que $H(c) = 0$ y
$$f(x) = f(c) + r(x-c) + H(x)(x-c), \quad x \in ]a,b[.$$
Si se verifica 1 o 2, tendremos que $r = f'(c)$.
Tags: proposición/teorema análisisI
<!--ID: 1709222724769-->
END

START
Básico
Anverso: Demostración de la formulación de Weierstrass (1861)
Reverso: **(i) $\implies$ (ii).**
Sea
$$ H(x) = \left \{ \begin{array}{c l}
\displaystyle \frac{f(x) - f(c)}{x-c} - f'(c), & x \in ]a,b[ - \{c\}; \\
0, & x = c.
\end{array} \right .
$$
Puesto que $f$ es derivable en $c$, entonces $\exists \lim_{x \to c} H(x) = 0 = H(c)$, por tanto $H$ es continua en $c$.

**(ii) $\implies$ (i).**
De la definición de [[Función derivable en un punto]], deducimos que si $x \in ]a,b[ - \{c\}$,
$$H(x) = \frac{f(x)-f(c)}{x-c} - f'(c).$$
Puesto que $H$ es continua en $c$, [[Función continua en un punto que es punto de acumulación]] nos dice que $\lim_{x \to c} H(x) = H(c) = 0$, así
$$\lim_{x \to c} \frac{f(x) - f(c)}{x-c} - f'(c) = \lim_{x \to c} \left ( \frac{f(x) - f(c)}{x-c} - f'(c) \right ) = \lim_{x \to c} H(x) = H(c) = 0.$$
Tags: demostración análisisI
<!--ID: 1709222724781-->
END



