### Proposición

Sea $A \in M_n (K)$. Son equivalentes:
1) $A$ es una [[Matriz invertible]].
2) $rg(A) = n$ ([[Rango de una matriz]]), esto es lo mismo que decir que el rango de $A$ es máximo.
3) $\exists P,Q \in GL_n (K)$ ([[Endomorfismo biyectivo]]) tales que $PAQ = I_n$.

---
### Demostración

#### i) $\implies$ ii)
$A$ invertible $\implies \exists C \in M_n (K)$ invertible tal que $AC = I_n \implies rg(A) = rg(AC)$ por [[Proposición el rango de una matriz no cambia al multiplicarla por matrices invertibles]]. Sin embargo, sabemos que $rg(AC) = rg(I_n) = n$.
#### ii) $\implies$ iii)
Consecuencia directa de [[Teorema producto por matrices invertibles matriz sencilla]].

#### iii) $\implies$ i)
$\exists P, Q \in GL_n (K)$ tal que $PAQ = I_n \implies A = P^{-1}I_nQ^{-1} = P^{-1} Q^{-1}$ es invertible, por lo tanto, $A$ es invertible.

---
### Referencias

[[Equivalencia de matrices#1. Rango]]