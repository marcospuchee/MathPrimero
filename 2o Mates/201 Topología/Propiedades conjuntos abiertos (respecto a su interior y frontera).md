### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ [[espacio topológico]], $S \subseteq X$. Entonces,
1. $\textrm{int}(S) \in \mathcal T$.
2. $\forall A \in \mathcal T$ tal que $A \subseteq S$, entonces $A \subseteq \textrm{int}(S)$.
3. $A \in \mathcal T \iff \textrm{int}(A) = A$.
4. $A \in \mathcal T \iff \textrm{fr}(A) \cap A = \emptyset$.
```

```ad-proof
$(i)$.
$\int(S) = X \textrm{\\} \textrm{ad}(X \textrm{\\} S)$, pero como $\textrm{ad}(X \textrm{\\} S)$ es cerrado, entonces $\textrm{int}(S) \in \mathcal T$.

$(ii)$.
Sea $A \in \mathcal T$ tal que $A \subseteq S$. Sea $x \in A \subseteq S$, entonces $S \in \mathcal E(x)$, así, $x \in \textrm{int}(S)$.

$(iii)$.
$\rightarrow$. Sea $A \in \mathcal T$. Como $A \subseteq A$, por $(ii)$, sabemos que $A \subseteq \textrm{int}(A)$, y como $\textrm{int}(A) \subseteq A$, entonces $A = \textrm{int}(A)$.
$\leftarrow$. $A = \textrm{int}(A)$ implica (por $(i)$) que $A \in \mathcal T$.

$(iv)$.
$\rightarrow$. Como $A \in \mathcal T$, $A = \textrm{int}(A)$, y $\textrm{fr}(A) = \textrm{ad}(A) \textrm{\\} \textrm{int}(A)$, lo que implica que $\textrm{fr}(A) = \textrm{ad}(A) \textrm{\\} A$. Y, por tanto, $\textrm{fr}(A) \cap A = \emptyset$.
$\leftarrow$. $\emptyset = \textrm{fr}(A) \cap A = (\textrm{ad}(A) \textrm{\\} \textrm{int}(A)) \cap A = A \textrm{\\} \textrm{int}(A)$. Así, $A \subseteq \textrm{int}(A)$ implica que $A = \textrm{int}(A)$, luego $A \in \mathcal T$.

```

**Tema:** [[Puntos especiales#3. Puntos interiores.]]

---
### Anki

START
Básico
Anverso: Relación de los conjuntos abiertos con el interior y la frontera
Reverso: Sean $(X, \mathcal T)$ [[Espacio topológico]], $S \subseteq X$. Entonces,
1. $\textrm{int}(S) \in \mathcal T$.
2. $\forall A \in \mathcal T$ tal que $A \subseteq S$, entonces $A \subseteq \textrm{int}(S)$.
3. $A \in \mathcal T \iff \textrm{int}(A) = A$.
4. $A \in \mathcal T \iff \textrm{fr}(A) \cap A = \emptyset$.
Tags: top
<!--ID: 1729160606438-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ [[Espacio topológico]], $S \subseteq X$. Entonces,
1. $\textrm{int}(S) \in \mathcal T$.
2. $\forall A \in \mathcal T$ tal que $A \subseteq S$, entonces $A \subseteq \textrm{int}(S)$.
3. $A \in \mathcal T \iff \textrm{int}(A) = A$.
4. $A \in \mathcal T \iff \textrm{fr}(A) \cap A = \emptyset$.
Reverso:
$(i)$.
$\textrm{int}(S) = X \textrm{\\} \textrm{ad}(X \textrm{\\} S)$, pero como $\textrm{ad}(X \textrm{\\} S)$ es cerrado, entonces $\textrm{int}(S) \in \mathcal T$.

$(ii)$.
Sea $A \in \mathcal T$ tal que $A \subseteq S$. Sea $x \in A \subseteq S$, entonces $S \in \mathcal E(x)$, así, $x \in \textrm{int}(S)$.

$(iii)$.
$\rightarrow$. Sea $A \in \mathcal T$. Como $A \subseteq A$, por $(ii)$, sabemos que $A \subseteq \textrm{int}(A)$, y como $\textrm{int}(A) \subseteq A$, entonces $A = \textrm{int}(A)$.
$\leftarrow$. $A = \textrm{int}(A)$ implica (por $(i)$) que $A \in \mathcal T$.

$(iv)$.
$\rightarrow$. Como $A \in \mathcal T$, $A = \textrm{int}(A)$, y $\textrm{fr}(A) = \textrm{ad}(A) \textrm{\\} \textrm{int}(A)$, lo que implica que $\textrm{fr}(A) = \textrm{ad}(A) \textrm{\\} A$. Y, por tanto, $\textrm{fr}(A) \cap A = \emptyset$.
$\leftarrow$. $\emptyset = \textrm{fr}(A) \cap A = (\textrm{ad}(A) \textrm{\\} \textrm{int}(A)) \cap A = A \textrm{\\} \textrm{int}(A)$. Así, $A \subseteq \textrm{int}(A)$ implica que $A = \textrm{int}(A)$, luego $A \in \mathcal T$.
Tags: dem top
<!--ID: 1729160606440-->
END