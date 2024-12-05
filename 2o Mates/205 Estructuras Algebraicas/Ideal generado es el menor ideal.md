### Contenido Principal

```ad-proposition
Sea $R$ un anillo conmutativo con identidad, $a \in R$, y el ideal generado por $a$, $(a)$. Entonces,
1. $a \in (a)$.
2. $(a)$ es un ideal de $R$.
3. Si $I$ es un ideal de $R$ tal que $a \in I$, entonces $(a) \subseteq I$.
```

```ad-proof
1. $a = a \cdot 1_R \in (a)$.
2. Para ver que $(a)$ es ideal, primero demostramos que $((a), +) \le (R,+)$.
	- $0_R = a \cdot 0_R \in (a)$.
	- Sean $ar, as \in (a)$. Entonces $ar-as = a(r-s) \in (a)$.
	
	Sean $ar \in (a)$ y $x \in R$. Entonces $(ar)x = a(rx) \in (a)$. Como $R$ es conmutativo, $(a)$ es ideal de $R$.
3. Sea $I$ ideal de $R$, $a \in I$. Por definición de ideal, $\forall r \in R$, $ar \in I$. Así, $aR = (a) \subseteq I$.
```

**Tema:** [[Anillo de polinomios#3. Ideales y anillos cociente.]]

**Definiciones referenciadas:** [[Anillo conmutativo]], [[Anillo con identidad]], [[Ideal]], [$(a)$](Ideal generado)
**Resultados referenciados:** -.

---
### Anki

START
Básico
Anverso: Relación de un ideal generado con otros ideales que contengan el elemento que genera el ideal
Reverso: Sea $R$ un anillo conmutativo con identidad, $a \in R$, y el ideal generado por $a$, $(a)$. Entonces,
1. $a \in (a)$.
2. $(a)$ es un ideal de $R$.
3. Si $I$ es un ideal de $R$ tal que $a \in I$, entonces $(a) \subseteq I$.
Tags: est
<!--ID: 1733312056003-->
END

START
Básico
Anverso: Demostración de que sea $R$ un anillo conmutativo con identidad, $a \in R$, y el ideal generado por $a$, $(a)$. Entonces,
1. $a \in (a)$.
2. $(a)$ es un ideal de $R$.
3. Si $I$ es un ideal de $R$ tal que $a \in I$, entonces $(a) \subseteq I$.
Reverso: 
1. $a = a \cdot 1_R \in (a)$.
2. Para ver que $(a)$ es ideal, primero demostramos que $((a), +) \le (R,+)$.
	- $0_R = a \cdot 0_R \in (a)$.
	- Sean $ar, as \in (a)$. Entonces $ar-as = a(r-s) \in (a)$.
	
	Sean $ar \in (a)$ y $x \in R$. Entonces $(ar)x = a(rx) \in (a)$. Como $R$ es conmutativo, $(a)$ es ideal de $R$.
3. Sea $I$ ideal de $R$, $a \in I$. Por definición de ideal, $\forall r \in R$, $ar \in I$. Así, $aR = (a) \subseteq I$.
Tags: dem est
<!--ID: 1733312056005-->
END
