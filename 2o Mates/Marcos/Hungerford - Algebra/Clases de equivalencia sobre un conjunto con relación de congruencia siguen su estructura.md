
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-06, 10:43

```ad-theorem
Sea $R \, (\sim)$ una [[relación de equivalencia]] sobre un [[monoide]] $G$ tal que $a_1 \sim a_2$ y $b_1 \sim b_2$ implica que $a_1 b_1 \sim a_2 b_2$ para todo $a_i, b_i \in G$. Entonces, el conjunto $G/R$ de todas las clases de equivalencia ([[clase de equivalencia]]) de $G$ sobre $R$ es un monoide sobre la [[relación binaria]] definida por $(\overline a)(\overline b) = \overline{ab}$. Si $G$ es un [[grupo]] ([[grupo abeliano]]), también lo será $G/R$.
```

```ad-note
Una relación de equivalencia sobre un monoide $G$ que cumple las hipótesis del teorema es una [[relación de congruencia]] sobre $G$. 
```

```ad-proof
Veamos que la relación binaria definida por $(\overline a)(\overline b) = \overline{ab}$ está bien definida. Por definición, $a_1 \sim a_2 \implies \overline a_1 = \overline a_2$, del mismo modo, $\overline b_1 = \overline b_2$. Así, 
$$(\overline a_1)(\overline b_1) = (\overline a_2)(\overline b_2) \implies \overline{a_1b_1} = \overline{a_2b_2} \implies a_1 b_1 \sim a_2 b_2,$$
luego está bien definida según nuestra hipótesis.
Por lo demás, sean $\overline a, \overline b, \overline c \in G/R$, se cumple la propiedad asociativa (gracias a que $G$ es monoide):
$$(\overline a \overline b) \overline c = (\overline{ab}) \overline c = \overline{(ab)c} = \overline{abc} = \overline{a(bc)} = \overline a (\overline{bc}) = \overline a (\overline b \overline c).$$
Sea $e \in G$ el elemento unidad en $G$, está claro que $\overline a \overline e = \overline{ae} = \overline a$. Por tanto, $G/R$ es un monoide.

Supongamos que $G$ es grupo, entonces $\exists a^{-1} \in G$ tal que $a \sim a^{-1} = e$. Entonces, $\overline{a} \overline{a^{-1}} = \overline{aa^{-1}} = \overline e$, luego $G/R$ es grupo.

Supongamos que $G$ es abeliano, entonces $\forall a,b \in G, \, a \sim b = b \sim a$. Por tanto, $\overline a \overline b = \overline{ab} = \overline{ba} = \overline b \overline a$.
```

**Tema:** [[Grupos#1. Semigrupos, monoides y grupos]]
**Demostrado por:** Definiciones básicas.
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Teorema que afirma que las clases de equivalencia de un conjunto con una relación de congruencia siguen su estructura.
Reverso: Sea $R \, (\sim)$ una [[relación de equivalencia]] sobre un [[monoide]] $G$ tal que $a_1 \sim a_2$ y $b_1 \sim b_2$ implica que $a_1 b_1 \sim a_2 b_2$ para todo $a_i, b_i \in G$. Entonces, el conjunto $G/R$ de todas las clases de equivalencia ([[clase de equivalencia]]) de $G$ sobre $R$ es un monoide sobre la [[relación binaria]] definida por $(\overline a)(\overline b) = \overline{ab}$. Si $G$ es un [[Grupo]] ([[grupo abeliano]]), también lo será $G/R$.
Tags: proposición/teorema hungerford
<!--ID: 1721211803063-->
END

