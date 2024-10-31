
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-19, 13:41

```ad-cor
Si $H$ es un [[subgrupo]] de $G$, entonces $|G| = [G: H]|H|$. En particular, si $G$ es finito, el orden $|a|$ ([[orden de un elemento de un grupo]]) de $a \in G$ divide a $|G|$.
```

```ad-proof
Si tomamos $K = \langle e \rangle = \{e\}$, cumple las hipótesis de [[teorema índice entre varios subgrupos]] ($K < H < G$). Por tanto, $[G: K] = [G:H][H:K]$. Sin embargo, por definición, cualquier [[clase lateral]] de $K$ sobre $G$ tiene la forma:
$$Ka = \{ka \, | \, k \in K \} = \{ka \, | \, k \in \{e\} \} = \{a\},$$
lo que implica que $|G| = [G: K]$. Por un razonamiento análogo, $[H: K] = |H|$. Y así, $|G| = [G:H]|H|$.

Si tomamos $H = \langle a \rangle$, hemos visto que $|G| = [G:H]|H| = [G:H]|a|$. Por tanto, está claro que $|a|$ divide a $[G:H]$.
```



**Tema:** [[Grupos#4. Clases laterales y conteo.]]
**Corolarios:** [[Caracterización de subgrupo]]

---
### Anki

START
Respuesta anidada
Si $H$ es un [[subgrupo]] de $G$, entonces {{c1::$|G|$}} $=$ {{c2::$[G: H]|H|$}}. En particular, si $G$ es finito, el orden $|a|$ ([[orden de un elemento de un grupo]]) de $a \in G$ divide a $|G|$.
Tags: proposición/teorema hungerford
<!--ID: 1721893777237-->
END
