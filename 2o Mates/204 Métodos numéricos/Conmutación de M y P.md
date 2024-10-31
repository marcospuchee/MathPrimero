### Contenido Principal

```ad-proposition
Escribiendo el proceso de eliminación gaussiana con pivoteo parcial como
$$M_{n-1}P_{n-1} \dots M_2 P_2 M_1 P_1 A,$$
entonces tenemos que
$$M_{n-1} P_{n-1} \dots M_1 P_1 = M_{n-1}^{(n-1)} M_{n-2}^{(n-1)} \dots M_1^{(n-1)} P_{n-1} \dots P_1,$$
siendo
$$v_i = \sum_{j = k+1}^n \alpha_{j,k} e_j.$$
```

```ad-proof
Por inducción sobre el paso $k$ de la eliminación gaussiana, $1 \le k \le n-1$. Se cumple que, en general,
$$M_i^{(k)} := I_n - (P_k P_{k-1} \dots P_{i+1} v_i)e_i^T, \quad 1 \le i \le k, \quad 1 \le k \le n-1.$$
```

**Tema:** [[Descomposición LU#4. Eliminación gaussiana con pivoteo parcial.]]

---
### Anki
