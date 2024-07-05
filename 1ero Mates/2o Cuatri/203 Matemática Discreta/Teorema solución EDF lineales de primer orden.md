
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-05, 17:24

```ad-theorem
La solución de la [[Ecuación en diferencias finitas lineal de coeficientes constantes]] de primer orden
$$a_{n+1} = \lambda a_n + \psi (n)$$
con la condición inicial $a_0 = \alpha_0$, está dada por:
$$a_n = \alpha_0 \lambda^n + \sum_{i = 0}^{n-1} \psi (i) \lambda^{n-i-1}.$$
```


```ad-proof
Sea $(s_n)^{+\infty}_{n=1}$ una sucesión cuyo primer término es $\alpha_0$ y que para $n \ge 1$, los términos valen
$$s_n = \alpha_0 \lambda^n + \sum^{n-1}_{i = 0} \psi (i) \lambda^{n-i-1}.$$
Esta sucesión cumple la relación de recurrencia. En efecto,
$$
\begin{eqnarray}
\lambda s_n + \psi (n) &=& \lambda \left ( \alpha_0 \lambda^n + \sum_{i = 0}^{n-1} \psi (i) \lambda^{n-1-i} \right ) + \psi (n) \\
&=& \alpha_0 \lambda^{n+1} +\sum_{i = 0}^{n-1} \psi (i) \lambda^{n-i} + \psi(n) \\
&=& \alpha_0 \lambda^{n+1} + \sum_{i = 0}^{n-1} \psi(i) \lambda^{n-1} + \psi (n) \lambda^{n-n} \\
&=& \alpha_0 \lambda^{n+1} + \sum_{i = 0}^n \psi (i) \lambda^{n-i} = s_{n+1}.
\end{eqnarray}
$$
Para acabar la demostración, sea $a_n$ una sucesión que cumpla la [[Ley de recurrencia]] y que $a_0 = \alpha_0$. Es suficiente con probar que $a_1 = s_1$ para concluir que $a_n = s_n$, $\forall n \in \mathbb N$, pero esto es trivial porque
$$a_1 = a_0 \lambda + \psi (0) = \alpha_0 \lambda + \sum_{i = 0}^0 \psi (i) \lambda^{0-i} = \alpha_0 \lambda^n + \psi(0) \lambda^{0-0} = \alpha_0 \lambda^n + \psi (0) = s_1.$$
```

**Tema:** [[Ecuaciones de recurrencia#5. Ecuaciones en diferencias finitas]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que soluciona ecuaciones en diferencias finitas lineales de coeficientes constantes de primer orden?
Reverso: La solución de la [[Ecuación en diferencias finitas lineal de coeficientes constantes]] de primer orden
$$a_{n+1} = \lambda a_n + \psi (n)$$
con la condición inicial $a_0 = \alpha_0$, está dada por:
$$a_n = \alpha_0 \lambda^n + \sum_{i = 0}^{n-1} \psi (i) \lambda^{n-i-1}.$$
Tags: proposición/teorema MatDiscreta
<!--ID: 1709746655855-->
END

START
Básico
Anverso: Demostración del teorema que soluciona ecuaciones en diferencias finitas lineales de coeficientes constantes de primer orden
Reverso: Sea $(s_n)^{+\infty}_{n=1}$ una sucesión cuyo primer término es $\alpha_0$ y que para $n \ge 1$, los términos valen
$$s_n = \alpha_0 \lambda^n + \sum^{n-1}_{i = 0} \psi (i) \lambda^{n-i-1}.$$
Esta sucesión cumple la relación de recurrencia. En efecto,
$$
\begin{eqnarray}
\lambda s_n + \psi (n) &=& \lambda \left ( \alpha_0 \lambda^n + \sum_{i = 0}^{n-1} \psi (i) \lambda^{n-1-i} \right ) + \psi (n) \\
&=& \alpha_0 \lambda^{n+1} +\sum_{i = 0}^{n-1} \psi (i) \lambda^{n-i} + \psi(n) \\
&=& \alpha_0 \lambda^{n+1} + \sum_{i = 0}^{n-1} \psi(i) \lambda^{n-1} + \psi (n) \lambda^{n-n} \\
&=& \alpha_0 \lambda^{n+1} + \sum_{i = 0}^n \psi (i) \lambda^{n-i} = s_{n+1}.
\end{eqnarray}
$$
Para acabar la demostración, sea $a_n$ una sucesión que cumpla la [[Ley de recurrencia]] y que $a_0 = \alpha_0$. Es suficiente con probar que $a_1 = s_1$ para concluir que $a_n = s_n$, $\forall n \in \mathbb N$, pero esto es trivial porque
$$a_1 = a_0 \lambda + \psi (0) = \alpha_0 \lambda + \sum_{i = 0}^0 \psi (i) \lambda^{0-i} = \alpha_0 \lambda^n + \psi(0) \lambda^{0-0} = \alpha_0 \lambda^n + \psi (0) = s_1.$$
Tags: demostración MatDiscreta
<!--ID: 1709746655861-->
END