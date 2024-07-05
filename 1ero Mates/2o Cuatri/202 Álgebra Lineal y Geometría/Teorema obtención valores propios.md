
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-31, 18:35

Sea $f \in End(V)$, donde $V$ es un $K$-espacio vectorial, y sea $A \in M_n (K)$ la matriz coordenadas ([[Matriz asociada a una aplicación lineal]]) de $f$ con respecto a una [[Base]] $B$ arbitraria de $V$.

```ad-theorem
Entonces, $\lambda \in K$ es valor propio de $f$ ([[Valor propio de un endomorfismo]]) $\iff det(\lambda I_n - A) = 0$
```

```ad-proof
Tenemos que $\lambda$ es valor propio de $f$, lo cual ocurre $\iff$ $\lambda$ es valor propio de $A$ ([[Valor propio de una matriz]], [[Relación valor propio de endomorfismo y matriz]]) $\iff \exists x \in K^n - \{0\}$ tal que $Ax = \lambda x$ $\iff (\lambda I_n - A)x = 0$ para algún $x \in K^n - \{0\}$ $\iff$ el sistema de ecuaciones lineales (homogéneo) $(\lambda I_n - A)x = 0$ es compatible indeterminado $\iff$ $rg(\lambda I_n - A) < n$ (número de incógnitas)([[Teorema Rouche-Frobenius]]) $\iff det(\lambda I_n - A) = 0$.

```


**Tema:** [[Diagonalización]]
**Demostrado por:** [[Relación valor propio de endomorfismo y matriz]]
**Consecuencias:** [[Obtención de valores propios a través del polinomio característico de un endomorfismo]]

---
### Anki

START
Respuesta anidada
{{c1::Sea $f \in End(V)$, donde $V$ es un $K$-espacio vectorial, y sea $A \in M_n (K)$ la matriz coordenadas ([[Matriz asociada a una aplicación lineal]]) de $f$ con respecto a una [[Base]] $B$ arbitraria de $V$.}} Entonces, {{c2::$\lambda \in K$ es valor propio de $f$ ([[Valor propio de un endomorfismo]])}} $\iff$ {{c3::$det(\lambda I_n - A) = 0$}}
Tags: proposición/teorema
<!--ID: 1706723823915-->
END

START
Básico
Anverso: Demostración de que sea $f \in End(V)$, donde $V$ es un $K$-espacio vectorial, y sea $A \in M_n (K)$ la matriz coordenadas ([[Matriz asociada a una aplicación lineal]]) de $f$ con respecto a una [[Base]] $B$ arbitraria de $V$. Entonces, $\lambda \in K$ es valor propio de $f$ ([[Valor propio de un endomorfismo]]) $\iff det(\lambda I_n - A) = 0$
Reverso: Tenemos que $\lambda$ es valor propio de $f$, lo cual ocurre $\iff$ $\lambda$ es valor propio de $A$ ([[Valor propio de una matriz]], [[Relación valor propio de endomorfismo y matriz]]) $\iff \exists x \in K^n - \{0\}$ tal que $Ax = \lambda x$ $\iff (\lambda I_n - A)x = 0$ para algún $x \in K^n - \{0\}$ $\iff$ el sistema de ecuaciones lineales (homogéneo) $(\lambda I_n - A)x = 0$ es compatible indeterminado $\iff$ $rg(\lambda I_n - A) < n$ (número de incógnitas)([[Teorema Rouche-Frobenius]]) $\iff det(\lambda I_n - A) = 0$.
Tags: demostración
<!--ID: 1706723823920-->
END
