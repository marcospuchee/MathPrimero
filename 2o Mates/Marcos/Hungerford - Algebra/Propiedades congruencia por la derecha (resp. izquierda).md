
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-17, 16:55

```ad-theorem
Sea $H$ un [[subgrupo]] de $G$.
1. Congruencia por la derecha (resp. izquierda) módulo $H$ ([[congruente por la derecha]]) es una [[relación de equivalencia]] sobre $G$.
2. La [[clase de equivalencia]] de $a \in G$ bajo la congruencia derecha (resp. izquierda) es el conjunto $Ha = \{ha \, | \, h \in H \}$ (resp. $aH = \{ah \, | \, h \in H \}$).
3. $|Ha| = |H| = |aH|, \, \forall a \in G$.
```

```ad-proof
1. Como $(aa^{-1})(aa^{-1}) = a(a^{-1}a)a^{-1} = e \in H$, entonces sabemos que $e = aa^{-1} \in H$ (propiedad reflexiva). Si $a \equiv_r b \pmod H$, entonces $ab^{-1} \in H$. Pero como $H$ es grupo, entonces $(ab^{-1})^{-1} = ba^{-1} \in H$ (propiedad simétrica). Si $a \equiv_r b \pmod H$ y $b \equiv_r c \pmod H$, entonces $(ab^{-1}(bc^{-1})) = ac^{-1} \in H$ (propiedad transitiva).
2. Por definición, la clase de equivalencia de $a$ es
$$\{x \in G \, | \, x \equiv_r a \pmod H \} = \{x \in G \, | \, xa^{-1} \in H \} = \{x \in G \, | \, xa^{-1} = h \in H \} = \{x \in G \, | \, x = ha \in H\} = Ha.$$
3. Está claro que $f: H \to Ha$ con $h \to ha$ es una biyección.
```

**Tema:** [[Grupos#4. Clases laterales y conteo.]]
**Demostrado por:**
**Consecuencias:** [[Propiedades clases laterales]]

---
### Anki

START
Básico
Anverso: Cuáles son las propiedades de la congruencia por la derecha (resp. izquierda)?
Reverso: Sea $H$ un [[subgrupo]] de $G$.
1. Congruencia por la derecha (resp. izquierda) módulo $H$ ([[congruente por la derecha]]) es una [[relación de equivalencia]] sobre $G$.
2. La [[clase de equivalencia]] de $a \in G$ bajo la congruencia derecha (resp. izquierda) es el conjunto $Ha = \{ha \, | \, h \in H \}$ (resp. $aH = \{ah \, | \, h \in H \}$).
3. $|Ha| = |H| = |aH|, \, \forall a \in G$.
Tags: proposición/teorema hungerford
<!--ID: 1721893777201-->
END
