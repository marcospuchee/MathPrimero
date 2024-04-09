
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-27, 19:10

```ad-cor
Sea $(a^(p))^{+\infty}_{n = 0}$ una solución particular de la [[Ecuación en diferencias finitas lineal de coeficientes constantes]]:
$$a_{n+k} = c_0 a_n + \dots + c_{k-1} a_{n+k-1} + \psi(n).$$
Entonces, cualquier otra solución $(x_n)_{n=1}^{+\infty}$ se podrá expresar como $(a_n^{(H)} + a_n^{(P)})^{+\infty}_{n=1}$ donde $(a_n^{(H)})_{n=1}^{+\infty}$ es una solución de la [[Ley de recurrencia lineal y homogénea]] de orden $k$:
$$a_{n+k} = c_0 a_n + \dots + c_{k-1} a_{n+k-1}.$$

```

```ad-proof
Sea $x_n$ una solución de la EDF. Sea $z_n = x_n - a_n^{(P)}$. Según [[Resta de soluciones de una EDF es solución la ley de recurrencia que define la EDF]], $z_n$ es solución de la ley de recurrencia. Luego $z_n = a_n^{(H)}$, y despejando $x_n = z_n + a_n^{(P)}$, donde $z_n$ es solución de la ley de recurrencia.
```

**Tema:** [[Ecuaciones de recurrencia#5. Ecuaciones en diferencias finitas]]

---
### Anki
