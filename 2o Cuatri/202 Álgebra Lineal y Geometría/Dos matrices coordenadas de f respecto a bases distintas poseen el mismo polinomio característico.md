
---
mathLink: $P^{-1}AP = C \implies p_A(x) = p_C(x)$
---
### Contenido Principal

**Fecha:** 2024-02-02, 19:18

Sea $f \in End(V)$ ([[Endomorfismo]]), y sean $B_1, B_2$ bases ([[Base]]) de $V$. Sean $A \in M_n (K)$ matriz coordenadas de $f$ respecto a $B_1$ ([[Matriz asociada a una aplicación lineal]]) y $C \in M_n (K)$, matriz coordenada de $f$ respecto a $B_2$, entonces

```ad-proposition
$$p_A (x) = p_C (x)$$
```


```ad-proof
Sabemos que $\exists P \in GL_n (K)$ tal que $C = P^{-1}AP$ ([[Matrices asociadas a endomorfismos son semejantes]]). Tenemos que $p_C (x) = \det(x I_n - C)$ $= \det(xI_n - P^{-1}AP)$ $= \det(P^{-1} (xI_n) P - P^{-1} A P)$ (dado que la matriz identidad conmuta con todo) $= \det(P^{-1} (xI_n - A) P)$ (por las propiedades del determinante) $= \det(P^{-1}) · \det(xI_n - A) · \det(P)$ $= \frac{1}{\det P} · \det(x I_n - A) · \det (P) = \det(xI_n - A)$
```



**Tema:** [[Diagonalización]]
**Corolarios:** [[Polinomio característico de un endomorfismo]] está bien definido.

---
### Anki

START
Respuesta anidada
{{c1::Sea $f \in End(V)$ ([[Endomorfismo]]), y sean $B_1, B_2$ bases ([[Base]]) de $V$. Sean $A \in M_n (K)$ matriz coordenadas de $f$ respecto a $B_1$ ([[Matriz asociada a una aplicación lineal]]) y $C \in M_n (K)$, matriz coordenada de $f$ respecto a $B_2$, entonces}}
{{c3::$$p_A (x) = p_C (x)$$}}
Tags: proposición/teorema
<!--ID: 1707247432469-->
END

START
Básico
Anverso: Demostración de que sea $f \in End(V)$ ([[Endomorfismo]]), y sean $B_1, B_2$ bases ([[Base]]) de $V$. Sean $A \in M_n (K)$ matriz coordenadas de $f$ respecto a $B_1$ ([[Matriz asociada a una aplicación lineal]]) y $C \in M_n (K)$, matriz coordenada de $f$ respecto a $B_2$, entonces
$$p_A (x) = p_C (x)$$
Reverso: Sabemos que $\exists P \in GL_n (K)$ tal que $C = P^{-1}AP$ ([[Matrices asociadas a endomorfismos son semejantes]]). Tenemos que $p_C (x) = \det(x I_n - C)$ $= \det(xI_n - P^{-1}AP)$ $= \det(P^{-1} (xI_n) P - P^{-1} A P)$ (dado que la matriz identidad conmuta con todo) $= \det(P^{-1} (xI_n - A) P)$ (por las propiedades del determinante) $= \det(P^{-1}) · \det(xI_n - A) · \det(P)$ $= \frac{1}{\det P} · \det(x I_n - A) · \det (P) = \det(xI_n - A)$
Tags: demostración
<!--ID: 1707247432478-->
END
