
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-09, 19:34

```ad-theorem
Sea $f: G \to H$ un [[homomorfismo]] de [[grupo]]s. Entonces, $f$ es un [[monomorfismo]] si y sólo si $\ker f = \{e\}$.
```

```ad-proof
$\rightarrow$.
Supongamos por reducción al absurdo que $x \in \ker f$ y $x \neq e$. Tenemos entonces que $f(x) = f(e) = e$, luego como $f$ es un monomorfismo, esto es una contradicción. Así, $\ker f = \{e\}$.

$\leftarrow$.
Si $f(a) = f(b)$, entonces $f(a)(f(b))^{-1} = e_H = f(a)f(b^{-1}) = f(ab^{-1})$. Por tanto, $ab^{-1} \in \ker f$, y por hipótesis, $ab^{-1} = e$. Luego $a = b$.
```


**Tema:** [[Grupos#2. Homomorfismos y subgrupos.]]
**Referencias:** [[Proposiciones aplicación lineal espacios vectoriales]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sea $f: G \to H$ un [[homomorfismo]] de [[grupo]]s. Entonces, {{c1::$f$ es un [[monomorfismo]]}} si y sólo si {{c2::$\ker f = \{e\}$.}}
Tags: proposición/teorema hungerford
<!--ID: 1721211802880-->
END
