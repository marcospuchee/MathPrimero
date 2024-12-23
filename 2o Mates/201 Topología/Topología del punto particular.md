### Contenido principal

```ad-Formal
Dado un  conjunto $X$, $$\mathcal T_p = \{S \subseteq X : p \in S \} \cup \emptyset.$$
```

```ad-note
**Resumen del estudio de $(X, \mathcal T_p)$**.
- $\mathcal T_p = \{S \cup \{p\} : S \subseteq X \textrm{\\} \{p\} \}$.
- **Base de entornos:** $\mathcal B(x) = \{ \{ x,p \} \}$.
- **1AN**: sí.
- **Hausdorff:** no.
- **Base de abiertos:** $\mathcal B = \{\{ p,x\} : x \in X\}$.
- **2AN:** no.
- **Separable:** sí.
- **Conexo:** sí.
- **Conexo por arcos:** sí.
```

**Tema:** [[201 Topología#Topologías estudiadas.]]

---
### Estudio.

```ad-note
Observemos que si $X = \{p\}$, entonces $\mathcal T_p = \mathcal T_D = \mathcal T_T$. Luego estudiaremos el caso en que $\{p \} \subsetneq X$.
```
##### Topología
Vamos a demostrar que $\mathcal T_p$ sea una topología:
1. $p \in X \implies X \in \mathcal T_p$, y $\emptyset \in \mathcal T_p$, por definición.
2. Dados $A,B \in \mathcal T_p$, entonces $p \in A$, y $p \in B$ $\implies$ $p \in A \cap B$. Luego $A \cap B \in \mathcal T_p$.
3. Dados $\{A_i\}_{i \in I}$ tales que $A_i \in \mathcal T_p$, $\forall i \in I$. Entonces, $p \in A_i$, $\forall i \in I$, luego está claro que $p \in \bigcup_{i \in I} A_i \in \mathcal T_p$.
Así, $\mathcal T_p$ es una topología.

##### Abiertos
Notemos que $\mathcal T_p = \{S \cup \{p\} : S \subseteq X \}$.

##### Bases de entornos
Veamos que $\forall x \in X$, $\mathcal B(x) = \{\{x,p\}\}$ es una base de entornos:
1. Dado que $\{x,p\} \in \mathcal T_p$, $\{x,p\}$ es entorno de todos sus puntos. En particular, de $x$.
2. Sea $U \in \mathcal E(x)$, entonces $\exists A \in \mathcal T_p$ tal que $x \in A \subseteq U$. Por definición de abierto, $p \in A$, luego $\{x,p\} \subseteq A \subseteq U$.
Así, $\mathcal B(x) = \{ \{ x,p \} \}$ es base de entornos.

##### 1AN
$\mathcal B(x) = \{ \{x,p \} \}$ es base de entornos numerable. Luego está claro que es 1AN.

##### Hausdorff
No es Hausdorff porque dados $x,y \in X$, $\{x,p\} \in \mathcal B(x)$, $\{y,p\} \in \mathcal B(y)$, entonces $\{x,p\} \cap \{y,p\} = \{p\}$.

##### Base de abiertos
Veamos que $\mathcal B = \{\{p, x\} : x \in X \}$ es base de abiertos. Sea $A \in \mathcal T_p$, tenemos que ver que $\forall x \in A$, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A$.
Dado $x \in A$, como $p \in A$ por definición, entonces $\{x,p\} \subseteq A$.
Luego $\mathcal B = \{\{ p,x\} : x \in X\}$ es base de abiertos.

##### 2AN
Si $X$ es numerable, entonces $\mathcal B = \{\{p,x\} : x \in X \}$ es numerable.

Supongamos que $X$ es no numerable, entonces debemos encontrar $\mathcal B' \subseteq \mathcal B$ base de abiertos numerable. Supongamos por reducción al absurdo que $\mathcal B' \subseteq \mathcal B$ es base de abiertos numerable. Entonces, $\exists \{x,p\} \in \mathcal B$ tal que $\{x,p\} \notin \mathcal B'$. En particular, para este $\{x,p\} \in \mathcal T_p$, y para $x \in \{x,p\}$, $\nexists B \in \mathcal B$ tal que $x \in B \subseteq \{x,p\}$. Hemos llegado a una contradicción, por lo que $\mathcal B'$ no puede ser base de abiertos numerable.
Luego si $X$ es no numerable, entonces $(X, \mathcal T_p)$ no puede ser 2AN.

##### Separable
Está claro que $\{p\}$ es numerable y denso, porque $\forall \emptyset \neq A \in \mathcal T_p$, se cumple que $A \cap \{p\} = \{p\}$. Por tanto, $(X, \mathcal T_p)$ es separable.

##### Conexo
Supongamos por reducción al absurdo que $\exists X \neq A \in \mathcal T_p$ tal que $A^c \in \mathcal T_p$. Entonces, $p \in A$ y $p \in A^c$, lo cual es una contradicción. Por tanto, $(X, \mathcal T_p)$ es conexo.

##### Conexo por arcos
Dado $x \in X$, intentemos encontrar un arco $\sigma$ de $x$ a $p$. Es decir, tenemos que encontrar $\sigma:[0,1] \longrightarrow X$ continua tal que $\sigma(0) = x$ y $\sigma(1) = p$. Podemos definir: $$\sigma(t) := \left \{ \begin{array}{l l} x, & t \in [0,1[, \\ p, & t = 1. \end{array} \right .$$ veamos si $\sigma$ es continua. Sabemos que $\forall A \in \mathcal T_p$, $\sigma^{-1}(A) \in \mathcal T_u$. Distinguimos casos:
- $p \notin A$. Entonces, $A = \emptyset$, luego $\sigma^{-1}(A) = \emptyset \in \mathcal T_u$:
- $p \in A$. Entonces, $\sigma^{-1}(A) = [0,1] \in \mathcal T_u$ restringido a $[0,1]$ (es el total).
Por tanto, $\sigma$ es continua, y $(X, \mathcal T_p)$ es conexo por arcos.
