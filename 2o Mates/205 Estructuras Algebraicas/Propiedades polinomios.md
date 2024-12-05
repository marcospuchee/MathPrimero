### Contenido Principal

```ad-theorem
Sea $R$ un anillo. Entonces
1. $\forall p,q \in R[x], \delta(p+q) \le \max \{\delta(p), \delta(q) \}$. Por tanto, $p+q \in R[x]$.
2. $\forall p,q \in R[x], \delta(pq) \le \delta(p) + \delta(q)$. Por tanto, $pq \in R[x]$.
3. $(R[x], +, \cdot)$ es un anillo.
4. Si $R$ es conmutativo, entonces $R[x]$ es conmutativo.
5. Si $R$ tiene unidad, entonces $R[x]$ tiene identidad:
$$1_{R[x]} = 1_R = (1_R, 0_R, 0_R, \dots) \in R[x].$$
```

```ad-proof
1. Vemos que $\delta(p+q) \le \max \{\delta(p), \delta(q) \}$. Sea $i > \max \{\delta(p), \delta(q) \}$. Tenemos que $r_i = 0_R$ y $s_i = 0_R$. Por tanto, el coeficiente $i$-ésimo del polinomio $p+q$ es $r_i + s_i = 0_R + 0_R = 0_R$.
2. Vemos que $\delta(pq) \le \delta(p) + \delta(q)$. Sea $i > \delta(p) + \delta(q)$. Recordamos que el coeficiente $i$-ésimo de $pq$ es $\sum_{j+k = i} r_js_k$. Pero si $j+k = i > \delta(p) + \delta(q)$, entonces $j > \delta(p)$ o $k > \delta(q)$. Así, si $j > \delta(p)$, entonces $r_j = 0_R$, y $r_js_k = 0_R$. Un mismo razonamiento lleva a la misma conclusión con $k > \delta(q)$. Por tanto, el coeficiente $i$-ésimo de $pq$ es $0_R$.
3. Ejercicio.
4. Ejercicio.
5. Ejercicio.
```

**Tema:** [[Anillo de polinomios#2. Anillo de polinomios.]]

**Definiciones referenciadas:** [[Suma de polinomios]], [[Multiplicación de polinomios]], [[Anillo]], [[Anillo conmutativo]], [[Anillo con identidad]]
**Resultados referenciados:** -.

---
### Anki

START
Básico
Anverso: Propiedades de los polinomios
Reverso: Sea $R$ un anillo. Entonces
1. $\forall p,q \in R[x], \delta(p+q) \le \max \{\delta(p), \delta(q) \}$. Por tanto, $p+q \in R[x]$.
2. $\forall p,q \in R[x], \delta(pq) \le \delta(p) + \delta(q)$. Por tanto, $pq \in R[x]$.
3. $(R[x], +, \cdot)$ es un anillo.
4. Si $R$ es conmutativo, entonces $R[x]$ es conmutativo.
5. Si $R$ tiene unidad, entonces $R[x]$ tiene identidad:
$$1_{R[x]} = 1_R = (1_R, 0_R, 0_R, \dots) \in R[x].$$
Tags: est
<!--ID: 1733312055981-->
END

START
Básico
Anverso: Demostración de que sea $R$ un anillo. Entonces
1. $\forall p,q \in R[x], \delta(p+q) \le \max \{\delta(p), \delta(q) \}$. Por tanto, $p+q \in R[x]$.
2. $\forall p,q \in R[x], \delta(pq) \le \delta(p) + \delta(q)$. Por tanto, $pq \in R[x]$.
3. $(R[x], +, \cdot)$ es un anillo.
Reverso: 1. Vemos que $\delta(p+q) \le \max \{\delta(p), \delta(q) \}$. Sea $i > \max \{\delta(p), \delta(q) \}$. Tenemos que $r_i = 0_R$ y $s_i = 0_R$. Por tanto, el coeficiente $i$-ésimo del polinomio $p+q$ es $r_i + s_i = 0_R + 0_R = 0_R$.
2. Vemos que $\delta(pq) \le \delta(p) + \delta(q)$. Sea $i > \delta(p) + \delta(q)$. Recordamos que el coeficiente $i$-ésimo de $pq$ es $\sum_{j+k = i} r_js_k$. Pero si $j+k = i > \delta(p) + \delta(q)$, entonces $j > \delta(p)$ o $k > \delta(q)$. Así, si $j > \delta(p)$, entonces $r_j = 0_R$, y $r_js_k = 0_R$. Un mismo razonamiento lleva a la misma conclusión con $k > \delta(q)$. Por tanto, el coeficiente $i$-ésimo de $pq$ es $0_R$.
3. Se deduce de los puntos anteriores.
Tags: est dem 
<!--ID: 1733312055983-->
END
