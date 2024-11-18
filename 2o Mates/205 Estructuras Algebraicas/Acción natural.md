### Contenido principal

```ad-Formal
Sea $n \ge 2$. Definimos $S_n \curvearrowright \{1,2, \dots, n \}$ como sigue
1. $\sigma \cdot i = \sigma(i)$.
2. $\textrm{Orb} \\_ i = \{\sigma(i) : \sigma \in S_n \} = \{1,2, \dots, n \}$. La acción es transitiva.
3. $\textrm{Stab} \\_ i = \{\sigma \in S_n : \sigma(i) = i \} \cong S_{n-1}$.
4. No hay puntos fijos.
```

```ad-note
title: Nota
1. $|S_n:S_{n-1}| = n$.
2. El homomorfismo representación de esta acción es $\textrm{id} \\_ {S_n}: S_n \to S_n$.
```

```ad-proof
Verificamos que es una acción
1. Recordamos que $1_{S_n} = \textrm{id}$. Entonces, $\forall 1 \le i \le n$,
$$1_{S_n} \cdot i = \textrm{id} \cdot i = \textrm{id}(i) = i.$$

2. Sean $\sigma, \tau \in S_n$. Entonces, $\forall 1 \le i \le n$,
$$(\sigma \circ \tau) \cdot i = (\sigma \circ \tau)(i) = \sigma(\tau(i)) = \sigma \cdot (\tau (i)) = \sigma \cdot (\tau \cdot i).$$

Estudiamos la acción:
1. La acción es transitiva: $\forall 1 \le i,j \le n$, $(i,j) \cdot i = j$.
2. Como la acción es transitiva, por definición, sólo existe una órbita, y es el total. Por tanto, $\forall 1 \le i \le n$, $\textrm{Orb}_i = \{1, 2, \dots, n \}$.
3. Además, $\textrm{Stab}_i = \{\sigma \in S_n : \sigma(i) = i \} \cong S_{n-1}$.
4. No hay puntos fijos porque, si $i \in \Omega_\textrm{fix}$, entonces $\textrm{Orb}_i = \{i\}$, pero esto contradice que sólo exista una órbita y sea el total.

Por el teorema órbita-estabilizador, $|S_n:S_{n-1}| = |\textrm{Orb}_i| = n$. Además, construimos el homomorfismo representación de esta acción: para $\sigma \in S_n$,
$$\begin{array}{c c c l}
\rho_\sigma: & \{1,2, \dots, n \} & \to & \{1,2, \dots, n \} \\
& i & \mapsto & \sigma \cdot i = \sigma(i),
\end{array}$$
esto es, $\rho_\sigma = \sigma$. Así,
$$\begin{array}{c c c l}
\rho: & S_n & \to & S_n \\
& \sigma & \mapsto & \rho_\sigma = \sigma,
\end{array}$$
es decir, $\rho = \textrm{id}_{S_n}$. Por eso la llamamos la acción natural.
```


**Tema:** [[Acciones de grupos#3. La acción natural.]]

**Definiciones referenciadas:** [$S_n$](Permutación), [$S_n \curvearrowright \{1,2, \dots, n \}$](Acción de grupo), [$\textrm{Orb} \\_ i$](Órbita), [[Acción transitiva]], [$\textrm{Stab} \\_ i$](Estabilizador), [Punto fijo](Estabilizador), [Acción](Acción de grupo), [Homomorfismo representación](Teorema del homomorfismo representación).
**Resultados referenciados:** [$|\textrm{Orb}_ i | = |S_n: S_{n-1}|$](Teorema órbita-estabilizador)

---
### Anki
