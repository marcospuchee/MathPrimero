
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-02, 16:45

```ad-theorem
Sea $\varphi: [a,b] \to \mathbb R$ derivable en $[a,b]$, continua y estrictamente monótona. Si $f$ es continua en $\varphi ([a,b])$ entonces
$$\int_a^b f(\varphi (t)) \varphi'(t) \, dt = \int_{\varphi (a)}^{\varphi (b)} f(x) \, dx.$$
Además, $f(\varphi(t))\varphi'(t)$ es continua en $[a,b]$.
```

```ad-note
Si $c<d$,
$$\int_d^c f(x) \, dx = - \int_c^d f(x) \, dx.$$
```

```ad-proof
Como $\varphi([a,b])$ es cerrado y acotado, entonces es un intervalo cerrado y acotado (por Bolzano + Weierstrass). Es decir, $\varphi([a,b]) = [c,d]$. Además, por ser estrictamente monótona, $\varphi: [a,b] \to [c,d]$ es biyectiva.

Definimos $F: [c,d] \to \mathbb R$ tal que es la [[función primitiva]] de $f$. Luego $F(u) = \int^u_c f(x) \, dx$, $\forall u \in ]c,d[$, y $F(c) = 0$ por el [[teorema definción alternativa de primitiva]].

Sea $H = F \circ \varphi: [a,b] \to \mathbb R$ continua (porque [[composición de funciones continuas es continua]]). Si $t \in ]a,b[$, entonces
$$H'(t) = (F \circ \varphi)'(t) = F'(\varphi(t)) \varphi'(t) = f(\varphi(t)) \varphi'(t).$$

Sin embargo, como $(f \circ \varphi) \varphi'$ es continua (composición y producto de continuas), entonces $(f \circ \varphi) \varphi'$ es continua, y por [[teorema continuidad implica integrabilidad]], entonces es integrable en $[a,b]$.

Por la [[regla de Barrow]], $\int_a^b f(\varphi(t)) \varphi'(t) \, dt = H(b) - H(a)$. Ahora vamos a distinguir dos casos:

**Primer caso.** $\varphi : [a,b] \to [c,d]$ es estrictamente creciente, luego por [[teorema principal de Weierstrass (1861)]], tenemos que $c = \varphi(a)$ y $d = \varphi(b)$. Entonces,
$$
\begin{array}{l}
H(b) = F(\varphi(b)) = \int_c^{\varphi(b)} f(x) \, dx = \int_{\varphi(a)}^{\varphi(b)} f(x) \, dx, \\
H(a) = F(\varphi(a)) = F(c) = 0.
\end{array}
$$
Así,
$$\int_a^b f(\varphi(t))\varphi'(t) \, dt = \int_{\varphi(a)}^{\varphi(b)} f(x) \, dx.$$

**Segundo caso.** $\varphi: [a,b] \to [c,d]$ estrictamente decreciente, luego por el teorema principal de Wierstrass, $c = \varphi(b), d = \varphi(a)$. Tenemos:
$$
\begin{array}{l}
H(b) = F(\varphi(b)) = F(c) = 0, \\
H(a) = F(\varphi(a)) = F(d) = \int_c^d f(x) \, dx = \int_{\varphi (b)}^{\varphi (a)} f(x) \, dx.
\end{array}
$$
Luego
$$\int_a^b f(\varphi(t)) \varphi'(t) \, dt = - \int_{\varphi(b)}^{\varphi(a)} f(x) \, dx = \int_{\varphi(a)}^{\varphi(b)} f(x) \, dx.$$
```

