
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-13, 10:57

```ad-theorem
Toda imagen homomórfica y todo [[subgrupo]] de un [[grupo cíclico]] $G$ es cíclico. En particular, si $H$ es un [[subgrupo]] no-trivial de $G = \langle a \rangle$ y $m$ es el menor entero positivo tal que $a^m \in H$, entonces $H = \langle a^m \rangle$.
```

```ad-proof
Sea $f: G \to H$ un [[homomorfismo]]. Veamos que $\textrm{Im}f$ es un grupo cíclico. Consideramos $x \in G$ cualquiera. $x = a^n$ con $n \in \mathbb Z$. Por tanto,
$$f(x) = f(a^n) = f \left (\prod_{i = 1}^n a \right ) = \prod_{i = 1}^n f(a) = f(a)^n.$$
Así, $\textrm{Im} f = \langle f(a) \rangle$.

Sea $H < G$. Tenemos que $H \neq \emptyset$ y $H \subset G$; por tanto, $x \in H \implies x \in G$ $\implies x = a^n$ para algún $n \in \mathbb N$. Por tanto, está claro que $H$ es cíclico. Veamos que $x$ es de la forma de la hipótesis: supongamos por reducción al absurdo que $x = a^n$ con $n = mq + r$, $q,r \in \mathbb Z$ y $0 < r < m$. Tenemos que:
$$a^n = a^{mq+r} = a^{mq} a^r \implies a^r = a^{n-mq}.$$
Por el [[teorema condición necesaria y suficiente de subgrupo]], está claro que $a^r \in H$, lo cual es una contradicción porque $m$ es el menor entero positivo tal que $a^m \in H$. Por tanto, $r = 0$ y $a^n = a^{mq}$ con $q \in \mathbb Z$, y así $H = \langle a^m \rangle$.
```


**Tema:** [[Grupos#3. Grupos cíclicos.]]
**Demostrado por:** [[Teorema condición necesaria y suficiente de subgrupo]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que da forma a las imágenes y a los subgrupos de un grupo cíclico?
Reverso: Toda imagen homomórfica y todo [[subgrupo]] de un [[grupo cíclico]] $G$ es cíclico. En particular, si $H$ es un [[subgrupo]] no-trivial de $G = \langle a \rangle$ y $m$ es el menor entero positivo tal que $a^m \in H$, entonces $H = \langle a^m \rangle$.
Tags: proposición/teorema hungerford
<!--ID: 1721211802888-->
END

