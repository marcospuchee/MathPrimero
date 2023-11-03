### Proposición

Sean $a,b \in \mathbb{Z}^\times$, entonces $(a,b)[a,b] = |ab|$.

---
### Demostración

Puesto que $(a,b) = (\pm a, \pm b), \forall a,b \in Z^\times$, podemos suponer sin pérdida de generalidad que $a,b > 0$. Por tanto, tenemos que probar que $(a,b)[a,b] = ab$.

Sean $d = (a,b)$ y $m = [a,b]$. Puesto que $d|a$ y $d|b$, escribimos $da' = a$ y $db' = b$ con $a',b' \in \mathbb{Z}$ (recordemos [[Proposición existencia de los cocientes coprimos]]). Vamos a demostrar que $m = da'b'$ (si demostramos esto, tendremos que $dm = da'db' = ab)$.
- Veamos que $m | da'b'$. Tenemos que $a|ab' = da'b'$ y $b|a'b = da'b'$, con lo que $m | da'b'$ por (iii) [[Proposición existencia de mínimo común múltiplo]].
- Veamos que $da'b' | m$. Tenemos que $a|m$, con lo que podemos escribir $m = ak = da'k$, para cierto $k>0$. Ahora bien, $db' = b |m = da'k$ y por tanto $b'|a'k$ por [[Lema divisibilidad a,b,c]]. Como $(a',b') = 1$, por [[Proposición divisibilidad de un producto]] tenemos que $b'|k$. Entonces $da'b' | da'k$.

---
### Referencias

[[Divisibilidad]]