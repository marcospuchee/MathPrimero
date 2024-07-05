
---
mathLink: $F$ definida positiva $\iff A$ definida positiva
---
### Contenido Principal

**Fecha:** 2024-03-20, 19:51

```ad-lemma
Sea $F$ una [[Forma bilineal simétrica]] sobre $V$ ($\mathbb R$-espacio vectorial), y sea $B$ base de $V$. Supongamos que $A$ es la [[Matriz coordenada de F]] con respecto a la base $B$. Entonces $F$ es definida positiva ([[Forma bilineal simétrica definida positiva]]) $\iff A$ es definida positiva ([[Matriz simétrica definida positiva]]).
```

```ad-proof
Escribimos $B = \{v_1, \dots, v_n\}$. Tenemos:
$F$ definida positiva $\iff F(v, v) \ge 0, \forall v \in V$ y $F(v,v) = 0$ sii $v = 0$ $\iff ([v]_B)^t A [v]_B \ge 0, \forall v \in V$ y $([v]_B)^t A [v]_B = 0$ sii $v = 0$ $\iff x^t A x \ge 0, \forall x \in \mathbb R$ y $x^t A x = 0$ sii $x = 0$ ($x= (x_1, \dots, x_n) \in \mathbb R^n$ cualquiera, tenemos que $v = x_1 v_1 + \dots + x_n v_n$ satisface $[v]_B = x$).
```

**Tema:** [[Espacios vectoriales euclídeos]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $F$ una [[Forma bilineal simétrica]] sobre $V$ ($\mathbb R$-espacio vectorial), y sea $B$ base de $V$. Supongamos que $A$ es la [[Matriz coordenada de F]] con respecto a la base $B$. {{c1::Entonces $F$ es definida positiva ([[Forma bilineal simétrica definida positiva]])}} $\iff$ {{c2::$A$ es definida positiva ([[Matriz simétrica definida positiva]]).}}
Tags: proposición/teorema ÁlgebraI
<!--ID: 1712235233667-->
END

START
Básico
Anverso: Demostración de que sea $F$ una [[Forma bilineal simétrica]] sobre $V$ ($\mathbb R$-espacio vectorial), y sea $B$ base de $V$. Supongamos que $A$ es la [[Matriz coordenada de F]] con respecto a la base $B$. Entonces $F$ es definida positiva ([[Forma bilineal simétrica definida positiva]]) $\iff A$ es definida positiva ([[Matriz simétrica definida positiva]]).
Reverso: Escribimos $B = \{v_1, \dots, v_n\}$. Tenemos:
$F$ definida positiva $\iff F(v, v) \ge 0, \forall v \in V$ y $F(v,v) = 0$ sii $v = 0$ $\iff ([v]_B)^t A [v]_B \ge 0, \forall v \in V$ y $([v]_B)^t A [v]_B = 0$ sii $v = 0$ $\iff x^t A x \ge 0, \forall x \in \mathbb R$ y $x^t A x = 0$ sii $x = 0$ ($x= (x_1, \dots, x_n) \in \mathbb R^n$ cualquiera, tenemos que $v = x_1 v_1 + \dots + x_n v_n$ satisface $[v]_B = x$).
Tags: demostración ÁlgebraI
<!--ID: 1712235233674-->
END
