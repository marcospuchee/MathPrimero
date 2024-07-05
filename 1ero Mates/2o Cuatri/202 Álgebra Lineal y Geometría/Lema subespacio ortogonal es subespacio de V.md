
---
mathLink: $U^\perp \le V$
---
### Contenido Principal

**Fecha:** 2024-02-23, 16:52

Sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ ([[Subespacio vectorial]]). Entonces,

```ad-lemma
$$U^\perp \le V$$
```

```ad-proof
Notemos que $\forall u \in U, F(0, u) = F(0v, u) = 0F(v,u)$. Por tanto, $0 \in U^\perp$, de modo que $U^\perp \neq \emptyset$.

Sean $x,y \in U^\perp$, y sean $\alpha, \beta \in \mathbb K$. Queremos ver que $\alpha x + \beta y \in U^\perp$. Sea $u \in U$ arbitrario. Entonces,
$$F(\alpha x + \beta y, u) = \alpha F(x,u) + \beta F(y,u) = 0,$$
luego $\alpha x + \beta y \in U^\perp$.
```

**Tema:** [[Formas bilineales]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Demostración de que sea $F$ una [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ ([[Subespacio vectorial]]). Entonces,
$$U^\perp \le V$$
Reverso: Notemos que $\forall u \in U, F(0, u) = F(0v, u) = 0F(v,u)$. Por tanto, $0 \in U^\perp$, de modo que $U^\perp \neq \emptyset$.

Sean $x,y \in U^\perp$, y sean $\alpha, \beta \in \mathbb K$. Queremos ver que $\alpha x + \beta y \in U^\perp$. Sea $u \in U$ arbitrario. Entonces,
$$F(\alpha x + \beta y, u) = \alpha F(x,u) + \beta F(y,u) = 0,$$
luego $\alpha x + \beta y \in U^\perp$.
Tags: demostración ÁlgebraI
<!--ID: 1708973800443-->
END