### Contenido Principal

```ad-proposition
Si $A$ es simétrica y definida positiva, entonces $\exists G$ triangular inferior tal que $A = GG^T$. Esta descomposición se llama descomposición de Choleski de $A$.
```

```ad-proof
Como $A$ es definida positiva, en particular $\forall x \neq 0$, $Ax \neq 0$, y por tanto $A$ es invertible. Por [[descomposición LDL^T]], $A = LDL^T$.
Sea $x_i = (L^{-1})e_i \implies x_i^T A x_i = d_{ii}$. Consideremos $D^{1/2} = \textrm{diag}(d^{1/2}_{11}, \dots, d_{nn}^{1/2})$, entonces $A = LD^{1/2}D^{1/2}L^T = GG^T$ donde $G = LD^{1/2}$.
```

**Tema:** [[Descomposición LU#3. Matrices especiales y propiedades de la descomposición LU.]]

---
### Anki

START
Básico
Anverso: Cuál es la descomposición de Choleski y cuáles son sus condiciones suficientes?
Reverso: Si $A$ es simétrica y definida positiva, entonces $\exists G$ triangular inferior tal que $A = GG^T$. Esta descomposición se llama descomposición de Choleski de $A$.
Tags: met 
<!--ID: 1735044171459-->
END

START
Básico
Anverso: Demostración de que si $A$ es simétrica y definida positiva, entonces $\exists G$ triangular inferior tal que $A = GG^T$. Esta descomposición se llama descomposición de Choleski de $A$.
Reverso:Como $A$ es definida positiva, en particular $\forall x \neq 0$, $Ax \neq 0$, y por tanto $A$ es invertible. Por [[descomposición LDL^T]], $A = LDL^T$.
Sea $x_i = (L^{-1})e_i \implies x_i^T A x_i = d_{ii}$. Consideremos $D^{1/2} = \textrm{diag}(d^{1/2}_{11}, \dots, d_{nn}^{1/2})$, entonces $A = LD^{1/2}D^{1/2}L^T = GG^T$ donde $G = LD^{1/2}$.
Tags: dem met
<!--ID: 1735044171461-->
END

