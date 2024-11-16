### Contenido Principal

```ad-theorem
Sea $\Omega \subseteq \mathbb R^n$ abierto y $f: \Omega \to \mathbb R$ una función de clase $C^2$ en $\Omega$. Para $B(a;r) \subset \Omega$ con $r > 0$, se tiene que para cualquier $x \in B(a; r)$ se cumple que
$$f(x) = f(a)  + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a)(x_i - a_i)(x_j - a_j) + R(x),$$
donde $\lim \limits_{x \to a} \frac{R(x)}{||x-a||^2} = 0$. Es decir,
$$\lim \limits_{x \to a} \frac{f(x) - P_2(x)}{||x-a||^2} = 0.$$
```

```ad-proof
Sea $x \in B(a;r)$, consideramos $\varphi: [0,1] \to \mathbb R$ definida por $\varphi(t) = f(a + t(x-a))$. Por la regla de la cadena, $\varphi$ admite derivadas de orden dos y, de hecho, son continuas:
$$\begin{eqnarray}
\varphi'(t) &=& \langle \nabla f(a+t(x-a)), x-a \rangle = \sum_{j = 1}^n D_j f(a+t(x-a))(x_j - a_j) \\
\varphi''(t) &=& \sum_{j = 1}^n \langle \nabla (D_jf)(a+t(x-a)), x-a \rangle (x_j - a_j) \\
&=& \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a+t(x-a)) \cdot (x_i - a_i)(x_j - a_j)
\end{eqnarray}$$
Por el teorema de Taylor de $\mathbb R$, $\exists 0 < \theta < t$ tal que 
$$\varphi(t) = \varphi(0) + \varphi'(0)t + \frac{ \varphi''(\theta)}{2}t^2.$$
Para $t = 1$, tenemos que
$$\varphi(1) = \varphi(0) + \varphi'(0) + \frac{\varphi''(\theta)}{2},$$
lo que implica que
$$\begin{eqnarray}
f(x) &=& f(a) + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a + \theta(x-a))(x_i - a_i)(x_j - a_j) \\
&=& f(a) + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a)(x_i - a_i)(x_j - a_j) + R(x).
\end{eqnarray},$$
donde $R(x) = \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n \left [ D_{ij}f(a+\theta(x-a)) - D_{ij}f(a) \right ](x_i - a_i)(x_j - a_j)$ $=$ $f(x) - P_2f(x)$. Ahora,
$$\begin{eqnarray}
\left | \frac{R(x)}{||x-a||^2} \right | &\le& \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n \frac{\left | D_{ij}f(a + \theta(x-a)) - D_{ij}f(a) \right| |x_i a_i| |x_j - a_j|}{||x-a||^2} \\
&\le& \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n \left | D_{ij}f(a + \theta(x-a)) - D_{ij}f(a) \right|,
\end{eqnarray}$$
pero esto último tiende a $0$ por la continuidad de $D_{ij}f$ en $a$, luego
$$\lim_{x \to a} \frac{R(x)}{||x-a||^2} = 0.$$

```

**Tema:** [[Derivadas de orden superior y extremos relativos#2. Fórmula de Taylor.]]
**Corolario:**

**Definiciones referenciadas:**
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Teorema de Taylor para varias variables.
Reverso: Sea $\Omega \subseteq \mathbb R^n$ abierto y $f: \Omega \to \mathbb R$ una función de clase $C^2$ en $\Omega$. Para $B(a;r) \subset \Omega$ con $r > 0$, se tiene que para cualquier $x \in B(a; r)$ se cumple que
$$f(x) = f(a)  + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a)(x_i - a_i)(x_j - a_j) + R(x),$$
donde $\lim \limits_{x \to a} \frac{R(x)}{||x-a||^2} = 0$. Es decir,
$$\lim \limits_{x \to a} \frac{f(x) - P_2(x)}{||x-a||^2} = 0.$$
Tags: anII
<!--ID: 1731446305307-->
END

START
Básico
Anverso: Demostración de que sea $\Omega \subseteq \mathbb R^n$ abierto y $f: \Omega \to \mathbb R$ una función de clase $C^2$ en $\Omega$. Para $B(a;r) \subset \Omega$ con $r > 0$, se tiene que para cualquier $x \in B(a; r)$ se cumple que
$$f(x) = f(a)  + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a)(x_i - a_i)(x_j - a_j) + R(x),$$
donde $\lim \limits_{x \to a} \frac{R(x)}{||x-a||^2} = 0$. Es decir,
$$\lim \limits_{x \to a} \frac{f(x) - P_2(x)}{||x-a||^2} = 0.$$
Reverso: Sea $x \in B(a;r)$, consideramos $\varphi: [0,1] \to \mathbb R$ definida por $\varphi(t) = f(a + t(x-a))$. Por la regla de la cadena, $\varphi$ admite derivadas de orden dos y, de hecho, son continuas:
$$\begin{eqnarray}
\varphi'(t) &=& \langle \nabla f(a+t(x-a)), x-a \rangle = \sum_{j = 1}^n D_j f(a+t(x-a))(x_j - a_j) \\
\varphi''(t) &=& \sum_{j = 1}^n \langle \nabla (D_jf)(a+t(x-a)), x-a \rangle (x_j - a_j) \\
&=& \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a+t(x-a)) \cdot (x_i - a_i)(x_j - a_j)
\end{eqnarray}$$
Por el teorema de Taylor de $\mathbb R$, $\exists 0 < \theta < t$ tal que 
$$\varphi(t) = \varphi(0) + \varphi'(0)t + \frac{ \varphi''(\theta)}{2}t^2.$$
Para $t = 1$, tenemos que
$$\varphi(1) = \varphi(0) + \varphi'(0) + \frac{\varphi''(\theta)}{2},$$
lo que implica que
$$\begin{eqnarray}
f(x) &=& f(a) + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a + \theta(x-a))(x_i - a_i)(x_j - a_j) \\
&=& f(a) + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n D_{ij}f(a)(x_i - a_i)(x_j - a_j) + R(x).
\end{eqnarray},$$
donde $R(x) = \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n \left [ D_{ij}f(a+\theta(x-a)) - D_{ij}f(a) \right ](x_i - a_i)(x_j - a_j)$ $=$ $f(x) - P_2f(x)$. Ahora,
$$\begin{eqnarray}
\left | \frac{R(x)}{||x-a||^2} \right | &\le& \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n \frac{\left | D_{ij}f(a + \theta(x-a)) - D_{ij}f(a) \right| |x_i a_i| |x_j - a_j|}{||x-a||^2} \\
&\le& \frac{1}{2} \sum_{i = 1}^n \sum_{j = 1}^n \left | D_{ij}f(a + \theta(x-a)) - D_{ij}f(a) \right|,
\end{eqnarray}$$
pero esto último tiende a $0$ por la continuidad de $D_{ij}f$ en $a$, luego
$$\lim_{x \to a} \frac{R(x)}{||x-a||^2} = 0.$$
Tags: dem anII
<!--ID: 1731446305316-->
END

