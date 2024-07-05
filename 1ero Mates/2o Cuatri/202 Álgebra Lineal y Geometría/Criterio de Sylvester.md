
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-20, 20:15

```ad-theorem
Sea $V$ un $\mathbb R$-espacio vectorial, $\dim V = n$, y sea $F: V \times V \to \mathbb R$ una [[Forma bilineal simétrica]]. Sea $B$ base de $V$ y $A = (a_{ij}) \in M_n(\mathbb R)$ la [[Matriz coordenada de F]] respecto a la base $B$. Entonces:
$$F \textrm{ es producto escalar} \iff a_{11} > 0, \det \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} > 0, \dots, \det(A) > 0$$
([[Producto escalar]])
```


```ad-proof
$\rightarrow$.
Supongamos que $F$ es producto escalar. Escribimos $B = \{v_1, \dots, v_n\}$. Consideramos $V_i = \langle v_1, \dots, v_i \rangle \le V, \forall i = 1, \dots, n$ ($V_n = V$), $\implies \dim V_i = i$. Consideramos $F_i = F \restriction_{V_i \times V_i} : V_i \times V_i \to \mathbb R$ con $(u,v) \to u · v$. Notemos que $F_i$ es un producto escalar en $V_i$.
La matriz coordenada de $F_i$ ([[Matriz coordenada de F]]) respecto a la base $\{v_1 ,\dots, v_i\}$ de $V_i$ es:
$$A_i = \begin{pmatrix}
F_i(v_1, v_1) & \dots & F_i(v_1, v_i) \\
F_i(v_2, v_1) & \dots & F_i(v_2, v_i) \\
\vdots & & \vdots \\
F_i(v_i, v_1) & \dots & F_i(v_i, v_i)
\end{pmatrix} = \begin{pmatrix}
a_{11} & \dots & a_{1i} \\
a_{21} & \dots & a_{2i} \\
\vdots & & \vdots \\
a_{i1} & \dots & a_{ii}
\end{pmatrix} \in M_i(\mathbb R).
$$
Por [[Lema determinante matriz coordenada de un producto escalar]], $\det(A_i) > 0, \forall i = 1, \dots, n$.

$\leftarrow$.
Supongamos que $A$ satisface:
$$a_{11} > 0, \det \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} > 0, \dots, \det(A) > 0.$$
Procederemos por inducción sobre $n = \dim V$.

$n = 1$.
Tenemos $\dim V = 1$ y $A = (a_{11})$ con $a_{11} > 0$. Si $x \in V$, con $[x]_B = (\alpha), \alpha \in \mathbb R$, entonces $F(x,x) = \alpha · A · \alpha = \alpha^2 · a_{11} \ge 0$, y $F(x,x) = 0$ sii $\alpha = 0$ sii $x = 0$. Así, $F$ es producto escalar.

$n-1 \implies n$.
Supongamos el resultado cierto para formas definidas en $\mathbb R$-espacio vectorial de dimensión $n-1$. Tomamos $W = \langle v_1, \dots, v_{n-1} \rangle \le V$, luego $B = \{v_1, \dots, v_n\}$ es base de $W$.
Está claro que $\dim W = n-1$. Consideramos la restricción de $F$ a $W$, es decir, $G = F \restriction_{W \times W} : W \times W \to \mathbb R$. La matriz coordenada de $G$ ([[Matriz coordenada de F]]) respecto a la base $\{v_1, \dots, v_{n-1}\}$ de $W$ es:
$$M = \begin{pmatrix} a_{11} & a_{12} & \dots & a_{1, n-1} \\ a_{21} & a_{22} & \dots & a_{2,n-1} \\ dots & & & \vdots \\ a_{n-1, 1} & a_{n-1, 2} & \dots & a_{n-1, n-1} \end{pmatrix} = (G(v_i, v_j)) \in M_{n-1}(\mathbb R), \quad 1 \le i, j, \le n-1.$$
La matriz $M$ satisface:
$$a_{11} > 0, \det \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} > 0, \dots, \det(M) > 0.$$
Por hipótesis, $G$ es [[Forma bilineal simétrica definida positiva]], es decir, es [[Producto escalar]]. Notemos que $G$ es regular (sobre $W$), de modo que $0 = W^{\perp G} = W^{\perp F} \cap W$. Así, $W$ es [[Subespacio regular]] y entonces $W \bigoplus W^{\perp F} = V$. Está claro que $\dim W^{\perp F} = \dim W^\perp = 1$.
Sea $\{w_1, \dots, w_{n-1} \}$ base ortogonal ([[Conjunto F-ortogonal]]) de $W$, y sea $\{z\}$ una base de $W^\perp \implies \{w_1, \dots, w_{n-1}, z\}$ es base ortogonal de $V$. Ahora,
$$
\begin{array}
F(w_1, w_1) = G(w_1, w_1) > 0 \\
\dots \\
F(w_{n-1}, w_{n-1}) = G(w_{n-1}, w_{n-1}) > 0.
\end{array}
$$
Además, la [[Matriz coordenada de F]] con respecto a la base $\{w_1, w_2, \dots, w_{n-1}, z \}$ es $D = Diag(F(w_1, w_1), \dots, F(w_{n-1}, w_{n-1}), F(z,z))$. Tenemos que $\det (D) =$ $F(w_1, w_1) \dots F(w_{n-1}, w_{n-1}) · F(z,z)$. Basta ver que $\det (D) > 0$, ya que en este caso, $F(z,z) > 0$, y por tanto $sig(F) = n$, y por [[Teorema rango y signatura de un producto escalar]], tendríamos que $F$ es producto escalar.
Observamos que $A, D$ son [[Matrices congruentes]], por ser matrices coordenadas de $F$ ([[Dos matrices coordenadas de F son congruentes]]), de modo que $D = P^t A P$ para $P \in GL_n(\mathbb R)$, lo que implica que $\det (D) = \det(P)^2 · \det(A) > 0$, porque ambos determinantes son mayores que $0$. Luego $F$ es producto escalar.
```


