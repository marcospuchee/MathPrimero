
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-10, 08:57

```ad-theorem
Sea $G$ un [[grupo]] y $H \subseteq G$. Entonces son equivalentes:
1. $H \le G$.
2. $H$ satisface:
	1. $1_G \in H$;
	2. $\forall x,y \in H$, $xy^{-1} \in H$.
```

^653795

```ad-proof
$\rightarrow$. Si $b \in H$ y $H$ subgrupo, entonces por definición de elemento inverso, $b^{-1} \in H$. Dado que un subgrupo es cerrado ([[conjunto cerrado bajo una relación binaria]]), entonces $ab^{-1} \in H$, $\forall a,b \in H$.

$\leftarrow$.
- $1_G \in H \implies H \neq \emptyset$.
- $(x \in H \land 1_G \in H) \implies 1_G x^{-1} = x^{-1} \in H$.
- $x,y \in H \implies x,y^{-1} \in H \implies x(y^{-1})^{-1} = y \in H$.

Por tanto, $H$ es subgrupo de $G$.
```


**Tema:** [[Teoría de grupos#5. Subgrupo.]]

---
### Anki

START
Básico
Anverso: Caracterización de subgrupo
Reverso: Sea $G$ un [[grupo]] y $H \subseteq G$. Entonces son equivalentes:
1. $H \le G$.
2. $H$ satisface:
	1. $1_G \in H$;
	2. $\forall x,y \in H$, $xy^{-1} \in H$.
<!--ID: 1727339263702-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[grupo]] y $H \subseteq G$. Entonces son equivalentes:
1. $H \le G$.
2. $H$ satisface:
	1. $1_G \in H$;
	2. $\forall x,y \in H$, $xy^{-1} \in H$.
Reverso: $\rightarrow$. Si $b \in H$ y $H$ subgrupo, entonces por definición de elemento inverso, $b^{-1} \in H$. Dado que un subgrupo es cerrado ([[conjunto cerrado bajo una relación binaria]]), entonces $ab^{-1} \in H$, $\forall a,b \in H$.

$\leftarrow$.
- $1_G \in H \implies H \neq \emptyset$.
- $(x \in H \land 1_G \in H) \implies 1_G x^{-1} = x^{-1} \in H$.
- $x,y \in H \implies x,y^{-1} \in H \implies x(y^{-1})^{-1} = y \in H$.

Por tanto, $H$ es subgrupo de $G$.
Tags: dem est
<!--ID: 1727339263704-->
END
