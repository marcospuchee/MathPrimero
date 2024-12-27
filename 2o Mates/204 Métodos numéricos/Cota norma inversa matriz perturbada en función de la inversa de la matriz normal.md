### Lema.

```ad-lemma
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
**Resultados referenciados:** [[Teorema de Cauchy-Schwartz]],

---
### Resultado principal.

```ad-proposition
Si $A \in \mathbb R^{n \times n}$ es una matriz invertible, y $E \in \mathbb R^{n \times n}$ verifica que $p:= ||A^{-1}E|| < 1$ en alguna norma matricial subordinada, entonces $A+E$ es también una matriz invertible, y (en la misma norma) se verifica que:
$$||(A+E)^{-1}|| \le \frac{||A^{-1}||}{1-p}.$$
```

```ad-proof
Definimos $B := -A^{-1}E$. Entonces,
$$A+E = A(I+A^{-1}E) = A(I - B).$$
Como consecuencia, sabemos que $\exists (A+E)^{-1}$ porque $||B||$ $=$ $||A^{-1}E||$ $=$ $p$ $<$ $1$, luego sabemos, aplicando el lema anterior, que $I-B$ es invertible. Por hipótesis $A$ es invertible, entonces el producto de matrices invertibles es invertible y:
$$(A+E)^{-1}=(I-B)^{-1}A^{-1}.$$
Además, sus normas cumplen que:
$$||(A+E)^{-1}|| = ||(I-B)^{-1}A^{-1}|| \le ||(I-B)^{-1}|| \cdot ||A^{-1}|| \le \frac{||A^{-1}||}{1 - ||B||},$$
y sabiendo que $||B|| = p$, lo tenemos.
```

**Tema:** [[Sistemas lineales y su solución numérica#2. Solución numérica perturbada de los sistemas lineales.]]

**Definiciones referenciadas:** [[Norma matricial subordinada a una norma vectorial]]
**Resultados referenciados:** [$||(I - B)^{-1}|| \le \frac{1}{1 - ||B||}$](Cota norma inversa matriz perturbada en función de la inversa de la matriz normal)

---
### Anki

START
Básico
Anverso: Condiciones suficientes para la cota de la norma de la matriz $||(I-B)^{-1}||$ donde $||B||<1$
Reverso: Si $B \in \mathbb R^{n \times n}$ cumple $||B|| < 1$ en alguna norma matricial subordinada, entonces $I - B$ es invertible, con
$$||(I - B)^{-1}|| \le \frac{1}{1 - ||B||}.$$
Tags: met
<!--ID: 1735044171479-->
END

START
Básico
Anverso: Demostración de que si $B \in \mathbb R^{n \times n}$ cumple $||B|| < 1$ en alguna norma matricial subordinada, entonces $I - B$ es invertible, con
$$||(I - B)^{-1}|| \le \frac{1}{1 - ||B||}.$$
Reverso: Supongamos que $||B|| < 1$, veamos que $I-B$ es invertible. Para ello, veremos que $(I-B)x \neq 0$, $\forall x \in \mathbb R^{n} \textrm{\\} \{0\}$. Procediendo por reducción al absurdo, supongamos que $\exists x \in \mathbb R^n \textrm{\\} \{0\}$ tal que $(I-B)x = 0$.
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
Tags: dem met
<!--ID: 1735044171481-->
END

START
Básico
Anverso: Condiciones suficientes para la cota, y cota, de la norma de la inversa de la matriz de coeficientes perturbada
Reverso: Si $A \in \mathbb R^{n \times n}$ es una matriz invertible, y $E \in \mathbb R^{n \times n}$ verifica que $p:= ||A^{-1}E|| < 1$ en alguna norma matricial subordinada, entonces $A+E$ es también una matriz invertible, y (en la misma norma) se verifica que:
$$||(A+E)^{-1}|| \le \frac{||A^{-1}|1}{1-p}.$$
Tags: met
<!--ID: 1735044171483-->
END

START
Básico
Anverso: Demostración de que si $A \in \mathbb R^{n \times n}$ es una matriz invertible, y $E \in \mathbb R^{n \times n}$ verifica que $p:= ||A^{-1}E|| < 1$ en alguna norma matricial subordinada, entonces $A+E$ es también una matriz invertible, y (en la misma norma) se verifica que:
$$||(A+E)^{-1}|| \le \frac{||A^{-1}|1}{1-p}.$$
Reverso: Definimos $B := -A^{-1}E$. Entonces,
$$A+E = A(I+A^{-1}E) = A(I - B).$$
Como consecuencia, sabemos que $\exists (A+E)^{-1}$ porque $||B||$ $=$ $||A^{-1}E||$ $=$ $p$ $<$ $1$, luego sabemos, aplicando el lema anterior, que $I-B$ es invertible. Por hipótesis $A$ es invertible, entonces el producto de matrices invertibles es invertible y:
$$(A+E)^{-1}=(I-B)^{-1}A^{-1}.$$
Además, sus normas cumplen que:
$$||(A+E)^{-1}|| = ||(I-B)^{-1}A^{-1}|| \le ||(I-B)^{-1}|| \cdot ||A^{-1}|| \le \frac{||A^{-1}||}{1 - ||B||},$$
y sabiendo que $||B|| = p$, lo tenemos.
Tags: dem met
<!--ID: 1735044171485-->
END



