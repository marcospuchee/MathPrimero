### Contenido Principal

```ad-proposition
$1 \textrm{AN}$ es propiedad topológica. Sea $(X, \mathcal T)$ espacio topológico $1 \textrm{AN}$ y $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $(Y, \mathcal T')$ es $1\textrm{AN}$.
```

```ad-proof
Como $(X, \mathcal T)$ es $1\textrm{AN}$, $\forall x \in X$, $\exists B(x) = \{B_n^x : n \in \mathbb N \}$ que es base de entornos numerable.

Sea $y \in Y$, como $f$ biyectiva, $\exists ! x \in X$ tal que $f(x) = y$. Sea $B(y) = \{f(B_n^x) : n \in \mathbb N \}$, comprobemos que es base de entornos:
1. $B_n^x \in \mathcal E(x) \implies \exists A \in \mathcal T$ tal que $x \in A \subseteq B_n^x$, pero como $f^{-1}$ continua, entonces $f(A) \in \mathcal T'$. Luego $y = f(x) \in f(A) \subseteq f(B_n^x)$. Por tanto, $f(B_n^x) \in \mathcal E(y)$.
2. Sea $U \in \mathcal E(y)$. Como $f$ continua, $\exists V \in \mathcal E(x)$ tal que $f(V) \subseteq U$, pero como $\mathcal B(x)$ es base de entornos, $\exists B_n^x \in \mathcal B(x)$ tal que $B_n^x \subseteq V$. Por tanto, $f(B_n^x) \subseteq f(V) \subseteq U$.
```

**Tema:** [[Continuidad#2. Homeomorfismos.]]

**Definiciones referenciadas:** [[Espacio topológico 1 AN]], [[Homeomorfismo]], [[Base de entornos]], [[Entorno]], [[Función continua]]
**Resultados referenciados:** [[Caracterización de continuidad global (antiimagen de abiertos)]]

---
### Anki

START
Básico
Anverso: Demostración de que $1 \textrm{AN}$ es propiedad topológica. Sea $(X, \mathcal T)$ espacio topológico $1 \textrm{AN}$ y $f: (X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $(Y, \mathcal T')$ es $1\textrm{AN}$.
Reverso: Como $(X, \mathcal T)$ es $1\textrm{AN}$, $\forall x \in X$, $\exists B(x) = \{B_n^x : n \in \mathbb N \}$ que es base de entornos numerable.

Sea $y \in Y$, como $f$ biyectiva, $\exists ! x \in X$ tal que $f(x) = y$. Sea $B(y) = \{f(B_n^x) : n \in \mathbb N \}$, comprobemos que es base de entornos:
1. $B_n^x \in \mathcal E(x) \implies \exists A \in \mathcal T$ tal que $x \in A \subseteq B_n^x$, pero como $f^{-1}$ continua, entonces $f(A) \in \mathcal T'$. Luego $y = f(x) \in f(A) \subseteq f(B_n^x)$. Por tanto, $f(B_n^x) \in \mathcal E(y)$.
2. Sea $U \in \mathcal E(y)$. Como $f$ continua, $\exists V \in \mathcal E(x)$ tal que $f(V) \subseteq U$, pero como $\mathcal B(x)$ es base de entornos, $\exists B_n^x \in \mathcal B(x)$ tal que $B_n^x \subseteq V$. Por tanto, $f(B_n^x) \subseteq f(V) \subseteq U$.
Tags: dem top
<!--ID: 1731446305413-->
END
