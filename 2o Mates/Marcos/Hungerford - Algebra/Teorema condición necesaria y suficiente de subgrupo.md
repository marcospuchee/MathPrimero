
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-10, 08:57

```ad-theorem
Sea $H$ un subconjunto no vacío del [[grupo]] $G$. Entonces, $H$ es un [[subgrupo]] de $G$ si y sólo si $ab^{-1} \in H$, $\forall a,b \in H$.
```

```ad-proof
$\rightarrow$. Si $b \in H$ y $H$ subgrupo, entonces por definición de elemento inverso, $b^{-1} \in H$. Dado que un subgrupo es cerrado ([[conjunto cerrado bajo una relación binaria]]), entonces $ab^{-1} \in H$, $\forall a,b \in H$.

$\leftarrow$. Tenemos que ver que $H$ sea cerrado y grupo.
- Grupo. La relación es asociativa porque $G$ es grupo ($H$ semigrupo). Como $H \neq \emptyset$, entonces $\exists a \in H$. Por hipótesis, $aa^{-1} = e \in H$ ($H$ monoide). $\forall b \in B$, tenemos que $b^{-1} = eb^{-1} \in H$ ($H$ grupo).
- Cerrado. Tenemos que $\forall a,b \in H, ab^{-1} \in H$. Pero $b^{-1} \in H$ ,luego $a(b^{-1})^{-1} = ab \in H$. Por tanto, $H$ es cerrado bajo $G$.

Por tanto, $H$ es subrupo de $G$.
```


**Tema:** [[Grupos#2. Homomorfismos y subgrupos.]]
**Demostrado por:**
**Consecuencias:** [[Intersección de subgrupos es subgrupo]], [[Teorema cardinal producto de subgrupos de un grupo]]

---
### Anki

START
Respuesta anidada
Sea $H$ un subconjunto no vacío del [[grupo]] $G$. Entonces, {{c1::$H$ es un [[subgrupo]] de $G$}} si y sólo si {{c2::$ab^{-1} \in H$, $\forall a,b \in H$.}}
Tags: proposición/teorema hungerford
<!--ID: 1721211802907-->
END
