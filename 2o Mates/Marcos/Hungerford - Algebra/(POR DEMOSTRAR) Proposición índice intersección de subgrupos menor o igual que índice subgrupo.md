
---
mathLink: $[H: H \cap K] \le [G:K]$
---
### Contenido Principal

**Fecha:** 2024-07-27, 09:27

```ad-proposition
Si $H$ y $K$ son [[subgrupo]]s de un [[grupo]] $G$. Entonces, $[H: H \cap K] \le [G:K]$. Si $[G:K]$ es finito, entonces $[H: H \cap K] = [G:K]$ si y sólo si $G = KH$.
```

```ad-proof
Sea $A = \{(H \cap K)h \, | \, h \in H \}, B = \{Ka \, | \, a \in G\}$. Veamos que $f: A \to B$ con $(H\cap K)h \to Kh$ está bien definida. Sean $(H \cap K)x = (H \cap K)y$, entonces $x \equiv_r y \pmod{H \cap K}$, luego $xy^{-1} \in H \cap K < K$. Por tanto, $xy^{-1} \in K$ y $x \equiv_r y \pmod K$. Es decir, $Kx = Ky$.

Veamos que $f$ inyectiva: sean $(H \cap K)x, (H\cap K)y \in A$ tales que $f((H \cap K)x) = f((H \cap K)y)$. Es decir, $Kx = Ky$. Luego, $x \equiv_r y \pmod K$. Falta ver que $x \equiv_r y \pmod H$. Sin embargo, por [[teorema condición necesaria y suficiente de subgrupo]], $xy^{-1} \in H$, luego $x \equiv_r y \pmod H$. Así, $x \equiv_r y \pmod{H \cap K}$, luego $(H \cap K)x = (H \cap K)y$. Luego $f$ es inyectiva. Por tanto,
$[H: H \cap K] = |A| \le |B| = [G: K]$.

Falta ver el resto.
```

**Tema:** [[Grupos#4. Clases laterales y conteo.]]
**Corolarios:** [[Proposición índice intersección menor o igual que producto índices de la intersección]]

---
### Anki
