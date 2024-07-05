
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-29, 17:07

Sean $A, B \subset \mathbb R, a \in A, b \in B, f: A \to \mathbb R, g : B \to \mathbb R, f(a) \subset B$ y $f(a) = b$.

```ad-theorem
Si $f$ es derivable en $a$ ([[Función derivable en un punto]]) y $g$ es derivable en $b$, entonces $g \circ f$ es derivable en $a$ y
$$(g \circ f)'(a) = g'(f(a))f'(a).$$
```


```ad-proof
Puesto que $f$ es derivable en $a$, $\exists \delta > 0$ tal que $]a - \delta, a + \delta[ \subset A$. De acuerdo con la [[Formulación de Weierstrass (1861)]], $\exists H : B \to \mathbb R$, continua en $b$ ([[Función continua en un punto]]), tal que $H(b) = 0$ y
$$g(y) = g(b) + g'(b)(y-b) + H(y)(y-b), \quad y \in B.$$
Entonces
$$g(f(x)) - g(f(a)) = g'(f(a))(f(x) - f(a)) + H(f(x))(f(x) - f(a)), \quad x \in A.$$
Tendremos que si $x \in A - \{a\}$,
$$\frac{g(f(x)) - g(f(a))}{x-a} = g'(f(a)) \frac{f(x)-f(a)}{x-a} + H(f(x))\frac{f(x)-f(a)}{x-a}.$$
Puesto que $f$ es derivable en $a$, existe el límite de $\frac{f(x)-f(a)}{x-a}$ cuando $x$ tiende a $a$ y es $f'(a)$. Demostraremos que $\lim_{x \to a} H(f(x)) = 0$, con lo que la prueba estará terminada.
Veámoslo, puesto que $f$ es derivable en $a$, será continua en $a$. Como $h$ es continua en $f(a) = b$, tendremos que $H \circ f$ es continua en $a$, [[Función continua en un punto que es punto de acumulación]] nos da que
$$\exists \lim_{x \to a} H(f(x)) = H(f(a)) = H(b) = 0.$$
```


**Tema:** [[Funciones derivables#3. Regla de la cadena]]
**Demostrado por:** [[Función continua en un punto que es punto de acumulación]], [[Formulación de Weierstrass (1861)]]

**Consecuencias:** [[Nota previa a teorema función inversa]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema que asegura la regla de la cadena?
Reverso: Sean $A, B \subset \mathbb R, a \in A, b \in B, f: A \to \mathbb R, g : B \to \mathbb R, f(a) \subset B$ y $f(a) = b$. Si $f$ es derivable en $a$ ([[Función derivable en un punto]]) y $g$ es derivable en $b$, entonces $g \circ f$ es derivable en $a$ y
$$(g \circ f)'(a) = g'(f(a))f'(a).$$
Tags: proposición/teorema análisisI
<!--ID: 1709231331304-->
END

START
Básico
Anverso: Demostración de que sean $A, B \subset \mathbb R, a \in A, b \in B, f: A \to \mathbb R, g : B \to \mathbb R, f(a) \subset B$ y $f(a) = b$. Si $f$ es derivable en $a$ ([[Función derivable en un punto]]) y $g$ es derivable en $b$, entonces $g \circ f$ es derivable en $a$ y
$$(g \circ f)'(a) = g'(f(a))f'(a).$$
(Regla de la cadena)
Reverso: Puesto que $f$ es derivable en $a$, $\exists \delta > 0$ tal que $]a - \delta, a + \delta[ \subset A$. De acuerdo con la [[Formulación de Weierstrass (1861)]], $\exists H : B \to \mathbb R$, continua en $b$ ([[Función continua en un punto]]), tal que $H(b) = 0$ y
$$g(y) = g(b) + g'(b)(y-b) + H(y)(y-b), \quad y \in B.$$
Entonces
$$g(f(x)) - g(f(a)) = g'(f(a))(f(x) - f(a)) + H(f(x))(f(x) - f(a)), \quad x \in A.$$
Tendremos que si $x \in A - \{a\}$,
$$\frac{g(f(x)) - g(f(a))}{x-a} = g'(f(a)) \frac{f(x)-f(a)}{x-a} + H(f(x))\frac{f(x)-f(a)}{x-a}.$$
Puesto que $f$ es derivable en $a$, existe el límite de $\frac{f(x)-f(a)}{x-a}$ cuando $x$ tiende a $a$ y es $f'(a)$. Demostraremos que $\lim_{x \to a} H(f(x)) = 0$, con lo que la prueba estará terminada.
Veámoslo, puesto que $f$ es derivable en $a$, será continua en $a$. Como $h$ es continua en $f(a) = b$, tendremos que $H \circ f$ es continua en $a$, [[Función continua en un punto que es punto de acumulación]] nos da que
$$\exists \lim_{x \to a} H(f(x)) = H(f(a)) = H(b) = 0.$$
Tags: demostración análisisI
<!--ID: 1709231331315-->
END