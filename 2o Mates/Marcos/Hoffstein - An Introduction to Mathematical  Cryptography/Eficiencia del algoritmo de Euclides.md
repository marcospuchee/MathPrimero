### Contenido Principal

```ad-theorem
El paso de la división del [[algoritmo de Euclides]] se ejecuta, como mucho, $2log_2(b) + 2$ veces.
```

```ad-proof
Demostremos primero que $r_{i+2} < \frac{1}{2}r_i$, $\forall i = 0, 1, 2, \dots$ Consideramos dos casos:
1. $r_{i+1} \le \frac{1}{2}r_i$. Como los valores de $r_i$ son estrictamente decrecientes:
$$r_{i+2} < r_{i+1} \le \frac{1}{2} r_i.$$
2. $r_{i+1} > \frac{1}{2} r_i$. Consideremos lo que ocurre cuando dividimos $r_i$ entre $r_{i+1}$. El valor de $r_{i+1}$ es tan grande que obtenemos
$$r_i = r_{i+1} \cdot1 + r_{i+1}, \quad r_{i+1} = r_i - r_{i+1} < r_i - \frac{1}{2}r_i = \frac{1}{2}r_i.$$

Por tanto, acabamos de demostrar que $r_{i+2} < \frac{1}{2}r_i, \forall i$. Si aplicamos esta desigualdad repetidas veces, obtenemos
$$r_{2k+1} < \frac{1}{2}r_{2k-1} < \frac{1}{2}r_{2k-3} < \frac{1}{8}r_{2k-5} < \frac{1}{16} r_{2k-7} < \dots < \frac{1}{2^k}r_1 = \frac{1}{2^k}b.$$
Así, si $2^k \ge b$, entonces $r_{2k+1} < 1 \implies r_{2k+1} = 0$, y el algoritmo acaba.

Eligiendo el $k$ más pequeño tal que $2^k \ge b > 2^{k-1}$. Entonces,
$$\textrm{\# de iteraciones} \le 2k = 2(k-1) + 2 < 2log_2(b) + 2.$$
```

**Tema:** [[An Introduction to Cryptography#1. Divisibilidad y máximo común divisor.]]
**Corolario:**

---
### Anki
