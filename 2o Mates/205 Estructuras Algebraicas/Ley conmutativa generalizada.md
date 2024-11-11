
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-07, 18:24

```ad-cor
Si $G$ es un [[semigrupo abeliano]] y $a_1, \dots, a_n \in G$, entonces para cualquier permutación $i_1, \dots, i_n$ de $1,2, \dots, n$, $a_1 a_2 \dots a_n = a_{i_1} a_{i_2} \dots a_{i_n}$.
```

^3f6a43


```ad-proof
Vamos a proceder por el [[principio de inducción fuerte]].

**Caso base, $n = 2$.** Demostrado por definición de semigrupo abeliano.
**Paso inductivo**. Supongamos que $a_{i1} a_{i2} \dots a_{ik} = a_1 a_2 \dots a_k, \, \forall 2 \le k \le n$. Distinguimos tres casos:
1. $a_{in} = a_n$. Por la [[ley asociativa generalizada]], tenemos $(a_{i1} a_{i2} \dots a_{in-1})a_n$. Por hipótesis, $a_{i1} a_{i2} \dots a_{in-1} = a_1 a_2 \dots a_{n-1}$.
2. $a_{in} = a_1$. Igual que el primer caso.
3. $a_{in} = a_j$ con $j \in \{2, \dots, n-1\}$. Por hipótesis, $a_{i1} a_{i2} \dots a_{in-1} =$ $a_1 a_2 \dots a_{j-1} a_{j+1} \dots a_n$. Luego tenemos: $(a_1 a_2 \dots a_{j-1})(a_{j+1} \dots a_n)a_j$, que por la [[ley asociativa generalizada]],
$$(a_1 a_2 \dots a_{j-1})a_j(a_{j+1} \dots a_n) = a_1 a_2 \dots a_n.$$
```

**Tema:** [[Grupos#1. Semigrupos, monoides y grupos]]

---
### Anki
