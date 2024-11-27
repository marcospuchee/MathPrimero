### Contenido Principal

```ad-proposition
Sea $f: \Omega \subset \mathbb R^n \to \mathbb R^n$ inyectiva de clase $C^1$ tal que $J_f(x) \neq 0$, $\forall x \in \Omega$. Entonces, $B= f(\Omega)$ es abierto, $f: \Omega \to B$ es una biyección y $g = f^{-1}:B \to \Omega$ es continua.
```

```ad-proof
Falta probar la continuidad de la inversa. Tomamos $b \in B = f(a)$, luego $b = f(a)$ con $a \in \Omega$. Dado $\varepsilon > 0$, queremos encontrar $\delta > 0$ tal que $g(B(b; \delta)) \subset B(g(b); \varepsilon) = B(a; \varepsilon)$.

Por el teorema anterior, $f$ abierta, luego observemos que $f(B(a;\varepsilon))$ es un abierto y $f(a) \in f(B(a;\varepsilon))$, luego $f(B(a; \varepsilon))$ es un entorno de $f(a)$. Por tanto, $\exists \delta > 0$ tal que $f(a) \in B(f(a); \delta) \subset f(B(a; \varepsilon))$. Aplicando la función inversa, 
$$g(B(b; \delta)) = f^{-1}(B(f(a); \delta)) \subset B(a;\varepsilon) = B(g(b); \varepsilon),$$
lo que implica que $g$ es continua en $b$.
```

**Tema:** [[Los teoremas de la función inversa y de la función implícita#1. Teorema de la función inversa.]]

**Definiciones referenciadas:** [$C^1$](Función de clase C1), [$J_f(a)$](Determinante jacobiano), [[Función continua]], [[Entorno]]
**Resultados referenciados:** [$f \in C^1(\Omega, \mathbb R^n) : J_f(x) \neq 0, \forall x \in \Omega \implies f$ aplicación abierta](Función de clase C1 con jacobiano no nulo es abierta)

---
### Anki
