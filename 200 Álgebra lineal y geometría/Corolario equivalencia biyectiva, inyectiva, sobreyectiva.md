### Proposición

Sea $f: V \rightarrow V'$ lineal con $dimV = dimV'$, entonces son equivalentes:
- $f$ biyectiva.
- $f$ inyectiva.
- $f$ sobreyectiva.

---
### Demostración

##### i) $\implies$ ii)
Obvio.
##### i) $\implies$ iii)
Obvio.
##### ii) $\implies$ i)
$f$ inyectiva $\implies Kerf = \{0\}$ ([[Proposiciones aplicación lineal espacios vectoriales]]). Por el [[Teorema suma de dimensiones de núcleo e imagen]], $dimV = dim(Kerf) + dim(Imf)$, pero acabamos de ver que $dim(Kerf) = 0$, por tanto, $dimV = dim(Imf) = dimV'$. Como $Imf \le V'$ y $dim(Imf) = dimV'$, entonces, por [[Prop 5. EV]], $Imf = V'$, lo que por definición implica que $f$ es sobreyectiva.
##### iii) $\implies$ i)
$f$ sobre $\implies Imf = V'$. Aplicando [[Teorema suma de dimensiones de núcleo e imagen]], $dimV = dim(Kerf) + dim(Imf) = dim(Kerf) + dimV'$. $dimV$ y $dimV'$ se cancelan y queda que $dim(Kerf) = 0$, lo que, según [[Proposiciones aplicación lineal espacios vectoriales]] implica que $f$ es inyectiva.

---
### Referencias

[[Aplicación lineal]]
[[Aplicaciones inyectivas, sobreyectivas y biyectivas]]