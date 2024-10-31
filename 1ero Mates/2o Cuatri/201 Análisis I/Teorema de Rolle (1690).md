
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-29, 18:49

Sean $a, b \in \mathbb R, a<b$.

```ad-theorem
Si $f: [a,b] \to \mathbb R$ es una función continua en $[a,b]$ ([[Función continua en un conjunto]]), que es derivable en cada punto de $]a,b[$ ([[Función derivable en un punto]]) y tal que $f(a) = f(b)$, entonces $\exists \xi \in ]a,b[$ tal que $f'(\xi) = 0$.
```


```ad-proof
Por el [[Teorema principal de Weierstrass (1861)]], $\exists x_1, x_2 \in [a,b]$ donde la función alcanza su máximo y su mínimo, es decir, $f(x_1) \ge f(x) \ge f(x_2), \forall x \in [a,b]$.
- Si $f(x_1) = f(x_2)$, la función es constante, y la afirmación del teorema es trivial.
- Si $f(x_1) \neq f(x_2)$, como $f(a) = f(b)$, o bien $x_1 \notin \{a,b\}$, o bien $x_2 \notin \{a,b\}$. Por tanto, si por ejemplo $x_1 \in ]a,b[$, el [[Teorema derivada de un extremo relativo]] nos dice que $f'(x_1) = 0$.
```


**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:** [[Teorema principal de Weierstrass (1861)]], [[Teorema derivada de un extremo relativo]]
**Consecuencias:** [[Teorema del valor medio]], [[Teorema función es convexa sii la gráfica de f está por encima de su tangente]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Rolle (1690)?
Reverso: Sean $a, b \in \mathbb R, a<b$. Si $f: [a,b] \to \mathbb R$ es una función continua en $[a,b]$ ([[Función continua en un conjunto]]), que es derivable en cada punto de $]a,b[$ ([[Función derivable en un punto]]) y tal que $f(a) f(b)$, entonces $\exists \xi \in ]a,b[$ tal que $f'(\xi) = 0$.
Tags: proposición/teorema análisisI
<!--ID: 1709231331176-->
END

START
Básico
Anverso: Demostración de que sean $a, b \in \mathbb R, a<b$. Si $f: [a,b] \to \mathbb R$ es una función continua en $[a,b]$ ([[Función continua en un conjunto]]), que es derivable en cada punto de $]a,b[$ ([[Función derivable en un punto]]) y tal que $f(a) f(b)$, entonces $\exists \xi \in ]a,b[$ tal que $f'(\xi) = 0$ (TEOREMA DE ROLLE (1690))
Reverso: Por el [[Teorema principal de Weierstrass (1861)]], $\exists x_1, x_2 \in [a,b]$ donde la función alcanza su máximo y su mínimo, es decir, $f(x_1) \ge f(x) \ge f(x_2), \forall x \in [a,b]$.
- Si $f(x_1) = f(x_2)$, la función es constante, y la afirmación del teorema es trivial.
- Si $f(x_1) \neq f(x_2)$, como $f(a) = f(b)$, o bien $x_1 \notin \{a,b\}$, o bien $x_2 \notin \{a,b\}$. Por tanto, si por ejemplo $x_1 \in ]a,b[$, el [[Teorema derivada de un extremo relativo]] nos dice que $f'(x_1) = 0$.
Tags: demostración análisisI
<!--ID: 1709231331181-->
END