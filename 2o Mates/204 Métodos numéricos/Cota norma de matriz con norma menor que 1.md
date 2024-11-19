### Contenido Principal

```ad-proposition
Si $B \in \mathbb R^{n \times n}$ cumple $||B|| < 1$ en alguna norma matricial subordinada, entonces $I - B$ es invertible, con
$$||(I - B)^{-1}|| \le \frac{1}{1 - ||B||}.$$
```

```ad-proof
Supongamos que $||B|| < 1$, veamos que $I-B$ es invertible. Para ello, veremos que $(I-B)x \neq 0$, $\forall x \in \mathbb R^{n} \textrm{\\} \{0\}$. Procediendo por reducción al absurdo, supongamos que $\exists x \in \mathbb R^n \textrm{\\} \{0\}$ tal que $(I-B)x = 0$.
$$(I-B)x = 0 \iff x-Bx = 0 \iff Bx = x \iff ||x|| = ||Bx|| \le ||B|| ||x||,$$
de donde se deriva que $||B|| \ge 1$, lo cual es una contradicción.

Para probar lo siguiente, notemos que
$$||(I - B)^{-1}|| \le \frac{1}{1 - ||B||} \iff ||(I-B)^{-1}||(1-||B||) \le 1.$$
Aplicando la propiedad distributiva, la desigualdad de Cauchy-Schwarz y la segunda desigualdad triangular,
$$\begin{eqnarray}
||(I-B)^{-1}|| (1-||B||) &=& ||(I-B)^{-1}|| - ||(I-B)^{-1}|| \cdot ||B|| \\ &\le& ||(I-B)^{-1}|| - ||(I-B)^{-1}B|| \\
&\le& ||(I-B)^{-1} - (I-B)^{-1}B||\\
&=& ||(I-B)^{-1}(I - B)|| \\
&=& ||I|| = 1.
\end{eqnarray}$$
```

**Tema:** [[Sistemas lineales y su solución numérica#2. Solución numérica perturbada de los sistemas lineales.]]

**Definiciones referenciadas:** [[Norma matricial subordinada a una norma vectorial]]
**Resultados referenciados:**

---
### Anki
