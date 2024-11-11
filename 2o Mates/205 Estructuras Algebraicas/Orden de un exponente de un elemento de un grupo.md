### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]], $k \in \mathbb Z^+$ y $x \in G$ con $o(x) = n$ ([[orden de un elemento de un grupo]]). Entonces,
$$o(x^k) = \frac{n}{\textrm{mcd}(n,k)}.$$
```

^baeb14

```ad-proof
Vamos a denotar primero $o(x) = n$, $o(x^k) = m$, $\textrm{mcd}(n,k) = d$. Queremos ver que $m = \frac{n}{d}$.

Veamos primero que $m | \frac{n}{d}$. Tenemos:
$$(x^k)^{n/d} = x^{kn/d} = (x^n)^{k/d} = 1_G,$$
por la proposición [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], $m | \frac{n}{d}$.

Veamos ahora que $\frac{n}{d} | m$. Sabemos (por el [[teorema de Bezout]]) que $\exists a,b \in \mathbb Z$ tal que $d = an+bk$. Por tanto, $x^{d \cdot m} = x^{man + mbk}$. Sin emabrgo,
$$x^{man + mbk} = (x^n)^{ma} \cdot ((x^k)^m)^b = 1_G \cdot 1_G = 1_G.$$
Por [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], $n | dm$; es decir, $\frac{n}{d} | m$.
```


**Tema:** [[Teoría de grupos#4. Exponenciales y orden de un elemento.]]

---
### Anki

START
Básico
Anverso: Sea $G$ un [[Grupo]], $k \in \mathbb Z^+$ y $x \in G$ con $o(x) = n$. Cuánto es $o(x^k)$?
Reverso:
$$o(x^k) = \frac{n}{\textrm{mcd}(n,k)}.$$
Tags:
<!--ID: 1727083427918-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]], $k \in \mathbb Z^+$ y $x \in G$ con $o(x) = n$ ([[Orden de un elemento de un grupo]]). Entonces,
$$o(x^k) = \frac{n}{\textrm{mcd}(n,k)}.$$
Reverso: Vamos a denotar primero $o(x) = n$, $o(x^k) = m$, $\textrm{mcd}(n,k) = d$. Queremos ver que $m = \frac{n}{d}$.

Veamos primero que $m | \frac{n}{d}$. Tenemos:
$$(x^k)^{n/d} = x^{kn/d} = (x^n)^{k/d} = 1_G,$$
por la proposición [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], $m | \frac{n}{d}$.

Veamos ahora que $\frac{n}{d} | m$. Sabemos (por el [[teorema de Bezout]]) que $\exists a,b \in \mathbb Z$ tal que $d = an+bk$. Por tanto, $x^{d \cdot m} = x^{man + mbk}$. Sin emabrgo,
$$x^{man + mbk} = (x^n)^{ma} \cdot ((x^k)^m)^b = 1_G \cdot 1_G = 1_G.$$
Por [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], $n | dm$; es decir, $\frac{n}{d} | m$.
Tags: dem est
<!--ID: 1727083427921-->
END

