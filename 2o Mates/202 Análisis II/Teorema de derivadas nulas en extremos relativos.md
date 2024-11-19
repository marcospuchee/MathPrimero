### Contenido Principal

```ad-theorem
Sean $\Omega \subset \mathbb R^n$ abierto, $f: \Omega \to \mathbb R$ tal que tiene un extremo relativo en $a \in \Omega$ y $f$ tiene derivadas parciales $D_if$ en $a$. Entonces,
$$D_if(a) = 0, \quad \forall i = 1, \dots, n,$$
es decir, $\nabla f(a) = 0$.
```

```ad-note
Notemos que solamente nos otorga candidatos a extremos relativos, pero no extremos relativos directamente. A los puntos donde el gradiente se anula los llamamos puntos críticos.
Un punto crítico que no es máximo ni mínimo relativo lo llamamos punto de silla. Para un puntos de silla $a$ de $f$, tendremos que para cualquier $B(a; r) \subset \Omega$ podemos encontrar $x_1, x_2 \in B(a;r)$ tales que $f(x_1) < f(a) < f(x_2)$.
```

```ad-proof
Supongamos que $f$ tiene un máximo relativo en $a$ $\implies$ $\exists r > 0$ tal que $B(a; r) \subset \Omega$ y $f(x) \le f(a)$, $\forall x \in B(a; r)$. Por definición de derivada parcial,
$$\begin{eqnarray}
D_if(a) &=& \lim_{t \to 0^+} \frac{f(a+te_i)-f(a)}{t} \le 0 \\
&=& \lim_{t \to 0^-} \frac{f(a+te_i)-f(a)}{t} \ge 0,
\end{eqnarray}$$
lo que implica que $D_if(a) = 0$.
```

**Tema:** [[Derivadas de orden superior y extremos relativos#3. Extremos relativos y absolutos.]]
**Corolario:**

**Definiciones referenciadas:**
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Qué valor tienen las derivadas en los extremos relativos?
Reverso: Sean $\Omega \subset \mathbb R^n$ abierto, $f: \Omega \to \mathbb R$ tal que tiene un extremo relativo en $a \in \Omega$ y $f$ tiene derivadas parciales $D_if$ en $a$. Entonces,
$$D_if(a) = 0, \quad \forall i = 1, \dots, n,$$
es decir, $\nabla f(a) = 0$.
Tags: anII
<!--ID: 1731446305288-->
END

START
Básico
Anverso: Demostración de que sean $\Omega \subset \mathbb R^n$ abierto, $f: \Omega \to \mathbb R$ tal que tiene un extremo relativo en $a \in \Omega$ y $f$ tiene derivadas parciales $D_if$ en $a$. Entonces,
$$D_if(a) = 0, \quad \forall i = 1, \dots, n,$$
es decir, $\nabla f(a) = 0$.
Reverso: Supongamos que $f$ tiene un máximo relativo en $a$ $\implies$ $\exists r > 0$ tal que $B(a; r) \subset \Omega$ y $f(x) \le f(a)$, $\forall x \in B(a; r)$. Por definición de derivada parcial,
$$\begin{eqnarray}
D_if(a) &=& \lim_{t \to 0^+} \frac{f(a+te_i)-f(a)}{t} \le 0 \\
&=& \lim_{t \to 0^-} \frac{f(a+te_i)-f(a)}{t} \ge 0,
\end{eqnarray}$$
lo que implica que $D_if(a) = 0$.
Tags: dem anII
<!--ID: 1731446305297-->
END

START
Básico
Anverso: Definición de punto crítico
Reverso: A los puntos donde el gradiente se anula los llamamos puntos críticos.
Tags: anII
<!--ID: 1731931805139-->
END

START
Básico
Anverso: Definición de puntos de silla
Reverso: Un punto crítico que no es máximo ni mínimo relativo lo llamamos punto de silla. Para un puntos de silla $a$ de $f$, tendremos que para cualquier $B(a; r) \subset \Omega$ podemos encontrar $x_1, x_2 \in B(a;r)$ tales que $f(x_1) < f(a) < f(x_2)$.
Tags: anII
<!--ID: 1731931805148-->
END

