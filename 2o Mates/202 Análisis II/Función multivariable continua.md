### Contenido principal

```ad-Formal
$f: A \subseteq \mathbb R^n \to \mathbb R^m$, $a \in A$. Decimos que $f$ es continua en $a$ si $\forall \varepsilon > 0$, $\exists \delta > 0$ tal que si $x \in A$ y $||x-a|| < \delta$, entonces $||f(x) - f(a)|| < \varepsilon$.

También se puede decir que $\forall \varepsilon > 0$, $\exists \delta > 0$ tal que $f(B(a; \delta) \cap A) \subseteq B(f(a); \varepsilon)$.

Además, $f$ es continua en $a$ $\iff$ $\forall (x_n)_{n \in \mathbb N} \subseteq A$, $(x_n) \to_n a$, entonces $(f(x_n)) \to_n f(a)$.
```

^02cc47

**Tema:** [[Funciones de varias variables#3. Continuidad.]]

---
### Anki

START
Básico
Anverso: Definición de función multivariable continua
Reverso: Sea $f: A \subseteq \mathbb R^n \to \mathbb R^p$, $a \in A$. Se dice que $f$ es continua en $a$ si $\forall \varepsilon > 0$, $\exists \delta > 0$ tal que si $x \in A$ y $||x-a|| < \delta$, entonces $||f(x) - f(a)|| < \varepsilon$.

En particular, si $a \in A \cap \textrm{ac}A$, entonces $f$ es continua en $a$ $\iff$ $\lim_{x \to a} f(x) = f(a)$.
<!--ID: 1727422026729-->
END
