
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-01, 19:58

Sea $F$ una [[Forma bilineal]] sobre $V$, donde $V$ es un $\mathbb K$-espacio vectorial de dimensión finita con $car \mathbb K \neq 2$. Entonces,

```ad-theorem
$\exists B$ base de $V$ $F$-ortogonal ([[Conjunto F-ortogonal]]).
```


```ad-proof
Podemos suponer que $V \neq 0$. Procedemos por inducción sobre $n = \dim V$.

$n=1$. 
En este caso toda base de $V$ es ortogonal.

$n-1 \implies n$.
Supongamos el resultado cierto para espacios vectoriales de dimensión $n-1$, y probémoslo para espacios vectoriales de dimensión $n$. Si la forma $F$ es nula, es decir, $F(x,y) = 0, \forall x,y \in V$, tenemos que cualquier base es ortogonal. Por tanto, suponemos que $F \neq 0$.
Veamos que $\exists v \in V: F(v,v) \neq 0$. Sabemos que $\exists x,y \in V$ tales que $F(x,y) \neq 0$ (porque $F$ es no nula). Si $F(x,x) \neq 0$ o $F(y,y) \neq 0$, tomamos $v = x$ o $v = y$. En caso contrario, 
$$F(x+y, x+y) = F(x,x) + F(x,y) + F(y,x) + F(y,y) = 2F(x,y) \neq 0$$ 
porque $car \mathbb K \neq 2$, y tomamos $v = x+y$. Por tanto, $U = \langle v \rangle \le V$ es regular ([[Subespacio regular]]). Efectivamente $\{v\}$ es base de $U$, y la matriz coordenada de $F \restriction_{U \times U}$ con respecto a $\{v \}$ es $0 \neq (F(v,v)) \in M_n(\mathbb K)$, luego $(F(v,v))$ es regular ([[Matriz invertible]]). Por [[Suma directa de subespacio con su ortogonal]], tenemos $\dim U^\perp = n-1$. Por hipótesis de inducción, $\exists B' = \{v_2, \dots, v_n\}$ base de $U^\perp$ tal que $B'$ es ortogonal respecto a $G = F \restriction_{U^\perp \times U^\perp}$. Esto implica que $B = \{v, v_2, \dots, v_n\}$ es base $F$-ortogonal de $V$.
```


**Tema:** [[Formas bilineales]]
**Demostrado por:** [[Suma directa de subespacio con su ortogonal]]
**Consecuencias:** [[Toda matriz simétrica es congruente a una matriz diagonal]], [[Matriz compleja simétrica es congruente a matriz con 0 y la identidad]], [[Matriz real simétrica es congruente a matriz diagonal con 1, -1, 0]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema que asegura la existencia de una base $F$-ortogonal?
Reverso: Sea $F$ una [[Forma bilineal]] sobre $V$, donde $V$ es un $\mathbb K$-espacio vectorial de dimensión finita con $car \mathbb K \neq 2$. Entonces, $\exists B$ base de $V$ $F$-ortogonal ([[Conjunto F-ortogonal]]).
Tags: proposición/teorema ÁlgebraI
<!--ID: 1709571902524-->
END

START
Básico
Anverso: Demostración de que sea $F$ una [[Forma bilineal]] sobre $V$, donde $V$ es un $\mathbb K$-espacio vectorial de dimensión finita con $car \mathbb K \neq 2$. Entonces, $\exists B$ base de $V$ $F$-ortogonal ([[Conjunto F-ortogonal]]).
Reverso: Podemos suponer que $V \neq 0$. Procedemos por inducción sobre $n = \dim V$.

$n=1$. 
En este caso toda base de $V$ es ortogonal.

$n-1 \implies n$.
Supongamos el resultado cierto para espacios vectoriales de dimensión $n-1$, y probémoslo para espacios vectoriales de dimensión $n$. Si la forma $F$ es nula, es decir, $F(x,y) = 0, \forall x,y \in V$, tenemos que cualquier base es ortogonal. Por tanto, suponemos que $F \neq 0$.
Veamos que $\exists v \in V: F(v,v) \neq 0$. Sabemos que $\exists x,y \in V$ tales que $F(x,y) \neq 0$ (porque $F$ es no nula). Si $F(x,x) \neq 0$ o $F(y,y) \neq 0$, tomamos $v = x$ o $v = y$. En caso contrario, 
$$F(x+y, x+y) = F(x,x) + F(x,y) + F(y,x) + F(y,y) = 2F(x,y) \neq 0$$ 
porque $car \mathbb K \neq 2$, y tomamos $v = x+y$. Por tanto, $U = \langle v \rangle \le V$ es regular ([[Subespacio regular]]). Efectivamente $\{v\}$ es base de $U$, y la matriz coordenada de $F \restriction_{U \times U}$ con respecto a $\{v \}$ es $0 \neq (F(v,v)) \in M_n(\mathbb K)$, luego $(F(v,v))$ es regular ([[Matriz invertible]]). Por [[Suma directa de subespacio con su ortogonal]], tenemos $\dim U^\perp = n-1$. Por hipótesis de inducción, $\exists B' = \{v_2, \dots, v_n\}$ base de $U^\perp$ tal que $B'$ es ortogonal respecto a $G = F \restriction_{U^\perp \times U^\perp}$. Esto implica que $B = \{v, v_2, \dots, v_n\}$ es base $F$-ortogonal de $V$.
Tags: demostración ÁlgebraI
<!--ID: 1709571902534-->
END