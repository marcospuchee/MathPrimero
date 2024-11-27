### Contenido Principal

```ad-theorem
Sea $\Omega \subset \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^n$ de clase $C^1$ en $\Omega$ y $a \in \Omega$. Si $J_f(a) \neq 0$, entonces $\exists r > 0$ tal que $B(a; r) \subset \Omega$ y $f_{\restriction B(a; r)}$ es inyectiva. Luego $f$ es inyectiva en $B(a; r)$.
```

```ad-note
Si $J_f(x) \neq 0$, $\forall x \in \Omega$, no se tiene en general que $f$ sea inyectiva en $\Omega$. Es decir, el resultado anterior tiene caracter local.
```

```ad-proof
Consideramos $h : \Omega^n \to \mathbb R$ definida como:
$$h(z^1, \dots, z^n) = \det(D_jf_i(z^i)_{1 \le i,j \le n}) = \det \begin{pmatrix} D_1 f_1(z^1) & \dots & D_nf_1(z^1) \\ \vdots & \ddots & \vdots \\ D_1f_n(z^n) & \dots & D_nf_n(z ^n) \end{pmatrix}.$$
$f \in C^1(\Omega) \implies h$ es continua en $\Omega^n$. Además, $h(a, \dots, a) = J_f(a) \neq 0$. Juntando ambas cosas, $\exists r > 0$ tal que $B(a; r) \subset \Omega$ y $h(z^1, \dots, z^n) \neq 0$, $\forall (z^1, \dots, z^n) \in B(a; r) \times \dots \times B(a; r)$.

Tomamos $x, y \in B(a; r)$ tal que $f(x) = f(y)$, queremos ver que $x = y$. Si aplicamos el teorema del valor medio a cada $f_i : B(a;r) \to \mathbb R$, obtenemos $z^i \in [x,y] \subset B(a; r)$ tal que
$$0 = f_i(y) - f_i(x) = \langle \nabla f(z^i), y-x \rangle = \sum_{j = 1}^n D_jf_i(z^i)(y_j - x_j); \quad i = 1, \dots, n.$$
Obtenemos un sistema de ecuaciones lineal homogéneo con incógnitas $y_j - x_j$ y matriz de coeficientes $(D_jf_i(z^i))_{1 \le i,j \le n}$, donde
$$\det(D_jf_i(z^i)) = h(z^1, \dots, z^n) \neq 0,$$
ya que $z_i \in B(a; r)$. Entonces, la solución al sistema es $y_j - x_j = 0$, $\forall j = 1, \dots , n$. Luego, $x = y$.
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [$C^1$](Función de clase C1), [$J_f(a)$](Determinante jacobiano)
**Resultados referenciados:** [[Teorema del valor medio]]

---
### Anki

START
Básico
Anverso: Demostración de que sea $\Omega \subset \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^n$ de clase $C^1$ en $\Omega$ y $a \in \Omega$. Si $J_f(a) \neq 0$, entonces $\exists r > 0$ tal que $B(a; r) \subset \Omega$ y la restricción de $f$ a la bola abierta $B(a; r)$ es inyectiva. Luego $f$ es inyectiva en $B(a; r)$.
Reverso: Consideramos $h : \Omega^n \to \mathbb R$ definida
$$h(z^1, \dots, z^n) = \det(D_jf_i(z^i))_{1 \le i,j \le n} = \det \begin{pmatrix} D_1 f_1(z^1) & \dots & D_nf_1(z^1) \\ \vdots & \ddots & \vdots \\ D_1f_n(z^n) & \dots & D_nf_n(z ^n) \end{pmatrix}.$$
$f \in C^1(\Omega) \implies h$ es continua en $\Omega^n$. Además, $h(a, \dots, a) = J_f(a) \neq 0$. Juntando ambas cosas, $\exists r > 0$ tal que $B(a; r) \subset \Omega$ y $h(z^1, \dots, z^n) \neq 0$, $\forall (z^1, \dots, z^n) \in B(a; r) \times \dots \times B(a; r)$.

Tomamos $x, y \in B(a; r)$ tal que $f(x) = f(y)$, queremos ver que $x = y$. Si aplicamos el teorema del valor medio a cada $f_i : B(a;r) \to \mathbb R$, obtenemos $z^i \in [x,y] \subset B(a; r)$ tal que
$$0 = f_i(y) - f_i(x) = \langle \nabla f(z^i), y-x \rangle = \sum_{j = 1}^n D_jf_i(z^i)(y_j - x_j); \quad i = 1, \dots, n.$$
Obtenemos un sistema de ecuaciones lineal homogéneo con incógnitas $y_j - x_j$ y matriz de coeficientes $(D_jf_i(z^i))_{1 \le i,j \le n}$, donde
$$\det(D_jf_i(z^i)) = h(z^1, \dots, z^n) \neq 0,$$
ya que $z_i \in B(a; r)$. Entonces, la solución al sistema es $y_j - x_j = 0$, $\forall j = 1, \dots , n$. Luego, $x = y$.
Tags: dem anII
<!--ID: 1732364239582-->
END
