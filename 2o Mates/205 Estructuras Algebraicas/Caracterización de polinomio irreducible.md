### Contenido Principal

```ad-theorem
Sea $K$ un cuerpo y $p \in K[x]$ mónico. Entonces son equivalentes
1. $p$ es irreducible.
2. $K[x]/(p)$ es cuerpo.
```

```ad-proof
$1 \implies 2$. Suponemos que $p$ es irreducible.
Como $p$ no es invertible, $\nexists q \in K[x]$ tal que $pq = 1_{K[x]}$. Por tanto, $1_{K[x]} \notin (p)$. Así, $1_{K[x]}+(p) \neq 0_{K[x]}+(p) = (p)$. Por el teorema del anillo cociente, sabemos que $K[x]/(p)$ es un anillo conmutativo con identidad.
Demostramos que si $a+(p) \in K[x]/(p)$ con $a+(p) \neq 0_{K[x]}+(p)$, entonces $a+(p)$ es elemento invertible. Consideremos $(a)+(p)$ ideal de $K[x]$. Por el teorema de existencia y unicidad de un polinomio mónico que genere al ideal, sabemos que $\exists q \in K[x]$ mónico tal que $(a)+(p)=(q)$. Como $p \in (p) \subseteq (q)$. Entonces $\exists r \in K[x]$ tal que $p=qr$. Como $p$ es irreducible, $q$ o $r$ es invertible:
- Suponemos que $r$ es invertible. Entonces, $\exists r^{-1} \in K[x]$ tal que $r \cdot r^{-1} = 1_{K[x]} = 1_K$. Así, $\delta(r) + \delta(r^{-1}) = 0$ y, por tanto, $\delta(r) = 0$. Como $p = qr$ con $p,q$ mónicos, entonces $r = 1_K$. Por tanto, $p = q$. Así, $a \in (a) \subseteq (q) = (p)$ y $a+(p) = 0+(p)$, lo cual es una contradicción.
- Entonces, $q$ es invertible. Luego, $\exists q^{-1} \in K[x]$ tal que $qq^{-1} = 1_{K[x]} = 1_K$. Así, $1_{K[x]} \in (q) = (a) + (p)$. Por tanto, $\exists u,v \in K[x]$ tales que $1_{K[x]} = au+pv$. Finalmente,
$$1_{K[x]}+(p) = (au+pv) + (p) = (au + (p)) + (pv + (p)) = (a+(p))(u+(p))$$
y $a+(p)$ es invertible.


$2 \implies 1$. Suponemos que $K[x]/(p)$ cuerpo.
Demostramos que $p$ es irreducible:
- Si $p = 0_{K[x]}$, entonces, $(p) = \{0_{K[x]} \}$. Entonces, $K[x]/(p) \cong K[x]$ cuerpo pero $x \in K[x]$ no es invertible, lo cual contradice que $K[x]/(p)$ sea cuerpo.
- Si $p$ es invertible, $\exists p^{-1} \in K[x]$ tal que $pp^{-1} = 1_{K[x]}$. Entonces $(p) = K[x]$ y $K[x]/(p) = \{0+(p) \}$ el anillo nulo, lo cual contradice que $K[x]/(p)$ sea cuerpo.
- Supongamos que $p = qr$ con $q,r$ mónicos. Entonces,
$$0 + (p) = p+(p) = (q+(p))(r+(p)).$$
Como $K$ cuerpo, $q+(p) = 0+(p)$ o $r+(p) = 0+(p)$. Es decir, $q \in (p)$ o $r \in (p)$.
Supongamos sin pérdida de generalidad que $q \in (p)$.  Entonces $\exists s \in K[x]$ tal que $q = ps$. Así, $p=qr = psr$. Entonces, $sr = 1_{K[x]}$ y $r$ es un elemento invertible.
```

**Tema:** [[Anillo de polinomios#5. Irreducibilidad]]

**Definiciones referenciadas:** [[Cuerpo]], [[Polinomio mónico]], [[Polinomio irreducible]], [$(p)$](Ideal generado), [$R/I$](Teorema del anillo cociente) 
**Resultados referenciados:**

---
### Anki
