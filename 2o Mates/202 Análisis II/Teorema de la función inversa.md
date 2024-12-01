### Contenido principal

```ad-theorem
Sea $\Omega$ un abierto de $\mathbb R^n$ y $f: \Omega \to \mathbb R^n$ función de clase $C^1$ en $\Omega$ y $a \in \Omega$. Si $J_f(a) \neq 0$, entonces $\exists U \in \mathcal E(a)$ abierto tal que $U \subset \Omega$ y verifica:
1. $f$ es inyectiva en $U$.
2. $V = f(U)$ es un abierto de $\mathbb R^n$.
3. $J_f(x) \neq 0$, $\forall x \in U$.
4. Si denotamos $\varphi = f \restriction_U : U \to V$ (biyectiva), la inversa local $\varphi^{-1}: V \to U$ es de clase $C^1$ y $D_{\varphi^{-1}} (f(x)) = D_f(x)^{-1}.$
```

```ad-note
title: Notación
$\Omega \subset \mathbb R^n$ abierto, 
$$\Omega^n := \{z = (z^1, z^2, \dots, z^n) : z^j \in \Omega, \, \, \forall j = 1, \dots, n \}; \quad z \in \Omega^n \subset (\mathbb R^n)^n = \mathbb R^{n^2}.$$
Dado $(a_1, \dots, a) \in \Omega^n$, una base de entornos del punto $(a, \dots, a)$ viene dada por los conjunto de la forma
$$B(a; \varepsilon) \times \dots \times B(a; \varepsilon); \quad \varepsilon > 0.$$
```

