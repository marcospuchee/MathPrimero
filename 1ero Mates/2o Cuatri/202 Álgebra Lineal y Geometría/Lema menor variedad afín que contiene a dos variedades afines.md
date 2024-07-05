
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 17:01

```ad-lemma
$(A, V, +)$ [[espacio afín]]. Sean $U_P, W_Q \subseteq A$ dos variedades afines ([[variedad afín]]). La variedad $(U+W+ \langle \vec{PQ} \rangle)_P \subseteq A$ es la menor variedad (en el sentido de inclusión de conjuntos) que contiene a $U_P \cup W_Q$. Se escribe $(U+W+\langle \vec{PQ} \rangle)_P = U_P + W_Q$.
```

```ad-proof
Primero veamos que $U_P \cup W_Q \subseteq (U+W+ \langle \vec{PQ} \rangle)_P$. Notemos que: $U \le U+W + \langle \vec{PQ} \rangle$ $\implies U_P \subseteq (U+W + \langle \vec{PQ} \rangle)_P$. Además, $Q = P+ \vec{PQ} \in (U+W+ \langle PQ \rangle)_P$, luego $(U+W+\langle \vec{PQ} \rangle)_P = (U+W+ \langle \vec{PQ} \rangle)_Q$. Por tanto, $W \le U+W + \langle \vec{PQ} \rangle \implies W_Q \subseteq (U+W+\langle \vec{PQ} \rangle)_Q$. Así, $U_P \cup W_Q \subseteq (U+W+ \langle \vec{PQ} \rangle)_P$.

Veamos ahora que si $L \subseteq A$ variedad afín tal que $U_P \cup W_Q \subseteq L$, entonces $(U+W+\langle \vec{PQ} \rangle)_P \subseteq L$. Escribimos $L = Z_R$, donde $Z \le V$ y $R \in A$. Tenemos: $P \in U_P \subseteq U_P \cup W_Q \subseteq L$, y por tanto $L = Z_R = Z_P$. Dado que $U_P \subseteq L = Z_P$, tenemos que $U \le Z$. Análogamente, $W_Q \le L \implies W \le Z$. Además, $Q \in W_Q \subseteq L \implies$ (dado que $P \in L$) $\vec{PQ} \in Z$. Por tanto, $\langle \vec{PQ} \rangle \le Z$.
Por tanto, como tenemos que $U,W,\vec{PQ} \le Z$, entonces $U+W+ \langle \vec{PQ} \rangle \le Z$. Luego $(U+W+\langle \vec{PQ} \rangle)_P \subseteq Z_P = L$.
```

**Tema:** [[Espacios afines]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la menor variedad que contiene a la unión de dos variedades afines?
Reverso: $(A, V, +)$ [[Espacio afín]]. Sean $U_P, W_Q \subseteq A$ dos variedades afines ([[Variedad afín]]). La variedad $(U+W+ \langle \vec{PQ} \rangle)_P \subseteq A$ es la menor variedad (en el sentido de inclusión de conjuntos) que contiene a $U_P \cup W_Q$. Se escribe $(U+W+\langle \vec{PQ} \rangle)_P = U_P + W_Q$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714669443553-->
END

START
Básico
Anverso: Demostración de que sea $(A, V, +)$ [[Espacio afín]]. Sean $U_P, W_Q \subseteq A$ dos variedades afines ([[Variedad afín]]). La variedad $(U+W+ \langle \vec{PQ} \rangle)_P \subseteq A$ es la menor variedad (en el sentido de inclusión de conjuntos) que contiene a $U_P \cup W_Q$. Se escribe $(U+W+\langle \vec{PQ} \rangle)_P = U_P + W_Q$.
Reverso: Primero veamos que $U_P \cup W_Q \subseteq (U+W+ \langle \vec{PQ} \rangle)_P$. Notemos que: $U \le U+W + \langle \vec{PQ} \rangle$ $\implies U_P \subseteq (U+W + \langle \vec{PQ} \rangle)_P$. Además, $Q = P+ \vec{PQ} \in (U+W+ \langle PQ \rangle)_P$, luego $(U+W+\langle \vec{PQ} \rangle)_P = (U+W+ \langle \vec{PQ} \rangle)_Q$. Por tanto, $W \le U+W + \langle \vec{PQ} \rangle \implies W_Q \subseteq (U+W+\langle \vec{PQ} \rangle)_Q$. Así, $U_P \cup W_Q \subseteq (U+W+ \langle \vec{PQ} \rangle)_P$.

Veamos ahora que si $L \subseteq A$ variedad afín tal que $U_P \cup W_Q \subseteq L$, entonces $(U+W+\langle \vec{PQ} \rangle)_P \subseteq L$. Escribimos $L = Z_R$, donde $Z \le V$ y $R \in A$. Tenemos: $P \in U_P \subseteq U_P \cup W_Q \subseteq L$, y por tanto $L = Z_R = Z_P$. Dado que $U_P \subseteq L = Z_P$, tenemos que $U \le Z$. Análogamente, $W_Q \le L \implies W \le Z$. Además, $Q \in W_Q \subseteq L \implies$ (dado que $P \in L$) $\vec{PQ} \in Z$. Por tanto, $\langle \vec{PQ} \rangle \le Z$.
Por tanto, como tenemos que $U,W,\vec{PQ} \le Z$, entonces $U+W+ \langle \vec{PQ} \rangle \le Z$. Luego $(U+W+\langle \vec{PQ} \rangle)_P \subseteq Z_P = L$.
Tags: demostración ÁlgebraI
<!--ID: 1714669443557-->
END