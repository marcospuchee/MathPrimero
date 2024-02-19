
---
mathLink: $n = \dim V \land f$ tiene $n$ valores propios distintos $\implies f$ diagonalizable
---
### Contenido Principal

**Fecha:** 2024-02-12, 17:55

Sea $f \in End(V)$, donde $n = \dim V$.

```ad-cor
Supongamos que $f$ tiene $n$ valores propios distintos $\lambda_1, \dots, \lambda_n \in \mathbb K$ ([[Valor propio de un endomorfismo]]). Entonces $f$ es diagonalizable ([[Endomorfismo diagonalizable]]).
```


```ad-proof
Sabemos que $\dim E_f(\lambda_i) \ge 1, \forall i = 1, \dots, n$. Entonces: $n = \dim V \ge$ (por ser [[Subespacio vectorial]]) $\dim(E_f (\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_n))$ $= \sum_{i = 1}^n \dim E_f(\lambda_i) \ge n = \dim V$ $\implies \dim (E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_n))$ $= n = \dim V$ $\implies E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_n) = V$, y  por tanto, $f$ es diagonalizable por [[f diagonalizable sii la suma directa de espacios propios es V]]
```

**Tema:** [[Diagonalización]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $f \in End(V)$, donde $n = \dim V$. {{c1::Supongamos que $f$ tiene $n$ valores propios distintos $\lambda_1, \dots, \lambda_n \in \mathbb K$ ([[Valor propio de un endomorfismo]]).}} {{c2::Entonces $f$ es diagonalizable ([[Endomorfismo diagonalizable]]).}}
Tags: proposición/teorema ÁlgebraI
<!--ID: 1707764224898-->
END

START
Básico
Anverso: Demostración de que sea $f \in End(V)$, donde $n = \dim V$. Supongamos que $f$ tiene $n$ valores propios distintos $\lambda_1, \dots, \lambda_n \in \mathbb K$ ([[Valor propio de un endomorfismo]]). Entonces $f$ es diagonalizable ([[Endomorfismo diagonalizable]]).
Reverso: Sabemos que $\dim E_f(\lambda_i) \ge 1, \forall i = 1, \dots, n$. Entonces: $n = \dim V \ge$ (por ser [[Subespacio vectorial]]) $\dim(E_f (\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_n))$ $= \sum_{i = 1}^n \dim E_f(\lambda_i) \ge n = \dim V$ $\implies \dim (E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_n))$ $= n = \dim V$ $\implies E_f(\lambda_1) \bigoplus \dots \bigoplus E_f(\lambda_n) = V$, y  por tanto, $f$ es diagonalizable por [[f diagonalizable sii la suma directa de espacios propios es V]]
Tags: demostración ÁlgebraI
<!--ID: 1707764224910-->
END

