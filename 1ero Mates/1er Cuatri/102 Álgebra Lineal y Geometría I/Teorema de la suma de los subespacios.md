### Enunciado Teorema

Sean $V$ un $k$-ev y $U, W$ subespacios de $V$, entonces $U+W$ es el menor subespacio de $V$ que contiene a $U$ y $W$.

---
### Demostración

Hay que ver:
1) $U+W$ es un subespacio vectorial.
2) $U,W \subseteq U+W$.
3) Si $X$ es un subespacio de $V$ tal que $U, W \subseteq X$, entonces, $U+W \subseteq X$.

##### Paso 1.
Sean $\lambda, \mu \in K, v, v' \in U+W$, hay que ver que $\lambda v + \mu v' \in U+W$. Sabemos que $v = u + w, v' = u' + w'$. Entonces, $\lambda v + \mu v' = \lambda (u+w) + \mu (u'+w') = \lambda u + \mu u' + \lambda w + \mu w'$. Como $\lambda u + \mu u' \in U$ y $\lambda w + \mu w' \in W$, entonces $\lambda u + \mu u' + \lambda w + \mu w' \in U + W$.

##### Paso 2.
Empezamos viendo $U \subseteq U + W$. Sea $u \in U$, entonces $u = u + 0$ y $0 \in W$. Análogamente, hacemos lo mismo con $W \subseteq U + W$.

##### Paso 3.
Sea $X$ un subespacio de $V$ tal que $U, W \subseteq X$. Hay que ver que $U+W \subseteq X$. Sea $v \in U+X, v = u + w$ para algunos $u \in U$ y $w \in W$. Como $U \subseteq X, u \in X$. Como $V \subseteq X, v \in X$. Por tanto, $v = u + w \in X$.

---
### Referencias
[[Espacio vectorial]]
[[Subespacio vectorial]]
[[Suma de subespacios]]