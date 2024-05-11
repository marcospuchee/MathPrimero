
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 16:51

```ad-lemma
Sea $(A, V, +)$ [[espacio afín]], $U_P, W_Q \subseteq A$ variedades afines ([[variedad afín]]). Supongamos que $U_P \cap W_Q \neq \emptyset$, y sea $R \in U_P \cap W_Q$. Entonces, $U_P \cap W_Q = (U \cap W)_R$
```

```ad-proof
$\supseteq$. Tenemos $(U \cap W) \le U \implies (U\cap W)_R \subseteq U_R$, y dado que $R \in U_P$, entonces $U_R = U_P$. Luego $(U \cap W)_P \subseteq U_P$ El mismo argumento implica: $(U \cap W)_R \subseteq W_Q \implies$ $(U \cap W)_R \subseteq U_P \cap W_Q$.

$\subseteq$. Tenemos $U_P \cap W_Q = U_R \cap W_R$, dado que $R \in U_P \cap W_Q$. Sea $X \in U_R \cap W_R$. Entonces $X = R+u = R+w \implies$ $\vec{RX} = u = w \in U \cap W$, donde $u \in U, w \in W$. Así, $X \in (U \cap W)_R$.
```

**Tema:** [[Espacios afines]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $(A, V, +)$ [[espacio afín]], $U_P, W_Q \subseteq A$ variedades afines ([[variedad afín]]). Supongamos que{{c1:: $U_P \cap W_Q \neq \emptyset$, y sea $R \in U_P \cap W_Q$}}. Entonces, {{c2::$U_P \cap W_Q$}} $=$ {{c3::$(U \cap W)_R$}}
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714669443569-->
END

START
Básico
Anverso: Demostración de que sea $(A, V, +)$ [[espacio afín]], $U_P, W_Q \subseteq A$ variedades afines ([[variedad afín]]). Supongamos que $U_P \cap W_Q \neq \emptyset$, y sea $R \in U_P \cap W_Q$. Entonces, $U_P \cap W_Q = (U \cap W)_R$
Reverso: $\supseteq$. Tenemos $(U \cap W) \le U \implies (U\cap W)_R \subseteq U_R$, y dado que $R \in U_P$, entonces $U_R = U_P$. Luego $(U \cap W)_P \subseteq U_P$ El mismo argumento implica: $(U \cap W)_R \subseteq W_Q \implies$ $(U \cap W)_R \subseteq U_P \cap W_Q$.

$\subseteq$. Tenemos $U_P \cap W_Q = U_R \cap W_R$, dado que $R \in U_P \cap W_Q$. Sea $X \in U_R \cap W_R$. Entonces $X = R+u = R+w \implies$ $\vec{RX} = u = w \in U \cap W$, donde $u \in U, w \in W$. Así, $X \in (U \cap W)_R$.
Tags: demostración ÁlgebraI
<!--ID: 1714669443573-->
END

