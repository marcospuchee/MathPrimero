
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-12, 19:36

Sea $f \in End(V)$ un [[Endomorfismo]], y sea $\lambda \in \mathbb K$ un valor propio de $f$ ([[Valor propio de un endomorfismo]]). Supongamos que $\alpha$ es la [[Multiplicidad algebraica]] de $\lambda$, y $d$ es la [[Multiplicidad geométrica]] de $\lambda$. Entonces,

```ad-proposition
$$ \alpha \ge d$$
```


```ad-proof
Sea $\{v_1, \dots, v_d \}$ una base de $E_f(\lambda)$ ([[Subespacio propio de un endomorfismo]]) (subespacio de $V$). Por el lema de prolongación, $\exists v_{d+1}, \dots, v_n \in V$ tales que $\{v_1, \dots, v_\alpha, v_{d + 1}, \dots, v_n\} = B$ es base de $V$.

Sea $A$ la matriz coordenadas de $f$ con respecto a la base $B$ ([[Matriz asociada a una aplicación lineal]]), notemos que $A$ tiene $\lambda$ en la diagonal hasta la $d$-ésima columna (por pertenecer todos esos vectores al subespacio propio de $f$).
Para calcular ahora el polinomio característico de $f$ ([[Polinomio característico de un endomorfismo]]), recurrimos al polinomio característico de $A$, que se calcula a través de $\det(xI_n - A)$. Luego este determinante es el determinante de una matriz con $x-\lambda$ en la diagonal hasta la $d$-ésima posición. Es decir, $\det (xI_n - A) = (x- \lambda)^{d} \cdot q(x)$, donde $q(x) \in \mathbb K [x]$ es el polinomio resultante de el resto de la matriz (las $n-\alpha$ columnas restantes correspondientes a las coordenadas de los vectores $v_{d+1}, \dots, v_n$ en la base $B$).
Por tanto, $\alpha \ge d$.

```



**Tema:** [[Diagonalización]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Qué relación de orden guarda la multiplicidad algebraica con la multiplicidad geométrica?
Reverso: Sea $f \in End(V)$ un [[Endomorfismo]], y sea $\lambda \in \mathbb K$ un valor propio de $f$ ([[Valor propio de un endomorfismo]]). Supongamos que $\alpha$ es la [[Multiplicidad algebraica]] de $\lambda$, y $d$ es la [[Multiplicidad geométrica]] de $\lambda$. Entonces,
$$ \alpha \ge d$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1707764224873-->
END

START
Básico
Anverso: Demuestra que sea $f \in End(V)$ un [[Endomorfismo]], y sea $\lambda \in \mathbb K$ un valor propio de $f$ ([[Valor propio de un endomorfismo]]). Supongamos que $\alpha$ es la [[Multiplicidad algebraica]] de $\lambda$, y $d$ es la [[Multiplicidad geométrica]] de $\lambda$. Entonces,
$$ \alpha \ge d$$
Reverso: Sea $\{v_1, \dots, v_d \}$ una base de $E_f(\lambda)$ ([[Subespacio propio de un endomorfismo]]) (subespacio de $V$). Por el lema de prolongación, $\exists v_{d+1}, \dots, v_n \in V$ tales que $\{v_1, \dots, v_\alpha, v_{d + 1}, \dots, v_n\} = B$ es base de $V$.

Sea $A$ la matriz coordenadas de $f$ con respecto a la base $B$ ([[Matriz coordenada]]), notemos que $A$ tiene $\lambda$ en la diagonal hasta la $d$-ésima columna (por pertenecer todos esos vectores al subespacio propio de $f$).
Para calcular ahora el polinomio característico de $f$ ([[Polinomio característico de un endomorfismo]]), recurrimos al polinomio característico de $A$, que se calcula a través de $\det(xI_n - A)$. Luego este determinante es el determinante de una matriz con $x-\lambda$ en la diagonal hasta la $d$-ésima posición. Es decir, $\det (xI_n - A) = (x- \lambda)^{d} \cdot q(x)$, donde $q(x) \in \mathbb K [x]$ es el polinomio resultante de el resto de la matriz (las $n-\alpha$ columnas restantes correspondientes a las coordenadas de los vectores $v_{d+1}, \dots, v_n$ en la base $B$).
Por tanto, $\alpha \ge d$.

Tags: demostración ÁlgebraI
<!--ID: 1707764224886-->
END
