### Proposición

Si $x \in \mathbb{R}, \exists z \in \mathbb{Z}$ tal que $z \le x < z +1$. A $z$ se la llama parte entera de $x$, y se denota: $z = [x]$

---
### Demostración

##### Caso 1. $x \ge 0$
Como $\mathbb{N}$ no está acotado ([[N no está acotado en R]]), $\exists m \in \mathbb{N} : x \le m$. Considero $A = \{n \in \mathbb{N}: x < n\}$. Por el [[Ley de buena ordenación]], $\exists n \in \mathbb{N}$ que es el primer elemento de $A.$ Entonces $n-1 \not \in A$; esto es, $x \ge n-1$.
$n-1 \le x < n$. Por este caso, $z = n-1$.

##### Caso 2. $x < 0$
Entonces $-x > 0$. Por el caso anterior, $\exists m \in \mathbb{Z}: m \le -x < m+1$. Invirtiendo los signos: $-m-1 < x \le -m$.
Si $x = -m$, entonces $z = -m$.
Si $x < -m$, entonces $-m-1 < x < -m, z = -m-1$.


---
### Referencias
[[N no está acotado en R]]
[[Ley de buena ordenación]]