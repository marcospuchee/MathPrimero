
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-06, 17:10

```ad-theorem
Sea $(b_n)_{n=1}^\infty$ la solución la [[Ley de recurrencia lineal y homogénea]]:
$$a_{n+k} = c_0 a_n + c_1 a_{n+1} + \dots + c_{k-1} a_{n+k-1}$$
con condiciones iniciales $b_0 = 0, b_1 = 0, \dots, b_{k-2} = 0, b_{k-1} = 1$. Entonces, para cualquier sucesión $(\psi(n))_{n=0}^\infty$, la sucesión $(a_n)_{n=0}^\infty$ definida por $a_0 = 0, a_1 = 0, \dots, a_{k-2} = 0, a_{k-1} = 0$ y
$$a_n = (\psi (0), \dots, \psi(n-k)) · (b_{n-1}, \dots, b_{k-1}) = \sum_{j = 0}^{n-k} b_{n-j-1} \psi(j)$$
es una solución particular de la [[Ecuación en diferencias finitas lineal]]
$$a_{n+k} = c_0 a_n + c_1 a_{n+1} + \dots + c_{k-1} a_{n+k-1} + \psi(n).$$
```


```ad-proof
Haremos la solución para $k=2$, porque es más simple, pero se puede resolver análogamente para cualquier $k$.

Sea la [[Ecuación en diferencias finitas lineal de coeficientes constantes]]:
$$a_{n+2} = c_0 a_n + c_1 a_{n+1} + \psi(n).$$
Tenemos que $b_n$ es solución de $a_{n+2} = c_0 a_n + c_1 a_{n+1}$ con $b_0 = 0$ y $b_1 = 1$.
Queremos demostrar que
$$a_n = \sum_{j = 0}^{n-2} b_{n-j-1} \psi(j)$$
es solución de la EDF.ema Para ello vamos a ver que $a_{n+2} = c_0 a_n + c_1 a_{n+1}$ con $a_n$ y $a_{n+1}$ definidos como en la ecuación de arriba.
$$
\begin{eqnarray}
c_0 a_n + c_1 a_{n+1} + \psi(n) &=& c_0 \sum_{j= 0}^{n-2} b_{n-j-1} \psi(j) + c_1 \sum_{j=0}^{n-1} b_{n-j} \psi(j) + \psi(n) \\
&=& \sum_{j = 0}^{n-2} (c_0 b_{n-j-1} \psi(j) + c_1 b_{n-j} \psi(j)) + c_1 b_{n-(n-1)} \psi(n-1) + \psi(n) \\
&=& \sum_{j = 0}^{n-2} (c_0 b_{n-j-1} + c_1 b_{n-j}) \psi (j) + c_1 b_1 \psi (n-1) + \psi (n).
\end{eqnarray}
$$
Sin embargo, como $b_{n+2} = c_0 b_0 + c_1 b_{n+1}$ (por ser solución de la ley de recurrencia), análogamente, $b_{n-j+1} = c_0b_{n-j-1} + c_1 b_{n-j}$. Luego, lo anterior es igual a
$$
\sum_{j = 0}^{n-2} b_{n-j+1} \psi(j) + c_1 b_1 \psi(n-1) + \psi(n).
$$
Conocemos $b_1 = 1$ y $b_{n+2} = c_0 b_n + c_1 b_{n+1}$, luego $b_2 = c_0 b_0 + c_1 b_1$, pero como $b_0 = 0$ y $b_1 = 1$, entonces $b_2 = c_1$. Así, lo anterior es igual a
$$
\begin{eqnarray}
&=& \sum_{j = 0}^{n-2} b_{n-j+1} \psi(j) + b_2 \psi(n-1) + \psi(n) \\
&=& \sum_{j = 0}^{n-2} b_{n-j+1} \psi(j) + b_2 \psi(n-1) + b_1 \psi(n) = \sum_{j = 0}^n b_{n-j+1} = a_{n+2}
\end{eqnarray}
$$
```


