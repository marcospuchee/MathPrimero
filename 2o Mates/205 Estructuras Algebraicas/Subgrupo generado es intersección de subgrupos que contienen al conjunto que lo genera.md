### Contenido Principal

```ad-cor
Sea $G$ un [[grupo]] y $X \subseteq G$. Entonces
$$\langle X \rangle = \bigcap_{X \subseteq H \le G} H.$$

```

^bd69c3

```ad-proof
$(\le)$. Notamos que: por [[intersección de subgrupos es subgrupo]], $\bigcap_{X \subseteq H \subseteq G} H \le G$, $X \subseteq \bigcap_{X \subseteq H \le G} H$ está claro. Por [[subgrupo generado es mínimo subgrupo que contiene al conjunto que lo genera]], entonces $\langle X \rangle \le \bigcap_{X \subseteq H \le G} H$.

$(\ge)$. Por [[subgrupo generado es subgrupo]], entonces $X \subseteq \langle X \rangle \subseteq G$, lo que implica que $\bigcap_{X \subseteq H \le G} H \le \langle X \rangle$.
```

**Tema:** [[Teoría de grupos#7. Subgrupo generado.]]

---
### Anki

START
Básico
Anverso: Proposición subgrupo generado es intersección de los subgrupos que contienen al conjunto que lo genera
Reverso: Sea $G$ un [[Grupo]] y $X \subseteq G$. Entonces
$$\langle X \rangle = \bigcap_{X \subseteq H \le G} H.$$
<!--ID: 1727966476972-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]] y $X \subseteq G$. Entonces
$$\langle X \rangle = \bigcap_{X \subseteq H \le G} H.$$
Reverso: $(\le)$. Notamos que: por [[intersección de subgrupos es subgrupo]], $\bigcap_{X \subseteq H \subseteq G} H \le G$, $X \subseteq \bigcap_{X \subseteq H \le G} H$ está claro. Por [[subgrupo generado es mínimo subgrupo que contiene al conjunto que lo genera]], entonces $\langle X \rangle \le \bigcap_{X \subseteq H \le G} H$.

$(\ge)$. Por [[subgrupo generado es subgrupo]], entonces $X \subseteq \langle X \rangle \subseteq G$, lo que implica que $\bigcap_{X \subseteq H \le G} H \le \langle X \rangle$.
Tags: dem est
<!--ID: 1727966477031-->
END