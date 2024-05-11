
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-20, 17:35

```ad-theorem
Sea, $n \in \mathbb N$ con $p_1^{\alpha_1} p_2^{\alpha_2} \dots p_k^{\alpha_k}$ su descomposición en factores primos y $\Phi (n)$ la [[función de Euler]]. Entonces,
$$\Phi (n) = n \prod_{i = 1}^n \left (1 - \frac{1}{p_i} \right ).$$
```

```ad-proof
Lo que tenemos que calcular es el cardinal del conjunto de número naturales positivos y menores o igual que $n$ que son coprimos con $n$, o equivalentemente, el cardinal del conjunto de número naturales positivos y menores o igual que $n$ que no son divisibiles por ninguno de los número primos $p_1, p_2, \dots, p_k$.

Teniendo en cuenta que si $a|b$ con $a,b \in \mathbb N$, el número de múltiplos de $a$ que no exceden a $b$ es el cociente $\frac{a}{b}$, así, pues, para aplicar el [[principio de inclusión-exclusión]], consideramos los siguientes conjuntos: $X = \{1,2, \dots, n \}$ y, $\forall i = 1, 2, \dots, k$,
$$A_i = \{x \in X : p_i | x \} = \{\textrm{Conjunto de múltiplos de } p_i \textrm{ que no exceden a } n \}.$$
Lo que tenemos que calcular es
$$|X - \cup_{i = 1}^k A_i|.$$
Claramente tenemos que
$$|X| = n, \quad |A_i| = \frac{n}{p_i}, \quad |A_i \cap A_j| = \frac{n}{p_i p_j}, \quad |A_i \cap A_j \cap A_l| = \frac{n}{p_ip_lp_j} \dots$$
ya que, por ejemplo, para $i \neq j$, $p_i$ y $p_j$ son primos, y los múltiplos de ambos son los que sean múltiplos del producto $p_i · p_j$. De la misma manera, $|A_i \cap A_j \cap A_l| = \frac{n}{p_i p_j p_l}$ para $i \neq j \neq l$, y así sucesivamente. Ahora aplicando el [[principio de inclusión-exclusión]], tenemos
$$
\begin{eqnarray}
|X - \cup_{i = 1}^k A_i| &=& n- \left (\frac{n}{p_1} + \frac{n}{p_2} + \dots + \frac{n}{p_k} - \frac{n}{p_1 p_2} - \dots - \frac{n}{p_{k-1}p_k} + \dots  + (-1)^{k-1} \frac{n}{p_1 p_2 \dots p_k} \right ) \\
&=& n \left ( 1- \frac{1}{p_1} - \frac{1}{p_2} - \dots - \frac{1}{p_k} + \frac{1}{p_1 p_2} + \dots + \frac{1}{p_{k-1} p_k} + \dots + (-1)^k \frac{1}{p_1 p_2 \dots p_k} \right ) \\
&=& n \left ( 1 - \frac{1}{p_1} \right ) \left ( 1 - \frac{1}{p_2} \right ) \dots \left ( 1 - \frac{1}{p_l} \right ) .
\end{eqnarray}
$$
```

**Tema:** [[Aritmética modular#5. Primer teorema de Fermat - Teorema de Euler]]
**Demostrado por:** [[Principio de inclusión-exclusión]]
**Consecuencias:**

---
### Anki
