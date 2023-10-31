### Lema

Si $b \in \mathbb{Z} - \{0\}$, entonces $\forall q,r \in \mathbb{Z}$, tenemos que $mcd(bq+r, b) = mcd(b,r)$.

---
### Demostración

Tomamos $d = mcd(bq+r, b)$, y $d' = mcd(b,r)$. Queremos probar que $d = d'$ a través de que eso solo se cumple si $d | d'$ y $d'|d$.
#### $d | d'$
¿$d | b$? sí. 
¿$d | r$? Como $d|bq$ y $d|bq+r$, entonces $d|r$ por (ii) del [[Lema divisibilidad a,b,c]].
#### $d'|d$
¿$d'|b$? sí.
¿$d' | bq +r$? Como $d'|bq$ y $d'|r$, entonces $d'|bq+r$.

Por tanto, $d = d'$.

---
### Referencias

[[Divisibilidad]]

25-10-23. Matemática Básica.