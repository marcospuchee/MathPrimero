### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]], $H \le G$ y $x,y \in G$. Entonces,
1. $xH = H \iff x \in H$.
2. $xH = yH \iff y^{-1}x \in H$.
3. $xH \cap yH \neq \emptyset \iff xH = yH$.
```

^af496a

```ad-proof
1. $\rightarrow$. Supongamos que $xH = H$. Veamos que $x \in H$. $x = x 1_G \in xH = H$.
$\leftarrow$. Supongamos que $x \in H$, veamos que $xH = H$.
$\subseteq$. Sea $xh \in xH$. Veamos que $xh \in H$: como $x,h \in H$, $xh \in H$.
$\supseteq$. Sea $h \in H$, veamos que $h \in xH$. $x \in H \implies x^{-1} \in H$. Luego $x^{-1}h \in H$. Por tanto, $h = x(x^{-1})h \in xH$.

2. $xH = yH \iff y^{-1}(xH) = y^{-1}(yH) = 1_GH = H$. Tenemos por $(i)$ que $(y^{-1}x)H = H \iff y^{-1}x \in H$.

3. $\leftarrow$. Evidente.
$\rightarrow$. Supongamos que $xH \cap yH \neq \emptyset$, veamos que $xH = yH$. Sea $z \in xH \cap yH$, entonces $\exists h_1 \in H, z = xh_1$, $\exists h_2 \in H, z = yh_2$. Como $xh_1 = yh_2$, entonces $y^{-1}x = h_2 h_1^{-1} \in H \iff xH = yH$ por $(ii)$.
```

**Tema:** [[Teoría de grupos#6. Teorema de Lagrange.]]

---
### Anki

START
Básico
Anverso: Propiedades de las coclases
Reverso: Sea $G$ un [[grupo]], $H \le G$ y $x,y \in G$. Entonces,
1. $xH = H \iff x \in H$.
2. $xH = yH \iff y^{-1}x \in H$.
3. $xH \cap yH \neq \emptyset \iff xH = yH$.
<!--ID: 1727339263712-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[grupo]], $H \le G$ y $x,y \in G$. Entonces, $xH = H \iff x \in H$.
Reverso: $\rightarrow$. Supongamos que $xH = H$. Veamos que $x \in H$. $x = x 1_G \in xH = H$.

$\leftarrow$. Supongamos que $x \in H$, veamos que $xH = H$.
$\subseteq$. Sea $xh \in xH$. Veamos que $xh \in H$: como $x,h \in H$, $xh \in H$.
$\supseteq$. Sea $h \in H$, veamos que $h \in xH$. $x \in H \implies x^{-1} \in H$. Luego $x^{-1}h \in H$. Por tanto, $h = x(x^{-1})h \in xH$.
Tags: dem est
<!--ID: 1727339263714-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[grupo]], $H \le G$ y $x,y \in G$. Entonces, $xH = yH \iff y^{-1}x \in H$.
Reverso: $xH = yH \iff y^{-1}(xH) = y^{-1}(yH) = 1_GH = H$. Tenemos por $(i)$ que $(y^{-1}x)H = H \iff y^{-1}x \in H$.
Tags: dem est
<!--ID: 1727339263719-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[grupo]], $H \le G$ y $x,y \in G$. Entonces, $xH \cap yH \neq \emptyset \iff xH = yH$.
Reverso: $\leftarrow$. Evidente.
$\rightarrow$. Supongamos que $xH \cap yH \neq \emptyset$, veamos que $xH = yH$. Sea $z \in xH \cap yH$, entonces $\exists h_1 \in H, z = xh_1$, $\exists h_2 \in H, z = yh_2$. Como $xh_1 = yh_2$, entonces $y^{-1}x = h_2 h_1^{-1} \in H \iff xH = yH$ por $(ii)$.
Tags: dem est
<!--ID: 1727339263721-->
END