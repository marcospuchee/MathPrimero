
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 16:27

```ad-proposition
Sea $(A, V, +)$ un [[espacio afín]] y sean $\mathcal R = \{O, B\}, \mathcal R' = \{O', B'\}$ dos sistemas de referencia cartesianos ([[sistema de referencia cartesiano]]). Sea $A$ la [[matriz cambio de base]] de $B$ a $B'$.

Sea $P \in A$, con $[P]_{\mathcal R} = X \in \mathbb K^n$ y $[P]_{\mathcal R'} = X' \in \mathbb K^n$. Entonces:
$$X' = [O]_{\mathcal R'} + AX.$$
```

```ad-proof
Tenemos:
$$
\begin{eqnarray}
X' &=& [\vec{O'P}]_{B'} = [\vec{O'O} + \vec{OP}]_{B'} = [\vec{O'O}]_{B'} + [\vec{OP}]_{B'} = \\
&=& [\vec{O'O}]_{B'} + A[\vec{OP}]_B = [O]_{\mathcal R'} + AX.
\end{eqnarray}
$$
[[Propiedades del espacio afín]], [[Corolario producto cambio de base por coordenadas de una base]].
```



**Tema:** [[Espacios afines]]
**Corolarios:** [[Matriz afín del cambio de sistema de referencia]]

---
### Anki

START
Básico
Anverso: Cuál es la ecuación de cambio de sistema de referencia?
Reverso: Sea $(A, V, +)$ un [[Espacio afín]] y sean $\mathcal R = \{O, B\}, \mathcal R' = \{O', B'\}$ dos sistemas de referencia cartesianos ([[Sistema de referencia cartesiano]]). Sea $A$ la [[Matriz cambio de base]] de $B$ a $B'$.

Sea $P \in A$, con $[P]_{\mathcal R} = X \in \mathbb K^n$ y $[P]_{\mathcal R'} = X' \in \mathbb K^n$. Entonces:
$$X' = [O]_{\mathcal R'} + AX.$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060761117-->
END

START
Básico
Anverso: Desarrollo de la ecuación de cambio de sistema de referencia.
Reverso: Tenemos:
$$
\begin{eqnarray}
X' &=& [\vec{O'P}]_{B'} = [\vec{O'O} + \vec{OP}]_{B'} = [\vec{O'O}]_{B'} + [\vec{OP}]_{B'} = \\
&=& [\vec{O'O}]_{B'} + A[\vec{OP}]_B = [O]_{\mathcal R'} + AX.
\end{eqnarray}
$$
[[Propiedades del espacio afín]], [[Corolario producto cambio de base por coordenadas de una base]].
Tags: demostración ÁlgebraI
<!--ID: 1714060761142-->
END