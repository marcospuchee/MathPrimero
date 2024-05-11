
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-15, 16:48

```ad-lemma
Sea $f: [a,b] \to \mathbb R$ acotada. $P, Q$ particiones de $[a,b]$ ([[Partición de un intervalo]]), donde $P \subset Q$. Entonces,
$$L(f,P) \le L(f, Q) \le U(f, Q) \le U(f,P).$$
[[Suma superior de Riemann]], [[Suma inferior de Riemann]]
```


```ad-proof
Vamos a demostrar que $U(f, Q) \le U(f,P)$, ya que el resto de las desigualdades se demuestra de manera análoga.

Supondremos que $Q = P \cup \{x^* \}$. Veremos que $U(f, Q) \le U(f, P)$. Tenemos que $P = \{x_0, x_1, \dots, x_n \}$ y $x_{j-1} < x^* < x_j$ para algún $j = 0, \dots, n$.

Consideramos: 
$$ \begin{array}
MM_k = \sup \{f(x): x \in [x_{k-1}, x_k] \}; \quad M' = \sup \{f(x): x \in [x_{j-1}, x^*] \}; \\ \quad M'' = \sup \{f(x): x \in [x^*, x_j] \}. \end{array}$$

Entonces,
$$
\begin{eqnarray}
&U(f,P)& = \sum_{k \neq j} M_k (x_k - x_{k-1}) + M_j (x_j - x_{j-1}) \\
&U(f,Q)&= \sum_{k \neq j} M_k (x_k - x_{k-1}) + M'(x^* - x_{j-1}) + M''(x_j - x^*) 
\end{eqnarray}
$$
Dado que el primer sumatorio es igual para ambos, tenemos que ver que $M_j(x_j - x_{j-1}) \le M'(x^* - x_{j-1}) + M''(x_j - x^*)$. 

Sin embargo, si $x \in [x_{j-1}, x^*]$, entonces $f(x) \le M_j$, luego $M' \le M_j$.
Si $x \in [x^*, x_j]$, entonces $f(x) \le M_j$, luego $M'' \le M_j$.

Así,
$$
\begin{eqnarray}
U(f, Q) &=& \sum_{k \neq j} M_k (x_k - x_{k-1}) + M'(x^* - x_{j-1}) + M''(x_j - x^*) \\ &\le& \sum_{k \neq j} M_k (x_k - x_{k-1}) + M_j(x^* - x_{j-1}) + M_j(x_j-x^*) \\ &=& \sum_{k \neq j} M_k (x_k - x_{k-1}) + M_j(x_j - x_{j-1}) = U(f, P).
\end{eqnarray}
$$

```

**Tema:** [[Integración de funciones de una variable real#]]
**Corolarios:** [[Corolario suma inferior de Riemann menor o igual que suma superior de Riemann]]

---
### Anki

START
Básico
Anverso: Qué desigualdades se derivan directamente de las definiciones de suma superior de Riemann y suma inferior de Riemann?
Reverso: Sea $f: [a,b] \to \mathbb R$ acotada. $P, Q$ particiones de $[a,b]$ ([[Partición de un intervalo]]), donde $P \subset Q$. Entonces,
$$L(f,P) \le L(f, Q) \le U(f, Q) \le U(f,P).$$
[[Suma superior de Riemann]], [[Suma inferior de Riemann]]
Tags: proposición/teorema análisisI
<!--ID: 1714669443761-->
END

START
Básico
Anverso: Demostración de que sea $f: [a,b] \to \mathbb R$ acotada. $P, Q$ particiones de $[a,b]$ ([[Partición de un intervalo]]), donde $P \subset Q$. Entonces,
$$L(f,P) \le L(f, Q) \le U(f, Q) \le U(f,P).$$
[[Suma superior de Riemann]], [[Suma inferior de Riemann]]
Reverso: Vamos a demostrar que $U(f, Q) \le U(f,P)$, ya que el resto de las desigualdades se demuestra de manera análoga.

Supondremos que $Q = P \cup \{x^* \}$. Veremos que $U(f, Q) \le U(f, P)$. Tenemos que $P = \{x_0, x_1, \dots, x_n \}$ y $x_{j-1} < x^* < x_j$ para algún $j = 0, \dots, n$.

Consideramos: 
$$ \begin{array}
MM_k = \sup \{f(x): x \in [x_{k-1}, x_k] \}; \quad M' = \sup \{f(x): x \in [x_{j-1}, x^*] \}; \\ \quad M'' = \sup \{f(x): x \in [x^*, x_j] \}. \end{array}$$

Entonces,
$$
\begin{eqnarray}
&U(f,P)& = \sum_{k \neq j} M_k (x_k - x_{k-1}) + M_j (x_j - x_{j-1}) \\
&U(f,Q)&= \sum_{k \neq j} M_k (x_k - x_{k-1}) + M'(x^* - x_{j-1}) + M''(x_j - x^*) 
\end{eqnarray}
$$
Dado que el primer sumatorio es igual para ambos, tenemos que ver que $M_j(x_j - x_{j-1}) \le M'(x^* - x_{j-1}) + M''(x_j - x^*)$. 

Sin embargo, si $x \in [x_{j-1}, x^*]$, entonces $f(x) \le M_j$, luego $M' \le M_j$.
Si $x \in [x^*, x_j]$, entonces $f(x) \le M_j$, luego $M'' \le M_j$.

Así,
$$
\begin{eqnarray}
U(f, Q) &=& \sum_{k \neq j} M_k (x_k - x_{k-1}) + M'(x^* - x_{j-1}) + M''(x_j - x^*) \\ &\le& \sum_{k \neq j} M_k (x_k - x_{k-1}) + M_j(x^* - x_{j-1}) + M_j(x_j-x^*) \\ &=& \sum_{k \neq j} M_k (x_k - x_{k-1}) + M_j(x_j - x_{j-1}) = U(f, P).
\end{eqnarray}
$$

Tags: proposición/teorema análisisI
<!--ID: 1714669443764-->
END
