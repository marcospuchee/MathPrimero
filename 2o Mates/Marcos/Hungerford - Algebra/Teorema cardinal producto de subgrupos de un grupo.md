
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-19, 13:57

```ad-theorem
Sea $H, K \subset G$ finitos, donde $G$ es un [[grupo]]. Entonces, $|HK|$  $=$ $|H||K|\textrm{/}|H \cap K|$; donde $HK = \{ab \, | \, a \in H, \, b \in K\}$
```

```ad-proof
Sea $C = H \cap K$. Veamos que $C < G$ ([[subgrupo]]). Sean $x,y \in C$. Basta ver que $xy^{-1} \in C$ ([[teorema condición necesaria y suficiente de subgrupo]]). Como $x,y \in H$ y $H$ subgrupo, entonces $xy^{-1} \in H$. Por un razonamiento análogo, $xy^{-1} \in K$. Por tanto, $xy^{-1} \in H \cap K$ y $C = H \cap K < K$.

Veamos ahora el índice de $C$ ([[índice de un subgrupo]]). Por el [[corolario cardinal de un grupo a partir del índice de un subgrupo (Lagrange)]], $|K| = [K:C]|C|$, lo que implica que $|K||C|^{-1} = [K:C]$. Es decir, $[K:C] = |K|/|H \cap K| = n$.

Por definición de índice, existen $n$ clases laterales ([[clase lateral]]) por la derecha distintas. Sin embargo, $K$ es la unión de todas las clases laterales por la derecha (resp. izquierda), luego $K = \bigcup_{i = 1}^n Ck_i$ con algunos $k_i \in K$.

Notemos que $HC = H$. En efecto, sea $x \in HC$, $x = hc$ con $h \in H$ y $c \in C = H \cap K < H$, luego $h,c \in H$. Está claro que $x = hc \in H$. Por tanto, $HC < H$. Sea $x \in H$, $x = xe$ con $x \in H$ y $e \in C$, luego $H < HC$. Así, HC = H$.

Por tanto,
$$HK = H \bigcup_{i = 1}^n Ck_i = \bigcup_{i = 1}^n HCk_i = \bigcup_{i = 1}^N Hk_i,$$
lo que nos lleva a que $|HK| = |H|n = |H||K| / |H \cap K|$.
```

**Tema:** [[Grupos#4. Clases laterales y conteo.]]
**Demostrado por:** [[Corolario cardinal de un grupo a partir del índice de un subgrupo (Lagrange)]], [[Caracterización de subgrupo]]
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sea $H, K \subset G$ finitos, donde $G$ es un [[grupo]]. Entonces, {{c1::$|HK|$}}  $=$ {{c2::$|H||K|\textrm{/}|H \cap K|$}}; donde $HK = \{ab \, | \, a \in H, \, b \in K\}$
Tags: proposición/teorema hungerford
<!--ID: 1721893777179-->
END
