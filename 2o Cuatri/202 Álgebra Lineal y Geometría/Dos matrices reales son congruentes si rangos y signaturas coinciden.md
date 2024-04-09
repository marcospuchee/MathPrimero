
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-20, 19:37

```ad-cor
Sean $A, C \in M_n(\mathbb R)$ matrices simétrica. Entonces $A, C$ son congruntes ([[Matrices congruentes]]) $\iff rg(A) = rg(C)$ ([[Rango de una matriz]]) y $sig(A) = sig(C)$ ([[Signatura de una matriz simétrica]]).
```


```ad-proof
$\leftarrow$.
Supongamos que $rg(A) = rg(C) = r$, $sig(A) = sig(C) = s$. Por [[Matriz real simétrica es congruente a matriz diagonal con 1, -1, 0]], $A$ y $C$ son congruentes a $Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0)$ (con la respectiva signatura y rango), luego $A$ y $C$ son congruentes.

$\rightarrow$.
Supongamos que $A, C$ son congruentes. Sean $rg(A) = r, sig(A) = s$, $rg(C) = r', sig(C) = s'$. Tenemos que $r ? r'$ (porque matrices congruentes son equivalentes ([[La relación de congruencia es de equivalencia]])). Por [[Matriz real simétrica es congruente a matriz diagonal con 1, -1, 0]], $A$ es congruente a $M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0)$ (con signatura $s$ y rango $r$), y $C$ es congruente a $M' = Diag(1, \dots,1, -1, \dots, -1, 0, \dots, 0)$ (con signatura $s'$ y rango $r$). Consideramos $F_A: \mathbb R^n \times \mathbb R^n \to \mathbb R$ con $(x,y) \to x^t A y$.
Tenemos que $M = P^t A P$, donde $A$ es la [[Matriz coordenada de F]]$A$ respecto a la base canónica de $\mathbb R^n$, para cierta $P \in GL_n(\mathbb R)$ ([[Matriz invertible]]).
Sea $B$ la base de $\mathbb R^n$ tal que $P$ es la [[Matriz cambio de base]] de la base canónica a $B$. Por tanto, $M$ es la matriz coordenada de $F_A$ respecto a $B$.
$M$ diagonal $\implies B$ es $F_A$-ortogonal ([[Conjunto F-ortogonal]]) de $\mathbb R^n$. Así, $sig(F_A) = sig(B) = s$. Razonando de manera análoga, de que $A, C$ son congruentes, y $C, M'$ son congruentes, entonces $A, M'$ son congruentes. Luego $sig(F_A) = s' \implies s = s'$.
```

**Tema:** [[Formas bilineales]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sean $A, C \in M_n(\mathbb R)$ matrices simétrica. {{c1::Entonces $A, C$ son congruntes ([[Matrices congruentes]])}} $\iff${{c2:: $rg(A) = rg(C)$ ([[Rango de una matriz]]) y $sig(A) = sig(C)$ ([[Signatura de una matriz simétrica]]).}}
Tags: proposición/teorema ÁlgebraI
<!--ID: 1712235233690-->
END

START
Básico
Anverso: Demostración de que sean $A, C \in M_n(\mathbb R)$ matrices simétrica. Entonces $A, C$ son congruntes ([[Matrices congruentes]]) $\iff rg(A) = rg(C)$ ([[Rango de una matriz]]) y $sig(A) = sig(C)$ ([[Signatura de una matriz simétrica]]).
Reverso: $\leftarrow$.
Supongamos que $rg(A) = rg(C) = r$, $sig(A) = sig(C) = s$. Por [[Matriz real simétrica es congruente a matriz diagonal con 1, -1, 0]], $A$ y $C$ son congruentes a $Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0)$ (con la respectiva signatura y rango), luego $A$ y $C$ son congruentes.

$\rightarrow$.
Supongamos que $A, C$ son congruentes. Sean $rg(A) = r, sig(A) = s$, $rg(C) = r', sig(C) = s'$. Tenemos que $r ? r'$ (porque matrices congruentes son equivalentes ([[La relación de congruencia es de equivalencia]])). Por [[Matriz real simétrica es congruente a matriz diagonal con 1, -1, 0]], $A$ es congruente a $M = Diag(1, \dots, 1, -1, \dots, -1, 0, \dots, 0)$ (con signatura $s$ y rango $r$), y $C$ es congruente a $M' = Diag(1, \dots,1, -1, \dots, -1, 0, \dots, 0)$ (con signatura $s'$ y rango $r$). Consideramos $F_A: \mathbb R^n \times \mathbb R^n \to \mathbb R$ con $(x,y) \to x^t A y$.
Tenemos que $M = P^t A P$, donde $A$ es la [[Matriz coordenada de F]]$A$ respecto a la base canónica de $\mathbb R^n$, para cierta $P \in GL_n(\mathbb R)$ ([[Matriz invertible]]).
Sea $B$ la base de $\mathbb R^n$ tal que $P$ es la [[Matriz cambio de base]] de la base canónica a $B$. Por tanto, $M$ es la matriz coordenada de $F_A$ respecto a $B$.
$M$ diagonal $\implies B$ es $F_A$-ortogonal ([[Conjunto F-ortogonal]]) de $\mathbb R^n$. Así, $sig(F_A) = sig(B) = s$. Razonando de manera análoga, de que $A, C$ son congruentes, y $C, M'$ son congruentes, entonces $A, M'$ son congruentes. Luego $sig(F_A) = s' \implies s = s'$.
Tags: demostración ÁlgebraI
<!--ID: 1712235233697-->
END
