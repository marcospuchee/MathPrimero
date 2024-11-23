### Contenido Principal

```ad-theorem
Sea $A \in \mathbb R^{n \times n}$ una matriz invertible, y $\hat A = A+E$, donde $E \in \mathbb R^{n \times n}$ es una perturbación tal que $p := ||A^{-1}E|| < 1$ (esto garantiza que $\hat A$ es invertible), con $|| \cdot ||$ una norma matricial subordinada.
Sea $b \in \mathbb R^n$, $\hat b = b+f \in \mathbb R^n$. Entonces, si $Ax = b$, $(A+E) \hat x = b+f$, $x, \hat x \in \mathbb R^n$, tenemos que:
$$\frac{||x- \hat x||}{||x||} \le \frac{\kappa(A)}{1-p} \left ( \frac{||\hat A - A||}{||A||} + \frac{||b- \hat b||}{||b||} \right ) = \frac{\kappa(A)}{1-p} \left ( \frac{||E||}{||A||} + \frac{||f||}{||b||} \right ).$$
```

```ad-proof
Considerando el sistema original $Ax = b$ y el sistema perturbado $(A+E) \hat x = b+f$, los diferenciamos:
$$\begin{eqnarray}
Ax - (A+E) \hat x &=& b - (b+f) \\
&=& -f.
\end{eqnarray}$$
Utilizando que $x = A^{-1}b$ y $\hat x = (A+E)^{-1}(b+f)$, diferenciamos otra vez:
$$\begin{eqnarray}
x - \hat x &=& A^{-1}b - (A+E)^{-1}(b+f) \\
&=& (A+E)^{-1}[(A+E)A^{-1}b - (b+f)] \\
&=& (A+E)^{-1}(b + EA^{-1}b - b - f) \\
&=& (A+E)^{-1}(Ex - f).
\end{eqnarray}$$
Si tomamos normas,
$$\begin{eqnarray}
||x- \hat x|| = ||(A+E)^{-1}(Ex-f)|| &\le& ||(A+E)^{-1}|| \, ||Ex - f|| \\
&\le& ||(A+E)^{-1}|| \, (||Ex|| + ||f||) \\
&\le& ||(A+E)^{-1}|| \, (||E|| \, ||x|| + ||f||) \\
&\le& \frac{||A^{-1}||}{1-p} \, (||E|| \, ||x|| + ||f||).
\end{eqnarray}$$
Si dividimos a ambos lados entre $||x||$ (para conseguir el error relativo),
$$
\frac{||x-\hat x||}{||x||} \le \frac{||A^{-1}||}{1-p} \left ( ||E|| + \frac{||f||}{||x||} \right ).
$$
Notemos que como $Ax = b$, $||b|| = ||Ax|| \le ||A|| \cdot ||x||$, luego $||x|| \ge \frac{||b||}{||A||}$. Así,
$$\begin{eqnarray}
\frac{||x-\hat x||}{||x||} \le \frac{||A^{-1}||}{1-p} \left ( ||E|| + \frac{||f|| \, ||A||}{||b||} \right ) &=& \frac{||A^{-1}||}{1-p} \left ( ||E|| + ||A|| \frac{||f||}{||b||} \right ) \\
&=& \frac{||A|| \cdot ||A^{-1}||}{1-p} \left ( \frac{||E||}{||A||} + \frac{||f||}{||b||} \right ) \\
&=& \frac{\kappa(A)}{1-p} \left ( \frac{||E||}{||A||} + \frac{||f||}{||b||} \right ).
\end{eqnarray}$$
```

**Tema:** [[Sistemas lineales y su solución numérica#2. Solución numérica perturbada de los sistemas lineales.]]
**Corolario:** -.

**Definiciones referenciadas:** [$\kappa(A)$](Número de condición de una matriz respecto de una norma), [[Norma matricial subordinada a una norma vectorial]], [$\frac{||x- \hat x||}{||x||}$](Errores absoluto y relativo de una aproximación) 
**Resultados referenciados:** [$||A^{-1}E|| < 1 \implies A+E$ invertible](Cota norma inversa matriz perturbada en función de la inversa de la matriz normal), [$||(A+E)^{-1}|| \le \frac{||A^{-1}||}{1-p}$](Cota norma inversa matriz perturbada en función de la inversa de la matriz normal)

---
### Anki