**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:** [[Teorema definición alternativa de primitiva]], [[Teorema principal de Weierstrass (1861)]],  [[Composición de funciones continuas es continua]], [[Regla de Barrow]], [[Teorema continuidad implica integrabilidad]]
**Consecuencias:** [[Teorema segunda sustitución de variable en integrales]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la primera sustitución de variable en integrales?
Reverso: Sea $\varphi: [a,b] \to \mathbb R$ derivable en $[a,b]$, continua y estrictamente monótona. Si $f$ es continua en $\varphi ([a,b])$ entonces
$$\int_a^b f(\varphi (t)) \varphi'(t) \, dt = \int_{\varphi (a)}^{\varphi (b)} f(x) \, dx.$$
Además, $f(\varphi(t))\varphi'(t)$ es continua en $[a,b]$.
Tags: proposición/teorema análisisI
<!--ID: 1714720468831-->
END



START
Básico
Anverso: Demostración de que sea $\varphi: [a,b] \to \mathbb R$ derivable en $[a,b]$, continua y estrictamente monótona. Si $f$ es continua en $\varphi ([a,b])$ entonces
$$\int_a^b f(\varphi (t)) \varphi'(t) \, dt = \int_{\varphi (a)}^{\varphi (b)} f(x) \, dx.$$
Además, $f(\varphi(t))\varphi'(t)$ es continua en $[a,b]$.
Reverso: Como $\varphi([a,b])$ es cerrado y acotado, entonces es un intervalo cerrado y acotado (por Bolzano + Weierstrass). Es decir, $\varphi([a,b]) = [c,d]$. Además, por ser estrictamente monótona, $\varphi: [a,b] \to [c,d]$ es biyectiva.

Definimos $F: [c,d] \to \mathbb R$ tal que es la [[función primitiva]] de $f$. Luego $F(u) = \int^u_c f(x) \, dx$, $\forall u \in ]c,d[$, y $F(c) = 0$ por el [[teorema definción alternativa de primitiva]].

Sea $H = F \circ \varphi: [a,b] \to \mathbb R$ continua (porque [[composición de funciones continuas es continua]]). Si $t \in ]a,b[$, entonces
$$H'(t) = (F \circ \varphi)'(t) = F'(\varphi(t)) \varphi'(t) = f(\varphi(t)) \varphi'(t).$$

Sin embargo, como $(f \circ \varphi) \varphi'$ es continua (composición y producto de continuas), entonces $(f \circ \varphi) \varphi'$ es continua, y por [[teorema continuidad implica integrabilidad]], entonces es integrable en $[a,b]$.

Por la [[regla de Barrow]], $\int_a^b f(\varphi(t)) \varphi'(t) \, dt = H(b) - H(a)$. Ahora vamos a distinguir dos casos:

**Primer caso.** $\varphi : [a,b] \to [c,d]$ es estrictamente creciente, luego por [[teorema principal de Weierstrass (1861)]], tenemos que $c = \varphi(a)$ y $d = \varphi(b)$. Entonces,
$$
\begin{array}{l}
H(b) = F(\varphi(b)) = \int_c^{\varphi(b)} f(x) \, dx = \int_{\varphi(a)}^{\varphi(b)} f(x) \, dx, \\
H(a) = F(\varphi(a)) = F(c) = 0.
\end{array}
$$
Así,
$$\int_a^b f(\varphi(t))\varphi'(t) \, dt = \int_{\varphi(a)}^{\varphi(b)} f(x) \, dx.$$

**Segundo caso.** $\varphi: [a,b] \to [c,d]$ estrictamente decreciente, luego por el teorema principal de Wierstrass, $c = \varphi(b), d = \varphi(a)$. Tenemos:
$$
\begin{array}{l}
H(b) = F(\varphi(b)) = F(c) = 0, \\
H(a) = F(\varphi(a)) = F(d) = \int_c^d f(x) \, dx = \int_{\varphi (b)}^{\varphi (a)} f(x) \, dx.
\end{array}
$$
Luego
$$\int_a^b f(\varphi(t)) \varphi'(t) \, dt = - \int_{\varphi(b)}^{\varphi(a)} f(x) \, dx = \int_{\varphi(a)}^{\varphi(b)} f(x) \, dx.$$
Tags: demostración análisisI
<!--ID: 1714669443628-->
END

