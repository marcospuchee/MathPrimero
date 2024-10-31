### Contenido Principal

```ad-proposition
Sea $A \in \mathbb R^{n \times n}$ regular tal que $\exists L \in \mathbb R^{n \times n}$ triangular inferior con $L(i,i) = 1$, $\forall 1 \le i \le n$ y $\exists U \in \mathbb R^{n \times n}$ triangular superior tal que $A = LU$. Entonces, esta descomposición es única.
```

```ad-proof
Supongamos que $\exists L_1, L_2, U_1, U_2 \in \mathbb R^{n \times n}$, que cumplan las hipótesis. Entonces,
$$L_1 U_1 = L_2 U_2 \implies L_2^{-1}L_1 U_1 U_1^{-1} = L_2^{-1} L_2 U_2 U_1^{-1} \implies L_2^{-1} L_1 = U_2 U_1^{-1}.$$
Sin embargo, $L_2^{-1} L_1$ es triangular inferior con $1$ en la diagonal, y $U_2 U_1^{-1}$ es triangular superior. Por tanto,
$$L_2^{-1}L_1 = U_2U_1^{-1} = I \implies L_1 = L_2 \land U_2 = U_1.$$
```

**Tema:** [[Descomposición LU#3. Matrices especiales y propiedades de la descomposición LU.]]

---
### Anki
