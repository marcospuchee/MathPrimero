### Contenido Principal

```ad-theorem
Sean $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Si existen las derivadas parciales $D_if$ y $D_jf$ es una bola $B(a; r) \subseteq \Omega$ y son diferenciables en $a$, entonces $D_{ij}f(a) = D_{ji}f(a)$.
```

^1d6945

```ad-note
$f: \Omega \to \mathbb R^m$ es diferenciable en $a$ $\iff$ $\lim_{x \to a} \frac{f(x) - f(a) - f'(a)(x-a)}{||x-a||} = 0$ $\iff$ $f(x) = f(a) + f'(a)(x-a) + E(x-a)||x-a||$ donde $\lim_{x \to 0} E(x) = 0$. Basta tomar
$$E(x-a) = \frac{f(x) - f(a) - f'(a)(x-a)}{||x-a||}.$$
```

```ad-proof
Podemos suponer sin pérdida de generalidad que $m = 1$, $n = 2$, $a = (0,0)$. Queremos ver que $D_{21} f(0,0) = D_{12}f(0,0)$.
La idea es que
$$\begin{eqnarray}
D_{12}f(0,0) &\sim& \frac{\frac{\partial f}{\partial y}(h,0) - \frac{\partial f}{\partial y}(0,0)}{h} \\
&\sim& \frac{\frac{f(h,h) - f(h,0)}{h} - \frac{f(0,h) - f(0,0)}{h}}{h} = \frac{f(h,h) - f(h,0) - f(0,h) + f(0,0)}{h^2}.
\end{eqnarray}$$

Sea $0 < h < \frac{r}{2}$, entonces $(h,h), (h,0), (0,h), (0,0) \in B((0,0); r)$. Consideramos $\varphi$ tal que
$$\varphi(h) = f(h,h) - f(h,0) - f(0,h) + f(0,0).$$
Vamos a ver que $\lim_{h \to 0} \frac{\varphi (h)}{h^2} = D_{12}f(0,0) = D_{21}f(0,0)$. Definimos
$$\begin{array}{c c c l}
G: & [0, \frac{r}{2}] & \to & \mathbb R \\
& G(x) & \mapsto & f(x,h) - f(x,0),
\end{array}$$
entonces $\varphi(h) = G(h) - G(0)$, $G$ es derivable y $G'(x) = D_1 f(x,h) - D_1f(x,0)$. Por el [[teorema del valor medio]], $\exists t \in ]0,h[$ tal que
$$\begin{eqnarray}
\varphi(h) &=& G(h) - G(0) = G'(t) \cdot h = (D_1f(t,h) - D_1f(t,0)) \cdot h \\
&=& \frac{\varphi(h)}{h^2} = \frac{D_1f(t,h) - D_1f(t,0)}{h}. \quad (*)
\end{eqnarray}$$
Como $D_1f$ es diferenciable en $(0,0)$, entonces
$$\lim_{(x,y) \to (0,0)} \frac{D_1f(x,y) - D_1f(0,0) - \langle \nabla (D_1f)(0,0), (x,y) \rangle}{||x,y||} = 0,$$
lo que implica que
$$\begin{eqnarray}
D_1f(x,y) &=& D_1f(0,0) + \langle \nabla (D_1f)(0,0), (x,y) \rangle + E(x,y) \, ||(x,y)|| \\
&=& D_1f(0,0) + D_{11}f(0,0) \cdot x + D_{21} f(0,0) \cdot y + E(x,y) \, ||(x,y)||,
\end{eqnarray}$$
donde $\lim_{(x,y) \to (0,0)} E(x,y) = 0$.

En particular,
$$\begin{eqnarray}
D_1f(t,h) &=& D_1f(0,0) + D_{11}f(0,0) \cdot t + D_{21}f(0,0) \cdot h + E(t,h) \, ||(t,h)|| \\
D_1f(t,0) &=& D_1f(0,0) + D_{11}f(0,0) \cdot t + E(t,0) \, ||(t,0)||,
\end{eqnarray}$$
pero por $(*)$, tenemos que
$$\frac{\varphi(h)}{h^2} = D_{21}f(0,0) + \frac{E(t,h) \, ||(t,h)||}{h} - \frac{E(t,0) \, ||(t,0)||}{h},$$
lo que podemos acotar dado que $t<h$ por:
$$\left | E(t,h) \frac{\sqrt{t^2 + h^2}}{h} - \frac{t}{h} E(t,0)| \right | \le |E(t,h)| \cdot 2 + |E(t,0)|,$$
pero esto tiende a cero, luego $\lim_{h \to 0} \frac{\varphi(h)}{h^2} = D_{21} f(0,0)$.

Análogamente, $\lim_{h \to 0} \frac{\varphi(h)}{h^2} = D_{12} f(0,0)$, usando $H(y) = f(h,y) - f(0,y)$.
```

