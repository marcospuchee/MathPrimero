### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]], $k \in \mathbb Z$ y $x \in G$ con $o(x) = n$ ([[orden de un elemento de un grupo]]). Entonces son equivalentes
1. $x^k = 1_G$.
2. $n | k$.
```

^acceff

```ad-proof
$\rightarrow$.
Supongamos que $x^k = 1_G$. Queremos ver que $n|k$. Por el [[teorema de la división euclídea]], $k = mn + r$ donde $0 \le r < n$. Entonces, 
$$x^k = x^{m \cdot n + r} = x^{m \cdot n} \cdot x^r = (x^n)^m \cdot x^r = 1_G^m \cdot x^r = x^r = 1_G.$$
Luego $r = 0$, y $n|k$.

$\leftarrow$.
Supongamos que $n|k$. Queremos ver que $x^k = 1_G$. Como $n|k$, $\exists m \in \mathbb Z$ tal que $k = m \cdot n$. Entonces,
$$x^k = x^{m \cdot n} = (x^n)^m = 1_G^m = 1_G.$$
```

**Tema:** [[Teoría de grupos#4. Exponenciales y orden de un elemento.]]

---
### Anki

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]], $k \in \mathbb Z$ y $x \in G$ con $o(x) = n$ ([[Orden de un elemento de un grupo]]). Entonces son equivalentes
1. $x^k = 1_G$.
2. $n | k$.
Reverso: $\rightarrow$.
Supongamos que $x^k = 1_G$. Queremos ver que $n|k$. Por el [[teorema de la división euclídea]], $k = mn + r$ donde $0 \le r < n$. Entonces, 
$$x^k = x^{m \cdot n + r} = x^{m \cdot n} \cdot x^r = (x^n)^m \cdot x^r = 1_G^m \cdot x^r = x^r = 1_G.$$
Luego $r = 0$, y $n|k$.

$\leftarrow$.
Supongamos que $n|k$. Queremos ver que $x^k = 1_G$. Como $n|k$, $\exists m \in \mathbb Z$ tal que $k = m \cdot n$. Entonces,
$$x^k = x^{m \cdot n} = (x^n)^m = 1_G^m = 1_G.$$
Tags: dem est
<!--ID: 1727083427927-->
END

START
Respuesta anidada
Sea $G$ un [[Grupo]], $k \in \mathbb Z$ y $x \in G$ con $o(x) = n$ ([[Orden de un elemento de un grupo]]). Entonces son equivalentes
1. {{c1::$x^k = 1_G$.}}
2. {{c2::$n | k$.}}
Tags:
<!--ID: 1727083427929-->
END