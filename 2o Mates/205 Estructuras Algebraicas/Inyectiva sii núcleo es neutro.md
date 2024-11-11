### Contenido Principal

```ad-proposition
Sea $f: G \to H$ un [[homomorfismo]]. Entonces son equivalentes
1. $\textrm{Ker}(f) = \{1_G\}$.
2. $f$ es inyectiva.
```

^8a74ea

```ad-proof
$\rightarrow$. Es suficiente ver que $\textrm{Ker}(f) \subseteq \{1_G\}$. Sea $x \in \textrm{Ker}(f)$, en particular, $f(x) = 1_H = f(1_G)$, luego $x = 1_G \in \{1_G \}$.

$\leftarrow$. Sean $x,y \in G$ tales que $f(x) = f(y)$. Entonces,
$$f(xy^{-1}) = f(x) = f(y)^{-1} = 1_H.$$
Por tanto, $xy^{-1} \in \textrm{Ker}f = \{1_G\} \implies xy^{-1} = 1_G \implies x = y$.
```

**Tema:** [[Teoría de grupos#9. Homomorfismos.]]

---
### Anki

START
Básico
Anverso: Caracterización de homomorfismo inyectivo
Reverso: Sea $f: G \to H$ un [[Homomorfismo]]. Entonces son equivalentes
1. $\textrm{Ker}(f) = \{1_G\}$.
2. $f$ es inyectiva.
Tags: est
<!--ID: 1728549801307-->
END

START
Básico
Anverso: Demostración de que sea $f: G \to H$ un [[Homomorfismo]]. Entonces son equivalentes
1. $\textrm{Ker}(f) = \{1_G\}$.
2. $f$ es inyectiva.
Reverso: 
$\rightarrow$. Es suficiente ver que $\textrm{Ker}(f) \subseteq \{1_G\}$. Sea $x \in \textrm{Ker}(f)$, en particular, $f(x) = 1_H = f(1_G)$, luego $x = 1_G \in \{1_G \}$.

$\leftarrow$. Sean $x,y \in G$ tales que $f(x) = f(y)$. Entonces,
$$f(xy^{-1}) = f(x) = f(y)^{-1} = 1_H.$$
Por tanto, $xy^{-1} \in \textrm{Ker}f = \{1_G\} \implies xy^{-1} = 1_G \implies x = y$.
Tags: dem est
<!--ID: 1728549801356-->
END
