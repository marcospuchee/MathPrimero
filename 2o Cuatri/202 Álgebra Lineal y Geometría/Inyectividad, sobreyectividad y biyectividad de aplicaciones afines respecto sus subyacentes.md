
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-02, 17:19

```ad-proposition
Sea $f: A \to A'$ [[aplicación afín]], con aplicación lineal subyacente $\hat f: V \to V'$ (donde $(A, V, +)$, $(A', V', +)$ son [[espacio afín]] con $V, V'$ $\mathbb K$-espacios vectoriales)). Entonces:
1. $f$ inyectiva $\iff$ $\hat f$ inyectiva.
2. $f$ sobreyectiva $\iff$ $\hat f$ sobreyectiva.
3. $f$ biyectiva $\iff$ $\hat f$ biyectiva.
```


```ad-proof
1. $\rightarrow$. Supongamos $f$ inyectiva. Sea $v \in Ker \hat f$. Tenemos: $\forall P \in A:$
$$f(P+v) = f(P) + \hat f(v) = f(P) + 0 = f(P) \implies P+v = P \implies v = 0.$$
Es decir, $\hat f$ inyectiva.
$\leftarrow$. Supongamos $\hat f$ inyectiva. Sea $P, Q \in A$ tales que $f(P) = f(Q)$. Tenemos:
$$0 = \overrightarrow{f(P)f(Q)} = \hat f(\vec{PQ}).$$
Es decir, $\vec{PQ} \in Ker \hat f = 0 \implies P = Q$.
2. Ejercicio.
3. Consecuencia de 1 y 2.
```

**Tema:** [[Aplicaciones afines]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la proposición que relaciona la inyectividad, sobreyectividad y biyectividad de una aplicación afín respecto de su subyacente?
Reverso: Sea $f: A \to A'$ [[aplicación afín]], con aplicación lineal subyacente $\hat f: V \to V'$ (donde $(A, V, +)$, $(A', V', +)$ son [[espacio afín]] con $V, V'$ $\mathbb K$-espacios vectoriales)). Entonces:
1. $f$ inyectiva $\iff$ $\hat f$ inyectiva.
2. $f$ sobreyectiva $\iff$ $\hat f$ sobreyectiva.
3. $f$ biyectiva $\iff$ $\hat f$ biyectiva.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714669443496-->
END

START
Básico
Anverso: Demostración de que sea $f: A \to A'$ [[aplicación afín]], con aplicación lineal subyacente $\hat f: V \to V'$ (donde $(A, V, +)$, $(A', V', +)$ son [[espacio afín]] con $V, V'$ $\mathbb K$-espacios vectoriales)). Entonces:
1. $f$ inyectiva $\iff$ $\hat f$ inyectiva.
2. $f$ sobreyectiva $\iff$ $\hat f$ sobreyectiva.
3. $f$ biyectiva $\iff$ $\hat f$ biyectiva.
Reverso: 1. $\rightarrow$. Supongamos $f$ inyectiva. Sea $v \in Ker \hat f$. Tenemos: $\forall P \in A:$
$$f(P+v) = f(P) + \hat f(v) = f(P) + 0 = f(P) \implies P+v = P \implies v = 0.$$
Es decir, $\hat f$ inyectiva.
$\leftarrow$. Supongamos $\hat f$ inyectiva. Sea $P, Q \in A$ tales que $f(P) = f(Q)$. Tenemos:
$$0 = \overrightarrow{f(P)f(Q)} = \hat f(\vec{PQ}).$$
Es decir, $\vec{PQ} \in Ker \hat f = 0 \implies P = Q$.
2. Ejercicio.
3. Consecuencia de 1 y 2.
Tags: demostración ÁlgebraI
<!--ID: 1714669443503-->
END