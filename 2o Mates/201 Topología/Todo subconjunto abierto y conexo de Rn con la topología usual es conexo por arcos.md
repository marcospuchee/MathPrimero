### Contenido Principal

```ad-proposition
Todo subconjunto abierto y conexo de $(\mathbb R^n, \mathcal T_u)$ es conexo por arcos.
```

```ad-note
$$L_{xy} := \{tx + (1-t)y : t \in [0,1] \}.$$ Notemos que un subconjunto $H \subseteq \mathbb R^n$ es convexo si $\forall x,y \in H$, se cumple que $L_{xy} \subseteq H$. 
```

```ad-proof
Sea $U$ abierto de $\mathbb R^n$. Sea $x \in U$, queremos poder encontrar un arco entre $x$ y cualquier otro punto de $U$. Definimos $$A := \{y \in U : \exists \textrm{arco de } x \textrm{ a } y  \}, \quad x \in A \implies A \neq \emptyset.$$ Veamos que $A$ es abierto y cerrado:

**$A$ abierto.** Sea $y \in A$, entonces $\exists \sigma_{yx}$ arco de $y$ a $x$. Dado que $U \in \mathcal T_u$, entonces $\exists \varepsilon > 0$ tal que $B(y; \varepsilon) \subseteq U$. Dado $z \in B(y; \varepsilon)$, entonces $\sigma_{xy} \cdot L_{yz}$ es arco de $x$ a $z$, luego $z \in A$. Por tanto, $B(y; \varepsilon) \subseteq A$, y $A$ es abierto.

**$A$ cerrado.** Sea $y \notin A$, entonces $\nexists \sigma_{xy}$ arco de $x$ a $y$. Como $y \in U \in \mathcal T_u$, entonces $\exists \varepsilon > 0$ tal que $B(y ; \varepsilon) \subseteq U$. Si $z \in B(y; \varepsilon)$, entonces $\nexists \sigma_{xz}$ arco de $x$ a $z$ (porque si $\exists \sigma_{xz}$, entonces $\sigma_{xz} \cdot L_{zy}$ es una contradicción).

Por tanto, tenemos que $A \neq \emptyset$ abierto y cerrado a la vez, y $U$ es conexo. Por tanto, $A = U$, y $U$ es conexo por arcos.
```

**Tema:** [[Conexión#4. Conexión por arcos.]]

**Definiciones referenciadas:** [[Conjunto abierto]], [Conjunto conexo](Espacio topológico disconexo), [[Espacio topológico conexo por arcos]], [[Producto de arcos]]
**Resultados referenciados:** [$(X, \mathcal T)$ conexo por arcos $\iff \, \exists x_0 \in X : \forall y \in X \, \, \exists \sigma$ arco $: \sigma(0) = x_0 \land \sigma(1) = y$](Caracterización conexo por arcos (existencia de arcos desde un punto)), [$(X, \mathcal T)$ conexo $\iff$ $X, \emptyset$ son los únicos abiertos y cerrados a la vez](Caracterización de espacio topológico conexo (total y vacío unicos abiertos y cerrados a la vez))

---
### Anki

START
Respuesta anidada
Todo {{c1::subconjunto abierto y conexo}} de $(\mathbb R^n, \mathcal T_u)$ es {{c2::conexo por arcos}}.
Tags: top
<!--ID: 1733393497244-->
END

START
Básico
Anverso: Demostración de que todo subconjunto abierto y conexo de $(\mathbb R^n, \mathcal T_u)$ es conexo por arcos.
Reverso: Sea $U$ abierto de $\mathbb R^n$. Sea $x \in U$, queremos poder encontrar un arco entre $x$ y cualquier otro punto de $U$. Definimos $$A := \{y \in U : \exists \textrm{arco de } x \textrm{ a } y  \}, \quad x \in A \implies A \neq \emptyset.$$ Veamos que $A$ es abierto y cerrado:

**$A$ abierto.** Sea $y \in A$, entonces $\exists \sigma_{yx}$ arco de $y$ a $x$. Dado que $U \in \mathcal T_u$, entonces $\exists \varepsilon > 0$ tal que $B(y; \varepsilon) \subseteq U$. Dado $z \in B(y; \varepsilon)$, entonces $\sigma_{xy} \cdot L_{yz}$ es arco de $x$ a $z$, luego $z \in A$. Por tanto, $B(y; \varepsilon) \subseteq A$, y $A$ es abierto.

**$A$ cerrado.** Sea $y \notin A$, entonces $\nexists \sigma_{xy}$ arco de $x$ a $y$. Como $y \in U \in \mathcal T_u$, entonces $\exists \varepsilon > 0$ tal que $B(y ; \varepsilon) \subseteq U$. Si $z \in B(y; \varepsilon)$, entonces $\nexists \sigma_{xz}$ arco de $x$ a $z$ (porque si $\exists \sigma_{xz}$, entonces $\sigma_{xz} \cdot L_{zy}$ es una contradicción).

Por tanto, tenemos que $A \neq \emptyset$ abierto y cerrado a la vez, y $U$ es conexo. Por tanto, $A = U$, y $U$ es conexo por arcos.
Tags: dem top
<!--ID: 1733393497250-->
END

