### Proposición

Sean $a,b,c \in \mathbb{Z}$ tal que $mcd(a,b) =1$, entonces:
1. $a|c$ y $b|c \implies ab |c$.
2. $a|bc \implies a|c$.

---
### Demostración

1. $\exists a', b' \in \mathbb{Z}$ tal que $aa' = c$ y $bb' = c$. Como $mcd(a,b) = 1, \exists x,y \in \mathbb{Z}$ tal que $ax + by = 1$ ([[Identidad de Bezout]]). $c = c1 = c(ax +by) = acx + bcy = abb'x + aa'by = ab(b'x +a'y) = c$. Por tanto, $ab | c$.
2. $c = c · 1 =  c(ax +by) = acx + bcy$. Como $a|bc, \exists k \in \mathbb{Z}$ tal que $ak =bc$. Con esto tenemos que $acx + bcy = acx + aky = a(cx + ky) = c$. Por tanto, $a | c$.

---
### Referencias

[[Divisibilidad]]

25-10-23. Matemática Básica.