**Tema:** [[Espacios vectoriales euclídeos]]
**Demostrado por:** [[Lema determinante matriz coordenada de un producto escalar]], [[Teorema rango y signatura de un producto escalar sobre los reales]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué dice el Criterio de Sylvester?
Reverso: Sea $V$ un $\mathbb R$-espacio vectorial, $\dim V = n$, y sea $F: V \times V \to \mathbb R$ una [[Forma bilineal simétrica]]. Sea $B$ base de $V$ y $A = (a_{ij}) \in M_n(\mathbb R)$ la [[Matriz coordenada de F]] respecto a la base $B$. Entonces:
$$F \textrm{ es producto escalar} \iff a_{11} > 0, \det \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} > 0, \dots, \det(A) > 0$$
([[Producto escalar]])
Tags: proposición/teorema ÁlgebraI
<!--ID: 1712235233708-->
END

START
Básico
Anverso: Demostración del Criterio de Sylvester
Reverso: $\rightarrow$.
Supongamos que $F$ es producto escalar. Escribimos $B = \{v_1, \dots, v_n\}$. Consideramos $V_i = \langle v_1, \dots, v_i \rangle \le V, \forall i = 1, \dots, n$ ($V_n = V$), $\implies \dim V_i = i$. Consideramos $F_i = F \restriction_{V_i \times V_i} : V_i \times V_i \to \mathbb R$ con $(u,v) \to u · v$. Notemos que $F_i$ es un producto escalar en $V_i$.
La matriz coordenada de $F_i$ ([[Matriz coordenada de F]]) respecto a la base $\{v_1 ,\dots, v_i\}$ de $V_i$ es:
$$A_i = \begin{pmatrix}
F_i(v_1, v_1) & \dots & F_i(v_1, v_i) \\
F_i(v_2, v_1) & \dots & F_i(v_2, v_i) \\
\vdots & & \vdots \\
F_i(v_i, v_1) & \dots & F_i(v_i, v_i)
\end{pmatrix} = \begin{pmatrix}
a_{11} & \dots & a_{1i} \\
a_{21} & \dots & a_{2i} \\
\vdots & & \vdots \\
a_{i1} & \dots & a_{ii}
\end{pmatrix} \in M_i(\mathbb R).
$$
Por [[Lema determinante matriz coordenada de un producto escalar]], $\det(A_i) > 0, \forall i = 1, \dots, n$.

