### Contenido Principal

```ad-proposition
Consideremos un problema de minimización genérico $$\begin{array}{c c l}
(P) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & x \in \mathcal F.
\end{array}$$ Sea $\{\mathcal F_i \}_{i = 1}^k$ una partición de $\mathcal F \subseteq \mathbb R^n$ y definamos los problemas $$\begin{array}{c c l}
(P_i) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & x \in \mathcal F_i,
\end{array}$$ para $i = 1, \dots, k$. Entonces se cumple que $$v(P) = \min \limits_{i = 1, \dots, k} \{v(P_i) \}.$$ Además, si $x^* \in \mathbb R^n$ es una solución óptima de $(P_{i_0})$, con $i_0 \in \textrm{argmin}_{i = 1, \dots, k} \{v(P_i) \}$, entonces $x^*$ es una solución óptima de $(P)$.
```

```ad-proof
*Ejercicio.*
```

---

```ad-cor
title: Corollarium
En el mismo contexto, sean $\underline z_i$ y $\overline z_i$ cotas inferior y superior, respectivamente del problema $(P_i)$; es decir $$\underline z_i \le v(P_i) \le \overline z_i, \quad \forall i = 1, \dots, k.$$ Entonces se cumple que $$\min \limits_{i = 1, \dots, k} \{\underline z_i \} \le v(P) \le \min \limits_{i = 1, \dots, k} \{\overline z_i \}.$$
```

```ad-note
En el caso de maximizar, las conclusiones son válidas pero tomando máximos, es decir,
$$\begin{array}{r} v(P) = \max \limits_{i = 1, \dots ,k} \{v(P_i) \}, \\ \max \limits_{i = 1, \dots, k} \{\underline z_i \} \le v(P) \le \max \limits_{i = 1, \dots ,k} \{\overline z_i \}. \end{array}$$
```

**Tema:** [[Métodos de PLE#2. Algoritmo de Branch & Bound.]]

**Definiciones referenciadas:** [[Partición de un conjunto]], [[Valor de un problema]]
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Solución óptima de un problema por particiones
Reverso: Consideremos un problema de minimización genérico $$\begin{array}{c c l}
(P) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & x \in \mathcal F.
\end{array}$$ Sea $\{\mathcal F_i \}_{i = 1}^k$ una partición de $\mathcal F \subseteq \mathbb R^n$ y definamos los problemas $$\begin{array}{c c l}
(P_i) & \textrm{Min} & c^Tx \\
& \textrm{s.a.} & x \in \mathcal F_i,
\end{array}$$ para $i = 1, \dots, k$. Entonces se cumple que $$v(P) = \min \limits_{i = 1, \dots, k} \{v(P_i) \}.$$ Además, si $x^* \in \mathbb R^n$ es una solución óptima de $(P_{i_0})$, con $i_0 \in \textrm{argmin}_{i = 1, \dots, k} \{v(P_i) \}$, entonces $x^*$ es una solución óptima de $(P)$.
Tags: prm
<!--ID: 1735044171493-->
END

START
Básico
Anverso: Cotas del valor de un problema solucionado por particiones
Reverso: En el mismo contexto, sean $\underline z_i$ y $\overline z_i$ cotas inferior y superior, respectivamente del problema $(P_i)$; es decir $$\underline z_i \le v(P_i) \le \overline z_i, \quad \forall i = 1, \dots, k.$$ Entonces se cumple que $$\min \limits_{i = 1, \dots, k} \{\underline z_i \} \le v(P) \le \min \limits_{i = 1, \dots, k} \{\overline z_i \}.$$
En el caso de maximizar, las conclusiones son válidas pero tomando máximos, es decir,
$$\begin{array}{r} v(P) = \max \limits_{i = 1, \dots ,k} \{v(P_i) \}, \\ \max \limits_{i = 1, \dots, k} \{\underline z_i \} \le v(P) \le \max \limits_{i = 1, \dots ,k} \{\overline z_i \}. \end{array}$$
Tags: prm
<!--ID: 1735044171495-->
END

