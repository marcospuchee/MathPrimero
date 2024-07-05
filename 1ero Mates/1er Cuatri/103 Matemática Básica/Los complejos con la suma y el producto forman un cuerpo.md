### Enunciado Teorema

Definiendo la suma y el producto entre complejos como:
- Suma: $z + w = (a + c) + i(b+d)$.
- Producto: $zw = (a+ib)(c+id) = (ac-bd)+(ad+bc)i$.

$\mathbb C$ con la suma y el producto definidos arriba, es un [[Cuerpo]].

---
### Demostración

Es rutinario comprobar que $(\mathbb C, +)$ es [[Grupos]] abeliano y que $·$ es distributiva y asociativa, con lo que $(\mathbb C, +, ·)$ es [[Anillo]]. Además es también inmediato comprobar que $·$ es conmutativa ([[Anillo conmutativo]]) y que $1 = 1+0i$ es neutro para el producto ([[Anillo unitario]]). Falta justificar que $\forall z \in \mathbb C, z \not = 0$ tiene inverso. 

Sea $0 \not = z = a+ib$, definimos $w = \frac{a}{a^2 + b^2} + i\frac{-b}{a^2 + b^2}$. Notad que, puesto que $z \not = 0$, necesariamente $a \not = 0$ o $b \not = 0$, con lo que $a^2 + b^2 \not = 0$ y $w$ está bien definido. Ahora bien,
$$zw = (a+ib)(\frac{a}{a^2+b^2} + i\frac{-b}{a^2+b^2}) = \frac{a^2 + b^2}{a^2+b^2} + i(\frac{-ab+ba}{a^2 + b^2}) = 1 + 0i = 1$$
y por tanto, $zw = wz = 1$ y $w$ es el inverso de $z$.

---
### Referencias

[[Número complejo]]

---
### Anki

START
Básico
Anverso: Demuestra que definiendo la suma y el producto entre complejos como:
- Suma: $z + w = (a + c) + i(b+d)$.
- Producto: $zw = (a+ib)(c+id) = (ac-bd)+(ad+bc)i$.

$\mathbb C$ con la suma y el producto definidos arriba, es un [[Cuerpo]].
Reverso: Es rutinario comprobar que $(\mathbb C, +)$ es [[Grupos]] abeliano y que $·$ es distributiva y asociativa, con lo que $(\mathbb C, +, ·)$ es [[Anillo]]. Además es también inmediato comprobar que $·$ es conmutativa ([[Anillo conmutativo]]) y que $1 = 1+0i$ es neutro para el producto ([[Anillo unitario]]). Falta justificar que $\forall z \in \mathbb C, z \not = 0$ tiene inverso. 

Sea $0 \not = z = a+ib$, definimos $w = \frac{a}{a^2 + b^2} + i\frac{-b}{a^2 + b^2}$. Notad que, puesto que $z \not = 0$, necesariamente $a \not = 0$ o $b \not = 0$, con lo que $a^2 + b^2 \not = 0$ y $w$ está bien definido. Ahora bien,
$$zw = (a+ib)(\frac{a}{a^2+b^2} + i\frac{-b}{a^2+b^2}) = \frac{a^2 + b^2}{a^2+b^2} + i(\frac{-ab+ba}{a^2 + b^2}) = 1 + 0i = 1$$
y por tanto, $zw = wz = 1$ y $w$ es el inverso de $z$.
Tags: demostración
<!--ID: 1705822944811-->
END
