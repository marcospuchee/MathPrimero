### Contenido principal

```ad-Formal
En $\mathbb R$,$$\mathcal T_e = \{A \cup B \subseteq \mathbb R : A \in \mathcal T_u \land B \subseteq \mathbb R \textrm{\\} \mathbb Q \}.$$
```

```ad-note
**Resumen del estudio de $(\mathbb R, \mathcal T_e)$.**
- $\mathcal T_u \subseteq \mathcal T_e$.
- **Base de entornos.**
	- $x \in \mathbb R \textrm{\\} \mathbb Q$. $\mathcal B(x) = \{x\}$.
	- $x \in \mathbb Q$. $\mathcal B(q) = \{B_{d_2}(q; \varepsilon) : \varepsilon > 0 \}$.
- **1AN:** sí.
- **Hausdorff:** sí.
- **Base de abiertos:** $\mathcal B = \{ B_{d_2}(q; \varepsilon) : q \in \mathbb Q, \, \varepsilon > 0 \} \cup \{\{x\} : x \in \mathbb R \textrm{\\} \mathbb Q \}$.
- **2AN:** no.
- **Separable:** no.
- **Conexo:** no.
- **Conexo por arcos:** no.
```

**Tema:** [[201 Topología#Topologías estudiadas.]]

---
### Estudio
##### Topología
1. $\mathbb R = \mathbb R \cup \emptyset, \emptyset = \emptyset \cup \emptyset \in \mathcal T_e$.
2. Sean  $A_1 \cup B_1, A_2 \cup B_2 \in \mathcal T_e$ con $A_1, A_2 \in \mathcal T_u$ y $B_1, B_2 \subseteq \mathbb R \textrm{\\} \mathbb Q$. Entonces, $$\begin{eqnarray}
(A_1 \cup B_1) \cap (A_2 \cup B_2) &=& [(A_1 \cup B_1) \cap A_2] \cup [(A_1 \cup B_1) \cap B_2] \\
&=& (A_1 \cap A_2)\cup (B_1 \cap A_2) \cup (A_1 \cap B_2) \cup (B_1 \cap B_2),
\end{eqnarray}$$ notemos que $(B_1 \cap A_2) \cup (A_1 \cap B_2) \cup (B_1 \cap B_2) \subseteq \mathbb R \textrm{\\} \mathbb Q$, y $A_1 \cap A_2 \in \mathcal T_u$, luego $(A_1 \cup B_1) \cap (A_2 \cup B_2) \in \mathcal T_e$.
3. Sean $\{A_i \cup B_i \}_{i \in I}$ tales que $A_i \in \mathcal T_u$ y $B_i \subseteq \mathbb R \textrm{\\} \mathbb Q$, $\forall i \in I$. Entonces, $$
\bigcup_{i \in I} A_i \cup B_i = \left ( \bigcup_{i \in I} A_i \right ) \cup \left ( \bigcup_{i \in I} B_i \right ),
$$ donde está claro que $\bigcup_{i \in I} A_i \in \mathcal T_u$, y $\bigcup_{i \in I} B_i \subseteq \mathbb R \textrm{\\} \mathbb Q$. Luego $\bigcup_{i \in I} A_i \cup B_i \in \mathcal T_e$.
Así, $\mathcal T_e$ es una topología.
##### Abiertos
La forma de los abiertos es clara, sin embargo, cabe destacar que $\mathcal T_u \subseteq \mathcal T_e$, dado que $\forall A \in \mathcal T_u$, entonces $A \cup \emptyset \in T_e$.

##### Base de entornos
Dado $x \in \mathbb R \textrm{\\} \mathbb Q$, entonces $\mathcal B(x) = \{\{x\}\}$.
1. Veamos que $\{x\} \in \mathcal E(x)$. Como $\{x\} \in \mathcal T_e$, está claro que $\{x\}$ es entorno de todos sus puntos. En particular, de $x$.
2. Sea $U \in \mathcal E(x)$, entonces $\exists A \cup B\in T_e$ tal que $x \in A \cup B \subseteq U$. Sin embargo, $$x \in \{x\} \subseteq A \subseteq A \cup B \subseteq U.$$
Si $q \in \mathbb Q$, entonces tomamos la base de entornos de $\mathcal T_u$: $\mathcal B(q) = \{B_{d_2}(q; \varepsilon) : \varepsilon > 0 \}$
1. Dado $B_{d_2}(q; \varepsilon)$ con $\varepsilon > 0$, entonces como $B_{d_2}(q; \varepsilon) = B_{d_2}(q; \varepsilon) \cup \emptyset \in \mathcal T_e$, es entorno de todos sus puntos, en particular, de $q$.
2. Sea $U \in \mathcal E(x)$, entonces $\exists A \cup B \in \mathcal T_e$ tal que $x \in A \cup B \subseteq U$. En particular, $A \in \mathcal T_u$, lo que implica que $\exists \varepsilon > 0$ tal que $$q \in B_{d_2}(q; \varepsilon) \subseteq A \subseteq A \cup B \subseteq U.$$
luego es base de entornos.
##### 1AN
Si $x \in \mathbb R \textrm{\\} \mathbb Q$, tenemos ya una base de entornos numerable. Si $q \in \mathbb Q$, veamos si $\mathcal B_q = \{B_{d_2}(q; \frac{1}{n}) : n \in \mathbb N \}$ es base de entornos:
1. Dado $B_{d_2}(q; \frac{1}{n})$ con $n \in \mathbb N$, entonces como $B_{d_2}(q; \frac{1}{n}) = B_{d_2}(q; \frac{1}{n}) \cup \emptyset \in \mathcal T_e$, es entorno de todos sus puntos, en particular, de $q$.
2. Sea $U \in \mathcal  E(x)$, entonces $\exists A \cup B \in \mathcal T_e$ tal que $x \in A \cup B \subseteq U$. En particular, $A \in \mathcal T_u$, lo que implica que $\exists \varepsilon > 0$ tal que $B_{d_2}(q; \varepsilon) \subseteq A$. Si tomamos $n \in \mathbb N$ tal que $n > \frac{1}{\varepsilon}$, entonces $$B_{d_2}(q; \frac{1}{n}) \subseteq B_{d_2}(q; \varepsilon) \subseteq A \subseteq A \cup B \subseteq U.$$
Luego $(\mathbb R, \mathcal T_e)$ es 1AN.

##### Hausdorff
Tomando $x,y \in \mathbb R \textrm{\\} \mathbb Q$, entonces $\{x\} \in \mathcal E(x)$, $\{y\} \in \mathcal E(y)$, pero $\{x\} \cap \{y\} = \emptyset$. Luego $(\mathbb R, \mathcal T_e)$ es Hausdorff.

##### Base de abiertos
Definimos $$\mathcal B = \{ B_{d_2}(q; \varepsilon) : q \in \mathbb Q, \, \varepsilon > 0 \} \cup \{\{x\} : x \in \mathbb R \textrm{\\} \mathbb Q \},$$ veamos que es base de abiertos: sea $A \cup B \in \mathcal T_e$, tenemos que ver que $\forall x \in A \cup B$, $\exists B \in \mathcal B$ tal que $x \in B \subseteq A \cup B$.
1. $x \in \mathbb R \textrm{\\} \mathbb Q$. Entonces, $x \in \{x\} \subseteq B \subseteq A \cup B$, donde $\{x\} \in \mathcal B$.
2. $x \in \mathbb Q$. Entonces, $x \in A$, que por ser abierto, $\exists B_{d_2}(x; \varepsilon)$ con $\varepsilon > 0$ tal que $B_{d_2}(x; \varepsilon) \subseteq A \subseteq A \cup B$, y $B_{d_2}(x; \varepsilon) \in \mathcal B$.
Luego $\mathcal B$ es base de abiertos.

##### 2AN
Sabemos que si $(\mathbb R, \mathcal T_e)$, entonces $\exists \mathcal B' \subseteq \mathcal B$ base de abiertos numerable. Si de algún modo existiese tal $\mathcal B'$, entonces tendríamos que haber encontrado un subconjunto de  $\{ \{x\} : x \in \mathbb R \textrm{\\} \mathbb Q \}$ que sea numerable. Por necesidad, $\exists \{x'\} \in \{\{x\}: x \in \mathbb R \textrm{\\} \mathbb Q \}$, que no se encuentra en este subconjunto, luego $\exists \{x'\}$ tal que $\nexists$ un elemento del subconjunto que esté contenido en $\{x'\}$. Entonces $(\mathbb R, \mathcal T_e)$ no es 2AN.

##### Separable
Tenemos que encontrar $A \subseteq \mathbb R$ que sea numerable y denso. En el caso de que existiese tal $A$, $A \cap \{x\} \neq \emptyset$, $\forall x \in \mathbb R \textrm{\\} \mathbb Q$, por lo tanto, $\mathbb R \textrm{\\} \mathbb Q \subseteq A$, luego $A$ jamás puede ser numerable. Así, $(\mathbb R, \mathcal T_e)$ no es 2AN.

##### Conexo
Tomando $\{x\}$ con $x \in \mathbb R \textrm{\\} \mathbb Q$, sabemos que $\{x\} \in \mathcal T_e$. Y además, $\{x\}^c = ]-\infty, x[ \cup ]x, +\infty[$, que está claro que es abierto en $\mathcal T_u$, luego existe un conjunto abierto y cerrado a la vez distinto de $\mathbb R$ y $\emptyset$. Luego $(\mathbb R, \mathcal T_e)$ es disconexo.

##### Conexo por arcos
Dado que conexo por arcos $\implies$ conexo, y no es conexo, entonces tampoco es conexo por arcos.
