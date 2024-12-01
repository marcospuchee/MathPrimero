### Contenido Principal

```ad-lemma
Sea $C$ un conexo y $C_x$ un componente conexo tal que $C \cap C_x \neq \emptyset$. Entonces, $C \subseteq C_x$.
```

```ad-proof
Como $C, C_x$ son conexo y $C_x \cap C \neq \emptyset$, entonces $C \cup C_x$ es conexo. Como $x \in C \cup C_x$, entonces, por definición, $C \cup C_x \subseteq C_x$, luego $C \subseteq C_x$.
```

**Tema:** [[Conexión#3. Componentes conexos.]]

**Definiciones referenciadas:** [Espacio topológico conexo](Espacio topológico disconexo), [$C_x$](Componente conexo)
**Resultados referenciados:** [$H_1, H_2$ conexos $: H_1 \cap H_2 \neq \emptyset \implies H_1 \cup H_2$ conexo](Familia de subconjuntos conexos con un subconjunto que intersecta al resto entonces la unión es conexa)

---
### Corolarios.

```ad-cor
title: Corollarium
$\forall C$ subespacio conexo, $\exists C_x$ componente conexo tal que $C \subseteq C_x$.
```

```ad-cor
title: Corollarium
$$y \in C_x \implies C_x = C_y.$$
```

```ad-proof
Dado que $y \in C_x$, $y \in C_y$, se tiene que $C_x \cap C_y \neq \emptyset$. Por tanto, por el lema anterior, tenemos tanto que $C_x \subseteq C_y$, como $C_y \subseteq C_x$. Entonces, $C_x = C_y$.
```



---
### Anki

START
Respuesta anidada
Sea $C$ un conexo y $C_x$ un componente conexo tal que {{c1::$C \cap C_x \neq \emptyset$}}. Entonces, {{c2::$C \subseteq C_x$}}.
Tags: top
<!--ID: 1733051328746-->
END

START
Básico
Anverso: Demostración de que sea $C$ un conexo y $C_x$ un componente conexo tal que $C \cap C_x \neq \emptyset$. Entonces, $C \subseteq C_x$.
Reverso: Como $C, C_x$ son conexo y $C_x \cap C \neq \emptyset$, entonces $C \cup C_x$ es conexo. Como $x \in C \cup C_x$, entonces, por definición, $C \cup C_x \subseteq C_x$, luego $C \subseteq C_x$.
Tags: dem top
<!--ID: 1733051328749-->
END

