### Contenido principal ($\mathbb R^n$, escalar).

```ad-theorem
Sea $\Omega \subseteq \mathbb R^n$ abierto, $a,b \in \Omega$ tales que $[a,b] \subseteq \Omega$ y $f: \Omega \to \mathbb R$ continua en $[a,b]$ y diferenciable en $]a,b[$. Entonces $\exists c \in ]a,b[$ tal que
$$f(b) - f(a) = \langle \nabla f(c), b-a \rangle.$$
```

^d52f8a

```ad-note
title: Notación
Dados $a,b \in \mathbb R^n$,
$$\begin{array}{c}
[a,b] = \{a+t(b-a): t \in [0,1] \}, \\
]a,b[ = \{a+t(b-a): t \in ]0,1[ \}.
\end{array}$$
```


```ad-proof
Consideramos $\varphi: [0,1] \to \mathbb R$ con $\varphi(t) = f(a+t(b-a))$, $\forall t \in [0,1]$, $\varphi$ continua en $[0,1]$. Por la [[regla de la cadena (Rn)]], $\varphi$ es derivable en $]0,1[$ y
$$\varphi'(t) = \langle \nabla f(a+t(b-a)), b-a \rangle.$$
Por el teorema del valor medio en $\mathbb R$, $\exists \xi \in ]0,1[$ tal que
$$f(b) - f(a) = \varphi(1) - \varphi(0) = \varphi'(\xi) = \langle \nabla f(a+\xi (b-a)), b-a \rangle.$$
Luego tomamos $c = a+ \xi(b-a)$.
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#6. Teorema del valor medio.]]
**Corolario:** [[Todas las derivadas parciales acotadas implica que la función es lipschitziana]], [[Derivadas parciales nulas implican que la función es constante]]

---
### Contenido principal ($\mathbb R$).

**Fecha:** 2024-02-29, 18:57

Sean $f$ y $g$ funciones reales.

```ad-theorem
Si $f$ y $g$ son continuas en $[a,b]$ ([[Función continua en un conjunto]]), y derivables en $]a,b[$ ([[Función derivable en un punto]]), entonces $\exists \xi \in ]a,b[$ tal que
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
En particular, para cualquier función real $f$, continua en $[a,b]$, derivable en $]a,b[$, $\exists \xi \in ]a,b[$ en el cual
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
```


```ad-proof
La igualdad
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi)$$
es consecuencia directa de aplicar el [[Teorema de Rolle (1690)]] a $h(x) = (f(b) - f(a))g(x) - (g(b) - g(a))f(x).$

Para
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
basta hacer $g(x) := x, x \in [a,b]$ en
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
```

**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:** [[Teorema de Rolle (1690)]]
**Consecuencias:** [[Teorema fundamental del cálculo diferencial]], [[Función derivable en el interior de un intervalo monótona]], [[Teorema de Lagrange (1797)]], [[Convexidad de f sii derivada de f creciente]]

---
### Anki

START
Básico
Anverso: Teorema del valor medio
Reverso: Sea $\Omega \subseteq \mathbb R^n$ abierto, $a,b \in \Omega$ tales que $[a,b] \subseteq \Omega$ y $f: \Omega \to \mathbb R$ continua en $[a,b]$ y diferenciable en $]a,b[$. Entonces $\exists c \in ]a,b[$ tal que
$$f(b) - f(a) = \langle \nabla f(c), b-a \rangle.$$
Tags: anII
<!--ID: 1730228001558-->
END

START
Básico
Anverso: Demostración de que sean $\Omega \subseteq \mathbb R^n$ abierto, $a,b \in \Omega$ tales que $[a,b] \subseteq \Omega$ y $f: \Omega \to \mathbb R$ continua en $[a,b]$ y diferenciable en $]a,b[$. Entonces $\exists c \in ]a,b[$ tal que
$$f(b) - f(a) = \langle \nabla f(c), b-a \rangle.$$
Reverso: Consideramos $\varphi: [0,1] \to \mathbb R$ con $\varphi(t) = f(a+t(b-a))$, $\forall t \in [0,1]$, $\varphi$ continua en $[0,1]$. Por la [[regla de la cadena (Rn)]], $\varphi$ es derivable en $]0,1[$ y
$$\varphi'(t) = \langle \nabla f(a+t(b-a)), b-a \rangle.$$
Por el teorema del valor medio en $\mathbb R$, $\exists \xi \in ]0,1[$ tal que
$$f(b) - f(a) = \varphi(1) - \varphi(0) = \varphi'(\xi) = \langle \nabla f(a+t(b-a)), b-a \rangle.$$
Luego tomamos $c = a+ \xi(b-a)$.
Tags: dem anII
<!--ID: 1730228001561-->
END


START
Básico
Anverso: Demostración de que sea $\Omega \subseteq \mathbb R^n$ abierto, $a,b \in \Omega$ tales que $[a,b] \subseteq \Omega$ y $f: \Omega \to \mathbb R$ continua en $[a,b]$ y diferenciable en $]a,b[$. Entonces $\exists c \in ]a,b[$ tal que
$$f(b) - f(a) = \langle \nabla f(c), b-a \rangle.$$
Reverso: Consideramos $\varphi: [0,1] \to \mathbb R$ con $\varphi(t) = f(a+t(b-a))$, $\forall t \in [0,1]$, $\varphi$ continua en $[0,1]$. Por la [[regla de la cadena (Rn)]], $\varphi$ es derivable en $]0,1[$ y
$$\varphi'(t) = \langle \nabla f(a+t(b-a)), b-a \rangle.$$
Por el teorema del valor medio en $\mathbb R$, $\exists \xi \in ]0,1[$ tal que
$$f(b) - f(a) = \varphi(1) - \varphi(0) = \varphi'(\xi) = \langle \nabla f(a+t(b-a)), b-a \rangle.$$
Luego tomamos $c = a+ \xi(b-a)$.
Tags: dem anII
<!--ID: 1730368366089-->
END



START
Básico
Anverso: Cuál es el teorema del valor medio de Cauchy (1821)?
Reverso: Sean $f$ y $g$ funciones reales. Si $f$ y $g$ son continuas en $[a,b]$ ([[Función continua en un conjunto]]), y derivables en $]a,b[$ ([[Función derivable en un punto]]), entonces $\exists \xi \in ]a,b[$ tal que
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
En particular, para cualquier función real $f$, continua en $[a,b]$, derivable en $]a,b[$, $\exists \xi \in ]a,b[$ en el cual
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
Tags: proposición/teorema análisisI
<!--ID: 1709231331157-->
END

START
Básico
Anverso: Demostración de que sean $f$ y $g$ funciones reales. Si $f$ y $g$ son continuas en $[a,b]$ ([[Función continua en un conjunto]]), y derivables en $]a,b[$ ([[Función derivable en un punto]]), entonces $\exists \xi \in ]a,b[$ tal que
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
En particular, para cualquier función real $f$, continua en $[a,b]$, derivable en $]a,b[$, $\exists \xi \in ]a,b[$ en el cual
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
(TEOREMA DEL VALOR MEDIO DE CAUCHY (1821))
Reverso: La igualdad
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi)$$
es consecuencia directa de aplicar el [[Teorema de Rolle (1690)]] a $h(x) = (f(b) - f(a))g(x) - (g(b) - g(a))f(x).$

Para
$$f'(\xi) = \frac{f(b)-f(a)}{b-a}$$
basta hacer $g(x) := x, x \in [a,b]$ en
$$[f(b)-f(a)]g'(\xi) = [g(b)-g(a)]f'(\xi).$$
Tags: demostración análisisI
<!--ID: 1709231331166-->
END