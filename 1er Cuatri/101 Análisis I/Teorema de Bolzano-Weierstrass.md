### Enunciado Teorema

Toda sucesión acotada contiene una subsucesión convergente.

---
### Demostración

Sea $A := \{n \in \mathbb{N} :n$ es cumbre ([[Índice cumbre]]) $\}$, se pueden dar dos casos:

#### Caso 1. A es infinito.
$A$ es infinito, $A = \{n_1, n_2, n_3, \dots \}, n_1 \le n_2 \le n_3 \dots$ aunque $a_{n_1} \ge a_{n_2} \ge a_{n_3} \dots$ Así, la subsucesión $(a_{n_k})^\infty_{k=1}$ es monótona decreciente y acotada (recuerda que la sucesión está acotada). [[Toda sucesión decreciente y acotada inferiormente es convergente]].

#### Caso 2. A es finito o vacío.
Sea $n_1 = max(A) + 1$ si $A \not = \emptyset$ y $n_1 = 1$ si $A = \emptyset$, entonces $n_1 \not \in A$, por lo que no es cumbre. Que no sea cumbre implica que $\exists n_2>n_1$ tal que $a_{n_1} < a_{n_2}, n_2 \not \in A$, al no ser cumbre, $\exists n_3$ tal que $a_{n_2} < a_{n_3}$ y así siempre.
Mediante una inducción, si suponemos que: $n_1, n_2, \dots, n_k \in \mathbb{N}, n_1 < n_2 < \dots < n_k : a_{n_1} < a_{n_2} < \dots < a_{n_k}$. Como $n_k \not \in A$, $\exists n_{k+1} > n_k : a_{n_{k+1}} > a_{n_k}$. Por inducción, tengo construida una sucesión $(a_{n_k})^\infty_{k=1}$ monótona creciente. Por ser subsucesión de $(a_n)^\infty_{n=1}$ está acotada. [[Toda sucesión creciente y acotada superiormente es convergente]].

---
### Referencias
[[Sucesión]]
