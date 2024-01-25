### Corolario

Sea $A \in M_n (K)$. Entonces $A$ es [[Matriz invertible]] $\iff A$ es un producto de matrices elementales ([[Matriz elemental de tipo I]], [[Matriz elemental de tipo II]], [[Matriz elemental de tipo III]]).

---
### Demostración

$\leftarrow$. Obvio porque sabemos que las matrices elementales son invertibles y el producto de matrices invertibles también es invertible.
$\rightarrow$. Por [[Teorema producto por matrices invertibles matriz sencilla (demostración 2)]], $\exists E_1, \dots E_k, E_1', \dots E_l'$ elementales tales que $(E_1 \dots E_k)A(E_1' \dots E_l') = I_n$ por [[Equivalencia matriz invertible, rango máximo y existencia matrices invertibles producto identidad]]. Esto quiere decir que $A = (E_1 \dots E_k)^{-1} (E_1' \dots E_l')^{-1}$ que esto es lo mismo que $E_K^{-1}\dots E_1^{-1} E_l'^{-1} \dots E_1'^{-1}$. Como la inversa de cada matriz elemental es una matriz elemental, queda el corolario. 

---
### Referencias

[[Equivalencia de matrices#2. Matrices elementales]]

---
### Anki

START
Básico
Anverso: Qué relación tiene que una matriz sea invertible con las matrices elementales?
Reverso: Sea $A \in M_n (K)$. Entonces $A$ es [[Matriz invertible]] $\iff A$ es un producto de matrices elementales ([[Matriz elemental de tipo I]], [[Matriz elemental de tipo II]], [[Matriz elemental de tipo III]]).
Tags: proposición/teorema
<!--ID: 1704822883782-->
END

START
Básico
Anverso: Demostración de que sea $A \in M_n (K)$. Entonces $A$ es [[Matriz invertible]] $\iff A$ es un producto de matrices elementales ([[Matriz elemental de tipo I]], [[Matriz elemental de tipo II]], [[Matriz elemental de tipo III]]).
Reverso: $\leftarrow$. Obvio porque sabemos que las matrices elementales son invertibles y el producto de matrices invertibles también es invertible.
$\rightarrow$. Por [[Teorema producto por matrices invertibles matriz sencilla (demostración 2)]], $\exists E_1, \dots E_k, E_1', \dots E_l'$ elementales tales que $(E_1 \dots E_k)A(E_1' \dots E_l') = I_n$ por [[Equivalencia matriz invertible, rango máximo y existencia matrices invertibles producto identidad]]. Esto quiere decir que $A = (E_1 \dots E_k)^{-1} (E_1' \dots E_l')^{-1}$ que esto es lo mismo que $E_K^{-1}\dots E_1^{-1} E_l'^{-1} \dots E_1'^{-1}$. Como la inversa de cada matriz elemental es una matriz elemental, queda el corolario. 
Tags: demostración
<!--ID: 1704822883787-->
END
