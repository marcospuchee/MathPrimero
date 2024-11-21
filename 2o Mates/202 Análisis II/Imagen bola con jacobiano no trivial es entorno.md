### Contenido Principal

```ad-proposition
Sea $f: \overline{B(a;r)} \subset \mathbb R^n \to \mathbb R^n$ continua en $\overline{B(a; r)}$ y diferenciable en $B(a;r)$. Si $J_f(x) \neq 0$, $\forall x \in B(a; r)$ y $f(x) \neq f(a)$, $\forall x \in S(a,r)$ $=$  $\{x \in \mathbb R^n : ||x-a|| = r \}$, entonces $f(B(a; r))$ es un entorno de $f(a)$.
```

```ad-proof
Queremos ver que $\exists R > 0$ tal que $f(a) \in B(f(a); R) \subset f(B(a; r))$. Definimos
$$\begin{array}{c c c l}
g: & S(a;r) & \to & \mathbb R \\
& x & \mapsto & ||f(x)-f(a)|| \ge 0.
\end{array}$$
Como $f(x) \neq f(a)$, $\forall x \in S(a; r)$, entonces, $g(x) > 0$, $\forall x \in S(a; r)$. Además, $g$ es continua y $S(a; r)$ es compacto, lo que implica que podemos aplicar el teorema de Weierstrass y afirmar que $g$ tiene mínimo absoluto en $S(a;r)$. Definimos:
$$m:= \min \limits_{x \in S(a; r)} g(x) = \min \limits_{x \in S(a;r)} ||f(x) - f(a)||; \quad m > 0.$$
Tomamos $R = \frac{m}{2}$ y vamos a ver $B(f(a); R) \subset f(B(a;r))$.
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [[Función continua]], [[Función diferenciable]], [$J_f(a)$](Determinante jacobiano), [[Entorno]]
**Resultados referenciados:**

---
### Anki