**Tema:** [[Derivadas de orden superior y extremos relativos#1. Derivada de orden dos.]]
**Corolario:** [[Corolario teorema de Young]]

---
### Anki

START
Básico
Anverso: Teorema de Young
Reverso: Sean $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Si existen las derivadas parciales $D_if$ y $D_jf$ es una bola $B(a; r) \subseteq \Omega$ y son diferenciables en $a$, entonces $D_{ij}f(a) = D_{ji}f(a)$.
Tags: anII
<!--ID: 1730228001563-->
END

START
Básico
Anverso: Demostración de que sean $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Si existen las derivadas parciales $D_if$ y $D_jf$ es una bola $B(a; r) \subseteq \Omega$ y son diferenciables en $a$, entonces $D_{ij}f(a) = D_{ji}f(a)$.
Reverso: Notemos primero que $f: \Omega \to \mathbb R^m$ es diferenciable en $a$ $\iff$ $\lim_{x \to a} \frac{f(x) - f(a) - f'(a)(x-a)}{||x-a||} = 0$ $\iff$ $f(x) = f(a) + f'(a)(x-a) + E(x-a)||x-a||$ donde $\lim_{x \to 0} E(x) = 0$. Basta tomar
$$E(x-a) = \frac{f(x) - f(a) - f'(a)(x-a)}{||x-a||}.$$
Podemos suponer sin pérdida de generalidad que $m = 1$, $n = 2$, $a = (0,0)$. Queremos ver que $D_{21} f(0,0) = D_{12}f(0,0)$.
La idea es que
$$\begin{eqnarray}
D_{12}f(0,0) &\sim& \frac{\frac{\partial f}{\partial y}(h,0) - \frac{\partial f}{\partial y}(0,0)}{h} \\
&\sim& \frac{\frac{f(h,h) - f(h,0)}{h} - \frac{f(0,h) - f(0,0)}{h}}{h} = \frac{f(h,h) - f(h,0) - f(0,h) + f(0,0)}{h^2}.
\end{eqnarray}$$

Sea $0 < h < \frac{r}{2}$, entonces $(h,h), (h,0), (0,h), (0,0) \in B((0,0); r)$. Consideramos $\varphi$ tal que
$$\varphi(h) = f(h,h) - f(h,0) - f(0,h) + f(0,0).$$
Vamos a ver que $\lim_{h \to 0} \frac{\varphi (h)}{h^2} = D_{12}f(0,0) = D_{21}f(0,0)$. Definimos
$$\begin{array}{c c c l}
G: & [0, \frac{r}{2}] & \to & \mathbb R \\
& G(x) & \mapsto & f(x,h) - f(x,0),
\end{array}$$
entonces $\varphi(h) = G(h) - G(0)$, $G$ es derivable y $G'(x) = D_1 f(x,h) - D_1f(x,0)$. Por el [[teorema del valor medio]], $\exists t \in ]0,h[$ tal que
$$\begin{eqnarray}
\varphi(h) &=& G(h) - G(0) = G'(t) \cdot h = (D_1f(t,h) - D_1f(t,0)) \cdot h \\
&=& \frac{\varphi(h)}{h^2} = \frac{D_1f(t,h) - D_1f(t,0)}{h}. \quad (*)
\end{eqnarray}$$
Como $D_1f$ es diferenciable en $(0,0)$, entonces
$$\lim_{(x,y) \to (0,0)} \frac{D_1f(x,y) - D_1f(0,0) - \langle \nabla (D_1f)(0,0), (x,y) \rangle}{||x,y||} = 0,$$
lo que implica que
$$\begin{eqnarray}
D_1f(x,y) &=& D_1f(0,0) + \langle \nabla (D_1f)(0,0), (x,y) \rangle + E(x,y) \, ||(x,y)|| \\
&=& D_1f(0,0) + D_{11}f(0,0) \cdot x + D_{21} f(0,0) \cdot y + E(x,y) \, ||(x,y)||,
\end{eqnarray}$$
donde $\lim_{(x,y) \to (0,0)} E(x,y) = 0$.

En particular,
$$\begin{eqnarray}
D_1f(t,h) &=& D_1f(0,0) + D_{11}f(0,0) \cdot t + D_{21}f(0,0) \cdot h + E(t,h) \, ||(t,h)|| \\
D_1f(t,0) &=& D_1f(0,0) + D_{11}f(0,0) \cdot t + E(t,0) \, ||(t,0)||,
\end{eqnarray}$$
pero por $(*)$, tenemos que
$$\frac{\varphi(h)}{h^2} = D_{21}f(0,0) + \frac{E(t,h) \, ||(t,h)||}{h} - \frac{E(t,0) \, ||(t,0)||}{h},$$
lo que podemos acotar dado que $t<h$ por:
$$\left | E(t,h) \frac{\sqrt{t^2 + h^2}}{h} - \frac{t}{h} E(t,0)| \right | \le |E(t,h)| \cdot 2 + |E(t,0)|,$$
pero esto tiende a cero, luego $\lim_{h \to 0} \frac{\varphi(h)}{h^2} = D_{21} f(0,0)$.

Análogamente, $\lim_{h \to 0} \frac{\varphi(h)}{h^2} = D_{12} f(0,0)$, usando $H(y) = f(h,y) - f(0,y)$.
Tags: anII dem
<!--ID: 1730228001565-->
END
