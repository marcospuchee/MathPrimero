### Contenido Principal

```ad-proposition
Podemos describir matricialmente el proceso de eliminación gaussiana con pivoteo parcial como
$$M_{n-1}P_{n-1} \dots M_2 P_2 M_1 P_1 A,$$
Con esta notación, tenemos que
$$M_{n-1} P_{n-1} \dots M_1 P_1 = M_{n-1}^{(n-1)} M_{n-2}^{(n-1)} \dots M_1^{(n-1)} P_{n-1} \dots P_1,$$
donde
$$M_i^{(n-1)}:= I_n + (P_{n-1} P_{n-2} \dots P_{i+1} v_i)e_i^T, \quad 1 \le i \le n-1$$
siendo
$$v_i = \sum_{j = k+1}^n \alpha_{j,k} e_j.$$
```

```ad-proof
Probemos el resultado por inducción sobre $1 \le m-1 \le n-1$. Vamos a probar que $\forall m \in \{2, \dots, n \}$,
$$M_{m-1}P_{m-1} \dots M_2 P_2 M_1 P_1 = M_{m-1}^{(m-1)} M_{m-2}^{(m-1)} \dots M_1^{(m-1)} P_{m-1} \dots P_1,$$
donde $M_i^{(m-1)} = I - (P_{m-1} P_{m-2} \dots P_{i+1} v_i)e_i^T$.

**$m = 1$.**
No tiene sentido aplicarlo ya que no está ni definido.

**Caso base: m = 2.**
¿ $M_1 P_1 = M_1^{(1)} P_1$ ? El resultado se obtiene con $M_1^{(1)} = M_1$.

**Paso inductivo.** 
Supongamos el resultado cierto para algún $1 \le m-1 \le n-1$. Entonces,
$$M_{m-1}P_{m-1} \dots M_2 P_2 M_1 P_1 = M_{m-1}^{(m-1)} M_{m-2}^{(m-2)} \dots M_1^{(m-1)} P_{m-1} \dots P_1,$$
donde $M_i^{(m-1)} = I - 

```

**Tema:** [[Descomposición LU#4. Eliminación gaussiana con pivoteo parcial.]]

---
### Anki
