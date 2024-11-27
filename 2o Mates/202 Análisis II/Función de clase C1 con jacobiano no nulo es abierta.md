### Lema.

```ad-lemma
Sean $\Omega$ abierto de $\mathbb R^n$, $f: \Omega \to \mathbb R^n$ diferenciable en $\Omega$. Entonces si $f$ es inyectiva en $\Omega$ y $J_f(x) \neq 0$, $\forall x \in \Omega$, entonces $f(\Omega)$ es un abierto
```

```ad-proof
*Ejercicio.*
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [[Función diferenciable]], [$J_f(a)$](Determinante jacobiano).

---

### Teorema.

```ad-theorem
Sean $\Omega$ abierto de $\mathbb R^n$, $f: \Omega \to \mathbb R^n$ función de clase $C^1(\Omega)$ tal que $J_f(x) \neq 0$, $\forall x \in \Omega$. Entonces, $f$ es una aplicación abierta
```

```ad-proof
Sea $U$ abierto de $\Omega$, queremos ver que $f(U)$ es abierto de $\mathbb R^n$. Queremos encontrar $f(a) \in f(U)$ con $a \in U$. Queremos encontrar $R > 0$ tal que $B(f(a); R) \subset f(U)$.

Por el teorema de inyectividad local, $\exists r > 0$ tal que $B(a;r) \subset U$ y $f$ es inyectiva en $B(a;r)$. Sabemos que $f_{\restriction {\overline{B(a;r/2)}}}:  \overline{B(a;r/2)}  \to  \mathbb R^n$ es continua e inyectiva en $\overline{B(a;r/2)}$ y diferenciable en $B(a;r/2)$ con $J_f(x) \neq 0$, $\forall x \in B(a;r/2)$, lo que, aplicando el lema anterior, $f(B(a;r/2))$ es un entorno de $f(a)$. Es decir, $\exists R > 0$ de forma que $B(f(a); R) \subset f(B(a;r/2)) \subset f(U)$. Por tanto, $f(U)$ es abierto de $\mathbb R^n$.
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [$C^1$](Función de clase C1), [$J_f(a)$](Determinante jacobiano), [[Función abierta]]
**Resultados referenciados:** [[Teorema de la inyectividad local]]

---
### Anki
