
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-25, 11:41

Sean $a,b \in \mathbb R$ con $a<b, c \in ]a,b[, f,g: ]a,b[ \to \mathbb R$. $f,g$ derivables en $c$ ([[Función derivable en un punto]]). Entonces

```ad-theorem
1. $f+g$ derivable en $c \implies (f+g)'(c) = f'(c) + g'(c)$.
2. $fg$ derivable en $c \implies (f·g)'(c) = f'(c)g(c) + f(c) g'(c)$.
3. $0 \neq g(x), \forall x \in ]a,b[$. $f/g$ derivable en $c \implies$ 
$$(f/g)'(c) = \frac{f'(c)g(c) - f(c)g'(c)}{g(c)^2}$$
```

```ad-proof
**(i).**
$$\frac{(f+g)(x) - (f+g)(c)}{x-c} = \frac{f(x)-f(c)}{x-c} + \frac{g(x) - g(c)}{x-c}.$$

**(ii).**
$$
\begin{eqnarray}
\frac{(fg)(x) - (fg)(c)}{x-c} &=& \frac{f(x)g(x) - f(x)g(c) + f(x)g(c) - f(c)g(c)}{x-c} \\ &=& f(x) \frac{g(x)-g(c)}{x-c} + g(c) \frac{f(x) - f(c)}{x-c}
\end{eqnarray}
$$



```


**Tema:** [[Funciones derivables#2. Cálculo de derivadas]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de las fórmulas de derivación entre funciones reales?
Reverso: Sean $a,b \in \mathbb R$ con $a<b, c \in ]a,b[, f,g: ]a,b[ \to \mathbb R$. $f,g$ derivables en $c$ ([[Función derivable en un punto]]). Entonces,
1. $f+g$ derivable en $c \implies (f+g)'(c) = f'(c) + g'(c)$.
2. $fg$ derivable en $c \implies (f·g)'(c) = f'(c)g(c) + f(c) g'(c)$.
3. $0 \neq g(x), \forall x \in ]a,b[$. $f/g$ derivable en $c \implies$ 
$$(f/g)'(c) = \frac{f'(c)g(c) - f(c)g'(c)}{g(c)^2}$$
Tags: proposición/teorema análisisI
<!--ID: 1708973800325-->
END

START
Básico
Anverso: Demostración de las fórmulas de derivación entre funciones reales
Reverso: **(i).**
$$\frac{(f+g)(x) - (f+g)(c)}{x-c} = \frac{f(x)-f(c)}{x-c} + \frac{g(x) - g(c)}{x-c}.$$

**(ii).**
$$
\begin{eqnarray}
\frac{(fg)(x) - (fg)(c)}{x-c} &=& \frac{f(x)g(x) - f(x)g(c) + f(x)g(c) - f(c)g(c)}{x-c} \\ &=& f(x) \frac{g(x)-g(c)}{x-c} + g(c) \frac{f(x) - f(c)}{x-c}
\end{eqnarray}
$$
Tags: demostración análisisI
<!--ID: 1708973800332-->
END