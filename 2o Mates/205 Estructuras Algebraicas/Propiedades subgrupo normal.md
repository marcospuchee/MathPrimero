### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]]. Entonces
1. $A \unlhd G \land H \le G \implies AH \le G$.
2. $A,B \unlhd G \implies AB \unlhd G$.
3. $A,B \unlhd G \implies A \cap B \unlhd G$.
4. $N \le H \le G \land N \unlhd G \implies N \unlhd H$.
```

^bbee11

```ad-proof
1. Veamos que $AH = HA$: $AH = \bigcup_{h \in H} Ah =$ (por $A \unlhd G$) $\bigcup_{h \in H} hA = HA$.
2. Sea $g \in G$, $ab \in AB$, veamos que $^g(ab) \in AB$. Como $\alpha_g$ es homomorfismo, entonces $^g(ab) = {}^g a {}^g b \in AB$.
3. Sea $g \in G$, $x \in A \cap B$. En particular, como $x \in A$ y $A \unlhd G$, entonces $^g \in A$. Por el mismo razonamiento, $^g x \in B$. Luego $^g x \in A \cap B$.
4. Suponemos $N \unlhd G$. Sea $n \in \mathbb N$, $h \in H \le G$. Como $N \unlhd G$, entonces $^h n \in N$.
```

**Tema:** [[Teoría de grupos#11. Subgrupos normales.]]

---
### Anki

START
Básico
Anverso: Propiedades de los subgrupos normales
Reverso: Sea $G$ un [[Grupo]]. Entonces
1. $A \unlhd G \land H \le G \implies AH \le G$.
2. $A,B \unlhd G \implies AB \unlhd G$.
3. $A,B \unlhd G \implies A \cap B \unlhd G$.
4. $N \le H \le G \land N \unlhd G \implies N \unlhd H$.
Tags: est
<!--ID: 1728820185257-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]]. Entonces
1. $A \unlhd G \land H \le G \implies AH \le G$.
2. $A,B \unlhd G \implies AB \unlhd G$.
3. $A,B \unlhd G \implies A \cap B \unlhd G$.
4. $N \le H \le G \land N \unlhd G \implies N \unlhd H$.
Reverso: 
1. Veamos que $AH = HA$: $AH = \bigcup_{h \in H} Ah =$ (por $A \unlhd G$) $\bigcup_{h \in H} hA = HA$.
2. Sea $g \in G$, $ab \in AB$, veamos que $^g(ab) \in AB$. Como $\alpha_g$ es homomorfismo, entonces $^g(ab) = {}^g a {}^g b \in AB$.
3. Sea $g \in G$, $x \in A \cap B$. En particular, como $x \in A$ y $A \unlhd G$, entonces $^g \in A$. Por el mismo razonamiento, $^g x \in B$. Luego $^g x \in A \cap B$.
4. Suponemos $N \unlhd G$. Sea $n \in \mathbb N$, $h \in H \le G$. Como $N \unlhd G$, entonces $^h n \in N$.
Tags: dem est
<!--ID: 1728820185259-->
END

