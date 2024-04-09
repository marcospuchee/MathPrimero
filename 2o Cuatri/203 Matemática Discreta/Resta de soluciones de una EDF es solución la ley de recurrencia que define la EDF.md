
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-27, 19:04

```ad-proposition
Sean $(x_n)_{n=1}^{+\infty}, (y_n)_{n=1}^{+\infty}$ dos soluciones de la [[Ecuación en diferencias finitas lineal de coeficientes constantes]]:
$$a_{n+k} = c_0 a_n + \dots + c_{k-1} a_{n+k-1} + \psi(n).$$
Entonces, $(z_n)_{n=1}^{+\infty}$ con $z_n = x_n - y_n$ es solución de la [[Ley de recurrencia lineal y homogénea]]
$$a_{n+k} = c_0 a_n + \dots + c_{k-1} a_{n+k-1}.$$
```


```ad-proof
Sabemos que $z_{n+k} = x_{n+k} - y_{n+k}$. Como $x_n$ e $y_n$ son soluciones:
$$
\begin{eqnarray}
z_{n+k} &=& c_0 x_n + \dots + c_{k-1} x_{n+k-1} + \psi(n) - (c_0 y_n + \dots + c_{k-1} y_{n+k-1} + \psi(n)) \\
&=& c_0(x_n - y_n) + \dots + c_{k-1}(x_{n+k-1} - y_{n+k-1}) \\
&=& c_0 z_n + c_1 z_{n+1} + \dots + c_{k-1} z_{n+k-1}.
\end{eqnarray}
$$
```



**Tema:** [[Ecuaciones de recurrencia#5. Ecuaciones en diferencias finitas]]
**Corolarios:** [[Cualquier solución de una EDF se escribe como solución de EDF + solución de ley de recurrencia]]

---
### Anki
