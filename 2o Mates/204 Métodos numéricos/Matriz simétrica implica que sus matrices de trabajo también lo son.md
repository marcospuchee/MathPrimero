### Contenido Principal

```ad-proposition
Sea
$$A = \left ( \begin{array}{c|c} \alpha & v^T \\ \hline v & C \end{array} \right )$$
simétrica y $\alpha \neq 0$, entonces
$$M_1 A = \left ( \begin{array}{c|c} 1 & 0 \\ \hline -\frac{v}{\alpha} & I_{n-1} \end{array} \right ) \left ( \begin{array}{c|c} \alpha & v^T \\ \hline v & C \end{array} \right ) = \left ( \begin{array}{c|c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha} vv^T  \end{array} \right ) = A^{(1)},$$
y la matriz de trabajo $C- \frac{1}{\alpha}vv^T$ es también simétrica.
```

```ad-proof
Lo vemos por inducción sobre la dimensión de $A$.

**Caso base: $n = 1$.**
$A = (a_{11}) = 11 \cdot a_{11} = L \cdot U$.

**Hipótesis de inducción.**
Supongamos el resultado cierto para $n-1$. Como $A = A^T$, $v=w$ y $C = C^T$. Como $\alpha \neq 0$, aplicamos la eliminación gaussiana:
$$M_1 A = \left ( \begin{array}{c | c} 1 & 0 \\ \hline - \frac{v}{\alpha} & I_{n-1} \end{array} \right ) = \left ( \begin{array}{c | c} \alpha & v^T \\ \hline v & C \end{array} \right ) = \left ( \begin{array}{c | c} \alpha & v^T \\ \hline 0 & - \frac{1}{\alpha} vv^T + C \end{array} \right ).$$
Veamos que $-\frac{1}{\alpha}vv^T + C$ es simétrica:
$$(- \frac{1}{\alpha}vv^T + C)^T = -\frac{1}{\alpha}(vv^T)+C^T = -\frac{1}{\alpha}(v^T)^T v^T + C = -\frac{1}{\alpha}vv^T + C.$$
Por hipótesis de inducción se sigue que el resto lo son.
```

**Tema:** [[Descomposición LU#3. Matrices especiales y propiedades de la descomposición LU.]]

---
### Anki

START
Respuesta anidada
Sea
$$A = \left ( \begin{array}{c|c} \alpha & v^T \\ \hline v & C \end{array} \right )$$
{{c1::simétrica}} y $\alpha \neq 0$, entonces
$$M_1 A = \left ( \begin{array}{c|c} 1 & 0 \\ \hline -\frac{v}{\alpha} & I_{n-1} \end{array} \right ) \left ( \begin{array}{c|c} \alpha & v^T \\ \hline v & C \end{array} \right ) = \left ( \begin{array}{c|c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha} vv^T  \end{array} \right ) = A^{(1)},$$
y la matriz de trabajo $C- \frac{1}{\alpha}vv^T$ es {{c2::también simétrica}}.
Tags: met
<!--ID: 1735044171414-->
END

START
Básico
Anverso: Demostración de que sea
$$A = \left ( \begin{array}{c|c} \alpha & v^T \\ \hline v & C \end{array} \right )$$
simétrica y $\alpha \neq 0$, entonces
$$M_1 A = \left ( \begin{array}{c|c} 1 & 0 \\ \hline -\frac{v}{\alpha} & I_{n-1} \end{array} \right ) \left ( \begin{array}{c|c} \alpha & v^T \\ \hline v & C \end{array} \right ) = \left ( \begin{array}{c|c} \alpha & v^T \\ \hline 0 & C - \frac{1}{\alpha} vv^T  \end{array} \right ) = A^{(1)},$$
y la matriz de trabajo $C- \frac{1}{\alpha}vv^T$ es también simétrica.
Reverso: Lo vemos por inducción sobre la dimensión de $A$.

**Caso base: $n = 1$.**
$A = (a_{11}) = 11 \cdot a_{11} = L \cdot U$.

**Hipótesis de inducción.**
Supongamos el resultado cierto para $n-1$. Como $A = A^T$, $v=w$ y $C = C^T$. Como $\alpha \neq 0$, aplicamos la eliminación gaussiana:
$$M_1 A = \left ( \begin{array}{c | c} 1 & 0 \\ \hline - \frac{v}{\alpha} & I_{n-1} \end{array} \right ) = \left ( \begin{array}{c | c} \alpha & v^T \\ \hline v & C \end{array} \right ) = \left ( \begin{array}{c | c} \alpha & v^T \\ \hline 0 & - \frac{1}{\alpha} vv^T + C \end{array} \right ).$$
Veamos que $-\frac{1}{\alpha}vv^T + C$ es simétrica:
$$(- \frac{1}{\alpha}vv^T + C)^T = -\frac{1}{\alpha}(vv^T)+C^T = -\frac{1}{\alpha}(v^T)^T v^T + C = -\frac{1}{\alpha}vv^T + C.$$
Por hipótesis de inducción se sigue que el resto lo son.
Tags: dem met
<!--ID: 1735044171418-->
END
