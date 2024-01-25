### Proposición

Sea $A$ un conjunto y sea $R$ una relación binaria de equivalencia ([[Relación de equivalencia]]) en $A$. Las clases de equivalencia ([[Clase de equivalencia]]) de $R$ forman una partición de $A$.

---
### Demostración

Tenemos que demostrar que $A = \cup_{a \in A} [a]$ y que si $[a] \not = [b]$, entonces $[a] \cap [b] = \emptyset$.

Veamos que $A = \cup_{a \in A} [a]$. Sea $a \in A$, entonces $a \in [a]$ (pues $R$ es reflexiva), y por tanto, $A \subseteq \cup_{a \in A} [a]$. Como $[a] \subseteq A, \forall a \in A$, tenemos que $\cup_{a \in A} [a] \subseteq A$, y por tanto, la igualdad.

Veamos que si $[a] \not = [b]$, entonces $[a] \cap [b] = \emptyset$. Supongamos lo contrario, es decir, supongamos que existe $x \in [a] \cap [b]$. Entonces $xRa$ y $xRb$. Como la relación es simétrica, tenemos que $aRx$. Como es transitiva y $aRx$y $xRb$, tenemos que $aRb$. Pero entonces, $[a] = [b]$, contradicción.

---
### Referencias

[[Relación binaria]]

---
### Anki

START
Básico
Anverso: Demostración de que sea $A$ un conjunto y sea $R$ una relación binaria de equivalencia ([[Relación de equivalencia]]) en $A$. Las clases de equivalencia ([[Clase de equivalencia]]) de $R$ forman una partición de $A$.
Reverso: 
Tenemos que demostrar que $A = \cup_{a \in A} [a]$ y que si $[a] \not = [b]$, entonces $[a] \cap [b] = \emptyset$.

Veamos que $A = \cup_{a \in A} [a]$. Sea $a \in A$, entonces $a \in [a]$ (pues $R$ es reflexiva), y por tanto, $A \subseteq \cup_{a \in A} [a]$. Como $[a] \subseteq A, \forall a \in A$, tenemos que $\cup_{a \in A} [a] \subseteq A$, y por tanto, la igualdad.

Veamos que si $[a] \not = [b]$, entonces $[a] \cap [b] = \emptyset$. Supongamos lo contrario, es decir, supongamos que existe $x \in [a] \cap [b]$. Entonces $xRa$ y $xRb$. Como la relación es simétrica, tenemos que $aRx$. Como es transitiva y $aRx$y $xRb$, tenemos que $aRb$. Pero entonces, $[a] = [b]$, contradicción.
Tags: demostración
<!--ID: 1705771400970-->
END