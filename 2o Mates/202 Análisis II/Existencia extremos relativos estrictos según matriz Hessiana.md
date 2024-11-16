### Contenido Principal

```ad-theorem
Sean $\Omega \subset \mathbb R^n$ abierto, $f \in C^2(\Omega, \mathbb R)$ y $a \in \Omega$ punto crítico.
1. Si $D^2f(a)$ es definida positiva, entonces $f$ tiene un mínimo relativo estricto en $a$.
2. Si $D^2f(a)$ es definida negativa, entonces $f$ tiene un máximo relativo estricto en $a$.
3. Si $D^2f(a)$ toma valores negativos y positivos, entonces $f$ tiene un punto de silla en $a$.
```

```ad-proof
**(i).**
Tenemos que $D^2f(a)(x) > 0$, $\forall x \in \mathbb R^n \textrm{\\} \{0\}$. Como $a$ es punto crítico, y por definición de $D^2f(a)$:
$$\begin{eqnarray}
P_2(x) &=& f(a) + \langle \nabla f(a), x-a \rangle + \frac{1}{2} \sum \sum D_{ij}f(a) (x_i - a_i)(x_j - a_j) \\
&=& f(a) + \frac{1}{2}D^2f(a)(x-a).
\end{eqnarray}$$
Para ver que $f$ tiene un mínimo relativo estricto en $a$, tenemos que ver que $f(x)-f(a) > 0$, $\forall x$. Sin embargo, esto ocurre $\iff$ $\frac{f(x) - f(a)}{||x-a||^2} > 0$. Esta expresión la podemos extender a:
$$\frac{f(x) - f(a)}{||x-a||^2} = \frac{f(x)-f(a) - \frac{1}{2} D^2 f(a)(x-a)}{||x-a||^2} + \frac{\frac{1}{2}D^2f(a)(x-a)}{||x-a||^2},$$
donde el primer término sabemos que tiende a $0$ por un resultado previo, y el segundo lo podemos reescribir como $\frac{\frac{1}{2} D^2f(a)(x-a)}{||x-a||^2} = \frac{1}{2}D^2f(a)(\frac{x-a}{||x-a||})$, de la que tenemos que encontrar una cota inferior mayor que $0$. Observamos que $S = \{x \in \mathbb R^n : ||x|| = 1 \}$ es un conjunto compacto y $D^f(a)$ es continua porque $f \in C^2$. Así, podemos aplicar Weierstrass, y sabemos que $D^2f(a)$ alcanza un mínimo en $S$ $\implies$ $\exists u \in S$ tal que $D^2f(a)(x) \ge D^2f(a)(u) = \alpha > 0$, $\forall x \in S$. En particular, para $x \neq a$,
$$\frac{D^2f(a)(x-a)}{||x-a||^2} =  D^2f(a) \left ( \frac{x-a}{||x-a||} \right ) \ge \alpha > 0 \implies D^2f(a)(x-a) \ge \alpha ||x-a||^2.$$
Por otro lado, como $\lim \limits_{x \to a} \frac{f(x)-f(a)- \frac{1}{2} D^2f(a)(x-a)}{||x-a||^2} = 0$, entonces $\exists \delta > 0$ tal que $B(a; \delta) \subset \Omega$ y para $x \in \mathbb R^n$ con $0 < ||x-a|| < \delta$,
$$\left |\frac{f(x)-f(a)-\frac{1}{2}D^2f(a)(x-a)}{||x-a||^2} \right | < \frac{\alpha}{2} \implies |f(x)-f(a) - \frac{1}{2} D^2f(a)(x-a) < \frac{\alpha}{2}||x-a||^2.$$
Así,
$$\begin{eqnarray}
f(x)-f(a) &=& f(x) - f(a) - \frac{1}{2}D^2 Df(a)(x-a) + \frac{1}{2} D^2 f(a)(x-a) \\
&>& - \frac{\alpha}{2} ||x-a||^2 + \frac{\alpha}{2}||x-a||^2 = 0.
\end{eqnarray}$$
Por tanto, $f(x) > f(a)$ para $x \in B(a; r)$ con $x \neq a$. Luego $f$ tiene un mínimo relativo estricto en $a$.


**$(ii)$.** Cambiamos $f$ por $-f$.

**$(iii)$.**
Sea $u \in \mathbb R^n \textrm{\\} \{0\}$ con $||u|| = 1$, tal que $\alpha = D^2f(a)(u) > 0$. Aplicamos $P_2(x)$ en la recta con dirección $u$:
$$\lim \limits_{t \to 0}\frac{f(a+tu) - f(a) - \frac{1}{2} D^2f(a)(tu)}{t^2} = 0.$$
Esto implica que $\exists r_1 > 0: B(a; r_1) \subset \Omega$ y para $0 < |t| < r$, entonces 
$$|f(a+tu)-f(a) - \frac{1}{2}D^2f(a)(tu)| < \frac{\alpha}{2} t^2.$$
Notemos que
$$\begin{eqnarray}
f(a+tu) - f(a) &=& f(a+tu)-f(a) - \frac{1}{2} D^2f(a)(tu) + \frac{1}{2} D^2f(a)(tu) \\
&>& - \frac{\alpha}{2} t^2 + \frac{\alpha}{2} t^2 = 0.
\end{eqnarray}$$
Por tanto, $f(a+tu) > f(a)$, $\forall 0 < |t| < r$.
Sea $v \in \mathbb R^n \textrm{\\} \{0\}$ con $||v|| = 1$ tal que $\beta = D^2f(a)(v) < 0$. Por el teorema de Taylor, $\exists r_2 > 0$ tal que $B(a; r_2) \subset \Omega$ y para $0 < |t| < r$
$$|f(a+tv) - f(a) - \frac{1}{2}D^2f(a)(tv)| < - \frac{\beta}{2}t^2.$$
Una vez más,
$$\begin{eqnarray}
f(a+tv) - f(a) &=& f(a+tv) - f(a) - \frac{1}{2}D^2 f(a)(tu) + \frac{1}{2}D^2f(a)(tu) \\
&<& - \frac{\beta}{2}t^2 + \frac{\beta}{2}t^2 = 0.
\end{eqnarray}$$
Por tanto, $f(a+tv)< f(a)$, $\forall 0 < |t| < r_2$. Por tanto, $f$ tiene un punto de silla en $a$.
```

**Tema:** [[Derivadas de orden superior y extremos relativos#3. Extremos relativos y absolutos.]]
**Corolario:**

**Definiciones referenciadas:** [[Extremos relativos]], [$C^2$](Función de clase C2), [$D^2f(a)$](Forma cuadrática), [Punto crítico](Teorema de derivadas nulas en extremos relativos),  [Punto de silla](Teorema de derivadas nulas en extremos relativos), [$P_2(x)$](Polinomio de Taylor de orden dos)
**Resultados referenciados:** [$\lim \limits_{x \to a} \frac{f(x)-P_2(x)}{||x-a||^2} = 0$](Teorema de Taylor para varias variables), [[Teorema de Weierstrass (R^n)]]

---
### Anki
