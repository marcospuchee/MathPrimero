
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-07, 11:43

```ad-theorem
Si $G$ es un [[semigrupo]] y $a_1, \dots, a_n \in G$, entonces dos productos significativos de $a_1, \dots, a_n$ en este orden son iguales. 
```

^8ff382

```ad-proof
Vamso a proceder por inducción fuerte ([[principio de inducción fuerte]]). Veamos que $\forall n \in \mathbb N$, cualquier producto significativo $a_1 \dots a_n$ es igual al $n$-producto estándar $\displaystyle \prod_{i = 1}^n a_i$.

Para los casos $n = 1,2$ está claro que es cierto por la propiedad asociativa del semigrupo.
Si $n > 2$, por definición $a_1 \dots a_n = (a_1 \dots a_m)(a_{m+1} \dots a_n)$ para algún $m<n$. Por tanto,
$$\begin{eqnarray}
a_1 \dots a_n &=& (a_1 \dots a_m)(a_{m+1} \dots a_n) = \left (\prod_{i = 1}^m a_i \right ) \left ( \prod_{i = 1}^{n-m} a_{m+i} \right ) \\ 
&=& \left (\prod_{i = 1}^m a_i \right ) \left ( \left ( \prod_{i = 1}^{n-m-1} a_{m+i} \right ) a_n \right ) = \left ( \left ( \prod_{i = 1}^m a_i \right ) \left ( \prod_{i = 1}^{n-m-1} a_{m+i} \right ) \right ) a_n \\
&=& \left ( \prod_{i = 1}^{n-1} a_i \right ) a_n = \prod_{i = 1}^n a_i.
\end{eqnarray}$$
```


**Tema:** [[Grupos#1. Semigrupos, monoides y grupos]]
**Demostrado por:** [[principio de inducción fuerte]]
**Consecuencias:** [[Ley conmutativa generalizada]]

---
### Anki
