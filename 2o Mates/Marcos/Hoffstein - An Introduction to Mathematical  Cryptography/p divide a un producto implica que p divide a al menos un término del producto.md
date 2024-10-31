### Contenido Principal

```ad-proposition
Sea $p$ un [[número primo]], $a_1, a_2, \dots, a_p \in \mathbb Z$.
$$p | a_1 a_2 \dots a_n \implies p | a_i \quad i \in \{1,2,\dots, n\}.$$
```

```ad-proof
Vamos a demostrar primero que sean $a,b \in \mathbb Z$, si $p |ab$, entonces $p | a \lor p | b$. Sea $g = \textrm{mcd}(a,p)$. Entonces, $g|p$, luego o $g = 1$, o $g =p$. Si $g = p$, entonces, $p|a$ (porque $g|a$). Si $g = 1$, por la [[identidad de Bezout]], podemos encontrar $u,v \in \mathbb Z$ tales que $au + pv = 1$. Multiplicando a ambos lados de la ecuación por $b$:
$$abu = pbv = b.$$
Como $p | abu$, y $p|pbv$, entonces $p|b$.

Para probar el resultado general, tomamos $a_1(a_2 \dots a_n)$ como $a = a_1$ y $b = a_2 \dots a_n$. Si $p | a_1$, ya estaría demostrado. Sino, $p | a_2 \dots a_n$, luego volvemos a aplicar el resultado a $a = a_2$ y $b = a_3 \dots a_n$. Así hasta encontrar algún $a_i$ tal que $p | a_i$.
```

**Tema:** [[An Introduction to Cryptography#3. Números primos, factorización única y cuerpos finitos.]]

---
### Anki