**Tema:** [[Ecuaciones de recurrencia#5. Ecuaciones en diferencias finitas]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que soluciona ecuaciones en diferencias finitas lineales de coeficientes constantes de orden k?
Reverso: Sea $(b_n)_{n=1}^\infty$ la solución la [[Ley de recurrencia lineal y homogénea]]:
$$a_{n+k} = c_0 a_n + c_1 a_{n+1} + \dots + c_{k-1} a_{n+k-1}$$
con condiciones iniciales $b_0 = 0, b_1 = 0, \dots, b_{k-2} = 0, b_{k-1} = 1$. Entonces, para cualquier sucesión $(\psi(n))_{n=0}^\infty$, la sucesión $(a_n)_{n=0}^\infty$ definida por $a_0 = 0, a_1 = 0, \dots, a_{k-2} = 0, a_{k-1} = 0$ y
$$a_n = (\psi (0), \dots, \psi(n-k)) · (b_{n-1}, \dots, b_{k-1}) = \sum_{j = 0}^{n-k} b_{n-j-1} \psi(j)$$
es una solución particular de la [[Ecuación en diferencias finitas lineal]]
$$a_{n+k} = c_0 a_n + c_1 a_{n+1} + \dots + c_{k-1} a_{n+k-1} + \psi(n).$$
Tags: proposición/teorema MatDiscreta
<!--ID: 1709746655826-->
END

START
Básico
Anverso: Demostración del teorema que soluciona ecuaciones en diferencias finitas lineales de coeficientes constantes de orden k
Reverso: Haremos la solución para $k=2$, porque es más simple, pero se puede resolver análogamente para cualquier $k$.

Sea la [[Ecuación en diferencias finitas lineal de coeficientes constantes]]:
$$a_{n+2} = c_0 a_n + c_1 a_{n+1} + \psi(n).$$
Tenemos que $b_n$ es solución de $a_{n+2} = c_0 a_n + c_1 a_{n+1}$ con $b_0 = 0$ y $b_1 = 1$.
Queremos demostrar que
$$a_n = \sum_{j = 0}^{n-2} b_{n-j-1} \psi(j)$$
es solución de la EDF. Para ello vamos a ver que $a_{n+2} = c_0 a_n + c_1 a_{n+1}$ con $a_n$ y $a_{n+1}$ definidos como en la ecuación de arriba.
$$
\begin{eqnarray}
c_0 a_n + c_1 a_{n+1} + \psi(n) &=& c_0 \sum_{j= 0}^{n-2} b_{n-j-1} \psi(j) + c_1 \sum_{j=0}^{n-1} b_{n-j} \psi(j) + \psi(n) \\
&=& \sum_{j = 0}^{n-2} (c_0 b_{n-j-1} \psi(j) + c_1 b_{n-j} \psi(j)) + c_1 b_{n-(n-1)} \psi(n-1) + \psi(n) \\
&=& \sum_{j = 0}^{n-2} (c_0 b_{n-j-1} + c_1 b_{n-j}) \psi (j) + c_1 b_1 \psi (n-1) + \psi (n).
\end{eqnarray}
$$
Sin embargo, como $b_{n+2} = c_0 b_0 + c_1 b_{n+1}$ (por ser solución de la ley de recurrencia), análogamente, $b_{n-j+1} = c_0b_{n-j-1} + c_1 b_{n-j}$. Luego, lo anterior es igual a
$$
\sum_{j = 0}^{n-2} b_{n-j+1} \psi(j) + c_1 b_1 \psi(n-1) + \psi(n).
$$
Conocemos $b_1 = 1$ y $b_{n+2} = c_0 b_n + c_1 b_{n+1}$, luego $b_2 = c_0 b_0 + c_1 b_1$, pero como $b_0 = 0$ y $b_1 = 1$, entonces $b_2 = c_1$. Así, lo anterior es igual a
$$
\begin{eqnarray}
&=& \sum_{j = 0}^{n-2} b_{n-j+1} \psi(j) + b_2 \psi(n-1) + \psi(n) \\
&=& \sum_{j = 0}^{n-2} b_{n-j+1} \psi(j) + b_2 \psi(n-1) + b_1 \psi(n) = \sum_{j = 0}^n b_{n-j+1} = a_{n+2}
\end{eqnarray}
$$
Tags: demostración MatDiscreta
<!--ID: 1709746655840-->
END