
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-18, 15:54

```ad-theorem
Si $K, H, G$ son [[grupo]]s con $K < H < G$, entonces $[G: K] = [G: H][H:K]$ ([[índice de un subgrupo]]). Si dos índices son finitos, también lo será el tercero.
```

```ad-proof
Por (i) [[propiedades clases laterales]], tenemos que $G = \bigcup_{i \in I} Ha_i$ con $a_i \in G$. Denotamos $|I| = [G: H]$. Además, por (ii) [[propiedades clases laterales]], tenemos que $Ha_i$ y $Ha_j$ son disjuntos para $i \neq j$.
Por un mismo razonamiento, $H = \bigcup_{j \in J} Kb_j$ con $b_j \in H$. Denotamos $|J| = [H: K]$. Y tenemos que $Kb_i$ y $Kb_j$ son disjuntos para $i \neq j$.

Así,
$$G = \bigcup_{i \in I} \left ( \bigcup_{j \in J} Kb_j \right ) a_i = \bigcup_{(i,j) \in I \times J} Kb_j a_i.$$

Tenemos entonces que $[G: K] = |I \times J|$. Luego, si vemos que dos $Kb_ja_i$ son disjuntos entre sí, tendremos que: 
$$[G: K] = |I \times J| = |I| |J| = [G: H][H:K].$$

Si $Kb_j a_i = Kb_r a_t$, entonces $b_ja_i = kb_r a_t$ con $k \in K$. Dado que $b_j, b_r, k \in H$, tenemos que $Ha_i = Hb_j a_i = Hkb_r a_t = Ha_t$; luego, $i = t$ y $b_j = kb_r$. Así, $Kb_j = Kkb_r = Kb_r$ y $j = r$. Por tanto, las clases laterales $Kb_j a_i$ son disjuntas.
```


**Tema:** [[Grupos#4. Clases laterales y conteo.]]
**Demostrado por:** [[Propiedades clases laterales]]
**Consecuencias:** [[Corolario cardinal de un grupo a partir del índice de un subgrupo (Lagrange)]], [[Proposición índice intersección menor o igual que producto índices de la intersección]]

---
### Anki

START
Respuesta anidada
Si $K, H, G$ son [[grupo]]s con $K < H < G$, entonces {{c1::$[G: K]$}} $=$ {{c2::$[G: H][H:K]$}} ([[índice de un subgrupo]]). Si dos índices son finitos, también lo será el tercero.
Tags: proposición/teorema hungerford
<!--ID: 1721893777147-->
END