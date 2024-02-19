
---
mathLink: $\lambda$ valor propio de $f \iff \lambda$ valor propio de $A$
---
### Contenido Principal

**Fecha:** 2024-01-31, 13:19

Sea $f \in End(V)$, donde $V$ es $K$-espacio vectorial, y sea $A \in M_n (K)$ la matriz coordenadas de $f$ con respecto a una [[Base]] cualquiera de $V$ ([[Matriz asociada a una aplicación lineal]]). Sea $\lambda \in K$. Entonces:

```ad-lemma
$\lambda$ es valor propio de $f$ ([[Valor propio de un endomorfismo]]) $\iff \lambda$ es valor propio de $A$ ([[Valor propio de una matriz]]).

```


```ad-proof
$\rightarrow$. $\lambda$ es valor propio de $f \implies \exists v \in V - \{0\}$ tal que $f(v) = \lambda v$ $\implies \exists v \in V-\{0\}$ tal que $[f(v)]_B = [\lambda v]_B$ ([[Coordenadas]]) (dado que son iguales) $\implies \exists v \in V-\{0\}$ tal que $A [v]_B = \lambda[v]_B$ ([[Cálculo de las coordenadas una imagen dada la matriz asociada]]). Por tanto, $\lambda$ es valor propio de $A$ (ya que $v \not = 0$ si $[v]_B \not = 0$)

$\leftarrow$. Supongamos ahora $\lambda$ valor propio de $A$. Por tanto, $\exists x \in K^n - \{0\}$ tal que $Ax = \lambda x$. Si $x = (x_1, \dots, x_n)$, construimos $v = x_1 v_1 + \dots + x_n v_n \in V$, donde $B = \{v_1, \dots, v_n\}$. Satisface $[v]_B = (x_1, \dots, x_n)$. Así, tenemos que $A[v]_B = \lambda [v]_B$, con $v \in V-\{0\}$. Deducimos que $\lambda$ es valor propio de $f$.
```



**Tema:** [[Diagonalización]]
**Corolarios:** [[Teorema obtención valores propios]]

---
### Anki

START
Básico
Anverso: Qué relación tienen los valores propios de un endomorfismo con los valores propios de una matriz?
Reverso: Sea $f \in End(V)$, donde $V$ es $K$-espacio vectorial, y sea $A \in M_n (K)$ la matriz coordenadas de $f$ con respecto a una [[Base]] cualquiera de $V$ ([[Matriz asociada a una aplicación lineal]]). Sea $\lambda \in K$. Entonces: $\lambda$ es valor propio de $f$ ([[Valor propio de un endomorfismo]]) $\iff \lambda$ es valor propio de $A$ ([[Valor propio de una matriz]]).
Tags: proposición/teorema
<!--ID: 1706723823956-->
END

START
Básico
Anverso: Demostración de que sea $f \in End(V)$, donde $V$ es $K$-espacio vectorial, y sea $A \in M_n (K)$ la matriz coordenadas de $f$ con respecto a una [[Base]] cualquiera de $V$ ([[Matriz asociada a una aplicación lineal]]). Sea $\lambda \in K$. Entonces: $\lambda$ es valor propio de $f$ ([[Valor propio de un endomorfismo]]) $\iff \lambda$ es valor propio de $A$ ([[Valor propio de una matriz]]).
Reverso: $\rightarrow$. $\lambda$ es valor propio de $f \implies \exists v \in V - \{0\}$ tal que $f(v) = \lambda v$ $\implies \exists v \in V-\{0\}$ tal que $[f(v)]_B = [\lambda v]_B$ ([[Coordenadas]]) (dado que son iguales) $\implies \exists v \in V-\{0\}$ tal que $A [v]_B = \lambda[v]_B$. Por tanto, $\lambda$ es valor propio de $A$ (ya que $v \not = 0$ si $[v]_B \not = 0$)

$\leftarrow$. Supongamos ahora $\lambda$ valor propio de $A$. Por tanto, $\exists x \in K^n - \{0\}$ tal que $Ax = \lambda x$. Si $x = (x_1, \dots, x_n)$, construimos $v = x_1 v_1 + \dots + x_n v_n \in V$, donde $B = \{v_1, \dots, v_n\}$. Satisface $[v]_B = (x_1, \dots, x_n)$. Así, tenemos que $A[v]_B = \lambda [v]_B$, con $v \in V-\{0\}$. Deducimos que $\lambda$ es valor propio de $f$.
Tags: demostración
<!--ID: 1706723823962-->
END