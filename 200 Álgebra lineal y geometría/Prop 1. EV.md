### Proposición

Sea $V$ un $k$-espacio vectorial, si $U$ y $W$ son subespacios, entonces $U \cap W$ es un subespacio vectorial de $W$.

---
### Demostración

Primero, como $U$ y $W$ son subespacios de $V$, entonces $0_v \in U,W \implies 0_v \in U \cap W$, por lo que $U \cap W \not = \emptyset$. Por otra parte, $U \cap W \subseteq U \subseteq V$.

$U \cap W$ es un subespacio de $V$ si se cumple que: $\forall \lambda , \mu \in K, \forall x, y \in U \cap W, \lambda x + \mu y \in U \cap W$.
Por ser $U \cap W$ un espacio vectorial cumple las operaciones $+$ y $·$ (producto):
- Producto por un escalar: $\lambda x, \mu y \in U \cap W$.
- Suma: $\lambda x + \mu y \in U \cap W$.

Por tanto, si:
- $\forall \lambda , \mu \in K, \forall x, y \in U, \lambda x + \mu y \in U$.
- $\forall \lambda , \mu \in K, \forall x, y \in W, \lambda x + \mu y \in W$.

Entonces: $\forall \lambda , \mu \in K, \forall x, y \in U \cap W, \lambda x + \mu y \in U \cap W$.

**Sin embargo, la unión de subespacios no tiene por qué ser un subespacio.**

---
### Referencias
[[Subespacio vectorial]]
[[Espacio vectorial]]