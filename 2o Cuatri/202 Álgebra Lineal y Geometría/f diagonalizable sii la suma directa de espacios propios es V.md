
---
mathLink: $f$ es diagonalizable $\iff V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ 
---
### Contenido Principal

**Fecha:** 2024-02-12, 17:40

Sea $f \in End(V)$ ([[Endomorfismo]]). Sean $\lambda_1, \dots, \lambda_p \in \mathbb K$ TODOS los valores propios de $f$ (distintos dos a dos) ([[Valor propio de un endomorfismo]]). Entonces,

```ad-theorem
$f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ ([[Subespacio propio de un endomorfismo]], [[Suma directa de t subespacios]])
```


```ad-proof
$\leftarrow$.
Supongamos que $V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$. Sea $B_i$ una base de $E_f(\lambda_i), \forall i = 1, \dots, p$. Entonces $B = \bigcup^p_{i = 1} B_i$ es una base de $V$ por las propiedades de la [[Suma directa de t subespacios]]. Por construcción, $B$ está formada por vectores propios de $f$ (notemos que $B_i$ no contiene al vector $0, \forall i = 1, \dots, p$ porque $B$ es linealmente independiente), así, $f$ es diagonalizable.

$\rightarrow$.
Supongamos que $f$ es diagonalizable. Sea $B$ una base de $V$, formada por vectores propios de $f$. Supongamos que $B$ contiene exactamente $d_i$ vectores propios asociados al valor propio $\lambda_i, \forall i = 1, \dots, p$. Por tanto, tenemos: 
$\dim V = |B| = \sum_{i =1}^p d_i \le$ $\sum_{i =1}^p \dim E_f(\lambda_i)=$ (por [[Corolario suma de subespacios propios directa y unión de bases es base de la suma]])  $\dim (E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p))$ $\le \dim V$.
Así, de esta cadena, extraemos que $\dim V = \dim (E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p))$ y deducimos que $V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ (y también $d_i = \dim E_f(\lambda_i), \forall i$).
```

```ad-note
Tenemos que $\dim(E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)) = \sum_{i = 1}^p \dim E_f(\lambda_i)$. Por tanto, $f$ es diagonalizable $\iff \sum_{i = 1}^p \dim E_f(\lambda_i) = \dim V$.
```


**Tema:** [[Diagonalización]]
**Demostrado por:** [[Corolario suma de subespacios propios directa y unión de bases es base de la suma]]
**Consecuencias:** [[Corolario f diagonalizable si f tiene n valores propios distintos]]

---
### Anki

START
Respuesta anidada
Sea $f \in End(V)$ ([[Endomorfismo]]). Sean $\lambda_1, \dots, \lambda_p \in \mathbb K$ TODOS los valores propios de $f$ (distintos dos a dos) ([[Valor propio de un endomorfismo]]). Entonces, {{c1::$f$ es diagonalizable ([[Endomorfismo diagonalizable]])}} {{c2::$\iff V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ ([[Subespacio propio de un endomorfismo]], [[Suma directa de t subespacios]])}}
Tags: ÁlgebraI proposición/teorema
<!--ID: 1707764224922-->
END

START
Básico
Anverso: Demostración de que sea $f \in End(V)$ ([[Endomorfismo]]). Sean $\lambda_1, \dots, \lambda_p \in \mathbb K$ TODOS los valores propios de $f$ (distintos dos a dos) ([[Valor propio de un endomorfismo]]). Entonces, $f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ ([[Subespacio propio de un endomorfismo]], [[Suma directa de t subespacios]])
Reverso: $\leftarrow$.
Supongamos que $V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$. Sea $B_i$ una base de $E_f(\lambda_i), \forall i = 1, \dots, p$. Entonces $B = \bigcup^p_{i = 1} B_i$ es una base de $V$ por las propiedades de la [[Suma directa de t subespacios]]. Por construcción, $B$ está formada por vectores propios de $f$ (notemos que $B_i$ no contiene al vector $0, \forall i = 1, \dots, p$ porque $B$ es linealmente independiente), así, $f$ es diagonalizable.

$\rightarrow$.
Supongamos que $f$ es diagonalizable. Sea $B$ una base de $V$, formada por vectores propios de $f$. Supongamos que $B$ contiene exactamente $d_i$ vectores propios asociados al valor propio $\lambda_i, \forall i = 1, \dots, p$. Por tanto, tenemos: 
$\dim V = |B| = \sum_{i =1}^p d_i \le$ $\sum_{i =1}^p \dim E_f(\lambda_i)=$ (por [[Corolario suma de subespacios propios directa y unión de bases es base de la suma]])  $\dim (E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p))$ $\le \dim V$.
Así, de esta cadena, extraemos que $\dim V = \dim (E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p))$ y deducimos que $V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ (y también $d_i = \dim E_f(\lambda_i), \forall i$).
Tags: demostración ÁlgebraI
<!--ID: 1707764224934-->
END