$\leftarrow$.
Supongamos que $A$ satisface:
$$a_{11} > 0, \det \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} > 0, \dots, \det(A) > 0.$$
Procederemos por inducción sobre $n = \dim V$.

$n = 1$.
Tenemos $\dim V = 1$ y $A = (a_{11})$ con $a_{11} > 0$. Si $x \in V$, con $[x]_B = (\alpha), \alpha \in \mathbb R$, entonces $F(x,x) = \alpha · A · \alpha = \alpha^2 · a_{11} \ge 0$, y $F(x,x) = 0$ sii $\alpha = 0$ sii $x = 0$. Así, $F$ es producto escalar.

$n-1 \implies n$.
Supongamos el resultado cierto para formas definidas en $\mathbb R$-espacio vectorial de dimensión $n-1$. Tomamos $W = \langle v_1, \dots, v_{n-1} \rangle \le V$, luego $B = \{v_1, \dots, v_n\}$ es base de $W$.
Está claro que $\dim W = n-1$. Consideramos la restricción de $F$ a $W$, es decir, $G = F \restriction_{W \times W} : W \times W \to \mathbb R$. La matriz coordenada de $G$ ([[Matriz coordenada de F]]) respecto a la base $\{v_1, \dots, v_{n-1}\}$ de $W$ es:
$$M = \begin{pmatrix} a_{11} & a_{12} & \dots & a_{1, n-1} \\ a_{21} & a_{22} & \dots & a_{2,n-1} \\ dots & & & \vdots \\ a_{n-1, 1} & a_{n-1, 2} & \dots & a_{n-1, n-1} \end{pmatrix} = (G(v_i, v_j)) \in M_{n-1}(\mathbb R), \quad 1 \le i, j, \le n-1.$$
La matriz $M$ satisface:
$$a_{11} > 0, \det \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} > 0, \dots, \det(M) > 0.$$
Por hipótesis, $G$ es [[Forma bilineal simétrica definida positiva]], es decir, es [[Producto escalar]]. Notemos que $G$ es regular (sobre $W$), de modo que $0 = W^{\perp G} = W^{\perp F} \cap W$. Así, $W$ es [[Subespacio regular]] y entonces $W \bigoplus W^{\perp F} = V$. Está claro que $\dim W^{\perp F} = \dim W^\perp = 1$.
Sea $\{w_1, \dots, w_{n-1} \}$ base ortogonal ([[Conjunto F-ortogonal]]) de $W$, y sea $\{z\}$ una base de $W^\perp \implies \{w_1, \dots, w_{n-1}, z\}$ es base ortogonal de $V$. Ahora,
$$
\begin{array}
F(w_1, w_1) = G(w_1, w_1) > 0 \\
\dots \\
F(w_{n-1}, w_{n-1}) = G(w_{n-1}, w_{n-1}) > 0.
\end{array}
$$
Además, la [[Matriz coordenada de F]] con respecto a la base $\{w_1, w_2, \dots, w_{n-1}, z \}$ es $D = Diag(F(w_1, w_1), \dots, F(w_{n-1}, w_{n-1}), F(z,z))$. Tenemos que $\det (D) =$ $F(w_1, w_1) \dots F(w_{n-1}, w_{n-1}) · F(z,z)$. Basta ver que $\det (D) > 0$, ya que en este caso, $F(z,z) > 0$, y por tanto $sig(F) = n$, y por [[Teorema rango y signatura de un producto escalar sobre los reales]], tendríamos que $F$ es producto escalar.
Observamos que $A, D$ son [[Matrices congruentes]], por ser matrices coordenadas de $F$ ([[Dos matrices coordenadas de F son congruentes]]), de modo que $D = P^t A P$ para $P \in GL_n(\mathbb R)$, lo que implica que $\det (D) = \det(P)^2 · \det(A) > 0$, porque ambos determinantes son mayores que $0$. Luego $F$ es producto escalar.
Tags: demostración ÁlgebraI
<!--ID: 1712235233714-->
END
