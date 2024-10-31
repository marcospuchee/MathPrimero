### Contenido Principal


```ad-theorem
Sea $G$ un [[grupo cíclico]] finito y $d | |G|$. Entonces $G$ tiene un único [[subgrupo]] de orden $d$.
```

^9c8693

```ad-proof
Sabemos que $|G| = | \langle x \rangle | = o(x) = n$, $\quad d|n$.

Notemos que $\langle x^{n/d} \rangle \le G$ por [[subgrupo generado es subgrupo]]. Entonces,
$| \langle x^{n/d} \rangle$ $=$ (por [[propiedades orden grupos cíclicos]]) $o(x^{n/d})$ $=$ (por [[orden de un exponente de un elemento de un grupo]]) $\frac{n}{\textrm{mcd}(n, n/d)} = \frac{n}{n/d} = d$.

Sea $H \le G$ con $|H| = d$. Vemos que $H = \langle x^{n/d} \rangle$. Como $G$ [[grupo]] y $H \le G$, entonces $H$ cíclico. Es decir, $\exists y \in G$ tal que $H = \langle y \rangle$.
- $H$ cíclico, $|H| = |\langle y \rangle | = o(y) = d \implies y^d = 1_G$.
- $y \in G = \langle x \rangle \implies \exists m \in \mathbb Z, \, y = x^m$.

Sabemos que $1_G = y^d = (x^m)^d = x^{md}$. Por [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], $n | md$, lo que implica que $\exists k \in \mathbb Z$ tal que $kn = md$, luego $m = kn/d$.
Además, $y = x^m = (x^{n/d})^k \in \langle x^{n/d} \rangle$, lo que implica por [[subgrupo generado es mínimo subgrupo que contiene al conjunto que lo genera]] que $\langle y \rangle = H \le \langle x^{n/d} \rangle$, pero como tienen el mismo cardinal, $H = \langle x^{n/d} \rangle$.
```

**Tema:** [[Teoría de grupos#8. Grupos cíclicos.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Proposición grupo cíclico finito tiene un único subgrupo del orden de cada uno de sus divisores
Reverso: Sea $G$ un [[grupo cíclico]] finito y $d | |G|$. Entonces $G$ tiene un único [[subgrupo]] de orden $d$.
<!--ID: 1727966477535-->
END

START
Básico
Anverso:  Demostración de que sea $G$ un [[grupo cíclico]] finito y $d | |G|$. Entonces $G$ tiene un único [[subgrupo]] de orden $d$.
Reverso: Sabemos que $|G| = | \langle x \rangle | = o(x) = n$, $\quad d|n$.

Notemos que $\langle x^{n/d} \rangle \le G$ por [[subgrupo generado es subgrupo]]. Entonces,
$| \langle x^{n/d} \rangle$ $=$ (por [[Propiedades orden grupos cíclicos]]) $o(x^{n/d})$ $=$ (por [[orden de un exponente de un elemento de un grupo]]) $\frac{n}{\textrm{mcd}(n, n/d)} = \frac{n}{n/d} = d$.

Sea $H \le G$ con $|H| = d$. Vemos que $H = \langle x^{n/d} \rangle$. Como $G$ [[grupo]] y $H \le G$, entonces $H$ cíclico. Es decir, $\exists y \in G$ tal que $H = \langle y \rangle$.
- $H$ cíclico, $|H| = |\langle y \rangle | = o(y) = d \implies y^d = 1_G$.
- $y \in G = \langle x \rangle \implies \exists m \in \mathbb Z, \, y = x^m$.

Sabemos que $1_G = y^d = (x^m)^d = x^{md}$. Por [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], $n | md$, lo que implica que $\exists k \in \mathbb Z$ tal que $kn = md$, luego $m = kn/d$.
Además, $y = x^m = (x^{n/d})^k \in \langle x^{n/d} \rangle$, lo que implica por [[subgrupo generado es mínimo subgrupo que contiene al conjunto que lo genera]] que $\langle y \rangle = H \le \langle x^{n/d} \rangle$, pero como tienen el mismo cardinal, $H = \langle x^{n/d} \rangle$.
Tags: dem est
<!--ID: 1727966477588-->
END
