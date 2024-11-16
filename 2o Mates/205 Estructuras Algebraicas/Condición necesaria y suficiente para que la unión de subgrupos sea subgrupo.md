### Contenido Principal


```ad-theorem
Sea $G$ uh [[grupo]] y $H,K \le G$ ([[subgrupo]]). Entonces son equivalentes:
1. $H \cup K \le G$.
2. $K \subseteq H \lor H \subseteq K$.
```

^00809d

```ad-proof
$\leftarrow$. $K \subseteq H \implies H \cup K = H \le G$, $\quad H \subseteq K \implies H \cup K = K \le G$.

$\rightarrow$. Supongamos que $H \cup K \le G$. Veamos que $H \subseteq K$ o $K \subseteq H$.
Supongamos que $H \not \subseteq K$, veamos que $K \subseteq H$. Sea $k \in K$. Veamos que $k \in H$. Como $H \not \subseteq K$, $\exists h \in H$ tal que $h \notin K$. Como $h,k \in H \cup K$, $h \cdot k \in H \cup K$. Dos casos:
- $hk \in k$. $k \in K \implies k^{-1} \in K \implies (hk)k^{-1} \in K$. Contradicción.
- $hk \in H$. $k = h^{-1}(hk) \in h^{-1}H \subseteq HH = H$.
```

**Tema:** [[Teoría de grupos#5. Subgrupo.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Condición necesaria y suficiente para que la unión de subgrupos sea subgrupo
Reverso: Sea $G$ uh [[Grupo]] y $H,K \le G$ ([[Subgrupo]]). Entonces son equivalentes:
1. $H \cup K \le G$.
2. $K \subseteq H \lor H \subseteq K$.
<!--ID: 1727339263735-->
END

START
Básico
Anverso: Demostración de que sea $G$ uh [[Grupo]] y $H,K \le G$ ([[Subgrupo]]). Entonces son equivalentes:
1. $H \cup K \le G$.
2. $K \subseteq H \lor H \subseteq K$.
Reverso: $\leftarrow$. $K \subseteq H \implies H \cup K = H \le G$, $\quad H \subseteq K \implies H \cup K = K \le G$.

$\rightarrow$. Supongamos que $H \cup K \le G$. Veamos que $H \subseteq K$ o $K \subseteq H$.
Supongamos que $H \not \subseteq K$, veamos que $K \subseteq H$. Sea $k \in K$. Veamos que $k \in H$. Como $H \not \subseteq K$, $\exists h \in H$ tal que $h \notin K$. Como $h,k \in H \cup K$, $h \cdot k \in H \cup K$. Dos casos:
- $hk \in k$. $k \in K \implies k^{-1} \in K \implies (hk)k^{-1} \in K$. Contradicción.
- $hk \in H$. $k = h^{-1}(hk) \in h^{-1}H \subseteq HH = H$.
Tags: dem est
<!--ID: 1727339263738-->
END
