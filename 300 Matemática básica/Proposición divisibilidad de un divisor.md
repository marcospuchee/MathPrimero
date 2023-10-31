### Proposición

Sean $a,b \in  \mathbb{Z}, a \not = 0$ o $b \not = 0, d \in \mathbb{N}$ tal que si se cumple:
1. $d | a$ y $d|b$.
2. $d'|a, d'|b \implies d'|d$.

Entonces, $d = mcd(a,b)$.

---
### Demostración

Como $d, mcd(a,b) > 0$, basta con ver que $d | mcd(a,b)$ y $mcd(a,b)|d$:
- $d|mcd(a,b): d|a$ y $d|b$. $mcd(a,b)|a$ y $mcd(a,b)|b$. Por (iii) del [[Teorema de Bezout]], entonces $d | mcd(a,b)$.
- $mcd(a,b) | d: mcd(a,b) | a$ y $mcd(a,b)|b$ por ser [[Máximo común divisor]], tenemos como hipótesis (ii) que $mcd(a,b) | d$.

Así, ya hemos visto que $d|mcd(a,b)$ y $mcd(a,b)|d$.

---
### Referencias

[[Divisibilidad]]