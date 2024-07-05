
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-10, 23:46

Sea $f \in End(V)$. Supongamos que $\lambda_1, \dots, \lambda_p \in \mathbb K$ son valores propios de $f$ ([[Valor propio de un endomorfismo]]), con $\lambda_i \neq \lambda_j$ si $i \neq j$. Sean $v_i \in E_f (\lambda)$ ([[Subespacio propio de un endomorfismo]]) $\forall i = 1, \dots, p$, tales que $v_1 + v_2 + \dots + v_p = 0$. Entonces

```ad-theorem
$$v_1 = \dots = v_p = 0$$
```

```ad-proof
Inducción sobre $p$.

**Caso base:** $p = 1$. 
Trivial.

**Paso inductivo:** $p-1 \implies p$. 
Supongamos el resultado para $\lambda_1, \dots, \lambda_{p-1} \in \mathbb K$ valores propios de $f$. Sean ahora $\lambda_1, \dots, \lambda_{p-1}, \lambda_p \in \mathbb K$ valores propios (distintos dos a dos) de $f$ y sean $v_i \in E_f (\lambda), \forall i$, tales que $v_1 + v_2 + \dots + v_{p-1} + v_p = 0$.
Queremos ver que $v_i = 0, \forall i = 1, \dots, p$. Tenemos que $0 = f(0) = f(v_1 + \dots + v_p) = f(v_1) + \dots + f(v_{p-1}) + f(v_p)$, que por ser vectores de $E_f(\lambda)$, nos devuelve el siguiente resultado:
$$
\lambda_1 v_1 + \dots + \lambda_{p-1} v_{p-1} + \lambda_p v_p \tag{1}
$$
Por otro lado, $0 = \lambda_p 0 = \lambda_p (v_1 + \dots + v_{p-1} + v_p)$, lo que nos devuelve el siguiente resultado:
$$
\lambda_p v_1 + \dots + \lambda_p v_{p-1} + \lambda_p v_p \tag{2}
$$
Escribimos $(1) - (2)$: $0 = (\lambda_1 - \lambda_p)v_1 + \dots + (\lambda_{p-1} - \lambda_p) v_{p-1}$. Sin embargo, $(\lambda_i - \lambda_p)v_i \in E_f(\lambda)$, $\forall i = 1, \dots, p-1$. Así, por hipótesis de inducción, $(\lambda_i - \lambda_p)v_i = 0$, $\forall i = 1, \dots, p-1$.
Dado que $\lambda_i - \lambda_p \neq 0$ (por ser distintos dos a dos), $\forall i = 1, \dots, p-1$, deducimos que $v_1 = \dots = v_{p-1} = 0$. Luego $v_p = 0$.
```

**Tema:** [[Diagonalización]]
**Demostrado por:**
**Consecuencias:** [[Corolario suma de subespacios propios directa y unión de bases es base de la suma]]

---
### Anki

START
Respuesta anidada
{{c2::Sea $f \in End(V)$. Supongamos que $\lambda_1, \dots, \lambda_p \in \mathbb K$ son valores propios de $f$ ([[Valor propio de un endomorfismo]]), con $\lambda_i \neq \lambda_j$ si $i \neq j$. Sean $v_i \in E_f (\lambda)$ ([[Subespacio propio de un endomorfismo]]) $\forall i = 1, \dots, p$, tales que $v_1 + v_2 + \dots + v_p = 0$. Entonces}}
{{c1::$$v_1 = \dots = v_p = 0$$}}
Tags: proposición/teorema ÁlgebraI
<!--ID: 1707764225149-->
END

START
Básico
Anverso: Demuestra que sea $f \in End(V)$. Supongamos que $\lambda_1, \dots, \lambda_p \in \mathbb K$ son valores propios de $f$ ([[Valor propio de un endomorfismo]]), con $\lambda_i \neq \lambda_j$ si $i \neq j$. Sean $v_i \in E_f (\lambda)$ ([[Subespacio propio de un endomorfismo]]) $\forall i = 1, \dots, p$, tales que $v_1 + v_2 + \dots + v_p = 0$. Entonces
$$v_1 = \dots = v_p = 0$$
Reverso: Inducción sobre $p$.

**Caso base:** $p = 1$. 
Trivial.

**Paso inductivo:** $p-1 \implies p$. 
Supongamos el resultado para $\lambda_1, \dots, \lambda_{p-1} \in \mathbb K$ valores propios de $f$. Sean ahora $\lambda_1, \dots, \lambda_{p-1}, \lambda_p \in \mathbb K$ valores propios (distintos dos a dos) de $f$ y sean $v_i \in E_f (\lambda), \forall i$, tales que $v_1 + v_2 + \dots + v_{p-1} + v_p = 0$.
Queremos ver que $v_i = 0, \forall i = 1, \dots, p$. Tenemos que $0 = f(0) = f(v_1 + \dots + v_p) = f(v_1) + \dots + f(v_{p-1}) + f(v_p)$, que por ser vectores de $E_f(\lambda)$, nos devuelve el siguiente resultado:
$$
\lambda_1 v_1 + \dots + \lambda_{p-1} v_{p-1} + \lambda_p v_p \tag{1}
$$
Por otro lado, $0 = \lambda_p 0 = \lambda_p (v_1 + \dots + v_{p-1} + v_p)$, lo que nos devuelve el siguiente resultado:
$$
\lambda_p v_1 + \dots + \lambda_p v_{p-1} + \lambda_p v_p \tag{2}
$$
Escribimos $(1) - (2)$: $0 = (\lambda_1 - \lambda_p)v_1 + \dots + (\lambda_{p-1} - \lambda_p) v_{p-1}$. Sin embargo, $(\lambda_i - \lambda_p)v_i \in E_f(\lambda)$, $\forall i = 1, \dots, p-1$. Así, por hipótesis de inducción, $(\lambda_i - \lambda_p)v_i = 0$, $\forall i = 1, \dots, p-1$.
Dado que $\lambda_i - \lambda_p \neq 0$ (por ser distintos dos a dos), $\forall i = 1, \dots, p-1$, deducimos que $v_1 = \dots = v_{p-1} = 0$. Luego $v_p = 0$.
Tags: demostración ÁlgebraI
<!--ID: 1707764225160-->
END

