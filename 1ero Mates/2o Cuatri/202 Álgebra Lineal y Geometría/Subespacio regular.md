### Contenido principal

**Fecha:** 2024-03-01, 19:16

Sea $F$ una [[Forma bilineal simétrica]] sobre $V$.

```ad-formal
title: Formal definition
Un [[Subespacio vectorial]] $0 \neq U \le V$ es regular si $U \cap U^\perp$ ([[Subespacio ortogonal a un subespacio]]) $= 0$.
```

```ad-note
Sea $U \le V$, y supongamos que $F: V \times V \to \mathbb K$ es una forma bilineal simétrica. Tenemos que la restricción $G = F \restriction_{U \times U} : U \times U \to \mathbb K$ con $(u_1, u_2) \to G(u_1, u_2) = F(u_1, u_2)$ es una forma bilineal simétrica sobre $U$ (fácil de demostrar con la definición de [[Forma bilineal]]). Además, $\forall u_1, u_2 \in U$,
$$G(u_1, u_2) = F(u_1, u_2) = F(u_2, u_1) = G(u_2, u_1)$$
Notemos que si $0 \neq U \le V$, entonces $U$ es regular si $G = F \restriction_{U \times U}$ es regular.
Efectivamente, $G$ es regular $\iff U^{\perp G} = 0$ (por [[Corolario F es regular sii su subespacio ortogonal es el 0]]) $\iff U^{\perp F} \cap U = 0 \iff U$ es subespacio regular.
Luego nos damos cuenta de que por definición,
- $U^{\perp G} = \{x \in U: G(x,u) = 0, \forall u \in U\} = \{x \in U : F(x,u) = 0, \forall u \in U\}$.
- $U^{\perp F} = \{x \in V: F(x,u) = 0, \forall u \in U\}$.

Así, $U^{\perp G} = U^{\perp F} \cap U$.
```


**Tema:** [[Formas bilineales]]
**Referencias:**
**Proposiciones:**
**Teoremas:** [[Teorema existencia base F-ortogonal]]

---
### Anki

START
Básico
Anverso: Definición de subespacio regular
Reverso: Sea $F$ una [[Forma bilineal simétrica]] sobre $V$. Un [[Subespacio vectorial]] $0 \neq U \le V$ es regular si $U \cap U^\perp$ ([[Subespacio ortogonal a un subespacio]]) $= 0$.
Tags: definición ÁlgebraI
<!--ID: 1709571902583-->
END