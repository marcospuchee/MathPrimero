### Proposición

Sea $(A,+,·)$ anillo con más de un elemento y unitario, llamamos $e$ al neutro de la primera operación ($+$) y $u$ al neutro de $·$. Entonces:
- $e \not = u$.
- $e$ no tiene inverso para el producto.
- $U_A = \{a \in A :$ a tiene inverso para $·\}$, entonces $(U_A, ·)$ es un grupo. $U_A$ es el conjunto de las Unidades de $A$.


---
### Demostración

1. Supongamos que $e = u. \forall a \in A, a = u · a = e · a = e$. Contradicción
2. Supongamos que $\exists f \in A$ tal que $e · f = f · e = u$. $e = e · f = u \implies e = u$. Contradicción.
3. ¿$(U_A, ·)$ grupo? $a, b \in U_A$, llamamos $a^{-1}, b^{-1}$ a sus inversos $(ab)(b^{-1}a^{-1}) = a (bb^{-1})a^{-1} = a · u · a^{-1} = a · a^{-1} = u$. Con esto hemos comprobado que $·$ es lci. $·$ es asociativa porque $(A, +, ·)$ es anillo. El elemento neutro es $u \in U_A$ (porque $u · u = u$). Todo elemento $a \in U_A$ tiene inverso, $a^{-1} \in A$ y $a^{-1} \in U_A$ porque $(a^{-1})^{-1} = a$.

---
### Referencias
[[Anillo]]
[[Estructuras algebraicas elementales]]