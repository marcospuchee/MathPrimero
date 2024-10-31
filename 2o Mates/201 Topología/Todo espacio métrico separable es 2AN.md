### Contenido Principal

```ad-proposition
Todo [[espacio métrico]] separable ([[espacio topológico separable]]) es 2AN ([[espacio topológico 2 AN]])
```

```ad-proof
Sea $(X, d)$ espacio métrico, $D = \{x_n \}_{n \in \mathbb N}$ un sub[[conjunto denso]] y numerable. Consideramos
$$\mathcal B = \{B(x_n, q) : x_n \in D, \, q \in \mathbb Q^+ \},$$
que es numerable.

Sean $A \in \mathcal T_d$, $x \in A$, entonces $\exists \varepsilon > 0$ tal que $B(x; \varepsilon) \subseteq A$ (por definición de abierto en un espacio métrico). Como $D$ es denso, $\exists n \in \mathbb N$ tal que $x_n \in B(x; \frac{\varepsilon}{4})$.

$\exists q \in \mathbb Q : \frac{\varepsilon}{4} < q < \frac{\varepsilon}{2}$. Tenemos que $d(x, x_n) < \frac{\varepsilon}{4} < q$, lo que implica que $x \in B(x_n ; q)$. Además, si $y \in B(x_n; q)$,
$$d(x,y) \le d(x, x_n) + d(x_n, y) < q+q < \varepsilon \implies B(x_n; q) \subseteq B(x; \varepsilon) \implies x \in B(x_n; q) \subseteq A.$$
Luego $\mathcal B$ es base de abiertos, y $(X, \mathcal T_d)$ es 2AN.
```

**Tema:** [[Puntos especiales#1. Puntos de adherencia.]]

---
### Anki

START
Respuesta anidada
Todo [[espacio métrico]] {{c1::separable ([[espacio topológico separable]])}} es {{c2::2AN ([[espacio topológico 2 AN]])}}
Tags: top
<!--ID: 1728820185240-->
END

START
Básico
Anverso: Demostración de que todo [[espacio métrico]] separable ([[espacio topológico separable]]) es 2AN ([[espacio topológico 2 AN]])
Reverso: Sea $(X, d)$ espacio métrico, $D = \{x_n \}_{n \in \mathbb N}$ un sub[[conjunto denso]] y numerable. Consideramos
$$\mathcal B = \{B(x_n, q) : x_n \in D, \, q \in \mathbb Q^+ \},$$
que es numerable.

Sean $A \in \mathcal T_d$, $x \in A$, entonces $\exists \varepsilon > 0$ tal que $B(x; \varepsilon) \subseteq A$ (por definición de abierto en un espacio métrico). Como $D$ es denso, $\exists n \in \mathbb N$ tal que $x_n \in B(x; \frac{\varepsilon}{4})$.

$\exists q \in \mathbb Q : \frac{\varepsilon}{4} < q < \frac{\varepsilon}{2}$. Tenemos que $d(x, x_n) < \frac{\varepsilon}{4} < q$, lo que implica que $x \in B(x_n ; q)$. Además, si $y \in B(x_n; q)$,
$$d(x,y) \le d(x, x_n) + d(x_n, y) < q+q < \varepsilon \implies B(x_n; q) \subseteq B(x; \varepsilon) \implies x \in B(x_n; q) \subseteq A.$$
Luego $\mathcal B$ es base de abiertos, y $(X, \mathcal T_d)$ es 2AN.
Tags: dem top
<!--ID: 1728820185242-->
END

