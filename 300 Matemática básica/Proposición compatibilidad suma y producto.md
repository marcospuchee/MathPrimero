### Proposición

La suma y el producto en $\mathbb Z$ son leyes de composición internas ([[Ley de composición interna (lci)]]) compatibles ([[Compatibilidad de una ley de composición interna]]) con la [[Relación de congruencia]] módulo $n$.

---
### Demostración

##### Suma.
Tenemos que ver que si $\overline a = \overline{a'}$, y $\overline b = \overline{b'}$, entonces $\overline{a+b} = \overline{a'+b'}$, como en [[Proposición ley de composición interna compatible]]. En efecto, como $\overline a = \overline{a'}$, tenemos que $nk = a-a'$ (por definición de [[Relación de congruencia]]) para algún $k \in \mathbb Z$. De la misma manera, $nl = b-b'$ para algún $l \in \mathbb Z$. Así, tenemos que $(a+b) - (a'+b') = (a-a') + (b-b') = nk + nl = n(k+l)$, con lo que $n | (a+b) - (a'+b')$ y tenemos que $\overline{a+b} = \overline{a'+b'}$.

##### Producto.
Ahora tenemos que ver que si $\overline a = \overline{a'}$, y $\overline b = \overline{b'}$, entonces $\overline{ab} = \overline{a'b'}$. De nuevo escribimos $nk = a-a'$ para algún $k \in \mathbb Z$ y $nl = b-b'$ para algún $l \in \mathbb Z$. Entonces, $ab - a'b' = (nk+a')(nl+b') -a'b' =$ $n^2kl + nkb' + nla' + a'b' - a'b = n(nkl + kb' +la')$, con lo que $n|ab - a'b'$, como queríamos.

Por [[Proposición ley de composición interna compatible]], la suma y el producto son leyes de composición internas en $\mathbb Z / n \mathbb Z$.

---
### Referencias

[[Relación binaria]]