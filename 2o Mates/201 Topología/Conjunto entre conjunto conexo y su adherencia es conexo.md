### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ espacio topológico, $H \subseteq X$ subespacio conexo. Si $H \subseteq S \subseteq \textrm{ad}(H)$, entonces $S$ conexo.
```

```ad-cor
title: Corollarium
$H \subseteq X$ conexo $\implies$ $\textrm{ad}(H)$ conexo.
```

```ad-proof
Por reducción al absurdo, supongamos que $S$ es disconexo, luego $\exists \emptyset \neq A,B \in \mathcal T_S$ tales que $A \cap B = \emptyset$ y $A \cup B = S$. 

Como $A,B$ son abiertos, $\exists A',B' \in \mathcal T$ tales que $A' \cap S = A$ y $B' \cap S = B$. Entonces, $A \cap H = (A' \cap S) \cap H = A' \cap H$, de la misma forma con $B$, $B \cap H = B' \cap H$.
Por un lado, tenemos que
$$(A' \cap H) \cap (B' \cap H) = (A \cap H ) \cap (B \cap H) = (A \cap B) \cap H = \emptyset.$$
Por otro,
$$(A' \cap H) \cup (B' \cap H) = (A \cap H)\cup(B \cap H) = (A \cup B) \cap H = H.$$
Además, $A' \cap H, B' \cap H \in \mathcal T_H$, luego tenemos una partición de abiertos de $H$. Pero o bien $A' \cap H = \emptyset$ o $B' \cap H = \emptyset$ porque $H$ es conexo.

Supongamos, sin pérdida de generalidad, que $A' \cap H = \emptyset$. Sabemos que $A \neq \emptyset$, luego $\exists x \in A = A' \cap S \subseteq A' \cap \textrm{ad}(H)$, luego $x \in A'$ y $x \in \textrm{ad}(H)$. Dado que $x \in \textrm{ad}(H)$, $\forall E \in \mathcal E(x)$, $E \cap H \neq \emptyset$. Notemos que como $A' \in \mathcal T$, entonces, $A' \in \mathcal E(x)$, luego $A' \cap H \neq \emptyset$ y tenemos una contradicción. Luego $S$ es conexo.
```

**Tema:** [[Conexión#2. Subespacios conexos de $( mathbb R, mathcal T_u)$.]]

**Definiciones referenciadas:** [Espacio topológico conexo](Espacio topológico disconexo), [$\mathcal T_H$](Topología inducida)
**Resultados referenciados:** [[Caracterización de punto de adherencia (base de entornos)]].

---
### Anki

START
Respuesta anidada
Sean $(X, \mathcal T)$ espacio topológico, $H \subseteq X$ subespacio conexo. Si {{c1::$H$}} $\subseteq$ {{c2::$S$}} $\subseteq$ {{c3::$\textrm{ad}(H)$}}, entonces {{c4::$S$ conexo}}.
Tags: top 
<!--ID: 1733051328741-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ espacio topológico, $H \subseteq X$ subespacio conexo. Si $H \subseteq S \subseteq \textrm{ad}(H)$, entonces $S$ conexo.
Reverso: Por reducción al absurdo, supongamos que $S$ es disconexo, luego $\exists \emptyset \neq A,B \in \mathcal T_S$ tales que $A \cap B = \emptyset$ y $A \cup B = S$. 

Como $A,B$ son abiertos, $\exists A',B' \in \mathcal T$ tales que $A' \cap S = A$ y $B' \cap S = B$. Entonces, $A \cap H = (A' \cap S) \cap H = A' \cap H$, de la misma forma con $B$, $B \cap H = B' \cap H$.
Por un lado, tenemos que
$$(A' \cap H) \cap (B' \cap H) = (A \cap H ) \cap (B \cap H) = (A \cap B) \cap H = \emptyset.$$
Por otro,
$$(A' \cap H) \cup (B' \cap H) = (A \cap H)\cup(B \cap H) = (A \cup B) \cap H = H.$$
Además, $A' \cap H, B' \cap H \in \mathcal T_H$, luego tenemos una partición de abiertos de $H$. Pero o bien $A' \cap H = \emptyset$ o $B' \cap H = \emptyset$ porque $H$ es conexo.

Supongamos, sin pérdida de generalidad, que $A' \cap H = \emptyset$. Sabemos que $A \neq \emptyset$, luego $\exists x \in A = A' \cap S \subseteq A' \cap \textrm{ad}(H)$, luego $x \in A'$ y $x \in \textrm{ad}(H)$. Dado que $x \in \textrm{ad}(H)$, $\forall E \in \mathcal E(x)$, $E \cap H \neq \emptyset$. Notemos que como $A' \in \mathcal T$, entonces, $A' \in \mathcal E(x)$, luego $A' \cap H \neq \emptyset$ y tenemos una contradicción. Luego $S$ es conexo.
Tags: dem top
<!--ID: 1733051328744-->
END

