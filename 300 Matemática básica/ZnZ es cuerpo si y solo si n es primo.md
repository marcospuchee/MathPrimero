### Proposición

$\mathbb Z / n \mathbb Z$ es [[Cuerpo]] $\iff n$ es primo ([[Número primo]]). Sabemos que [[ZnZ es anillo conmutativo y unitario]].

---
### Demostración

Supongamos que $\mathbb Z / n \mathbb Z$ es cuerpo. Si $n$ no es primo, $\exists 1 < a,b < n$ tales que $n = ab$. Entonces $\overline a \overline b = \overline{ab} = \overline n = \overline 0$. Como $a,b < n$, tenemos que $\overline a, \overline b \not = \overline 0$ y, como $\mathbb Z / n \mathbb Z$ es cuerpo, $\exists \overline a ^{-1}$. Multiplicando $\overline a · \overline{a}^{-1}$, obtenemos $\overline b = \overline 0$, lo cual es contradicción.

Supongamos ahora que $n$ es primo. Tenemos que demostrar que si $\overline 0 \not = \overline a$, entonces $\overline a$ tiene inverso. Como $n$ es primo y $\overline a \not = \overline 0$, tenemos que $mcd(a,n) = 1$. Por la [[Identidad de Bezout]], $\exists x, y \in \mathbb Z$ tales que $ax + ny = 1$. Por tanto, $\overline a \overline x + \overline n \overline y= \overline 1 \implies \overline a \overline x = \overline 1$, dado que $\overline n = \overline 0$.

---
### Referencias

[[Relación binaria]]