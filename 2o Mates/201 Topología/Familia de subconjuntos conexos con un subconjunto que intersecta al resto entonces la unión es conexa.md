### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ espacio topológico, $\{H_i \}_{i \in I}$ familia de subconjuntos conexos tales que $\exists i_0$ tal que $H_i \cap H_{i_0} \neq \emptyset$, $\forall i \in I$. Entonces, $H = \bigcup_{i \in I} H_i$ es conexo.
```

```ad-proof
Sean $A, B \in \mathcal T_H$ tales que $A \cup B = H$ y $A \cap B = \emptyset$. Si demostramos que o bien $A = \emptyset$, o bien $B = \emptyset$, entonces $H$ será conexo.

Para ello, como $A,B$ son abiertos, $\exists A',B' \in \mathcal T$ tales que $A = A' \cap H$ y $B = B' \cap H$. Notemos que $\forall i \in I$, se cumple que $A' \cap H_i$, $B' \cap H_i \in \mathcal T_{H_i}$, y además, $A' \cap H_i = A \cap H_i$, y $B' \cap H_i = B \cap H_i$. Notemos que,
$$\begin{array}{l}
(A' \cap H_i) \cap (B' \cap H_i) = (A \cap B) \cap H_i = \emptyset \\
(A' \cap H_i) \cup (B' \cap H_i) = (A \cup B) \cap H_i = H_i,
\end{array}$$
sin embargo, $H_i$ es conexo, luego o bien $A' \cap H_i = \emptyset$, o bien $B' \cap H_i = \emptyset$. Es decir, o bien $H_i \subseteq B'$, o bien $H_i \subseteq A'$.

Podemos suponer sin pérdida de generalidad que $H_{i_0} \subseteq A'$. Como $\forall i \in I$, $H_i \cap H_{i_0} \neq \emptyset$, entonces $H_i \subseteq A'$, $\forall i \in I$, esto es, $H \subseteq A'$, luego $H \subseteq A$. Por lo tanto, $B = \emptyset$.

Así, $H$ es conexo.
```

**Tema:** [[Conexión#2. Subespacios conexos de $( mathbb R, mathcal T_u)$.]]

**Definiciones referenciadas:**
**Resultados referenciados:**

---
### Corolarios.

```ad-cor
Si $\{H_i\}_{i \in I}$ es una familia de conexos tales que $\bigcap_{i \in I} H_i \neq \emptyset$, entonces $\bigcup_{i \in I} H_i$ es conexo.
```

```ad-cor
title: Corollarium
En particular, dados $H_1, H_2$ conexos tales que $H_1 \cap H_2 \neq \emptyset$, entonces $H_1 \cup H_2$ es conexo.
```

**Tema:** [[Conexión#2. Subespacios conexos de $( mathbb R, mathcal T_u)$.]]

**Definiciones referenciadas:** [Espacio topológico conexo](Espacio topológico disconexo)

---
### Anki

START
Respuesta anidada
Sean $(X, \mathcal T)$ espacio topológico, $\{H_i \}_{i \in I}$ familia de subconjuntos conexos tales que {{c1::$\exists i_0$}} tal que {{c1::$H_i \cap H_{i_0} \neq \emptyset$, $\forall i \in I$.}} Entonces, {{c3::$H = \bigcup_{i \in I} H_i$ es conexo}}.
Tags: top
<!--ID: 1733051328736-->
END

START
Básico
Anverso: Demostración de que 
Reverso: Sean $A, B \in \mathcal T_H$ tales que $A \cup B = H$ y $A \cap B = \emptyset$. Si demostramos que o bien $A = \emptyset$, o bien $B = \emptyset$, entonces $H$ será conexo.

Para ello, como $A,B$ son abiertos, $\exists A',B' \in \mathcal T$ tales que $A = A' \cap H$ y $B = B' \cap H$. Notemos que $\forall i \in I$, se cumple que $A' \cap H_i$, $B' \cap H_i \in \mathcal T_{H_i}$, y además, $A' \cap H_i = A \cap H_i$, y $B' \cap H_i = B \cap H_i$. Notemos que,
$$\begin{array}{l}
(A' \cap H_i) \cap (B' \cap H_i) = (A \cap B) \cap H_i = \emptyset \\
(A' \cap H_i) \cup (B' \cap H_i) = (A \cup B) \cap H_i = H_i,
\end{array}$$
sin embargo, $H_i$ es conexo, luego o bien $A' \cap H_i = \emptyset$, o bien $B' \cap H_i = \emptyset$. Es decir, o bien $H_i \subseteq B'$, o bien $H_i \subseteq A'$.

Podemos suponer sin pérdida de generalidad que $H_{i_0} \subseteq A'$. Como $\forall i \in I$, $H_i \cap H_{i_0} \neq \emptyset$, entonces $H_i \subseteq A'$, $\forall i \in I$, esto es, $H \subseteq A'$, luego $H \subseteq A$. Por lo tanto, $B = \emptyset$.

Así, $H$ es conexo.
Tags: dem top
<!--ID: 1733051328739-->
END

