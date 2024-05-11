
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-19, 13:23

```ad-proposition
Las siguientes propiedades se derivan inmediatamente de la definición de [[relación de congruencia]]:
1. $a \equiv b \pmod m \land c \equiv d \pmod m \implies a+c \equiv b+d \pmod m \land ac \equiv bd \pmod m.$ Es decir, $\mathbb Z_m$ es un [[anillo conmutativo]].
2. Sea $d \in \mathbb Z$ tal que $d | m$, entonces $a \equiv b \pmod m \implies a \equiv b \pmod m$.
3. $a \equiv b \pmod m \land a \equiv b \pmod n$ y $m$ y $n$ son [[coprimos]] entre si $\implies a \equiv b \pmod{mn}$
```

```ad-proof
Vamos a demostrar la última.

Si $a \equiv b \pmod m$, entonces $a-b = k_1m$. Si $a \equiv b \pmod n$, entonces $a-b = k_2 n$. Como $k_1 m = k_2 n$ y $m$ y $n$ no tienen factores comunes, entonces $m | k_2$, es decir, $k_2 = rm$. Por lo tanto,
$$a-b = k_2 n = rmn,$$
es decir, $a \equiv b \pmod{mn}$.
```

**Tema:** [[Aritmética modular#2. Congruencias en los enteros]]
**Corolarios:**

---
### Anki
