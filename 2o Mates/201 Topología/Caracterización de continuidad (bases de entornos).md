### Contenido Principal

```ad-proposition
Sea $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$, supongamos que $\mathcal B(x_0)$ y $\mathcal B(f(x_0))$ son bases de entornos de $x_0 \in X$ y $f(x_0) \in Y$. Entonces, $f$ es continua en $x_0$ $\iff$ $\forall B \in \mathcal B(f(x_0))$, $\exists B' \in \mathcal B(x_0)$ tal que $f(B') \subseteq B$.
```

```ad-note
title: Espacios métricos
Sea $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$ aplicación entre espacios métricos. $f$ es continua en $x_0$ $\iff$ $\forall \varepsilon > 0$, $\exists \delta > 0$ tal que si $d(x,x_0) < \delta$, entonces $d(f(x), f(x_0)) < \varepsilon$.
```

```ad-proof
$\Rightarrow$.
Supongamos que $f$ continua en $x_0$. Sea $B \in \mathcal B(f(x_0))$, entonces $B \in \mathcal E(f(x_0))$. Por ser $f$ continua, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq B$, y $\exists B' \in \mathcal B(x_0)$ tal que $B' \subseteq V$. Por tanto, $f(B') \subseteq B$.

$\Leftarrow$.
Sea $U \in \mathcal E(f(x_0))$, entonces $\exists B \in \mathcal B(f(x_0))$ tal que $B \subseteq U$. Por hipótesis, $\exists B' \in \mathcal B(x_0)$ tal que $f(B') \subseteq B$. Así, $f(B') \subseteq U$ y $B' \in \mathcal E(x_0)$, lo que implica que $f$ es continua en $x_0$.
```

**Tema:** [[Continuidad]]

---
### Anki

START
Básico
Anverso: Caracterización de continuidad por bases de entornos
Reverso: Sea $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$, supongamos que $\mathcal B(x_0)$ y $\mathcal B(f(x_0))$ son bases de entornos de $x_0 \in X$ y $f(x_0) \in Y$. Entonces, $f$ es continua en $x_0$ $\iff$ $\forall B \in \mathcal B(f(x_0))$, $\exists B' \in \mathcal B(x_0)$ tal que $f(B') \subseteq B$.
Tags: top
<!--ID: 1730228001621-->
END

START
Básico
Anverso: Caracterización de continuidad en espacios métricos por distancias
Reverso: Sea $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$ aplicación entre espacios métricos. $f$ es continua en $x_0$ $\iff$ $\forall \varepsilon > 0$, $\exists \delta > 0$ tal que si $d(x,x_0) < \delta$, entonces $d(f(x), f(x_0)) < \varepsilon$.
Tags: top
<!--ID: 1730228001623-->
END


START
Básico
Anverso: Demostración de que sea $f: (X, \mathcal T) \mapsto (Y, \mathcal T')$, supongamos que $\mathcal B(x_0)$ y $\mathcal B(f(x_0))$ son bases de entornos de $x_0 \in X$ y $f(x_0) \in Y$. Entonces, $f$ es continua en $x_0$ $\iff$ $\forall B \in \mathcal B(f(x_0))$, $\exists B' \in \mathcal B(x_0)$ tal que $f(B') \subseteq B$.
Reverso: $\Rightarrow$.
Supongamos que $f$ continua en $x_0$. Sea $B \in \mathcal B(f(x_0))$, entonces $B \in \mathcal E(f(x_0))$. Por ser $f$ continua, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq B$, y $\exists B' \in \mathcal B(x_0)$ tal que $B' \subseteq V$. Por tanto, $f(B') \subseteq B$.

$\Leftarrow$.
Sea $U \in \mathcal E(f(x_0))$, entonces $\exists B \in \mathcal B(f(x_0))$ tal que $B \subseteq U$. Por hipótesis, $\exists B' \in \mathcal B(x_0)$ tal que $f(B') \subseteq B$. Así, $f(B') \subseteq U$ y $B' \in \mathcal E(x_0)$, lo que implica que $f$ es continua en $x_0$.
Tags: dem top
<!--ID: 1730228001626-->
END
