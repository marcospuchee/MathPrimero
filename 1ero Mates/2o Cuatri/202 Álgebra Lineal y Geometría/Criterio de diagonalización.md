
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-06, 20:04

Sea $f \in End(V)$ ([[Endomorfismo]]), donde $V$ es un $K$-espacio vectorial de dimensión finita $n = \dim V$. Supongamos que $\lambda_1, \dots, \lambda_m \in K$ son todos los valores propios de $f$ (sin repeticiones).

Sea $\alpha_i$ la [[Multiplicidad algebraica]] de $\lambda_i$, y $d_i$ la [[Multiplicidad geométrica]] de $\lambda_i$, $\forall i = 1, \dots, m$. Entonces,

```ad-theorem
$f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff$ $\sum_{i = 1}^n \alpha_i = n$ $\quad \land \quad \alpha_i = d_i, \forall i = 1, \dots, m$.
```


```ad-proof
$\leftarrow$.
Supongamos que $\sum_{i =1}^m \alpha_i = n$, y $d_i = \alpha_i, \forall i \in \{ 1, \dots, m\}$. Entonces, $\sum_{i = 1}^m d_i = n = \dim V$, y deducimos que $f$ es diagonalizable por la nota de [[f diagonalizable sii la suma directa de espacios propios es V]].

$\rightarrow$.
Supongamos que $f$ es diagonalizable. Entonces $V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ por [[f diagonalizable sii la suma directa de espacios propios es V]], y por tnato, $n = \dim V = \sum_{i = 1}^m \dim E_f(\lambda_i) = \sum_{i = 1}^m d_i$.
Tenemos que $\delta(p_f(x)) = n \ge$ (comparando grados de polinomios) $\sum_{i = 1}^m \alpha_i \ge$ (por [[Multiplicidad algebraica es mayor o igual que multiplicidad geométrica]]) $\sum_{i =1}^m d_i = n$. Por tanto, $\sum_{i = 1}^m \alpha_i = n$ y $\sum_{i = 1}^m \alpha_i = \sum_{i = 1}^m$, lo que implica que $\alpha_i = d_i$ porque como $\alpha_i \ge d_i, \forall i \in \{1, \dots, m\}$, $d_i$ nunca puede compensar que $\alpha_i > d_i$
```


**Tema:** [[Diagonalización]]
**Demostrado por:** [[f diagonalizable sii la suma directa de espacios propios es V]], [[Multiplicidad algebraica es mayor o igual que multiplicidad geométrica]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué dice el criterio de diagonalización?
Reverso: Sea $f \in End(V)$ ([[Endomorfismo]]), donde $V$ es un $K$-espacio vectorial de dimensión finita $n = \dim V$. Supongamos que $\lambda_1, \dots, \lambda_m \in K$ son todos los valores propios de $f$ (sin repeticiones).

Sea $\alpha_i$ la [[Multiplicidad algebraica]] de $\lambda_i$, y $d_i$ la [[Multiplicidad geométrica]] de $\lambda_i$, $\forall i = 1, \dots, m$. Entonces, $f$ es diagonalizable ([[Endomorfismo diagonalizable]]) $\iff$ $\sum_{i = 1}^n \alpha_i = n$ $\quad \land \quad \alpha_i = d_i, \forall i = 1, \dots, m$.
Tags: proposición/teorema
<!--ID: 1707247432395-->
END

START
Básico
Anverso: Demostración del criterio de diagonalización
Reverso: $\leftarrow$.
Supongamos que $\sum_{i =1}^m \alpha_i = n$, y $d_i = \alpha_i, \forall i \in \{ 1, \dots, m\}$. Entonces, $\sum_{i = 1}^m d_i = n = \dim V$, y deducimos que $f$ es diagonalizable por la nota de [[f diagonalizable sii la suma directa de espacios propios es V]].

$\rightarrow$.
Supongamos que $f$ es diagonalizable. Entonces $V = E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_p)$ por [[f diagonalizable sii la suma directa de espacios propios es V]], y por tnato, $n = \dim V = \sum_{i = 1}^m \dim E_f(\lambda_i) = \sum_{i = 1}^m d_i$.
Tenemos que $\delta(p_f(x)) = n \ge$ (comparando grados de polinomios) $\sum_{i = 1}^m \alpha_i \ge$ (por [[Multiplicidad algebraica es mayor o igual que multiplicidad geométrica]]) $\sum_{i =1}^m d_i = n$. Por tanto, $\sum_{i = 1}^m \alpha_i = n$ y $\sum_{i = 1}^m \alpha_i = \sum_{i = 1}^m$, lo que implica que $\alpha_i = d_i$ porque como $\alpha_i \ge d_i, \forall i \in \{1, \dots, m\}$, $d_i$ nunca puede compensar que $\alpha_i > d_i$
Tags: demostración ÁlgebraI
<!--ID: 1708275569384-->
END
