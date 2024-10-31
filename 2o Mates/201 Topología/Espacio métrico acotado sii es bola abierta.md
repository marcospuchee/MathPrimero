### Contenido Principal

```ad-proposition
Sean $(X,d)$ [[espacio métrico]], $x_0 \in X$. Entonces, $(X,d)$ es [[espacio métrico acotado]] $\iff$ $\exists k \in \mathbb R$ tal que $B(x_0; k) = X$.
```

```ad-proof
$\rightarrow$. Supongamos que $(X,d)$ es acotado. Entonces, $\exists k \in \mathbb R$ tal que $d(x,y) \le k$ $\forall x,y \in X$. Sea $x_0 \in X$, $\varepsilon > 0$, $B(x_0; k+\varepsilon) = X$.

$\leftarrow$. Supongamos que $B(x_0; k) = X$. Sean $x,y \in X$. Tenemos que:
$$d(x,y) \le d(x,x_0) + d(x_0, y) < 2k.$$
Así, $(X,d)$ es acotado.
```

**Tema:** [[Espacios métricos]]

---
### Anki

START
Respuesta anidada
Sean $(X,d)$ [[espacio métrico]], $x_0 \in X$. Entonces, {{c1::$(X,d)$ es [[espacio métrico acotado]]}} $\iff$ {{c2::$\exists k \in \mathbb R$ tal que $B(x_0; k) = X$.}}
Tags:
<!--ID: 1727083427850-->
END

START
Básico
Anverso: Demostración de que sean $(X,d)$ [[espacio métrico]], $x_0 \in X$. Entonces, $(X,d)$ es [[espacio métrico acotado]] $\iff$ $\exists k \in \mathbb R$ tal que $B(x_0; k) = X$.
Reverso: $\rightarrow$. Supongamos que $(X,d)$ es acotado. Entonces, $\exists k \in \mathbb R$ tal que $d(x,y) \le k$ $\forall x,y \in X$. Sea $x_0 \in X$, $\varepsilon > 0$, $B(x_0; k+\varepsilon) = X$.

$\leftarrow$. Supongamos que $B(x_0; k) = X$. Sean $x,y \in X$. Tenemos que:
$$d(x,y) \le d(x,x_0) + d(x_0, y) < 2k.$$
Así, $(X,d)$ es acotado.
Tags: top dem
<!--ID: 1727083427852-->
END
