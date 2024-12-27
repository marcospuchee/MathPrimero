### Contenido Principal

```ad-theorem
Si $A \in \mathbb R^{n \times n}$ es simétrica y definida positiva, entonces el proceso de eliminación gaussiana se puede llevar a término sin encontrar pivotes nulos.
```

```ad-proof
Por inducción sobre la dimensión de $A$.

**Caso base: $n=1$.**
$a_{11} \neq 0$.

**Paso inductivo.**
Al realizar un paso de eliminación gaussiana, y ser $A$ simétrica con $\alpha \neq 0$, obtenemos
$$M_1A = \left ( \begin{array}{c | c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha}vv^T \end{array} \right ).$$
Por [[matriz definida positiva tiene diagonal estrictamente positiva]], $C - \frac{1}{\alpha}vv^T$ es simétrica, veamos que es definida positiva. Dado $x \in \mathbb R^n \textrm{\\} \{0\}$, consideramos $y = \left ( \begin{array}{c} -\frac{1}{\alpha}x^Tv \\ x \end{array} \right )$ con $x \in \mathbb R^n \textrm{\\} \{0\}$, de forma que
$$\begin{eqnarray}
y^T A y &=& (-\frac{1}{\alpha}x^T v, x^T) \left ( \begin{array}{c | c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha}vv^T \end{array} \right ) \left ( \begin{array}{c} - \frac{1}{\alpha}xv^T \\ x \end{array} \right ) \\ &=& (- \frac{1}{\alpha}x^Tv, x^T) \left ( \begin{array}{c} -x^Tv + v^Tx \\ -\frac{1}{\alpha} vx^Tv + Cx \end{array} \right ) \\
&=& ( - \frac{1}{\alpha} x^T v, x^T) \left ( \begin{array}{c} 0 \\ (1-\frac{1}{\alpha}vv^T + C)x \end{array} \right ) \\
&=& x^T(C- \frac{1}{\alpha}vv^T)x.
\end{eqnarray}$$
Pero como $x \neq 0$, $y \neq 0$, entonces $y^TAy > 0$ implica que $x^TCx > 0$, luego $C$ es definida positiva y $C_{11} \neq 0$.
Por hipótesis de inducción se puede continuar con la eliminación gaussiana.
```

**Tema:** [[Descomposición LU#3. Matrices especiales y propiedades de la descomposición LU.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Demostración de que si $A \in \mathbb R^{n \times n}$ es simétrica y definida positiva, entonces el proceso de eliminación gaussiana se puede llevar a término sin encontrar pivotes nulos.
Reverso: Por inducción sobre la dimensión de $A$.

**Caso base: $n=1$.**
$a_{11} \neq 0$.

**Paso inductivo.**
Al realizar un paso de eliminación gaussiana, y ser $A$ simétrica con $\alpha \neq 0$, obtenemos
$$M_1A = \left ( \begin{array}{c | c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha}vv^T \end{array} \right ).$$
Por [[matriz definida positiva tiene diagonal estrictamente positiva]], $C - \frac{1}{\alpha}vv^T$ es simétrica, veamos que es definida positiva. Dado $x \in \mathbb R^n \textrm{\\} \{0\}$, consideramos $y = \left ( \begin{array}{c} -\frac{1}{\alpha}x^Tv \\ x \end{array} \right )$ con $x \in \mathbb R^n \textrm{\\} \{0\}$, de forma que
$$\begin{eqnarray}
y^T A y &=& (-\frac{1}{\alpha}x^T v, x^T) \left ( \begin{array}{c | c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha}vv^T \end{array} \right ) \left ( \begin{array}{c} - \frac{1}{\alpha}xv^T \\ x \end{array} \right ) \\ &=& (- \frac{1}{\alpha}x^Tv, x^T) \left ( \begin{array}{c} -x^Tv + v^Tx \\ -\frac{1}{\alpha} vx^Tv + Cx \end{array} \right ) \\
&=& ( - \frac{1}{\alpha} x^T v, x^T) \left ( \begin{array}{c} 0 \\ (1-\frac{1}{\alpha}vv^T + C)x \end{array} \right ) \\
&=& x^T(C- \frac{1}{\alpha}vv^T)x.
\end{eqnarray}$$
Pero como $x \neq 0$, $y \neq 0$, entonces $y^TAy > 0$ implica que $x^TCx > 0$, luego $C$ es definida positiva y $C_{11} \neq 0$.
Por hipótesis de inducción se puede continuar con la eliminación gaussiana.
Tags: dem met
<!--ID: 1735044171420-->
END
