### Proposición

Sea $V$ un $k$-espacio vectorial, sea $W$ un [[Subespacio vectorial]] de $V$ y $R$ la [[Relación de equivalencia]] definida en [[Espacio vectorial cociente]] ($uRv$ si $u-v \in W$), entonces:
1. $[u] + [v] = [u+v]$ ([[Clase de equivalencia]]) es una [[Ley de composición interna (lci)]] en $V/W$ ([[Conjunto cociente]]).
2. Sea $\lambda \in K$, si $[u] = [v]$ entonces $[\lambda u] = [\lambda v]$.

---
### Demostración

1. Tenemos que ver que la suma de $V$ y la relación $R$ son compatibles ([[Compatibilidad de una ley de composición interna]]) por la [[Proposición ley de composición interna compatible]]. Es decir, que si $uRu'$ y $vRv'$, entonces $(u+v)R(u'+v')$. Como $uRu'$, tenemos que $u-u' \in W$. De igual manera, $v-v' \in W$. Por tanto, $(u+v) - (u'+v') =$ $(u-u') + (v-v') \in W$, y $(u+v)R(u'+v')$, como queríamos demostrar.
2. Como $uRv$, sabemos que $u-w \in W$, y por tanto, $\lambda u - \lambda v =$ $\lambda(u-v) \in W$, luego $(\lambda u)R(\lambda v)$.

---
### Referencias

[[Relación binaria]]
[[Espacio vectorial cociente]]
[[Espacio vectorial]]