```ad-proof
Dado que $\Omega$ abierto, $f \in C^1(\Omega)$ y $J_f(a) \neq 0$, entonces $\exists r_1 > 0$ tal que $B(a; r_1) \subset \Omega$ y $h(z^1, \dots, z^n) = \det(D_j f_i(z^i)) \neq 0$, $\forall (z^1, \dots, z^n) \in B(a; r_1) \times \dots \times B(a; r_1)$ (visto en la demostración del teorema de inyectividad local). Por el teorema de inyectivdad local, $\exists 0 < r_2 < r_1$ tal que $f$ es inyectiva en $B(a; r_2)$.

Tomamos $U = B(a; r_2)$, y tenemos que
- $f$ es inyectiva en $U$.
- $J_f(x) \neq 0$, $\forall x \in U$ (notemos que $h(x, \dots, x) = J_f(x) \neq 0$, $\forall x \in B(a; r_2)$ $\subset$ $B(a; r_1)$).
- $f(U)$ = V$ es abierto.
- $\varphi = f_{\restriction U} : U \to V$ biyección y $\varphi^{-1}:V \to U$ es continua.

En particular, $\varphi$ es homeomorfismo. Veamos ahora que $g = \varphi^{-1} \in C^1$. Fijados $j \in \{1, \dots, n\}$, $y \in V$, comencemos por ver si $\exists D_jg(y)$. 

Notemos que como $y \in V = f(U)$, entonces $y = f(x)$ para algún $x \in U$. Como $V$ abierto, entonces $\exists \delta > 0$ tal que $B(y; r) \subset V$. Es decir, $y+te_j \in V$ para $t \in \mathbb R$ con $|t| < \delta$, luego $g(y+te_j) \in U$.
Si fijamos $t$ con $|t| < \delta$, como y $f(g(y)) = y$ y $f(g(y+te_j)) = y+te_j$, tenemos que
$$\begin{array}{l l}
f_i(g(y+te_j)) - f_i(g(y)) = 0 & \textrm{si } i \neq j \\
f_i(g(y + te_j)) - f_i(g(y)) = t & \textrm{si } i = j.
\end{array}$$
Fijémosnos en que $g(y+te_j), g(y) \in U = B(a; r_2)$ convexo, luego podemos aplicar el teorema del valor medio: $\exists z_t^i \in [g(y+te_j), g(y)] \subset U$ tales que
$$\begin{array}{l l}
0 = \frac{f_i(g(y+te_j)) - f_i(g(y))}{t} = \langle \nabla f_i(z_t^i), \frac{g(y + te_j) - g(y)}{t} \rangle & \textrm{si } i \neq j \\
1 = \frac{f_i(g(y+te_j)) - f_i(g(y))}{t} = \langle \nabla f_i(z^i_t), \frac{g(y+te_j) - g(y)}{t} \rangle & \textrm{si } i = j.
\end{array}$$

Esto se traduce en un sistema de ecuaciones que se puede expresar matricialmente como:
$$\begin{pmatrix} D_1f_1(z^1_t) & \dots & D_nf_1(z_t^1) \\
\vdots & \ddots & \vdots \\
D_1f_n(z_t^n) & \dots & D_nf_n(z_t^n)
\end{pmatrix} \begin{pmatrix} \vdots \\ \frac{g(y+te_j) - g(y)}{t} \\ \vdots \end{pmatrix} = e_j.$$
Donde llamaremos $A_t$ a la matriz de coeficientes. Notemos que $\det(A_t)$ $=$ $h(z_1^t, \dots, z_n^t)$ $\neq$ $0$ con $z_1^t, \dots, z_n^t \in B(a; r_2)$. Entonces, tenemos un sistema lineal compatible determinado cuya solución viene dada por
$$\frac{(g(y+te_j)-g(y))^{tr}}{t} = A_t^{-1}(e_j)^{tr}.$$
Por la regla de Cramer, para cada $i \in \{1, \dots, n\}$, tenemos que
$$\frac{g(y+te_j) - g_i(y)}{t} = \frac{\det(\widetilde{A_t})}{\det(A_t)},$$
donde $\widetilde{A_t}$ es la matriz obtenida al sustituir la columna $i$-ésima por $e_j$ en $A_t$.

Observamos que $\lim \limits_{t \to 0} (y+te_j) = y$. Como $g$ es continua, $\lim \limits_{t \to 0} g(y+te_j) = g(y)$, y como $z^i_t \in [g(y+te_j), g(y)]$, tenemos que $\lim \limits_{t \to 0} z_t^i = g(y)$. Además, $D_jf_i$ son continuas, lo que implica que $\lim \limits_{t \to 0} D_jf_i(z_t^i) = D_jf_i(g(y))$. Entonces, $\det(A^t) \rightarrow_{t \to 0} \widetilde{J_f(g(y))}$, luego $\exists D_jg_i:$
$$D_jg_i(y) = \lim_{t \to 0} \frac{g_i(y+te_j) - g_i(y)}{t} = \frac{1}{J_f(g(y))} \det \begin{pmatrix} D_1 f_i(g(y)) & \dots & 0 & \dots & D_nf_1(g(y)) \\ \vdots & & \vdots & & \vdots \\ \vdots & & 1 & & \vdots \\ \vdots & & \vdots & & \vdots \\ D_1 f_n(g(y)) & \dots & 0 & \dots & D_nf_n(g(y)) \end{pmatrix}.$$
Por tanto, $D_jg_i$ es una función continua en $y$ ya que $D_jf_i$ y $g$ son continuas, por tanto $g = \varphi^{-1} \in C^1$.

Además,
$$\begin{eqnarray}
D_jg(y) = f'(g(y))^{-1} \cdot e_j &\implies& D_j(\varphi^{-1})(f(x)) = f'(x)^{-1} \cdot e_j \\
&\implies& D_{\varphi^{-1}}(f(x)) = D_f(x)^{-1}.
\end{eqnarray}$$
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [$C^1$](Función de clase C1), [$J_f(a)$](Determinante jacobiano), [[Entorno]], [$D_f(x)$](Función diferenciable), [[Homeomorfismo]], [$D_jg(y)$](Derivada parcial)
**Resultados referenciados:** [[Teorema de la inyectividad local]], [$f \in C^1(\Omega, \mathbb R^n) : J_f(x) \neq 0, \forall x \in \Omega \implies f$ aplicación abierta](Función de clase C1 con jacobiano no nulo es abierta), [$f \in C^1(\Omega, \mathbb R^n)$ inyectiva $: J_f(x) \neq 0, \forall x \in \Omega \implies f^{-1}: f(\Omega) \to \Omega$ es continua ](Función inversa es continua), [[Teorema del valor medio]]

---
### Corolario.

```ad-cor
title: Corollarium
Sean $\Omega, B$ abiertos de $\mathbb R^n$, $f: \Omega \to B$ biyección de clase $C^1$. Entonces, son equivalentes:
1. $f^{-1} \in C^1$.
2. $J_f(x) \neq 0$, $\forall x \in \Omega$.
```


---
### Contenido Principal ($\mathbb R$)

```ad-theorem
Sea $f: ]u,v[ \to ]s, t[$ estrictamente monótona ([[Función monótona]], o inyectiva), sobreyectiva y continua en $]u,v[$ ([[Función continua en un conjunto]]), denotemos por $g : ]s,t[ \to ]u,v[$ a su [[Función inversa]].

Si $f$ es derivable en $a \in ]u,v[$ ([[Función derivable en un punto]]) y $f'(a) \neq 0$, entonces $g$ es derivable en $b = f(a)$ y
$$g'(b) = 1/f'(a).$$
```


```ad-proof
Puesto que $f$ es derivable en $a$, sea $H$ la función continua en $a$ que cumple con la [[Formulación de Weierstrass (1861)]], es decir, $H(a) = 0$ y
$$f(x) = f(a) + f'(a)(x-a) + H(x)(x-a), \quad x \in ]u,v[.$$
En particular
$$y = f(g(y)) = b + f'(a)(g(y) - g(b)) + H(g(y))(g(y)-g(b)), \quad y \in ]s,t[;$$
así
$$y - b = (f'(a)+H(g(y)))(g(y) - g(b)), \quad y \in ]s,t[.$$
De acuerdo con la igualdad anterior, si $y \neq b$ tendremos que $f'(a) + H(g(y)) \neq 0$, y podemos escribir
$$\frac{g(y) - g(b)}{y-b} = \frac{1}{f'(a) + H(g(y))}, \quad y \in ]s,t[ - \{b\}. \tag{*}$$
Según el [[Teorema función inversa mantiene continuidad y monotonía]],  la función $g$ es continua, entonces $H(g(y))$ también lo es en $b$. Existirá por tanto el límite $\lim_{y \to b} H(g(y)) = H(g(b)) = H(a) = 0$. Esta observación y (*) nos dan que
$$\exists \lim_{y \to b} \frac{g(y)-g(b)}{y-b} = 1/f'(a).$$
```


**Tema:** [[Funciones derivables#4. Teorema de la función inversa]]
**Demostrado por:** [[Formulación de Weierstrass (1861)]], [[Teorema función inversa mantiene continuidad y monotonía]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Teorema de la función inversa ($\mathbb R^n$)
Reverso: Sea $\Omega$ un abierto de $\mathbb R^n$ y $f: \Omega \to \mathbb R^n$ función de clase $C^1$ en $\Omega$ y $a \in \Omega$. Si $J_f(a) \neq 0$, entonces $\exists U \in \mathcal E(a)$ abierto tal que $U \subset A$ y verifica:
1. $f$ es inyectiva en $U$.
2. $V = f(U)$ es un abierto de $\mathbb R^n$.
3. $J_f(x) \neq 0$, $\forall x \in U$.
4. Si denotamos $(f \restriction_U)^{-1} = \varphi = f \restriction_U : U \to V$ (biyectiva), la inversa local $\varphi^{-1}: V \to U$ es de clase $C^1$ y $D_{\varphi^{-1}} (f(x)) = D_f(x)^{-1}.$
Tags: anII
<!--ID: 1732364239584-->
END

START
Básico
Anverso: Demostración del teorema de la función inversa
Reverso: Dado que $\Omega$ abierto, $f \in C^1(\Omega)$ y $J_f(a) \neq 0$, entonces $\exists r_1 > 0$ tal que $B(a; r_1) \subset \Omega$ y $h(z^1, \dots, z^n) = \det(D_j f_i(z^i)) \neq 0$, $\forall (z^1, \dots, z^n) \in B(a; r_1) \times \dots \times B(a; r_1)$ (visto en la demostración del teorema de inyectividad local). Por el teorema de inyectivdad local, $\exists 0 < r_2 < r_1$ tal que $f$ es inyectiva en $B(a; r_2)$.

Tomamos $U = B(a; r_2)$, y tenemos que
- $f$ es inyectiva en $U$.
- $J_f(x) \neq 0$, $\forall x \in U$ (notemos que $h(x, \dots, x) = J_f(x) \neq 0$, $\forall x \in B(a; r_2)$ $\subset$ $B(a; r_1)$).
- $f(U)$ = V$ es abierto.
- $\varphi = f_{\restriction U} : U \to V$ biyección y $\varphi^{-1}:V \to U$ es continua.

En particular, $\varphi$ es homeomorfismo. Veamos ahora que $g = \varphi^{-1} \in C^1$. Fijados $j \in \{1, \dots, n\}$, $y \in V$, comencemos por ver si $\exists D_jg(y)$. 

Notemos que como $y \in V = f(U)$, entonces $y = f(x)$ para algún $x \in U$. Como $V$ abierto, entonces $\exists \delta > 0$ tal que $B(y; r) \subset V$. Es decir, $y+te_j \in V$ para $t \in \mathbb R$ con $|t| < \delta$, luego $g(y+te_j) \in U$.
Si fijamos $t$ con $|t| < \delta$, como y $f(g(y)) = y$ y $f(g(y+te_j)) = y+te_j$, tenemos que
$$\begin{array}{l l}
f_i(g(y+te_j)) - f_i(g(y)) = 0 & \textrm{si } i \neq j \\
f_i(g(y + te_j)) - f_i(g(y)) = t & \textrm{si } i = j.
\end{array}$$
Fijémosnos en que $g(y+te_j), g(y) \in U = B(a; r_2)$ convexo, luego podemos aplicar el teorema del valor medio: $\exists z_t^i \in [g(y+te_j), g(y)] \subset U$ tales que
$$\begin{array}{l l}
0 = \frac{f_i(g(y+te_j)) - f_i(g(y))}{t} = \langle \nabla f_i(z_t^i), \frac{g(y + te_j) - g(y)}{t} \rangle & \textrm{si } i \neq j \\
1 = \frac{f_i(g(y+te_j)) - f_i(g(y))}{t} = \langle \nabla f_i(z^i_t), \frac{g(y+te_j) - g(y)}{t} \rangle & \textrm{si } i = j.
\end{array}$$

Esto se traduce en un sistema de ecuaciones que se puede expresar matricialmente como:
$$\begin{pmatrix} D_1f_1(z^1_t) & \dots & D_nf_1(z_t^1) \\
\vdots & \ddots & \vdots \\
D_1f_n(z_t^n) & \dots & D_nf_n(z_t^n)
\end{pmatrix} \begin{pmatrix} \vdots \\ \frac{g(y+te_j) - g(y)}{t} \\ \vdots \end{pmatrix} = e_j.$$
Donde llamaremos $A_t$ a la matriz de coeficientes. Notemos que $\det(A_t)$ $=$ $h(z_1^t, \dots, z_n^t)$ $\neq$ $0$ con $z_1^t, \dots, z_n^t \in B(a; r_2)$. Entonces, tenemos un sistema lineal compatible determinado cuya solución viene dada por
$$\frac{(g(y+te_j)-g(y))^{tr}}{t} = A_t^{-1}(e_j)^{tr}.$$
Por la regla de Cramer, para cada $i \in \{1, \dots, n\}$, tenemos que
$$\frac{g(y+te_j) - g_i(y)}{t} = \frac{\det(\widetilde{A_t})}{\det(A_t)},$$
donde $\widetilde{A_t}$ es la matriz obtenida al sustituir la columna $i$-ésima por $e_j$ en $A_t$.

Observamos que $\lim \limits_{t \to 0} (y+te_j) = y$. Como $g$ es continua, $\lim \limits_{t \to 0} g(y+te_j) = g(y)$, y como $z^i_t \in [g(y+te_j), g(y)]$, tenemos que $\lim \limits_{t \to 0} z_t^i = g(y)$. Además, $D_jf_i$ son continuas, lo que implica que $\lim \limits_{t \to 0} D_jf_i(z_t^i) = D_jf_i(g(y))$. Entonces, $\det(A^t) \rightarrow_{t \to 0} \widetilde{J_f(g(y))}$, luego $\exists D_jg_i:$
$$D_jg_i(y) = \lim_{t \to 0} \frac{g_i(y+te_j) - g_i(y)}{t} = \frac{1}{J_f(g(y))} \det \begin{pmatrix} D_1 f_i(g(y)) & \dots & 0 & \dots & D_nf_1(g(y)) \\ \vdots & & \vdots & & \vdots \\ \vdots & & 1 & & \vdots \\ \vdots & & \vdots & & \vdots \\ D_1 f_n(g(y)) & \dots & 0 & \dots & D_nf_n(g(y)) \end{pmatrix}.$$
Por tanto, $D_jg_i$ es una función continua en $y$ ya que $D_jf_i$ y $g$ son continuas, por tanto $g = \varphi^{-1} \in C^1$.

Además,
$$\begin{eqnarray}
D_jg(y) = f'(g(y))^{-1} \cdot e_j &\implies& D_j(\varphi^{-1})(f(x)) = f'(x)^{-1} \cdot e_j \\
&\implies& D_{\varphi^{-1}}(f(x)) = D_f(x)^{-1}.
\end{eqnarray}$$
Tags: dem anII
<!--ID: 1733051328702-->
END



START
Básico
Anverso: Cuál es el teorema de la función inversa?
Reverso: Sea $f: ]u,v[ \to ]s, t[$ estrictamente monótona ([[Función monótona]], o inyectiva), sobreyectiva y continua en $]u,v[$ ([[Función continua en un conjunto]]), denotemos por $g : ]s,t[ \to ]u,v[$ a su [[Función inversa]]. Si $f$ es derivable en $a \in ]u,v[$ ([[Función derivable en un punto]]) y $f'(a) \neq 0$, entonces $g$ es derivable en $b = f(a)$ y
$$g'(b) = 1/f'(a).$$
Tags: proposición/teorema análisisI
<!--ID: 1709231331288-->
END

START
Básico
Anverso: Demostración de que sea $f: ]u,v[ \to ]s, t[$ estrictamente monótona ([[Función monótona]], o inyectiva), sobreyectiva y continua en $]u,v[$ ([[Función continua en un conjunto]]), denotemos por $g : ]s,t[ \to ]u,v[$ a su [[Función inversa]]. Si $f$ es derivable en $a \in ]u,v[$ ([[Función derivable en un punto]]) y $f'(a) \neq 0$, entonces $g$ es derivable en $b = f(a)$ y
$$g'(b) = 1/f'(a).$$
(Teorema de la función inversa)
Reverso: Puesto que $f$ es derivable en $a$, sea $H$ la función continua en $a$ que cumple con la [[Formulación de Weierstrass (1861)]], es decir, $H(a) = 0$ y
$$f(x) = f(a) + f'(a)(x-a) + H(x)(x-a), \quad x \in ]u,v[.$$
En particular
$$y = f(g(y)) = b + f'(a)(g(y) - g(b)) + H(g(y))(g(y)-g(b)), \quad y \in ]s,t[;$$
así
$$y - b = (f'(a)+H(g(y)))(g(y) - g(b)), \quad y \in ]s,t[.$$
De acuerdo con la igualdad anterior, si $y \neq b$ tendremos que $f'(a) + H(g(y)) \neq 0$, y podemos escribir
$$\frac{g(y) - g(b)}{y-b} = \frac{1}{f'(a) + H(g(y))}, \quad y \in ]s,t[ - \{b\}. \tag{*}$$
Según el [[Teorema función inversa mantiene continuidad y monotonía]],  la función $g$ es continua, entonces $H(g(y))$ también lo es en $b$. Existirá por tanto el límite $\lim_{y \to b} H(g(y)) = H(g(b)) = H(a) = 0$. Esta observación y (*) nos dan que
$$\exists \lim_{y \to b} \frac{g(y)-g(b)}{y-b} = 1/f'(a).$$
Tags: demostración análisisI
<!--ID: 1709231331296-->
END