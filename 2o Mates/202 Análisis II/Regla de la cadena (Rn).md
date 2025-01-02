### Contenido Principal

```ad-theorem
Sean $\Omega \subseteq \mathbb R^n$, $U \subseteq \mathbb R^m$ abiertos, $f: \Omega \to \mathbb R^m$, $g: U \to \mathbb R^p$, $f(\Omega) \subseteq U$. Si $f$ es diferenciable en $a \in \Omega$ y $g$ diferenciable en $b = f(a) \in U$, entonces $g \circ f$ es diferenciable en $a$ y
$$D(g \circ f)(a) = Dg(f(a)) \circ Df(a) = Dg(b) \circ Df(a).$$
```

^84a58f

```ad-note
title: Formato matricial
Sea $\Omega \subseteq \mathbb R^n$ y $U \subseteq \mathbb R^m$ abiertos, $f: \Omega \to \mathbb R^m$ y $g: U \to \mathbb R^p$, $f(\Omega) \subseteq U$. Si $f$ es diferenciable en $a \in \Omega$ y $g$ es diferenciable en $b = f(a) \in U$, entonces $h = g \circ f$ es diferenciable en $a$ y su matriz jacobiana es
$$h'(a) = g'(f(a)) \cdot f'(a).$$
```

```ad-proof
**Primer paso.**
Definimos $\Phi : \Omega \to \mathbb R^+_0$ como $\Phi (x) = \frac{||f(x) - f(a) - Df(a)(x-a)||}{||x-a||}$ para $x \in \Omega \textrm{\\} \{a\}$, y definimos $\Phi(a) = 0$. Como $f$ es diferenciable en $a$, $\Phi$ es continua en $a$. Notemos que $||f(x)-f(a) - Df(a)(x-a)|| = \Phi(x)||x-a||$, $\forall x \in \Omega$. Definimos ahora $\Psi: U \to \mathbb R^+_0$ con $\Psi(y) = \frac{||g(y) - g(b) - Dg(b)(y-b)||}{||y-b||}$, $y \in U \textrm{\\} \{b\}$; en particular, definimos $\Psi(b) = 0$. Como $g$ es diferenciable en $b$, $\Psi$ es continua en $b$ y $||g(y) - g(b) - Dg(b)(y-b)|| = \Psi(y)||y-b||$, $\forall y \in U$.
Podemos entonces definir $\Lambda : \Omega \to \mathbb R^+_0$, con
$$\Lambda(x) = ||(g \circ f)(x) - (g \circ f)(a) - Dg(f(a)) \circ Df(a)(x-a)||, \quad \forall x \in \Omega.$$
Tenemos que ver que $\lim_{x \to a} \frac{\Lambda (x)}{||x-a||} = 0$.
Notemos que $Dg(f(a)) \circ Df(a) \in \mathcal L(\mathbb R^n, \mathbb R^p)$. Podemos aplicar [[aplicación lineal es uniformemente continua (lipschitziana)]], y decir que como $Df(a) \in \mathcal L(\mathbb R^n, \mathbb R^m)$ y $Dg(b) \in \mathcal L(\mathbb R^m, \mathbb R^p)$, entonces $\exists M_1, M_2 > 0$ tales que
$$||Df(a)(x)|| \le M_1 ||x||, \, \forall x \in \mathbb R^n; \quad ||Dg(b)(y)|| \le M_2 ||y||, \, \forall y \in \mathbb R^m.$$

**Segundo paso.**
Para $x \in \Omega$, $y=f(x)$, sabemos que
$$\begin{eqnarray}
0 \le \Lambda(x) &=& ||g(y) - g(b) - Dg(b) \circ Df(a)(x-a)|| \\ &\le& ||g(y) - g(b) - Dg(b)(y-b)|| + ||Dg(b)(y-b) - Dg(b) \circ Df(a)(x-a)|| \\
&=& ||g(y) - g(b) - Dg(b)(y-b)|| + ||Dg(b)(y-b)-Df(a)(x-a))||.
\end{eqnarray}$$

En el segundo de los sumandos tenemos que
$$\begin{eqnarray}
||Dg(b)(y-b-Df(a)(x-a))|| &\le& M_2||y-b-Df(a)(x-a)|| \\ &=& M_2||f(x)-f(a)-Df(a)(x-a)|| \\ &=& M_2 \Phi(x)||x-a||,
\end{eqnarray}$$
mientras que en el primero de los sumandos,
$$||g(y)-g(b)-Dg(b)(y-b)|| = \Psi(y)||y-b|| = \Psi(f(x))||f(x)-f(a)||. \quad (*)$$
Sin embargo, nos damos cuenta de que
$$\begin{eqnarray}
||f(x) - f(a)|| &\le& ||f(x)-f(a) - Df(a)(x-a)|| + ||Df(a)(x-a)|| \\
&=& \Phi(x)||x-a|| + ||Df(a)(x-a)|| \le \Phi(x)||x-a|| + M_1 ||x-a|| \\ &=& (\Phi(x) + M_1)||x-a||
\end{eqnarray}$$
lo que implica que
$$(*) \le \Psi(f(x))(\Phi(x) + M_1)||x-a||.$$
Por tanto,
$$0 \le \Lambda(x) \le \Psi(f(x))(\Phi(x) + M_1)||x-a|| + M_2 \Phi(x) ||x-a||.$$

**Tercer paso.**
Para $x \in \Omega \textrm{\\} \{a\}$, $0 \le \frac{\Lambda(x)}{||x-a||} \le \Psi(f(x))(\Phi(x) + M_1) + M_2 \Phi(x)$.
Como $\Phi$ es continua en $a$, $\lim_{x \to a} \Phi(x) = \Phi(a) = 0$.
$f$ es diferenciable (luego continua) y $\Psi$ es continua en $b = f(a)$. Por tanto, $\Psi \circ f$ es continua en $a$ con
$$\lim_{x \to a } \Psi(f(x)) = \Psi(f(a)) = \Psi(b) = 0,$$
lo que implica que
$$\lim_{x \to a} \frac{\Lambda(x)}{||x-a||} = 0.$$
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#5. Regla de la cadena.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es la regla de la cadena en $\mathbb R^n$
Reverso: Sean $\Omega \subseteq \mathbb R^n$, $U \subseteq \mathbb R^m$ abiertos, $f: \Omega \to \mathbb R^m$, $g: U \to \mathbb R^p$, $f(\Omega) \subseteq U$. Si $f$ es diferenciable en $a \in \Omega$ y $g$ diferenciable en $b = f(a) \in U$, entonces $g \circ f$ es diferenciable en $a$ y
$$D(g \circ f)(a) = Dg(f(a)) \circ Df(a) = Dg(b) \circ Df(a).$$
Tags: anII 
<!--ID: 1729160606423-->
END

START
Básico
Anverso: Regla de la cadena en $\mathbb R^n$ (formato matricial)
Reverso: Sea $\Omega \subseteq \mathbb R^n$ y $U \subseteq \mathbb R^m$ abiertos, $f: \Omega \to \mathbb R^m$ y $g: U \to \mathbb R^p$, $f(\Omega) \subseteq U$. Si $f$ es diferenciable en $b = f(a) \in U$, entonces $h = g \circ f$ es diferenciable en $a$ y su matriz jacobiana es
$$h'(a) = g'(f(a)) \cdot f'(a).$$
Tags: anII
<!--ID: 1729503364411-->
END

START
Básico
Anverso: Demostración de que sean $\Omega \subseteq \mathbb R^n$, $U \subseteq \mathbb R^m$ abiertos, $f: \Omega \to \mathbb R^m$, $g: U \to \mathbb R^p$, $f(\Omega) \subseteq U$. Si $f$ es diferenciable en $a \in \Omega$ y $g$ diferenciable en $b = f(a) \in U$, entonces $g \circ f$ es diferenciable en $a$ y
$$D(g \circ f)(a) = Dg(f(a)) \circ Df(a) = Dg(b) \circ Df(a).$$
Reverso: **Primer paso.**
Definimos $\Phi : \Omega \to \mathbb R^+_0$ como $\Phi (x) = \frac{||f(x) - f(a) - Df(a)(x-a)||}{||x-a||}$ para $x \in \Omega \textrm{\\} \{a\}$, y definimos $\Phi(a) = 0$. Como $f$ es diferenciable en $a$, $\Phi$ es continua en $a$. Notemos que $||f(x)-f(a) - Df(a)(x-a)|| = \Phi(x)||x-a||$, $\forall x \in \Omega$. Definimos ahora $\Psi: U \to \mathbb R^+_0$ con $\Psi(y) = \frac{||g(y) - g(b) - Dg(b)(y-b)||}{||y-b||}$, $y \in U \textrm{\\} \{b\}$; en particular, definimos $\Psi(b) = 0$. Como $g$ es diferenciable en $b$, $\Psi$ es continua en $b$ y $||g(y) - g(b) - Dg(b)(y-b)|| = \Psi(y)||y-b||$, $\forall y \in U$.
Podemos entonces definir $\Lambda : \Omega \to \mathbb R^+_0$, con
$$\Lambda(x) = ||(g \circ f)(x) - (g \circ f)(a) - Dg(f(a)) \circ Df(a)(x-a)||, \quad \forall x \in \Omega.$$
Tenemos que ver que $\lim_{x \to a} \frac{\Lambda (x)}{||x-a||} = 0$.
Notemos que $Dg(f(a)) \circ Df(a) \in \mathcal L(\mathbb R^n, \mathbb R^p)$. Podemos aplicar [[aplicación lineal es uniformemente continua (lipschitziana)]], y decir que como $Df(a) \in \mathcal L(\mathbb R^n, \mathbb R^m)$ y $Dg(b) \in \mathcal L(\mathbb R^m, \mathbb R^p)$, entonces $\exists M_1, M_2 > 0$ tales que
$$||Df(a)(x)|| \le M_1 ||x||, \, \forall x \in \mathbb R^n; \quad ||Dg(b)(y)|| \le M_2 ||y||, \, \forall y \in \mathbb R^m.$$

**Segundo paso.**
Para $x \in \Omega$, $y=f(x)$, sabemos que
$$\begin{eqnarray}
0 \le \Lambda(x) &=& ||g(y) - g(b) - Dg(b) \circ Df(a)(x-a)|| \\ &\le& ||g(y) - g(b) - Dg(b)(y-b)|| + ||Dg(b)(y-b) - Dg(b) \circ Df(a)(x-a)|| \\
&=& ||g(y) - g(b) - Dg(b)(y-b)|| + ||Dg(b)(y-b-Df(a)(x-a))||.
\end{eqnarray}$$

En el segundo de los sumandos tenemos que
$$\begin{eqnarray}
||Dg(b)(y-b-Df(a)(x-a))|| &\le& M_2||y-b-Df(a)(x-a)|| \\ &=& M_2||f(x)-f(a)-Df(a)(x-a)|| \\ &=& M_2 \Phi(x)||x-a||,
\end{eqnarray}$$
mientras que en el primero de los sumandos,
$$||g(y)-g(b)-Dg(b)(y-b)|| = \Psi(y)||y-b|| = \Psi(f(x))||f(x)-f(a)||. \quad (*)$$
Sin embargo, nos damos cuenta de que
$$\begin{eqnarray}
||f(x) - f(a)|| &\le& ||f(x)-f(a) - Df(a)(x-a)|| + ||Df(a)(x-a)|| \\
&=& \Phi(x)||x-a|| + ||Df(a)(x-a)|| \le \Phi(x)||x-a|| + M_1 ||x-a|| \\ &=& (\Phi(x) + M_1)||x-a||
\end{eqnarray}$$
lo que implica que
$$(*) \le \Psi(x)(f(x))(\Phi(x) + M_1)||x-a||.$$
Por tanto,
$$0 \le \Lambda(x) \le \Psi(f(x))(\Phi(x) + M_1)||x-a|| + M_2 \Phi(x) ||x-a||.$$

**Tercer paso.**
Para $x \in \Omega \textrm{\\} \{a\}$, $0 \le \frac{\Lambda(x)}{||x-a||} \le \Psi(f(x))(\Phi(x) + M_1) + M_2 \Phi(x)$.
Como $\Phi$ es continua en $a$, $\lim_{x \to a} \Phi(x) = \Phi(a) = 0$.
$f$ es diferenciable (luego continua) y $\Psi$ es continua en $b = f(a)$. Por tanto, $\Psi \circ f$ es continua en $a$ con
$$\lim_{x \to a } \Psi(f(x)) = \Psi(f(a)) = \Psi(b) = 0,$$
lo que implica que
$$\lim_{x \to a} \frac{\Lambda(x)}{||x-a||} = 0.$$
Tags: dem anII
<!--ID: 1729503364416-->
END
