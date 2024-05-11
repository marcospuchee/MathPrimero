### Contenido principal

**Fecha:** 2024-04-25, 17:15

```ad-formal
title: Formal definition
Sean $(A, V, +)$ [[espacio afín]], donde $V$ es un $\mathbb K$-espacio vectorial de dimensión $\dim V = n$, $L = W_P \subseteq A$ [[variedad afín]], $\mathcal R = \{O, B\}$ un [[sistema de referencia cartesiano]] en $A$. Supongamos que $\{w_1, \dots, w_k\}$ es una base de $W$ ($k = \dim L$). Escribimos $B = \{v_1, \dots, v_n \}$. Tenemos:
$$w_j = \alpha_{1j} v_1 + \alpha_{2j} v_2 + \dots + \alpha_{nj} v_n, \quad \forall j \in \{1, \dots, k\},$$
con $\alpha_{ij}, \dots, \alpha_{nj} \in \mathbb K$ únicos. Luego $[w_j]_B = (\alpha_{1j}, \dots, \alpha_{nj}) \in \mathbb K^n$. Sea $X \in A$.

Observemos por [[Ecuación paramétrica de una variedad afín]] que
$$[X]_{\mathcal R} - [P]_{\mathcal R} = \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B,$$
luego
$$[X]_{\mathcal R} - [P]_{\mathcal R} \in \langle [w_1]_B, \dots, [w_k]_B \rangle.$$
Sea $M$ la matriz asociada al sistema de ecuaciones lineales, lo anterior se cumple sii $rg (M) = k$. Mediante operaciones elementales por filas, obtenemos una matriz $N$ equivalente a $M$ en forma escalonada por filas:
![[Pasted image 20240425172407.png]]
Las entradas $(k+1,n), (k+2,n), \dots, (n-1,n), (n,n)$ no pueden añadir una unidad al rango de la matriz, por tanto, al igualarlas a cero, observamos un sistema de ecuaciones lineales cuya solución son las coordenadas respectivas de las partes de $L$.

Este sistema de ecuaciones lineales son las ecuaciones implícitas cartesianas de $L$ con respecto a $\mathcal R$.
```

**Tema:** [[Espacios afines]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Definición y desarrollo de la ecuación implícita cartesiana de una variedad afín
Reverso: Sean $(A, V, +)$ [[espacio afín]], donde $V$ es un $\mathbb K$-espacio vectorial de dimensión $\dim V = n$, $L = W_P \subseteq A$ [[variedad afín]], $\mathcal R = \{O, B\}$ un [[sistema de referencia cartesiano]] en $A$. Supongamos que $\{w_1, \dots, w_k\}$ es una base de $W$ ($k = \dim L$). Escribimos $B = \{v_1, \dots, v_n \}$. Tenemos:
$$w_j = \alpha_{1j} v_1 + \alpha_{2j} v_2 + \dots + \alpha_{nj} v_n, \quad \forall j \in \{1, \dots, k\},$$
con $\alpha_{ij}, \dots, \alpha_{nj} \in \mathbb K$ únicos. Luego $[w_j]_B = (\alpha_{1j}, \dots, \alpha_{nj}) \in \mathbb K^n$. Sea $X \in A$.

Observemos por [[Ecuación paramétrica de una variedad afín]] que
$$[X]_{\mathcal R} - [P]_{\mathcal R} = \lambda_1 [w_1]_B + \dots + \lambda_k [w_k]_B,$$
luego
$$[X]_{\mathcal R} - [P]_{\mathcal R} \in \langle [w_1]_B, \dots, [w_k]_B \rangle.$$
Sea $M$ la matriz asociada al sistema de ecuaciones lineales, lo anterior se cumple sii $rg (M) = k$. Mediante operaciones elementales por filas, obtenemos una matriz $N$ equivalente a $M$ en forma escalonada por filas:
![[Pasted image 20240425172407.png]]
Las entradas $(k+1,n), (k+2,n), \dots, (n-1,n), (n,n)$ no pueden añadir una unidad al rango de la matriz, por tanto, al igualarlas a cero, observamos un sistema de ecuaciones lineales cuya solución son las coordenadas respectivas de las partes de $L$.

Este sistema de ecuaciones lineales son las ecuaciones implícitas cartesianas de $L$ con respecto a $\mathcal R$.
Tags: definición ÁlgebraI
<!--ID: 1714060760609-->
END