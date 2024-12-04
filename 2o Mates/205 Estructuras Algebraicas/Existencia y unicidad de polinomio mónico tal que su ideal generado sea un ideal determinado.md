### Contenido Principal

```ad-theorem
Sea $K$ un cuerpo y $I \subseteq K[x]$ un ideal tal que $I \neq \{0_{K[x]} \}$. Entonces $\exists ! p \in K[x]$ mónico tal que $I = (p)$. En particular, si $K$ es un cuerpo, entonces $K[x]$ es un $\textrm{DIP}$.
```

```ad-proof
**Existencia.** Como $I \neq \{0_{K[x]} \}$, sea $p \neq 0_{K[x]}$ on $\delta(p)$ mínimo. Esto es, $\nexists q \in I$, $q \neq 0_{K[x]}$ con $\delta(q) < \delta(p)$. Podemos suponer que $p$ es mónico. En otro caso, si $a \in R$ es el coeficiente director, $a \neq 0_R$, entonces $a$ es invertible ya que $K$ es cuerpo. Podemos considerar $a^{-1}p$ que cumple $\delta(a^{-1}p)=\delta(p)$ y $a^{-1}p$ mónico.

Vemos que $I = (p)$.
$\supseteq$. 
Como $I$ ideal y $p \in I$, $(p) \subseteq I$.

$\subseteq$. 
Sea $q \in I$. Aplicando el algoritmo de la división, $\exists c,r \in K[x]$ tales que $q = cp+r$ con $\delta(r) < \delta(p)$. Si $r \neq 0_{K[x]}$, entonces $r = q-cp \in I$, lo cual es una contradicción dado que $p$ es mínimo.
Por tanto, $r = 0_{K[x]}$ y $q = cp \in (p)$.

**Unicidad.** Supongamos $I = (p) = (q)$ con $p,q$ mónicos. Como $p \in (q)$ y $q \in (p)$, tenemos que $p = rq$ y $q = sp$ para $r,s \in K[x]$.
Así, $p = rsp$ y, por tanto, $\delta(p) = \delta(r) + \delta(s) + \delta(p)$. Entonces, $\delta(r) + \delta(s) = 0$ y, por tanto, $\delta(r) = \delta(s) = 0$.
Como $p = sq$, igualando coeficientes directores, $1_k = s1_k$. Así, $s = 1_k$ y $p = q$.
```

**Tema:** [[Anillo de polinomios#4. $K[x]$]]

**Definiciones referenciadas:** [[Cuerpo]], [[Ideal]], [[Polinomio]], [[Polinomio mónico]], [$(p)$](Ideal generado), [DIP](Dominio de ideales principales)
**Resultados referenciados:** [[Teorema división de polinomios]]

---
### Anki
