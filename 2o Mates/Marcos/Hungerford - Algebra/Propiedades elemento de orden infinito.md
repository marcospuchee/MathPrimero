
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-12, 12:46

```ad-theorem
Sea $G$ un [[grupo]] y $a \in G$. Si $a$ tiene orden infinito ([[orden de un elemento de un grupo]]), entonces:
1. $a^k = e \iff k = 0$.
2. Los elementos $a^k \, (k \in \mathbb Z)$ son todos distintos.
```

```ad-proof
Sea $H = \langle a \rangle$.
1. Tomamos la aplicación $f: \mathbb Z \to H$ con $k \to a^k$ del [[teorema grupo cíclico infinito isomorfo a Z]]. Sabemos que es un isomorfo y que $a^0 = e$. Por tanto, si $a^k = e$ y $k \neq 0$, estaría contradiciendo la propiedad inyectiva de la aplicación.
2. Supongamos por reducción al absurdo que $a^m = a^n$ con $m \neq n$. Entonces, $a^m (a^n)^{-1} = e$. Esto es, $a^{m-n} = e$. Por (1), $m-n = 0 \implies m = n$.
```

**Tema:** [[Grupos#3. Grupos cíclicos.]]
**Demostrado por:** [[Teorema grupo cíclico infinito isomorfo a Z]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué propiedades cumple un elemento de orden infinito?
Reverso: Sea $G$ un [[grupo]] y $a \in G$. Si $a$ tiene orden infinito ([[orden de un elemento de un grupo]]), entonces:
1. $a^k = e \iff k = 0$.
2. Los elementos $a^k \, (k \in \mathbb Z)$ son todos distintos.
Tags: proposición/teorema hungerford
<!--ID: 1721211802931-->
END
