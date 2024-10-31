### Contenido principal

**Fecha:** 2024-02-24, 09:55

Sea $a \in A \subset \mathbb R, f : A \to \mathbb R$.

```ad-formal
title: Formal definition
Decimos que $f$ es derivable (respectivamente por la derecha) (respectivamente por la izquierda) en $a$ si $\exists \delta > 0$ tal que $]a-\delta, a + \delta[ \subset A$ y
$$\exists \lim_{x \to a} \frac{f(x) - f(a)}{x-a} = f'(a)$$
(respectivamente $\lim_{x \to a^+} = f(a)_+'$) (respectivamente $\lim_{x \to a^-} = f(a)_-'$).
```

```ad-note
Si $I$ es un intervalo abierto y $a \in I$, de acuerdo con [[Lema subintervalo con el mínimo]], $\exists \delta > 0$ tal que $]a-\delta, a + \delta[ \subset I$.
```

```ad-note
$f$ es derivable en $a$ (respectivamente por la izquierda) (respectivamente por la derecha) $\iff f \restriction_{]a-\delta, a + \delta[}$ lo es, y el valor de las correspondientes derivadas es el mismo.
```

**Tema:** [[Funciones derivables#1. Derivabilidad y continuidad]]
**Referencias:** [[Nota previa a teorema función inversa]]
**Proposiciones:** [[Formulación de Weierstrass (1861)]], [[Toda función derivable en un punto es continua en ese punto]]
**Teoremas:** [[Teorema fórmulas de derivación]], [[Regla de la cadena]], [[Teorema de la función inversa]], [[Teorema derivada de un extremo relativo]], [[Teorema de Rolle (1690)]], [[Teorema del valor medio]], [[Teorema fundamental del cálculo diferencial]], [[Función derivable en el interior de un intervalo monótona]]

---
### Anki

START
Básico
Anverso: Cuándo decimos que una función es derivable?
Reverso: Sea $a \in A \subset \mathbb R, f : A \to \mathbb R$. Decimos que $f$ es derivable (respectivamente por la derecha) (respectivamente por la izquierda) en $a$ si $\exists \delta > 0$ tal que $]a-\delta, a + \delta[ \subset A$ y
$$\exists \lim_{x \to a} \frac{f(x) - f(a)}{x-a} = f'(a)$$
(respectivamente $\lim_{x \to a^+} = f(a)_+'$) (respectivamente $\lim_{x \to a^-} = f(a)_-'$).
Tags: definición análisisI
<!--ID: 1708973800353-->
END

START
Básico
Anverso: Notas respecto a que una función sea derivable.
Reverso:
- Si $I$ es un intervalo abierto y $a \in I$, de acuerdo con [[Lema subintervalo con el mínimo]], $\exists \delta > 0$ tal que $]a-\delta, a + \delta[ \subset I$.
- $f$ es derivable en $a$ (respectivamente por la izquierda) (respectivamente por la derecha) $\iff f \restriction_{]a-\delta, a + \delta[}$ lo es, y el valor de las correspondientes derivadas es el mismo.
Tags: proposición/teorema análisisI
<!--ID: 1708973800358-->
END