### Contenido principal

```ad-Formal
Dada una matriz $A \in \mathbb R^{n \times n}$, el número de condición de $A$ en la norma $|| \cdot ||$ lo definimos como
$$\kappa (A) := ||A|| \cdot ||A^{-1}||.$$
```

```ad-note
Si definimos $r = b- \hat b = b- A \hat x$ como el residual y $e = x - \hat x$ como el error, tenemos que:
$$\frac{1}{\kappa(A)} \frac{||r||}{||b||} \le \frac{||e||}{||x||} \le \kappa(A) \frac{||r||}{||b||}.$$
Si definimos $r_r = ||r||/||b||$ como el residual relativo y $e_r = ||e||/||x||$ como el error relativo, el teorema se escribe como:
$$\frac{1}{\kappa(A)} \le \frac{e_r}{r_r} \le \kappa(A).$$
```


**Tema:** [[Sistemas lineales y su solución numérica#2. Solución numérica perturbada de los sistemas lineales.]]

**Definiciones referenciadas:** [[Norma matricial subordinada a una norma vectorial]]
**Resultados referenciados:** [$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}$](Teorema de las cotas del error relativo en la perturbación de los términos independientes)

---
### Anki
