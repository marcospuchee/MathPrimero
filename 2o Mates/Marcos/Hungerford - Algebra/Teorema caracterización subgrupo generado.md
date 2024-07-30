
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-10, 12:08

```ad-theorem
Sean $G$ un [[grupo]], $\emptyset \neq X \subset G$. Entonces, el [[subgrupo generado]] por $X$, $\langle X \rangle$, consiste en todos los productos finitos $a_1^{n_1} a_2^{n_2} \dots a_t^{n_t}$ (con $a_i \in X$; $n_i \in \mathbb Z$).

En particular, $\forall a \in G, \, \langle a \rangle = \{a^n \, | \, n \in \mathbb Z \}$.
```


```ad-proof
Veamos primero que $H = \{a_1^{n_1} a_2^{n_2} \dots a_t^{n_t} \, | \, a_i \in X, \, n_i \in \mathbb Z \}$ es [[subgrupo]] de $G$. Sean $a = a_1^{n_1} a_2^{n_2} \dots a_t^{n_t}$, $b = b_1^{m_1} b_2^{m_2} \dots b_s^{m_s}$ con $a_i, b_j \in X$. Está claro entonces que $a,b \in H$. Sin embargo, $b^{-1} = b_1^{-m_1}b_2^{-m_2} \dots b_m^{-m_s}$. Por tanto,
$$ab^{-1} = a_1^{n_1} a_2^{n_2} \dots a_t^{n_t} b_1^{-m_1} b_2^{-m_2} \dots b_s^{-m_s} = c_1^{t_1} c_2^{t_2} \dots c_k^{t_k},$$
con $c_i \in X$ y $t_j \in \mathbb Z$. Por tanto, $ab^{-1} \in H$. Por [[teorema condición necesaria y suficiente de subgrupo]], $H < G$.

Veamos que $X \subset H$. Sea $a \in X$ cualquiera. Está claro que $a = a^1 \in H$, luego $X \subset H$.

Veamos ahora que $H = \langle X \rangle$.
- $H < \langle X \rangle$. Sea $a = a_1^{n_1} a_2^{n_2} \dots a_t^{n_t}$, con $a_i \in X$. Sin embargo, $X \subset \bigcap_{i \in I} H_i$, por tanto $a_i \in \bigcap_{i \in I} H_i$. Como [[intersección de subgrupos es subgrupo]], se deriva que $a_1^{n_1} \dots a_t^{n_t} \in \bigcap_{i \in I} H_i$ (se puede comprobar por inducción).
- $\langle X \rangle < H$. Está claro porque $H$ es un subgrupo de $G$ que contiene a $X$, luego $H = H_j$ para algún $j \in I$, luego $\bigcap_{i \in I} H_i \subset H$.
```


**Tema:** [[Grupos#2. Homomorfismos y subgrupos.]]
**Demostrado por:** [[Teorema condición necesaria y suficiente de subgrupo]], [[Intersección de subgrupos es subgrupo]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que da forma a todo subgrupo generado?
Reverso: Sean $G$ un [[grupo]], $\emptyset \neq X \subset G$. Entonces, el [[subgrupo generado]] por $X$, $\langle X \rangle$, consiste en todos los productos finitos $a_1^{n_1} a_2^{n_2} \dots a_t^{n_t}$ (con $a_i \in X$; $n_i \in \mathbb Z$).

En particular, $\forall a \in G, \, \langle a \rangle = \{a^n \, | \, n \in \mathbb Z \}$.
Tags: proposición/teorema hungerford
<!--ID: 1721211802900-->
END
