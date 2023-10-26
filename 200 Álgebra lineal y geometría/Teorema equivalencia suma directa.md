### Enunciado Teorema

Sean $V$ un $k$-ev y $U,W$ dos subespacios vectoriales de $V$. Son equivalentes:
1. $U+W = U \bigoplus W$
2. $\forall x \in U+W, \exists u \in U, w \in W$ únicos tal que $x = u+w$.
3. Si $u \in U, w \in W$ tal que $u+w=0$ entonces $u=w=0$.

---
### Demostración

##### 1 $\implies$ 2
Hay que probar la unicidad. Supongamos que $x = u+w=u'+w'$ con $u,u' \in U, w,w' \in W$. Entonces, $u-u' = w'-w$. Como $u-u' \in U$ y $w'-w \in W$, entonces, ambos lados $\in U\cap W = \{0\}$. Así, obtenemos la igualdad $u-u' = 0$ y $w-w' = 0$, por lo que $u=u'$ y $w=w'$.
##### 2 $\implies$ 3
Aplicamos la hipótesis con $x=0$. Tenemos que $u+w = 0 = 0_U + 0_W$. Como $0$ se representa de una única forma, $u=0, w = 0$.
##### 3 $\implies$ 1
Sea $x \in U \cap W$. Queremos ver que $x = 0$. Aplicamos la hipótesis con $u = x, w = -x$. Entonces, $x + (-x) = 0$, luego, por hipótesis tenemos que $x = 0$.

---
### Referencias
[[Espacio vectorial]]