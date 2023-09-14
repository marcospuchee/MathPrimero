### Enunciado Teorema

Sea $A \subset \mathbb{R}$, si este está acotado inferiormente, existe la mayor de las cotas y a esta se le denomina ínfimo; inf(A).

---
### Demostración

Como $A$ está acotado inferiormente, $\exists c \in \mathbb{R}: c \le a, \forall a \in A$, de donde $-a \le -c, \forall a \in A$.
Llamamos $-A = \{-a \in \mathbb{R} : a \in A \}$. Por el axioma del supremo (OR5 en [[Conjunto Real]]), $\exists sup(-A) = s$. Veamos que $-s = inf(A)$:
1. Veamos que $-s$ es cota inferior de $A$: si $a \in A, -a \in -A, -a \le s, -s \le a$.
2. Veamos que $-s$ es ínfimo de A: sea $c$ una cota inferior de $A$, entonces $-c$ es una cota superior de $-A$. Por definición de supremo, $s$ es la menor de las cotas superiores de $-A$, $s \le -c$. Por tanto, $c \le -s$.

---
### Referencias

