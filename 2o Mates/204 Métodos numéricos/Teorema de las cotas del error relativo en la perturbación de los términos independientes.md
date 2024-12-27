### Contenido Principal

```ad-theorem
Sea $A \in \mathbb R^{n \times n}$ una matriz invertible. Consideramos los sistemas de ecuaciones lineales: $Ax = b$, $A\hat x = \hat b$, $b, \hat b \in \mathbb R^n$. Entonces, para cualquier norma en $\mathbb R^n$, $|| \cdot||$, y su correspondiente norma matricial subordinada, se cumple que:
$$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}.$$
```

```ad-proof
Dados $Ax = b$ y $A \hat x = \hat b$. Notemos que
$$\begin{eqnarray}
b - \hat b = A(x - \hat x) &\implies& ||b - \hat b|| = ||A(x- \hat x)|| \le ||A|| \cdot ||x-\hat x|| \\
&\implies& \frac{||b- \hat b||}{||A||} \le ||x - \hat x||
\end{eqnarray}$$
Igualmente,
$$x - \hat x = A^{-1}(b- \hat b) \implies ||x - \hat x|| = || A^{-1}(b- \hat b)|| \le ||A^{-1}|| \cdot ||b-\hat b||.$$

De ambos resultados, tenemos que
$$ \frac{||b- \hat b||}{||A|| \cdot ||x||} \le \frac{||x - \hat x||}{||x||} \le \frac{||A^{-1}|| \cdot ||b-\hat b||}{||x||}.$$
Ahora vamos a buscar acotar $||x||$:
$$\begin{eqnarray}
Ax = b &\implies& ||b|| = ||Ax|| \le ||A|| \cdot ||x|| \implies \frac{||b||}{||A||} \le ||x|| \\
x = A^{-1}b &\implies& ||x|| = ||A^{-1}b|| \le ||A^{-1}|| \cdot ||b||,
\end{eqnarray}$$
lo que, invirtiendo las desigualdades, queda:
$$\quad \frac{1}{||A^{-1}|| \cdot ||b||} \le \frac{1}{||x||} \le \frac{||A||}{||b||}.$$
Sustituyendo,
$$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}.$$
```

**Tema:** [[Sistemas lineales y su solución numérica#2. Solución numérica de los sistemas lineales.]]
**Corolario:**

**Definiciones referenciadas:** [$\hat A \hat x = \hat b$](Sistema perturbado), [$\frac{||x- \hat x||}{||x||}$](Errores absoluto y relativo de una aproximación), [[Norma]], [[Norma matricial subordinada a una norma vectorial]]
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Cotas del error relativo de un sistema de ecuaciones con los términos independientes perturbados
Reverso: Sea $A \in \mathbb R^{n \times n}$ una matriz invertible. Consideramos los sistemas de ecuaciones lineales: $Ax = b$, $A\hat x = \hat b$, $b, \hat b \in \mathbb R^n$. Entonces, para cualquier norma en $\mathbb R^n$, $|| \cdot||$, y su correspondiente norma matricial subordinada, se cumple que:
$$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}.$$
Tags: met
<!--ID: 1735044171347-->
END

START
Básico
Anverso: Demostración de que sea $A \in \mathbb R^{n \times n}$ una matriz invertible. Consideramos los sistemas de ecuaciones lineales: $Ax = b$, $A\hat x = \hat b$, $b, \hat b \in \mathbb R^n$. Entonces, para cualquier norma en $\mathbb R^n$, $|| \cdot||$, y su correspondiente norma matricial subordinada, se cumple que:
$$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}.$$
Reverso: Dados $Ax = b$ y $A \hat x = \hat b$. Notemos que
$$\begin{eqnarray}
b - \hat b = A(x - \hat x) &\implies& ||b - \hat b|| = ||A(x- \hat x)|| \le ||A|| \cdot ||x-\hat x|| \\
&\implies& \frac{||b- \hat b||}{||A||} \le ||x - \hat x||
\end{eqnarray}$$
Igualmente,
$$x - \hat x = A^{-1}(b- \hat b) \implies ||x - \hat x|| = || A^{-1}(b- \hat b)|| \le ||A^{-1}|| \cdot ||b-\hat b||.$$

De ambos resultados, tenemos que
$$ \frac{||b- \hat b||}{||A|| \cdot ||x||} \le \frac{||x - \hat x||}{||x||} \le \frac{||A^{-1}|| \cdot ||b-\hat b||}{||x||}.$$
Ahora vamos a buscar acotar $||x||$:
$$\begin{eqnarray}
Ax = b &\implies& ||b|| = ||Ax|| \le ||A|| \cdot ||x|| \implies \frac{||b||}{||A||} \le ||x|| \\
x = A^{-1}b &\implies& ||x|| = ||A^{-1}b|| \le ||A^{-1}|| \cdot ||b||,
\end{eqnarray}$$
lo que, invirtiendo las desigualdades, queda:
$$\quad \frac{1}{||A^{-1}|| \cdot ||b||} \le \frac{1}{||x||} \le \frac{||A||}{||b||}.$$
Sustituyendo,
$$\frac{1}{||A|| \, ||A^{-1}||} \frac{||b- \hat b||}{||b||} \le \frac{||x- \hat x||}{||x||} \le ||A|| \, ||A^{-1}|| \frac{||b-\hat b||}{||b||}.$$
Tags: met dem
<!--ID: 1735044171355-->
END

