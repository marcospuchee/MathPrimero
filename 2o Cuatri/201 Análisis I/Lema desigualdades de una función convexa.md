
---
mathLink: $\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a} \le \frac{f(b)-f(c)}{b-c}.$
---
### Contenido Principal

**Fecha:** 2024-04-13, 11:24

```ad-lemma
Sea $I \subset \mathbb R$ un [[Intervalo]] no vacío y $f: I \to \mathbb R$ una [[Función convexa]], si $a,b,c \in I$, $a < c < b$, tendremos:
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a} \le \frac{f(b)-f(c)}{b-c}.$$
```

```ad-proof
De la convexidad de $f$ y de
$$\tag{*} c = \frac{c-a}{b-a}b + \frac{b-c}{b-a}a = \frac{c-a}{b-a}b + \left ( 1-\frac{c-a}{b-a} \right ) a;$$
(nota de [[Segmento que une dos puntos]])
resulta que
$$f(c) \le \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a) = \frac{c-a}{b-a}f(b) + \left ( 1-\frac{c-a}{b-a} \right )f(a).$$
De la última parte de la desigualdad deducimos que
$$f(c)-f(a) \le \frac{c-a}{b-a}f(b) - \frac{c-a}{b-a}f(a);$$
luego
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a};$$
lo que nos da la primera desigualdad que buscábamos.

Para demostrar la segunda, observemos que
$$\frac{c-a}{b-a} = 1 - \frac{b-c}{b-a};$$
por tanto, al igual que antes, de la convexidad de $f$ y de $(*)$ se deduce que
$$f(c) \le \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a) = \left ( 1 - \frac{b-c}{b-a} \right ) f(b) + \frac{b-c}{b-a} f(a).$$
Así,
$$f(c) - f(b) \le - \frac{b-c}{b-a} f(b) + \frac{b-c}{b-a}f(a) = \frac{b-c}{b-a}(f(a) - f(b));$$
esto es,
$$f(b) - f(c) \ge \frac{b-c}{b-a}(f(b) - f(a));$$
lo que nos da
$$\frac{f(b)- f(c)}{b-c} \ge \frac{f(b)- f(a)}{b-a}.$$
```

```ad-note
Sean $I \subset \mathbb R$ un intervalo no vacío y $f: I \to \mathbb R$, si $\exists a_0, b_0, c_0 \in I, a_0 < c_0 < b_0$ tales que
$$f(\lambda b_0 + (1-\lambda)a_0) > \lambda f(b_0) + (1-\lambda)f(a_0),$$
entonces
$$\frac{f(c_0) - f(a_0)}{c_0 - a_0} > \frac{f(b_0) - f(a_0)}{b_0 - a_0} > \frac{f(b_0) - f(c_0)}{b_0 - c_0}.$$


**Proof.**
La misma que la del lema, sustituyendo en $(*)$ $\le$ por $>$ y haceindo a continuación los cambios correspondientes.
```


**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Corolarios:** [[Convexidad de f sii derivada de f creciente]], [[Teorema función es convexa sii la gráfica de f está por encima de su tangente]]

---
### Anki

START
Básico
Anverso: Qué desigualdades se derivan de la convexidad de una función?
Reverso: Sea $I \subset \mathbb R$ un [[Intervalo]] no vacío y $f: I \to \mathbb R$ una [[Función convexa]], si $a,b,c \in I$, $a < c < b$, tendremos:
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a} \le \frac{f(b)-f(c)}{b-c}.$$

Además,
Sean $I \subset \mathbb R$ un intervalo no vacío y $f: I \to \mathbb R$, si $\exists a_0, b_0, c_0 \in I, a_0 < c_0 < b_0$ tales que
$$f(\lambda b_0 + (1-\lambda)a_0) > \lambda f(b_0) + (1-\lambda)f(a_0),$$
entonces
$$\frac{f(c_0) - f(a_0)}{c_0 - a_0} > \frac{f(b_0) - f(a_0)}{b_0 - a_0} > \frac{f(b_0) - f(c_0)}{b_0 - c_0}.$$
Tags: proposición/teorema análisisI
<!--ID: 1713093070040-->
END

START
Básico
Anverso: Demostración de que sea $I \subset \mathbb R$ un [[Intervalo]] no vacío y $f: I \to \mathbb R$ una [[Función convexa]], si $a,b,c \in I$, $a < c < b$, tendremos:
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a} \le \frac{f(b)-f(c)}{b-c}.$$
Reverso: De la convexidad de $f$ y de
$$\tag{*} c = \frac{c-a}{b-a}b + \frac{b-c}{b-a}a = \frac{c-a}{b-a}b + \left ( 1-\frac{c-a}{b-a} \right ) a;$$
(nota de [[Segmento que une dos puntos]])
resulta que
$$f(c) \le \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a) = \frac{c-a}{b-a}f(b) + \left ( 1-\frac{c-a}{b-a} \right )f(a).$$
De la última parte de la desigualdad deducimos que
$$f(c)-f(a) \le \frac{c-a}{b-a}f(b) - \frac{c-a}{b-a}f(a);$$
luego
$$\frac{f(c)-f(a)}{c-a} \le \frac{f(b)-f(a)}{b-a};$$
lo que nos da la primera desigualdad que buscábamos.

Para demostrar la segunda, observemos que
$$\frac{c-a}{b-a} = 1 - \frac{b-c}{b-a};$$
por tanto, al igual que antes, de la convexidad de $f$ y de $(*)$ se deduce que
$$f(c) \le \frac{c-a}{b-a}f(b) + \frac{b-c}{b-a}f(a) = \left ( 1 - \frac{b-c}{b-a} \right ) f(b) + \frac{b-c}{b-a} f(a).$$
Así,
$$f(c) - f(b) \le - \frac{b-c}{b-a} f(b) + \frac{b-c}{b-a}f(a) = \frac{b-c}{b-a}(f(a) - f(b));$$
esto es,
$$f(b) - f(c) \ge \frac{b-c}{b-a}(f(b) - f(a));$$
lo que nos da
$$\frac{f(b)- f(c)}{b-c} \ge \frac{f(b)- f(a)}{b-a}.$$
Tags: demostración análisisI
<!--ID: 1713093070053-->
END