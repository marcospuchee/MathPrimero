### Contenido Principal

```ad-proposition
Sea $f: A \subseteq \mathbb R^n \to \mathbb R^m$. Son equivalentes:
1. $f$ continua en $A$.
2. Para todo abierto $V$ de $\mathbb R^n$, $f^{-1}(V)$ es abierto de $A$.
3. Para todo cerrado $F$ de $\mathbb R^n$, $f^{-1}(F)$ es cerrado de $A$.
```

^cc6894

```ad-proof
$(ii) \iff (iii)$.
$\rightarrow$. $F$ cerrado $\implies$ $\mathbb R^n \textrm{\\} F$ abierto $\implies$ $f^{-1}(\mathbb R^n \textrm{\\} F)$ abierto $\implies$ $f^{-1}(F)$ cerrado, porque $\mathbb R^n \textrm{\\} f^{-1}(F) = f^{-1}(\mathbb R^n \textrm{\\} F)$. 
$\leftarrow$. Igual.


$(i) \iff (ii)$.
$\rightarrow$. Sea $V$ abierto de $\mathbb R^n$, ¿ $f^{-1}(V)$ abierto ?
- Si $f^{-1}(V) = \emptyset$, entonces es abierto.
- Si $f^{-1}(V) \neq \emptyset$, sea $a \in f^{-1}(V)$, entonces $f(a) \in V$. Como $V$ abierto, $V$ es entorno de $f(A)$, lo que implica por [[caracterización continuidad función multivariable con entornos]] que $f^{-1}(V)$ es entorno de $a$ relativo a $A$. Luego como $a$ es arbitrario, $f^{-1}(V)$ es abierto en $A$.

$\leftarrow$. Sea $a \in A$, $V$ entorno de $f(A)$. Entonces $\exists U$ abierto tal que $f(a) \in U \subseteq V$. Esto es, $a \in f^{-1}(U) \cap A \subseteq f^{-1}(V)$. Así, $f^{-1}(V)$ es [[entorno]] de $a$ relativo a $A$, que por [[caracterización continuidad función multivariable con entornos]], $f$ continua en $a$.
```

**Tema:** [[Funciones de varias variables#3. Continuidad.]]

---
### Anki

START
Básico
Anverso: Caracterización de la continuidad de la antiimagen
Reverso: Sea $f: A \subseteq \mathbb R^n \to \mathbb R^m$. Son equivalentes:
1. $f$ continua en $A$.
2. Para todo abierto $V$ de $\mathbb R^n$, $f^{-1}(V)$ es abierto de $A$.
3. Para todo cerrado $F$ de $\mathbb R^n$, $f^{-1}(F)$ es cerrado de $A$.
<!--ID: 1727966478918-->
END

START
Básico
Anverso: Demostración de que sea $f: A \subseteq \mathbb R^n \to \mathbb R^m$. Son equivalentes:
1. $f$ continua en $A$.
2. Para todo abierto $V$ de $\mathbb R^n$, $f^{-1}(V)$ es abierto de $A$.
3. Para todo cerrado $F$ de $\mathbb R^n$, $f^{-1}(F)$ es cerrado de $A$.
Reverso: 
$(ii) \iff (iii)$.
$\rightarrow$. $F$ cerrado $\implies$ $\mathbb R^n \textrm{\\} F$ abierto $\implies$ $f^{-1}(\mathbb R^n \textrm{\\} F)$ abierto $\implies$ $f^{-1}(F)$ cerrado, porque $\mathbb R^n \textrm{\\} f^{-1}(F) = f^{-1}(\mathbb R^n \textrm{\\} F)$. 
$\leftarrow$. Igual.


$(i) \iff (ii)$.
$\rightarrow$. Sea $V$ abierto de $\mathbb R^n$, ¿ $f^{-1}(V)$ abierto ?
- Si $f^{-1}(V) = \emptyset$, entonces es abierto.
- Si $f^{-1}(V) \neq \emptyset$, sea $a \in f^{-1}(V)$, entonces $f(a) \in V$. Como $V$ abierto, $V$ es entorno de $f(A)$, lo que implica por [[caracterización continuidad función multivariable con entornos]] que $f^{-1}(V)$ es entorno de $a$ relativo a $A$. Luego como $a$ es arbitrario, $f^{-1}(V)$ es abierto en $A$.

$\leftarrow$. Sea $a \in A$, $V$ entorno de $f(A)$. Entonces $\exists U$ abierto tal que $f(a) \in U \subseteq V$. Esto es, $a \in f^{-1}(U) \cap A \subseteq f^{-1}(V)$. Así, $f^{-1}(V)$ es [[entorno]] de $a$ relativo a $A$, que por [[caracterización continuidad función multivariable con entornos]], $f$ continua en $a$.
Tags: dem anII
<!--ID: 1728138052352-->
END
