### Contenido Principal

```ad-theorem
Sean $\Omega \subseteq \mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Si existen las derivadas parciales de $f$ en un entorno de $a$ y son continuas en $a$, entonces $f$ es diferenciable en $a$.
```

^a90316

```ad-proof
Podemos suponer que $m = 1$. Tomamos $r>0$ tal que existan las derivadas parciales de $f$ en $B(a; r)$.

Para $a = (a_1, \dots, a_n)$, y $x = (x_1, \dots, x_n) \in B(a; r)$, notemos que:
$$\begin{eqnarray}
f(x) - f(a) &=& f(x) - f(a_1, x_2, \dots, x_n) + f(a_1, x_2, \dots, x_n) - f(a_1, a_2, \dots, x_n) + \dots + f(a_1, \dots, a_{n-1}, x_n) - f(a) \\
&=& \sum_{i = 1}^n ( f(a_1, \dots, a_{i-1}, x_i, \dots, x_n) - f(a_1, \dots, a_i, x_{i+1}, \dots, x_n) ).
\end{eqnarray}$$

Por [[derivada direccional a partir de parciales]], [[(ejercicio) diferenciable implica que existen todas las derivadas direccionales]], [[caracterización de función diferenciable]], se cumple que
$$\begin{eqnarray}
f(x) - f(a) - \langle \nabla f(a), x-a \rangle = f(x) - f(a) - \sum_{i = 1}^n D_i f(a)(x_i - a) .
\end{eqnarray}$$
Sin embargo, como hemos visto antes, esto es igual a
$$\sum_{i = 1}^n (f(a_1, \dots, a_{i-1}, x_i, \dots, x_n) - f(a_1, \dots, a_i, x_{i+1}, \dots, x_n) - D_i f(a)(x_i - a_i)),$$
donde vamos a llamar a lo de dentro del sumatorio como $R_i(x)$. Como $D_if$ es continua en $a$, dado $\varepsilon > 0$, podemos encontrar $0 < \delta < \frac{r}{\sqrt{2}}$ tal que si $z \in B(a; \delta)$, entonces $||D_if(z) - D_if(a)|| \le \frac{\varepsilon}{n}$, para $i = 1, \dots n$.
Si fijamos $x = (x_1, \dots, x_n) \in B(a; \delta)$, y fijamos $i = 1, \dots, n$, podemos considerar $I = ]a_i - \delta, a_i + \delta[$, y definir
$$\begin{matrix*}[c c c l]
\Psi: & I & \to & \mathbb R \\
& \Psi(t) & \to & f(a_1, \dots, a_{i-1}, t, x_{i+1}, \dots, x_n),
\end{matrix*}$$
luego, $R_i(x)= \Psi (x_i) - \Psi(a_i) - D_if(a)(x_i - a_i)$. Para $t \in I$, $\Psi$ es parcialmente derivable: $\Psi'(t) = D_if(a_1, \dots, a_{i-1}, t, x_{i+1}, \dots, x_n)$. Por el [[teorema del valor medio de Cauchy (1821)]], $\exists c \in ] \min \{a_i x_i\}, \max \{a_i, x_i\} [$ tal que 
$$\Psi(x_i) - \Psi(a_i) = \Psi'(c)(x_i - a_i) \implies \Psi(x_i) - \Psi(a_i) = D_if(a_1, \dots, a_{i-1}, c, x_{i+1}, \dots, x_n)(x_i - a_i).$$
Definimos $z := (a_1, \dots, a_{i-1}, c, x_{i+1}, \dots, x_n)$. Tenemos que
$$R_i(x) = \Psi(x_i) - \Psi(a_i) - D_if(a)(x_i - a_i) = (D_if(z) - D_if(a))(x_i - a_i).$$
Y como se cumple que $||z-a|| < ||x-a|| < \delta$, entonces $z \in B(a; \delta)$. Luego,
$$|R_i(x)| \le |D_if(z) - D_if(a)| |x_i - a_i| \le \frac{\varepsilon}{n}|x_i - a_i| \le \frac{\varepsilon}{n}||x-a||,$$
y podemos concluir que
$$|f(x) - f(a) - \langle \nabla f(a), x-a \rangle | \le n \frac{\varepsilon}{n} ||x-a|| \implies \lim_{x \to a} \frac{f(x) - f(a) - \langle \nabla f(a), x-a \rangle}{||x-a||} = 0.$$
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#4. Condición suficiente de diferenciabilidad.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Condición suficiente de diferenciabilidad
Reverso: Sean $\Omega \subseteq \mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Si existen las derivadas parciales de $f$ en un entorno de $a$ y son continuas en $a$, entonces $f$ es diferenciable en $a$.
Tags: anII
<!--ID: 1729160606429-->
END

START
Básico
Anverso: Demostración de que sean $\Omega \subseteq \mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Si existen las derivadas parciales de $f$ en un entorno de $a$ y son continuas en $a$, entonces $f$ es diferenciable en $a$.
Reverso: Podemos suponer que $m = 1$. Tomamos $r>0$ tal que existan las derivadas parciales de $f$ en $B(a; r)$.

Para $a = (a_1, \dots, a_n)$, y $x = (x_1, \dots, x_n) \in B(a; r)$, notemos que:
$$\begin{eqnarray}
f(x) - f(a) &=& f(x) - f(a_1, x_2, \dots, x_n) + f(a_1, x_2, \dots, x_n) - f(a_1, a_2, \dots, x_n) + \dots + f(a_1, \dots, a_{n-1}, x_n) - f(a) \\
&=& \sum_{i = 1}^n ( f(a_1, \dots, a_{i-1}, x_i, \dots, x_n) - f(a_1, \dots, a_i, x_{i+1}, \dots, x_n) ).
\end{eqnarray}$$

Por [[derivada direccional a partir de parciales]], [[(ejercicio) diferenciable implica que existen todas las derivadas direccionales]], [[caracterización de función diferenciable]], se cumple que
$$\begin{eqnarray}
f(x) - f(a) - \langle \nabla f(a), x-a \rangle = f(x) - f(a) - \sum_{i = 1}^n D_i f(a)(x_i - a) .
\end{eqnarray}$$
Sin embargo, como hemos visto antes, esto es igual a
$$\sum_{i = 1}^n (f(a_1, \dots, a_{i-1}, x_i, \dots, x_n) - f(a_1, \dots, a_i, x_{i+1}, \dots, x_n) - D_i f(a)(x_i - a_i)),$$
donde vamos a llamar a lo de dentro del sumatorio como $R_i(x)$. Como $D_if$ es continua en $a$, dado $\varepsilon > 0$, podemos encontrar $0 < \delta < \frac{r}{\sqrt{2}}$ tal que si $z \in B(a; \delta)$, entonces $||D_if(z) - D_if(a)|| \le \frac{\varepsilon}{n}$, para $i = 1, \dots n$.
Si fijamos $x = (x_1, \dots, x_n) \in B(a; \delta)$, y fijamos $i = 1, \dots, n$, podemos considerar $I = ]a_i - \delta, a_i + \delta[$, y definir
$$\begin{matrix*}[c c c l]
\Psi: & I & \to & \mathbb R \\
& \Psi(t) & \to & f(a_1, \dots, a_{i-1}, t, x_{i+1}, \dots, x_n),
\end{matrix*}$$
luego, $R_i(x)= \Psi (x_i) - \Psi(a_i) - D_if(a)(x_i - a_i)$. Para $t \in I$, $\Psi$ es parcialmente derivable: $\Psi'(t) = D_if(a_1, \dots, a_{i-1}, t, x_{i+1}, \dots, x_n)$. Por el [[Teorema del valor medio]], $\exists c \in ] \min \{a_i x_i\}, \max \{a_i, x_i\} [$ tal que 
$$\Psi(x_i) - \Psi(a_i) = \Psi'(c)(x_i - a_i) \implies \Psi(x_i) - \Psi(a_i) = D_if(a_1, \dots, a_{i-1}, c, x_{i+1}, \dots, x_n)(x_i - a_i).$$
Definimos $z := (a_1, \dots, a_{i-1}, c, x_{i+1}, \dots, x_n)$. Tenemos que
$$R_i(x) = \Psi(x_i) - \Psi(a_i) - D_if(a)(x_i - a_i) = (D_if(z) - D_if(a))(x_i - a_i).$$
Y como se cumple que $||z-a|| < ||x-a|| < \delta$, entonces $z \in B(a; \delta)$. Luego,
$$|R_i(x)| \le |D_if(z) - D_if(a)| |x_i - a_i| \le \frac{\varepsilon}{n}|x_i - a_i| \le \frac{\varepsilon}{n}||x-a||,$$
y podemos concluir que
$$|f(x) - f(a) - \langle \nabla f(a), x-a \rangle | \le n \frac{\varepsilon}{n} ||x-a|| \implies \lim_{x \to a} \frac{f(x) - f(a) - \langle \nabla f(a), x-a \rangle}{||x-a||} = 0.$$
Tags: dem anII
<!--ID: 1729160606431-->
END

