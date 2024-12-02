### Contenido Principal

```ad-proposition
Sean $(X, d), (Y, d')$ espacios métricos, $f: X \mapsto Y$ una aplicación. Entonces $f$ es continua en $x_0$ $\iff$ $\forall \{x_n \}_{n = 1}^\infty \subseteq X$ tal que $x_n \to x_0$, $\{f(x_n) \}_{n = 1}^\infty \to f(x_0)$.
```

```ad-proof
$\Rightarrow$.
Sea $f$ continua en $x_0$ y sea $\{x_n \} \to x_0$. Como $f$ continua en $x_0$, entonces $\forall U \in \mathcal E(f(x_0))$, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq U$, y $\exists n_0$ tal que $\forall n > n_0$, $x_n \in V$. Así, $\forall n > n_0$, $f(x_n) \in U$ $\implies$ $\{f(x_n) \} \to f(x_0)$.

$\Leftarrow$.
Supongamos por reducción al absurdo que $f$ no es continua en $x_0$, luego $\exists \varepsilon > 0$ tal que $\forall \delta > 0$, $\exists x_\delta \in X$ tal que $d(x_\delta, x_0) < \delta$, pero $d'(f(x_\delta), f(x_0)) \ge \varepsilon$. Consideramos $\delta := \frac{1}{n}$ y así tenemos $\{x_n \}_{n = 1}^\infty$ tal que $d(x_n, x_0) < \frac{1}{n}$ y $d'(f(x_n), f(x_0)) \ge \varepsilon$.
Por lo tanto, tenemos que $\{d(x_n, x_0) \} \to 0$, lo que implica que $\{x_n \} \to x_0$, y $\{d'(f(x_n), f(x_0)) \} \not \to 0$, lo que implica que $\{f(x_n) \} \not \to f(x_0)$, lo cual es una contradicción con la hipótesis. Luego $f$ es continua en $x_0$.
```

**Tema:** [[Continuidad]]

**Resultados referenciados:** [$\{x_n\} \to x \iff \forall \varepsilon > 0, \, \exists n_0 : \forall n > n_0 \quad d(x_n, x) < \varepsilon$](Caracterización de convergencia en espacios métricos (distancia)), [[(ejercicio) Caracterización de convergencia en espacios métricos (sucesión de distancias)]].

---
### Anki

START
Básico
Anverso: Caracterización de continuidad en espacios métricos por sucesiones
Reverso: Sean $(X, d), (Y, d')$ espacios métricos, $f: X \mapsto Y$ una aplicación. Entonces $f$ es continua en $x_0$ $\iff$ $\forall \{x_n \}_{n = 1}^\infty \subseteq X$ tal que $x_n \to x_0$, $\{f(x_n) \}_{n = 1}^\infty \to f(x_0)$.
Tags: top
<!--ID: 1730228001616-->
END

START
Básico
Anverso: Demostración de que sean $(X, d), (Y, d')$ espacios métricos, $f: X \mapsto Y$ una aplicación. Entonces $f$ es continua en $x_0$ $\iff$ $\forall \{x_n \}_{n = 1}^\infty \subseteq X$ tal que $x_n \to x_0$, $\{f(x_n) \}_{n = 1}^\infty \to f(x_0)$.
Reverso: $\Rightarrow$.
Sea $f$ continua en $x_0$ y sea $\{x_n \} \to x_0$. Como $f$ continua en $x_0$, entonces $\forall U \in \mathcal E(f(x_0))$, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq U$, y $\exists n_0$ tal que $\forall n > n_0$, $x_n \in V$. Así, $\forall n > n_0$, f(x_n) \in U$ $\implies$ $\{f(x_n) \} \to f(x_0)$.

$\Leftarrow$.
Supongamos por reducción al absurdo que $f$ no es continua en $x_0$, luego $\exists \varepsilon > 0$ tal que $\forall \delta > 0$, $\exists x_\delta \in X$ tal que $d(x_\delta, x_0) < \delta$, pero $d'(f(x_\delta), f(x_0)) \ge \varepsilon$. Consideramos $\delta := \frac{1}{n}$ y así tenemos $\{x_n \}_{n = 1}^\infty$ tal que $d(x_n, x_0) < \frac{1}{n}$ y $d'(f(x_n), f(x_0)) \ge \varepsilon$.
Por lo tanto, tenemos que $\{d(x_n, x_0) \} \to 0$, lo que implica que $\{x_n \} \to x_0$, y $\{d'(f(x_n), f(x_0)) \} \not \to 0$, lo que implica que $\{f(x_n) \} \not \to f(x_0)$, lo cual es una contradicción con la hipótesis. Luego $f$ es continua en $x_0$.
Tags: dem top
<!--ID: 1730228001618-->
END

