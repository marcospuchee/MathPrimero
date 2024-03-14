
---
mathLink: $A \in M_n(\mathbb R)$ simétrica es congruente a $Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0)$
---
### Contenido Principal

**Fecha:** 2024-03-07, 19:06

```ad-theorem
Sea $A \in M_n(\mathbb R)$ simétrica. Entonces, $A$ es congruente ([[Matrices congruentes]]) con:
$$M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0),$$
donde $s = sig(A)$ ([[Signatura de una matriz simétrica]]), $r = rg(A)$ ([[Rango de una matriz]]).
```

```ad-proof
Sea $F_A : \mathbb R^n \times \mathbb R^n \to \mathbb R$ una [[Forma bilineal]] definida por $F_A (x,y) = x^t A y, \forall x,y \in \mathbb R^n$. Sabemos por [[Teorema existencia base F-ortogonal]], que $\exists B$ base ortogonal ([[Conjunto F-ortogonal]]) de $\mathbb R^n$. Escribimos $B = \{v_1, \dots, v_n\}$. Podemos suponer que:
- $F(v_i, v_i) > 0$ para $1 \le i \le s'$.
- $F(v_i, v_i) < 0$ para $1+s' \le i \le r'$.
- $F(v_i, v_i) = 0$ para $1 + r' \le i \le n$.
con $r', s' \in \{0, \dots, n\}.$ La [[Matriz coordenada de F]] con respecto a $B$ es $Diag(F(v_1, v_1), \dots, F(v_r, v_r), 0, \dots, 0)$. Consideramos:
$$B' = \{\frac{1}{\sqrt{F(v_1, v_1)}} v_1, \dots, \frac{1}{\sqrt{F(v_{s'}, v_{s'})}} v_{s'}, \frac{1}{\sqrt{|F(v_{s'+1}, v_{s'+1})|}} v_{s'+1}, \dots, \frac{1}{\sqrt{|F(v_{r'}, v_{r'})|}} v_{r'}, v_{r'+1}, \dots, v_n \}.$$
Sin embargo, tenemos:
- $\forall 1 \le i \le s', \quad F(u_i, u_i) = \displaystyle F(\frac{1}{\sqrt{F(v_i, v_i)}} v_i, \frac{1}{\sqrt{F(v_i, v_i)}} v_i) = 1.$
- $\forall s'+1 \le i \le r', \quad F(u_i, u_i) = \displaystyle F(\frac{1}{\sqrt{|F(v_i, v_i)|}} v_i, \frac{1}{\sqrt{|F(v_i, v_i)|}} v_i) = -1.$
- $\forall r'+1 \le i \le n, \quad F(u_i, u_i) = F(v_i, v_i) = 0.$
Por tanto, la matriz coordenada de $F$ respecto a $B'$ será la matriz $M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots 0)$, donde la signatura de $A$ será $s'$, y el rango de $A$ será $r'$.
```


**Tema:** [[Formas bilineales]]
**Demostrado por:** [[Teorema existencia base F-ortogonal]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: A qué es congruente una matriz $A \in M_n(\mathbb R)$ simétrica?
Reverso: Sea $A \in M_n(\mathbb R)$ simétrica. Entonces, $A$ es congruente ([[Matrices congruentes]]) con:
$$M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0),$$
donde $s = sig(A)$ ([[Signatura de una matriz simétrica]]), $r = rg(A)$ ([[Rango de una matriz]]).
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709836068061-->
END

START
Básico
Anverso: Demostración de que sea $A \in M_n(\mathbb R)$ simétrica. Entonces, $A$ es congruente ([[Matrices congruentes]]) con:
$$M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0),$$
donde $s = sig(A)$ ([[Signatura de una matriz simétrica]]), $r = rg(A)$ ([[Rango de una matriz]]).
Reverso: Sea $F_A : \mathbb R^n \times \mathbb R^n \to \mathbb R$ una [[Forma bilineal]] definida por $F_A (x,y) = x^t A y, \forall x,y \in \mathbb R^n$. Sabemos por [[Teorema existencia base F-ortogonal]], que $\exists B$ base ortogonal ([[Conjunto F-ortogonal]]) de $\mathbb R^n$. Escribimos $B = \{v_1, \dots, v_n\}$. Podemos suponer que:
- $F(v_i, v_i) > 0$ para $1 \le i \le s'$.
- $F(v_i, v_i) < 0$ para $1+s' \le i \le r'$.
- $F(v_i, v_i) = 0$ para $1 + r' \le i \le n$.
con $r', s' \in \{0, \dots, n\}.$ La [[Matriz coordenada de F]] con respecto a $B$ es $Diag(F(v_1, v_1), \dots, F(v_r, v_r), 0, \dots, 0)$. Consideramos:
$$B' = \{\frac{1}{\sqrt{F(v_1, v_1)}} v_1, \dots, \frac{1}{\sqrt{F(v_{s'}, v_{s'})}} v_{s'}, \frac{1}{\sqrt{|F(v_{s'+1}, v_{s'+1})|}} v_{s'+1}, \dots, \frac{1}{\sqrt{|F(v_{r'}, v_{r'})|}} v_{r'}, v_{r'+1}, \dots, v_n \}.$$
Sin embargo, tenemos:
- $\forall 1 \le i \le s', \quad F(u_i, u_i) = \displaystyle F(\frac{1}{\sqrt{F(v_i, v_i)}} v_i, \frac{1}{\sqrt{F(v_i, v_i)}} v_i) = 1.$
- $\forall s'+1 \le i \le r', \quad F(u_i, u_i) = \displaystyle F(\frac{1}{\sqrt{|F(v_i, v_i)|}} v_i, \frac{1}{\sqrt{|F(v_i, v_i)|}} v_i) = -1.$
- $\forall r'+1 \le i \le n, \quad F(u_i, u_i) = F(v_i, v_i) = 0.$
Por tanto, la matriz coordenada de $F$ respecto a $B'$ será la matriz $M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots 0)$, donde la signatura de $A$ será $s'$, y el rango de $A$ será $r'$.
Tags: demostración ÁlgebraI
<!--ID: 1709836068065-->
END