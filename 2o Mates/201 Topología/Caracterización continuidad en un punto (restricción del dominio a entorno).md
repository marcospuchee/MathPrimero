### Contenido Principal

```ad-proposition
Sean $f: (X, \mathcal T) \to (Y, \mathcal T')$, $x_0 \in X$. Entonces, $f$ es continua en $x_0$ $\iff$ $\exists U \in \mathcal E(x_0)$ tal que $f \restriction_U : (U, \mathcal T_U) \to (Y, \mathcal T')$ es continua en $x_0$.
```

```ad-proof
$\Rightarrow$.
Tomando $U:= X \in \mathcal E(x_0)$, entonces $f \restriction_U$ $=$ $f \restriction_X$ $=$ $f$, que es continua en $x_0$.

$\Leftarrow$.
Supongamos que $\exists U \in \mathcal E(x)$ tal que $f \restriction_U: (U, \mathcal T_U) \to (Y, \mathcal T')$ es continua en $x_0$. Sea $U' \in \mathcal E(f(x_0))$, entonces $\exists V \in \mathcal E_U(x_0)$ tal que $f \restriction_U (V) \subseteq U'$. Como $V \in \mathcal E_U(x_0)$, entonces $\exists W \in \mathcal E(x_0)$ tal que $V = W \cap U \in \mathcal E(x_0)$, dado que $W,U \in \mathcal E(x_0)$. Por tanto, $f(V) = f \restriction_U (V) \subseteq U'$, lo que implica que $f$ es continua en $x_0$.
```

**Tema:** [[Subespacios topológicos#3. Continuidad y subespacios.]]

**Definiciones referenciadas:** [[Función continua]], [$\mathcal T_U$](Topología inducida), [[Entorno]]
**Resultados referenciados:** [$V \in \mathcal E_U(x) \iff \exists W \in \mathcal E(x_0) : V = W \cap U$](Caracterización entorno en topología inducida (entorno topología padre))

---
### Anki
