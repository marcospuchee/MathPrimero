
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-20, 20:01

```ad-theorem
Sea $F$ una [[Forma bilineal simétrica]] sobre un $\mathbb R$-espacio vectorial $V$. Entonces, $F$ es un [[Producto escalar]] $\iff rg(F)$ ([[Rango de una forma bilineal]]) $= sig(F)$ ([[Signatura de una forma bilineal simétrica]]) $= n = \dim V$.
```


```ad-proof
Sea $B = \{v_1, \dots, v_n\}$ una base ortogonal ([[Conjunto F-ortogonal]]) de $V$.

$\rightarrow$.
Supongamos que $F$ es un producto escalar. Dado que $v_i \neq 0, \forall 1, \dots, n$ (por ser $B$ base, es linealmente independiente), tenemos que $F(v_i, v_i) > 0, \forall i = 1, \dots, n$. Deducimos que $sig(F) = rg(F) = n$.

$\leftarrow$.
Supongamos ahora que $sig(F) = rg(F) = n$. Entonces tenemos $F(v_i, v_i) > 0, \forall i = 1, \dots, n$. Sea $x \in V$ cualquiera, escribimos $x = \alpha_1 v_1 + \dots + \alpha_n v_n$ con $\alpha_1, \dots, \alpha_n \in \mathbb R$ únicos.
$$F(x,x) = F(\sum_{i = 1}^n \alpha_i v_i, \sum_{j = 1}^n \alpha_j v_j) = \sum_{i,j = 1}^n \alpha_i \alpha_j F(v_i, v_j) = \sum_{i = 1}^n (\alpha_i)^2 F(v_i, v_i) \ge 0.$$
Luego,
$$F(x,x) = 0 \iff \alpha_1, \dots, \alpha_n = 0 \iff [x]_B = 0 \iff x = 0,$$
deducimos que $F$ es producto escalar.
```


**Tema:** [[Espacios vectoriales euclídeos]]
**Demostrado por:**
**Consecuencias:** [[Criterio de Sylvester]]

---
### Anki

START
Respuesta anidada
Sea $F$ una [[Forma bilineal simétrica]] sobre un $\mathbb R$-espacio vectorial $V$. {{c1::Entonces, $F$ es un [[Producto escalar]]}} $\iff$ {{c2::$rg(F)$ ([[Rango de una forma bilineal]]) $= sig(F)$ ([[Signatura de una forma bilineal simétrica]]) $= n = \dim V$}}.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1712235233548-->
END

START
Básico
Anverso: Demostración de que sea $F$ una [[Forma bilineal simétrica]] sobre un $\mathbb R$-espacio vectorial $V$. Entonces, $F$ es un [[Producto escalar]] $\iff rg(F)$ ([[Rango de una forma bilineal]]) $= sig(F)$ ([[Signatura de una forma bilineal simétrica]]) $= n = \dim V$.
Reverso: Sea $B = \{v_1, \dots, v_n\}$ una base ortogonal ([[Conjunto F-ortogonal]]) de $V$.

$\rightarrow$.
Supongamos que $F$ es un producto escalar. Dado que $v_i \neq 0, \forall 1, \dots, n$ (por ser $B$ base, es linealmente independiente), tenemos que $F(v_i, v_i) > 0, \forall i = 1, \dots, n$. Deducimos que $sig(F) = rg(F) = n$.

$\leftarrow$.
Supongamos ahora que $sig(F) = rg(F) = n$. Entonces tenemos $F(v_i, v_i) > 0, \forall i = 1, \dots, n$. Sea $x \in V$ cualquiera, escribimos $x = \alpha_1 v_1 + \dots + \alpha_n v_n$ con $\alpha_1, \dots, \alpha_n \in \mathbb R$ únicos.
$$F(x,x) = F(\sum_{i = 1}^n \alpha_i v_i, \sum_{j = 1}^n \alpha_j v_j) = \sum_{i,j = 1}^n \alpha_i \alpha_j F(v_i, v_j) = \sum_{i = 1}^n (\alpha_i)^2 F(v_i, v_i) \ge 0.$$
Luego,
$$F(x,x) = 0 \iff \alpha_1, \dots, \alpha_n = 0 \iff [x]_B = 0 \iff x = 0,$$
deducimos que $F$ es producto escalar.
Tags: demostración Álgebra I
<!--ID: 1712235233560-->
END

