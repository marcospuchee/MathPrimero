### Contenido Principal

```ad-lemma
Sea $\overline x \in \mathbb R^n$ una solución básica de $(P)$ asociada a la base $B$ y sea $\overline w:= (B^{-1})^T c_B \in \mathbb R^m$. Entonces, $\overline x$ cumple el [[criterio de optimalidad]] $\iff$ $\overline w$ es un punto factible de $(D)$.
```

```ad-proof
Para trabajar con bases, lo primero es pasar nuestro problema $(P)$ a formato estándar, restando variables de holgura $x_h = (x_{n+1}, \dots, x_{n+m})^T \in \mathbb R^m$. El problema queda de la siguiente forma:
$$\begin{matrix*}[c c l]
(P) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax - I_m x_h = b, \\
& & x \ge 0_n, \, x_h \ge 0_m.
\end{matrix*}$$

Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T \in \mathbb R^n$ una solución básica de $(P')$ asociada a la base $B$ (contiene columnas de $A$ y/o $I$) y tomemos
$$\overline w := (B^T)^{-1}c_B \in \mathbb R^m.$$
Como $\overline x$ verifica el [[criterio de optimalidad]], los costes reducidos deben ser no negativos
$$\begin{matrix}
c - A^T(B^{-1})^T c_B \ge 0_n \iff A^T \overline w \le c, \\
c_h - (-I)^T(B^{-1})^T c_B \ge 0_m \iff \overline w \ge 0_m,
\end{matrix}$$

que resulta equivalente a que $\overline w$ sea punto factible de $(D)$.
```

**Tema:** [[Dualidad y análisis de sensibilidad#2. Relaciones primal-dual.]]

---
### Anki

START
Básico
Anverso: Cuál es la relación primal-dual entre soluciones básicas?
Reverso: Sea $\overline x \in \mathbb R^n$ una solución básica de $(P)$ asociada a la base $B$ y sea $\overline w:= (B^{-1})^T c_B \in \mathbb R^m$. Entonces, $\overline x$ cumple el [[criterio de optimalidad]] $\iff$ $\overline w$ es un punto factible de $(D)$.
Tags: prm
<!--ID: 1728820185288-->
END

START
Básico
Anverso: Demostración de que sea $\overline x \in \mathbb R^n$ una solución básica de $(P)$ asociada a la base $B$ y sea $\overline w:= (B^{-1})^T c_B \in \mathbb R^m$. Entonces, $\overline x$ cumple el [[criterio de optimalidad]] $\iff$ $\overline w$ es un punto factible de $(D)$.
Reverso: Para trabajar con bases, lo primero es pasar nuestro problema $(P)$ a formato estándar, restando variables de holgura $x_h = (x_{n+1}, \dots, x_{n+m})^T \in \mathbb R^m$. El problema queda de la siguiente forma:
$$\begin{matrix*}[c c l]
(P) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & Ax - I_m x_h = b, \\
& & x \ge 0_n, \, x_h \ge 0_m.
\end{matrix*}$$

Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T \in \mathbb R^n$ una solución básica de $(P')$ asociada a la base $B$ (contiene columnas de $A$ y/o $I$) y tomemos
$$\overline w := (B^T)^{-1}c_B \in \mathbb R^m.$$
Como $\overline x$ verifica el [[criterio de optimalidad]], los costes reducidos deben ser no negativos
$$\begin{matrix}
c - A^T(B^{-1})^T c_B \ge 0_n \iff A^T \overline w \le c, \\
c_h - (-I)^T(B^{-1})^T c_B \ge 0_m \iff \overline w \ge 0_m,
\end{matrix}$$

que resulta equivalente a que $\overline w$ sea punto factible de $(D)$.
Tags: dem prm
<!--ID: 1728820185292-->
END
