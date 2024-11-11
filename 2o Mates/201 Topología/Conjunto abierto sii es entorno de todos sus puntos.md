### Contenido Principal

```ad-proposition
Sea $(X, \mathcal T)$ [[espacio topológico]],
$$A \in \mathcal T \iff A \in \mathcal E(x) \quad \forall x \in A.$$
```

^f73a10

```ad-proof
$\rightarrow$. Sup. $A \in \mathcal T$. Entonces, $x \in A \subseteq A$. Por tanto, $A \in \mathcal E(x), \, \forall x \in A$.

$\leftarrow$. Supongamos que $A \in \mathcal E(x), \, \forall x \in A$. Entonces, $\exists B_x \in \mathcal T$ tal que $x \in B_x \subseteq A$. Luego,
$$A = \bigcup_{x \in A} \{x\} \subseteq \bigcup_{x \in A} B_x \subseteq A,$$
de donde concluimos que $A = \bigcup_{x \in A} B_x \in \mathcal T$ por ser unión de abiertos.
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos|Espacios topológicos]]

---
### Proposición (espacios métricos)

```ad-proposition
Un conjunto es [[conjunto abierto]] $\iff$ es [[entorno]] de todos sus puntos.
```

```ad-proof
$A$ es abierto $\iff$ $\forall x \in A$ $\exists \varepsilon > 0$ tal que si $B(x, \varepsilon) \subseteq A$ $\iff$ $A \in \mathcal E(x)$ $\forall x \in A$.
```

**Tema:** [[Espacios métricos]]

---
### Anki

START
Básico
Anverso: Demostración de que un conjunto es [[conjunto abierto]] $\iff$ es [[entorno]] de todos sus puntos.
Reverso: $A$ es abierto $\iff$ $\forall x \in A$ $\exists \varepsilon > 0$ tal que si $B(x, \varepsilon) \subseteq A$ $\iff$ $A \in \mathcal E(x)$ $\forall x \in A$.
Tags: dem top
<!--ID: 1727083427869-->
END

START
Respuesta anidada
$A$ es abierto $\iff$ $\forall x \in A$ $\exists \varepsilon > 0$ tal que si $B(x, \varepsilon) \subseteq A$ $\iff$ $A \in \mathcal E(x)$ $\forall x \in A$.
Tags:
<!--ID: 1727083427871-->
END

START
Básico
Anverso: Demostración de que sea $(X, \mathcal T)$ [[espacio topológico]],
$$A \in \mathcal T \iff A \in \mathcal E(x) \quad \forall x \in A.$$
Reverso:
$\rightarrow$. Sup. $A \in \mathcal T$. Entonces, $x \in A \subseteq A$. Por tanto, $A \in \mathcal E(x), \, \forall x \in A$.

$\leftarrow$. Supongamos que $A \in \mathcal E(x), \, \forall x \in A$. Entonces, $\exists B_x \in \mathcal T$ tal que $x \in B_x \subseteq A$. Luego,
$$A = \bigcup_{x \in A} \{x\} \subseteq \bigcup_{x \in A} B_x \subseteq A,$$
de donde concluimos que $A = \bigcup_{x \in A} B_x \in \mathcal T$ por ser unión de abiertos.
Tags: dem top
<!--ID: 1727339263770-->
END

START
Respuesta anidada
Sea $(X, \mathcal T)$ [[espacio topológico]], {{c1::$A \in \mathcal T$}} $\iff$ {{c2::$A \in \mathcal E(x) \quad \forall x \in A.$}}
Tags:
<!--ID: 1727339263779-->
END