### Contenido Principal

```ad-theorem
Sea $\Omega \subseteq \mathbb R^{n+m}$ abierto, $f: \Omega \longrightarrow \mathbb R^m$ de clase $C^1$ en $\Omega$ y $(x_0, y_0) \in \Omega$ tal que $f(x_0, y_0) = 0$. Si $\det \left ( \frac{\partial f_i}{\partial y_j} (x_0, y_0) \right )_{1 \le i,j \le m} \neq 0$, entonces existe un entorno abierto $U$ de $(x_0, y_0)$ en $\mathbb R^{n+m}$, un entorno abierto $V$ de $x_0$ en $\mathbb R^n$ y una única función $g: V \longrightarrow \mathbb R^m$ de clase $C^1$ tal que
- $y_0 = g(x_0)$.
- $f(x, g(x)) = 0$, $\forall x \in V$.
- $\{(x,y) \in U : f(x,y) = 0 \} = \{(x,y) \in \mathbb R^{n+m} : x \in V, \, y = g(x) \}$.

$f(x,y)= 0$ define a $y$ como función implícita de $x$ en un entorno de $(x_0, y_0)$.
```

```ad-proof
Consideramos $F: \Omega \subseteq \mathbb R^{n+m} \longrightarrow \mathbb R^{n+m}$ donde $F(x,y) = (x, f(x,y))$, donde $x = (x_1, \dots, x_n) \in \mathbb R^n$ y $f(x,y) = (f_1(x,y), \dots, f_m(x,y)) \in \mathbb R^m$. Esta función cumple que $F(x_0, y_0) = (x_0, f(x_0, y_0)) = (x_0, 0)$. Además, $F \in C^1(\Omega)$, y $$F'(x_0, y_0) = \left ( \begin{array}{c | c} 
\begin{array}{c c c c}
1 & 0 & \dots & 0 \\
0 & 1 & \dots & 0 \\
\vdots & & & \vdots \\
0 & 0 & \dots & 1
\end{array} & \begin{array}{ c c c}
0 & \dots & 0 \\
0 & \dots & 0 \\
\vdots & & \vdots \\
0 & \dots & 0
\end{array} \\
\hline
\displaystyle \frac{\partial f_i}{\partial x_j}(x_0, y_0) & \displaystyle \frac{\partial f_i}{\partial y_j}(x_0, y_0)
\end{array} \right ), $$ y además, $J_F(x_0, y_0) = \det (\frac{\partial f_i}{\partial y_j}(x_0, y_0)) \neq 0$, por hipótesis.

Aplicamos el teorema de la función inversa a $F$ en $(x_0, y_0)$ (y $F(x_0, y_0) = (x_0, 0)$). Entonces existen
- $U$ entorno abierto de $(x_0, y_0)$ en $\mathbb R^{n+m}$.
- $W = F(U)$ entorno abierto de $F(x_0, y_0) = (x_0, 0)$.
- $F \restriction_U : U \longrightarrow W$ biyectiva con inversa de clase $C^1$, $G = (F \restriction_U)^{-1} : W \longrightarrow U$, $G= (G_1, G_2)$.

Tomamos $V = \{x : (x, 0) \in W \}$ abierto de $\mathbb R^n$ (por ser inversa de la función $x \longmapsto (x,0)$, que es continua), y además $x_0 \in V$. Dado $(x,y) \in U$, entonces $F(x,y) \in W$, luego se le puede aplicar $G$: $$(x,y) = G(F(x,y)) = G(x, f(x,y)) = (G_1(x,f(x,y)), G_2(x, f(x,y))),$$
de donde se obtiene que $x = G_1(x, f(x,y))$, luego $G_1(x,z) = x$, $\forall (x,z) \in W$. Además, $(x,y) \in U \implies y = G_2(x,f(x,y))$.

Definimos $g: V \longrightarrow \mathbb R^m$ con $g(x) = G_2(x,0)$. Notemos que $g \in C^1(V)$. Veamos que $$\{(x,y) \in U : f(x,y) = 0 \} = \{(x,y) \in \mathbb R^{n+m} : x \in V, y = g(x) \}.$$ $\supseteq$.
$x \in V \implies (x,0) \in W \implies G(x,0) = (x,g(x)) \in U$. Falta ver que $f(x,y) = 0$. Notemos que $$(x,0) = F(G(x,0)) = F(x,g(x)) = (x,f(x,g(x))) \implies f(x,g(x)) = 0.$$

$\subseteq$.
Si $(x,y) \in U$ con $f(x,y) = 0$, entonces $$F(x,y) = (x,f(x,y)) = (x,0) \in W \implies x \in V,$$ falta ver que $y = g(x)$. Dado que$(x,y) \in U$, entonces, como hemos visto antes, $$y = G_2(x,f(x,y)) = G_2(x,0) = g(x).$$

Para demostrar la unicidad de $g$, tomamos $\widetilde g: V \longrightarrow \mathbb R^n$ otra función cumpliendo las condiciones del teorema, entonces para $x \in V$, $(x, g(x)), (x, \widetilde g(x)) \in U$, y $f(x,g(x)) = 0 = f(x, \widetilde g(x))$. Por tanto, $$F(x, g(x)) = F(x, f(x,g(x))) = F(x,0) = F(x, f(x, \widetilde g(x))) = F(x, \widetilde g(x)),$$
sin embargo, como $F$ es inyectiva en $U$, entonces $(x, \widetilde g(x)) = (x, g(x))$, luego $\widetilde g = g$.
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#3. El teorema de la función implícita.]]

**Definiciones referenciadas:** [$C^1$](Función de clase C1), [[Derivada parcial]], [[Entorno]], [Gráfica](Función de varias variables)
**Resultados referenciados:** [[Teorema de la función inversa]]

---
### Anki



START
Básico
Anverso: Teorema de la función implícita
Reverso: Sea $\Omega \subseteq \mathbb R^{n+m}$ abierto, $f: \Omega \longrightarrow \mathbb R^m$ de clase $C^1$ en $\Omega$ y $(x_0, y_0) \in \Omega$ tal que $f(x_0, y_0) = 0$. Si $\det \left ( \frac{\partial f_i}{\partial y_j} (x_0, y_0) \right )_{1 \le i,j \le m} \neq 0$, entonces existe un entorno abierto $U$ de $(x_0, y_0)$ en $\mathbb R^{n+m}$, un entorno abierto $V$ de $x_0$ en $\mathbb R^n$ y una única función $g: V \longrightarrow \mathbb R^m$ de clase $C^1$ tal que
- $y_0 = g(x_0)$.
- $f(x, g(x)) = 0$, $\forall x \in V$.
- $\{(x,y) \in U : f(x,y) = 0 \} = \{(x,y) \in \mathbb R^{n+m} : x \in V, \, y = g(x) \}$.

$f(x,y)= 0$ define a $y$ como función implícita de $x$ en un entorno de $(x_0, y_0)$.
Tags: anII
<!--ID: 1734607182724-->
END

START
Básico
Anverso: Demostración de que sea $\Omega \subseteq \mathbb R^{n+m}$ abierto, $f: \Omega \longrightarrow \mathbb R^m$ de clase $C^1$ en $\Omega$ y $(x_0, y_0) \in \Omega$ tal que $f(x_0, y_0) = 0$. Si $\det \left ( \frac{\partial f_i}{\partial y_j} (x_0, y_0) \right )_{1 \le i,j \le m} \neq 0$, entonces existe un entorno abierto $U$ de $(x_0, y_0)$ en $\mathbb R^{n+m}$, un entorno abierto $V$ de $x_0$ en $\mathbb R^n$ y una única función $g: V \longrightarrow \mathbb R^m$ de clase $C^1$ tal que
- $y_0 = g(x_0)$.
- $f(x, g(x)) = 0$, $\forall x \in V$.
- $\{(x,y) \in U : f(x,y) = 0 \} = \{(x,y) \in \mathbb R^{n+m} : x \in V, \, y = g(x) \}$.

$f(x,y)= 0$ define a $y$ como función implícita de $x$ en un entorno de $(x_0, y_0)$.
Reverso: Consideramos $F: \Omega \subseteq \mathbb R^{n+m} \longrightarrow \mathbb R^{n+m}$ donde $F(x,y) = (x, f(x,y))$, donde $x = (x_1, \dots, x_n) \in \mathbb R^n$ y $f(x,y) = (f_1(x,y), \dots, f_m(x,y)) \in \mathbb R^m$. Esta función cumple que $F(x_0, y_0) = (x_0, f(x_0, y_0)) = (x_0, 0)$. Además, $F \in C^1(\Omega)$, y $$F'(x_0, y_0) = \left ( \begin{array}{c | c} 
\begin{array}{c c c c}
1 & 0 & \dots & 0 \\
0 & 1 & \dots & 0 \\
\vdots & & & \vdots \\
0 & 0 & \dots & 1
\end{array} & \begin{array}{ c c c}
0 & \dots & 0 \\
0 & \dots & 0 \\
\vdots & & \vdots \\
0 & \dots & 0
\end{array} \\
\hline
\displaystyle \frac{\partial f_i}{\partial x_j}(x_0, y_0) & \displaystyle \frac{\partial f_i}{\partial y_j}(x_0, y_0)
\end{array} \right ), $$ y además, $J_F(x_0, y_0) = \det (\frac{\partial f_i}{\partial y_j}(x_0, y_0)) \neq 0$, por hipótesis.

Aplicamos el teorema de la función inversa a $F$ en $(x_0, y_0)$ (y $F(x_0, y_0) = (x_0, 0)$). Entonces existen
- $U$ entorno abierto de $(x_0, y_0)$ en $\mathbb R^{n+m}$.
- $W = F(U)$ entorno abierto de $F(x_0, y_0) = (x_0, 0)$.
- $F \restriction_U : U \longrightarrow W$ biyectiva con inversa de clase $C^1$, $G = (F \restriction_U)^{-1} : W \longrightarrow U$, $G= (G_1, G_2)$.

Tomamos $V = \{x : (x, 0) \in W \}$ abierto de $\mathbb R^n$ (por ser inversa de la función $x \longmapsto (x,0)$, que es continua), y además $x_0 \in V$. Dado $(x,y) \in U$, entonces $F(x,y) \in W$, luego se le puede aplicar $G$: $$(x,y) = G(F(x,y)) = G(x, f(x,y)) = (G_1(x,f(x,y)), G_2(x, f(x,y))),$$
de donde se obtiene que $x = G_1(x, f(x,y))$, luego $G_1(x,z) = x$, $\forall (x,z) \in W$. Además, $(x,y) \in U \implies y = G_2(x,f(x,y))$.

Definimos $g: V \longrightarrow \mathbb R^m$ con $g(x) = G_2(x,0)$. Notemos que $g \in C^1(V)$. Veamos que $$\{(x,y) \in U : f(x,y) = 0 \} = \{(x,y) \in \mathbb R^{n+m} : x \in V, y = g(x) \}.$$ $\supseteq$.
$x \in V \implies (x,0) \in W \implies G(x,0) = (x,g(x)) \in U$. Falta ver que $f(x,y) = 0$. Notemos que $$(x,0) = F(G(x,0)) = F(x,g(x)) = (x,f(x,g(x))) \implies f(x,g(x)) = 0.$$

$\subseteq$.
Si $(x,y) \in U$ con $f(x,y) = 0$, entonces $$F(x,y) = (x,f(x,y)) = (x,0) \in W \implies x \in V,$$ falta ver que $y = g(x)$. Dado que$(x,y) \in U$, entonces, como hemos visto antes, $$y = G_2(x,f(x,y)) = G_2(x,0) = g(x).$$

Para demostrar la unicidad de $g$, tomamos $\widetilde g: V \longrightarrow \mathbb R^n$ otra función cumpliendo las condiciones del teorema, entonces para $x \in V$, $(x, g(x)), (x, \widetilde g(x)) \in U$, y $f(x,g(x)) = 0 = f(x, \widetilde g(x))$. Por tanto, $$F(x, g(x)) = F(x, f(x,g(x))) = F(x,0) = F(x, f(x, \widetilde g(x))) = F(x, \widetilde g(x)),$$
sin embargo, como $F$ es inyectiva en $U$, entonces $(x, \widetilde g(x)) = (x, g(x))$, luego $\widetilde g = g$.
Tags: dem anII
<!--ID: 1734607182727-->
END
