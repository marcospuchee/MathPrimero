### Contenido Principal

```ad-cor
$\Omega \subseteq \mathbb R^n$ abierto convexo ($[a,b] \subseteq \Omega, \, \forall a,b \in \Omega$), $f: \Omega \to \mathbb R$ diferenciable. Si todas las derivadas parciales de $f$ están acotadas en $\Omega$, entonces $\exists M \ge 0$ tal que
$$|f(b) - f(a)| \le M \, ||b-a||, \quad \forall a,b \in \Omega.$$
```

^8ab0eb

```ad-proof
Sean $a,b \in \Omega$. $\Omega$ convexo $\implies$ $[a,b] \subseteq \Omega$, luego $\exists c \in ]a,b[$ tal que $f(b) - f(a) = \langle \nabla f(c), b-a \rangle$. Así,
$$|f(b) - f(a)| \le || \nabla f(c) || \, ||b-a|| \le M \, ||b-a||.$$
Luego $\exists M \ge 0$ tal que
$$|| \nabla f(c) || = \left ( \sum_{i = 1}^n (D_if(c))^2 \right )^{1/2} \le M.$$
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#6. Teorema del valor medio.]]

---
### Anki

START
Respuesta anidada
$\Omega \subseteq \mathbb R^n$ abierto convexo ($[a,b] \subseteq \Omega, \, \forall a,b \in \Omega$), $f: \Omega \to \mathbb R$ diferenciable. Si {{c1::todas las derivadas parciales}} de $f$ {{c1::están acotadas en $\Omega$}}, entonces {{c2::$\exists M \ge 0$ tal que
$$|f(b) - f(a)| \le M \, ||b-a||, \quad \forall a,b \in \Omega.$$}}
Tags: anII
<!--ID: 1730228001554-->
END

START
Básico
Anverso: Demostración de que sean $\Omega \subseteq \mathbb R^n$ abierto convexo ($[a,b] \subseteq \Omega, \, \forall a,b \in \Omega$), $f: \Omega \to \mathbb R$ diferenciable. Si todas las derivadas parciales de $f$ están acotadas en $\Omega$, entonces $\exists M \ge 0$ tal que
$$|f(b) - f(a)| \le M \, ||b-a||, \quad \forall a,b \in \Omega.$$
Reverso: Sean $a,b \in \Omega$. $\Omega$ convexo $\implies$ $[a,b] \subseteq \Omega$, luego $\exists c \in ]a,b[$ tal que $f(b) - f(a) = \langle \nabla f(c), b-a \rangle$. Así,
$$|f(b) - f(a)| \le || \nabla f(c) || \, ||b-a|| \le M \, ||b-a||.$$
Luego $\exists M \ge 0$ tal que
$$|| \nabla f(c) || = \left ( \sum_{i = 1}^n (D_if(c))^2 \right )^{1/2} \le M.$$
Tags: dem anII
<!--ID: 1730228001556-->
END
