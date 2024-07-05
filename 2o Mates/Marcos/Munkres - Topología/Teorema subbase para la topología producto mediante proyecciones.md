
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-06-18, 22:23

```ad-theorem
La colección
$$\mathcal S = \{\pi_1^{-1}(U) \, | \, U \textrm{ es abierto en } X \} \cup \{\pi_2^{-1}(V) \, | \, V \textrm{ es abierto en } Y \}$$
es una subbase ([[subbase para una topología]]) para la [[topología producto]] sobre $X \times Y$.
```

```ad-proof
Sea $\mathcal T$ la topología producto sobre $X \times Y$ y $\mathcal T'$ la topología generada por $\mathcal S$. Puesto que cada elemento de $\mathcal S$ pertenece a $\mathcal T$, también pertenecen las uniones arbitrarias de intersecciones finitas de elementos de $\mathcal S$. Así $\mathcal T' \subset \mathcal T$. Por otro lado, cada elemento básico $U \times V$ para la topología $\mathcal T$ es una intersección finita de elementos de $\mathcal S$, puesto que
$$U \times V = \pi_1^{-1}(U) \cap \pi_2^{-1}(V).$$
Por lo tanto, $U \times V$ pertenece a $\mathcal T'$, y así $\mathcal T \subset \mathcal T'$.
```
w

**Tema:**
**Demostrado por:**
**Consecuencias:**

---
### Anki
