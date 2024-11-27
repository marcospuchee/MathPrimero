### Contenido Principal

```ad-proposition
Sea $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R$, $a \in \Omega$. Son equivalentes:
1. $f$ es [[función diferenciable]] en $a$.
2. Existen todas las derivadas parciales de $f$ en $a$ y se cumple
$$\lim_{x \to a} \frac{f(x) - f(a) - \langle \nabla f(a), x-a \rangle}{||x-a||}.$$
En cuyo caso, $Df(a)(x) = \langle \nabla f(a), x \rangle \quad \forall x \in \mathbb R^n$, $D_u f(a) = \sum u_i D_i f(a)$.
```

^897578

```ad-proof
$(i) \implies (ii)$. 
$$Df(a)(x) = Df(a)(\sum x_i e_i) = \sum x_i D_i f(a) = \langle \nabla f(a), x \rangle.$$

$(ii) \implies (i)$. Sabemos que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} = 0,$$
definimos $T(x) = \langle \nabla f(a), x \rangle$, que es lineal.
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#2. Matrices jacobianas y vector gradiente.]]

---
### Anki

START
Básico
Anverso: Caracterización de función diferenciable
Reverso: Sea $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R$, $a \in \Omega$. Son equivalentes:
1. $f$ es [[función diferenciable]] en $a$.
2. Existen todas las derivadas parciales de $f$ en $a$ y se cumple
$$\lim_{x \to a} \frac{f(x) - f(a) - \langle \nabla f(a), x-a \rangle}{||x-a||}.$$
En cuyo caso, $Df(a)(x) = \langle \nabla f(a), x \rangle \quad \forall x \in \mathbb R^n$, $D_u f(a) = \sum u_i D_i f(a)$.
Tags: anII
<!--ID: 1728820185235-->
END

START
Básico
Anverso: Demostración de que sea $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R$, $a \in \Omega$. Son equivalentes:
1. $f$ es [[función diferenciable]] en $a$.
2. Existen todas las derivadas parciales de $f$ en $a$ y se cumple
$$\lim_{x \to a} \frac{f(x) - f(a) - \langle \nabla f(a), x-a \rangle}{||x-a||}.$$
En cuyo caso, $Df(a)(x) = \langle \nabla f(a), x \rangle \quad \forall x \in \mathbb R^n$, $D_u f(a) = \sum u_i D_i f(a)$.
Reverso: 
$(i) \implies (ii)$. 
$$Df(a)(x) = Df(a)(\sum x_i e_i) = \sum x_i D_i f(a) = \langle \nabla f(a), x \rangle.$$

$(ii) \implies (i)$. Sabemos que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} = 0,$$
definimos $T(x) = \langle \nabla f(a), x \rangle$, que es lineal.
Tags: dem anII
<!--ID: 1728820185237-->
END
