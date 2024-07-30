
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-17, 17:33

```ad-proposition
Sea $H$ un [[subgrupo]] de $G$.
1. $G$ es la unión de las clases laterales por la derecha ([[clase lateral]]) (resp. izquierda) de $H$ en $G$.
2. Dos clases laterales por la derecha (resp. por la izquierda) de $H$ en $G$ son, o bien disjuntas, o bien iguales.
3. $\forall a, b \in G, \, Ha = Hb \iff ab^{-1} H$ y $aH = bH \iff a^{-1}b \in H$.
4. Si $\mathfrak R$ es el conjunto de las distintas clases laterales por la derecha de $H$ en $G$ y $\mathfrak L$ es el conjunto de las distintas clases laterales por la izquierda de $H$ en $G$, entonces $| \mathfrak R | = | \mathfrak L |$.
```

```ad-proof
1. Por definición, $H_a < G$. Por tanto, $\cup_{a \in G} H_a < G$. Sea $a \in G$, $a \equiv_r a \pmod H \implies a \in Ha$, pero $Ha < \cup_{a \in G} Ha$, lo que implica que $a \in \cup_{a \in G}Ha$ y así $G < \cup_{a \in G} Ha$. Luego $\cup_{a \in G} Ha = G$.
2. Sean $a,b \in G$, hay dos opciones: $a \equiv_r b \pmod H \implies Ha = Hb$ (por (1) de [[propiedades congruencia por la derecha (resp. izquierda)]]). Si $a \not \equiv_r b \pmod H$, podemos suponer por reducción al absurdo que $\exists h \in Ha \cap Hb$. Sin embargo, esto implica que $h \equiv_r a \pmod H$ (por ser relación de equivalencia, $a \equiv_r h \pmod H$) y $h \equiv_r b \pmod H$. Por la propiedad transitiva, $a \equiv_r b \pmod H$, lo cual es una contradicción.
3. Tenemos que $ab^{-1} \in H \iff a \equiv_r b \pmod H \iff Ha = Hb$.
4. Sea $f: \mathfrak R \to \mathfrak L$ con $Ha \to a^{-1}H$. $f$ es [[isomorfismo]].
```



**Tema:** [[Grupos#4. Clases laterales y conteo.]]
**Corolarios:**

---
### Anki
