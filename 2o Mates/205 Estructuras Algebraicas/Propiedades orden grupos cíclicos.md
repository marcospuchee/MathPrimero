### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]] y $x \in G$. Entonces $|\langle x \rangle | = o(x)$. Específicamente:
1. Si $o(x)$ es infinito, entonces, $\forall i \neq j$, $x^i \neq x^j$.
2. Si $o(x) = n$ finito, entonces $\langle x \rangle = \{1_G, x, x^2, \dots, x^{n-1} \}$.
```

^6f3ff9

```ad-proof
1. Por reducción al absurdo, supongamos que $\exists i,j \in \mathbb Z$ con $i<j$ tal que $x^i = x^j$. Entonces,
$$x_i \cdot x^{-j} = x^j \cdot x^{-j} = 1_G.$$
Por tanto, $i-j = 0 \implies i = j$. Contradicción.

2. $\supseteq$. Evidente.
$\subseteq$. Si $x^i \in \langle x \rangle$. Por el [[teorema de la división euclídea]], $\exists c,r \in \mathbb Z$ tales que $i = c \cdot n + r$, donde $0 \le r < n$. Entonces, 
$$x^i = (x^n)^c \cdot x^r = x^r \in \{1_G, x, \dots, x^{n-1}\}.$$

```

**Tema:** [[Teoría de grupos#8. Grupos cíclicos.]]

---
### Anki

START
Básico
Anverso: Qué propiedades cumple todo grupo cíclico respecto a su cardinal?
Reverso: Sea $G$ un [[Grupo]] y $x \in G$. Entonces $|\langle x \rangle | = o(x)$. Específicamente:
1. Si $o(x)$ es infinito, entonces, $\forall i \neq j$, $x^i \neq x^j$.
2. Si $o(x) = n$ finito, entonces $\langle x \rangle = \{1_G, x, x^2, \dots, x^{n-1} \}$.
<!--ID: 1727966477083-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]] y $x \in G$. Entonces $|\langle x \rangle | = o(x)$. Específicamente:
1. Si $o(x)$ es infinito, entonces, $\forall i \neq j$, $x^i \neq x^j$.
2. Si $o(x) = n$ finito, entonces $\langle x \rangle = \{1_G, x, x^2, \dots, x^{n-1} \}$.
Reverso: 
1. Por reducción al absurdo, supongamos que $\exists i,j \in \mathbb Z$ con $i<j$ tal que $x^i = x^j$. Entonces,
$$x_i \cdot x^{-j} = x^j \cdot x^{-j} = 1_G.$$
Por tanto, $i-j = 0 \implies i = j$. Contradicción.

2. $\supseteq$. Evidente.
$\subseteq$. Si $x^i \in \langle x \rangle$. Por el [[teorema de la división euclídea]], $\exists c,r \in \mathbb Z$ tales que $i = c \cdot n + r$, donde $0 \le r < n$. Entonces, 
$$x^i = (x^n)^c \cdot x^r = x^r \in \{1_G, x, \dots, x^{n-1}\}.$$
Tags: dem est
<!--ID: 1727966477143-->
END
