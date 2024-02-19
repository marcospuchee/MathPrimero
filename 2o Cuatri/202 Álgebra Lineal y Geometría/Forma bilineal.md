### Contenido principal

**Fecha:** 2024-02-18, 17:34

Sean $V$ un $\mathbb K$-espacio vectorial finitamente generado, $F: V \times V \to \mathbb K$ con $(u,v) \to F(u,v)$ una aplicación ([[Aplicaciones]]), entonces

```ad-formal
title: Formal definition
Decimos que $F$ es una forma bilineal sobre $V$ cuando satisface que:
- $\forall \alpha, \beta \in \mathbb K, \forall u_1, u_2, v \in V$
$$F(\alpha u_1 + \beta u_2, v) = \alpha F(u_1, v) + \beta F(u_2, v)$$
- $\forall \alpha, \beta \in \mathbb K, \forall u, v_1, v_2 \in V$
$$F(u, \alpha v_1 + \beta v_2) = \alpha F(u, v_1) + \beta F(u, v_2)$$
```

```ad-note
title: Ejemplo
Sea $A \in M_n(\mathbb K)$, consideramos $F_A: \mathbb K^n \times \mathbb K^n \to \mathbb K$ con $((x_1, \dots, x_n), (y_1, \dots, y_n)) \to (x_1, \dots, x_n) A (y_1, \dots, y_n)^t$. Está visto en [[2o Cuatri/202 Álgebra Lineal y Geometría/Clases/2024-02-15|2024-02-15]] que es una forma bilineal
```


**Tema:** [[Formas bilineales]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Qué es una forma bilineal?
Reverso: Sean $V$ un $\mathbb K$-espacio vectorial finitamente generado, $F: V \times V \to \mathbb K$ con $(u,v) \to F(u,v)$ una aplicación ([[Aplicaciones]]), entonces decimos que $F$ es una forma bilineal sobre $V$ cuando satisface que:
- $\forall \alpha, \beta \in \mathbb K, \forall u_1, u_2, v \in V$
$$F(\alpha u_1 + \beta u_2, v) = \alpha F(u_1, v) + \beta F(u_2, v)$$
- $\forall \alpha, \beta \in \mathbb K, \forall u, v_1, v_2 \in V$
$$F(u, \alpha v_1 + \beta v_2) = \alpha F(u, v_1) + \beta F(u, v_2)$$
Tags: definición ÁlgebraI
<!--ID: 1708275569373-->
END
