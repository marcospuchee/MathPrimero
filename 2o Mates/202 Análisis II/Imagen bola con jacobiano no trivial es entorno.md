### Contenido Principal

```ad-proposition
Sea $f: \overline{B(a;r)} \subset \mathbb R^n \to \mathbb R^n$ continua en $\overline{B(a; r)}$ y diferenciable en $B(a;r)$. Si $J_f(x) \neq 0$, $\forall x \in B(a; r)$ y $f(x) \neq f(a)$, $\forall x \in S(a,r)$ $=$  $\{x \in \mathbb R^n : ||x-a|| = r \}$, entonces $f(B(a; r))$ es un entorno de $f(a)$.
```

```ad-note
La hipótesis de que sea diferenciable en $B(a;r)$ se puede debilitar con la existencia de las parciales en $\Omega$.
```

```ad-proof
Queremos ver que $\exists R > 0$ tal que $f(a) \in B(f(a); R) \subset f(B(a; r))$. Definimos
$$\begin{array}{c c c l}
g: & S(a;r) & \to & \mathbb R \\
& x & \mapsto & ||f(x)-f(a)|| \ge 0.
\end{array}$$
Como $f(x) \neq f(a)$, $\forall x \in S(a; r)$, entonces, $g(x) > 0$, $\forall x \in S(a; r)$. Además, $g$ es continua y $S(a; r)$ es compacto, lo que implica que podemos aplicar el teorema de Weierstrass y afirmar que $g$ tiene mínimo absoluto en $S(a;r)$. Definimos:
$$m:= \min \limits_{x \in S(a; r)} g(x) = \min \limits_{x \in S(a;r)} ||f(x) - f(a)||; \quad m > 0.$$
Tomamos $R = \frac{m}{2}$ y vamos a ver $B(f(a); R) \subset f(B(a;r))$. Para cada $y \in B(f(a); R)$, queremos ver si $y \in f(B(a; r))$. Es decir, queremos encontrar $c \in B(a;r)$ de forma que $f(c) = y$. Consideramos
$$\begin{array}{c c c l}
h_y: & \overline{B(a;r)} & \to & \mathbb R \\
& x & \mapsto & ||f(x)-y||,
\end{array}$$
que es continua en $\overline{B(a;r)}$ por ser composición de continuas, y $\overline{B(a;r)}$ es compacto por ser cerrado y acotado. Por tanto, podemos aplicar Weierstrass y sabemos que tiene mínimo absoluto en $\overline{B(a;r)}$. En particular,
$$\min \limits_{x \in \overline{B(a;r)}} h_y(x) \le h_y(a) = ||f(a)-y|| < R = \frac{m}{2},$$
dado que $y \in B(f(a);R)$. Para $x \in S(a;r)$, se tiene que
$$h_y(x) = ||f(x) - y|| \ge ||f(x)-f(a)|| - ||f(a)-y|| = g(x) - ||f(a)-y||.$$
Dado que $g(x)$ tiene mínimo $m$ y $||f(a)-y|| < R = \frac{m}{2}$, entonces
$$h_y(x) > m-\frac{m}{2} = \frac{m}{2}.$$
Por tanto, el mínimo de $h_y(x)$ no se alcanza en $S(a; R)$, sino que se alcanza en un punto $c \in B(a;r)$. Como $h_y \ge 0$, $h_y^2$ también alcanza un mínimo (absoluto y, en particular,) relativo en $c \in B(a;r)$.
$$h_y^2(x) = ||f(x)-y||^2 = \sum_{i = 1}^n (f_i(x) - y_i)^2,$$
luego $h_y^2$ es diferenciable en $B(a;r)$. Por tanto, $D_jh_y^2(c) = 0$, $\forall j = 1, \dots, n$. Pero derivando,
$$D_jh_y^2(c) = 2 \sum D_jf_i(c)(f_i(c) - y_i) = 0; \quad j = 1, \dots, n.$$
Estas ecuaciones nos dan un sistema de ecuaciones lineal homogéneo, con incógnitas $f_i(c) - y_i$ y matriz de coeficientes $(D_jf_i(c))_{1 \le 1,j \le n}$ con
$$\det(D_jf_i(c))_{1 \le i,j \le n} = J_f(c) \neq 0 \implies y_i = f_i(c); \quad 1 = 1, \dots, n,$$
lo que implica que $y = f(c) \in f(B(a;r))$.
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [[Función continua]], [[Función diferenciable]], [$J_f(a)$](Determinante jacobiano), [[Entorno]], [[Conjunto compacto]], [[Extremos absoluto]]
**Resultados referenciados:** [[Teorema de Weierstrass (R^n)]]

---
### Anki

START
Respuesta anidada
Sea $f: \overline{B(a;r)} \subset \mathbb R^n \to \mathbb R^n$ continua en $\overline{B(a; r)}$ y diferenciable en $B(a;r)$. Si {{c1::$J_f(x) \neq 0$, $\forall x \in B(a; r)$}} y {{c1::$f(x) \neq f(a)$, $\forall x \in S(a,r)$ $=$  $\{x \in \mathbb R^n : ||x-a|| = r \}$}}, entonces {{c2::$f(B(a; r))$ es un entorno de $f(a)$}}.
Tags: anII
<!--ID: 1732364239587-->
END
