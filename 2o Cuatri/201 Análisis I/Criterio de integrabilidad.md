
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 16:36

```ad-theorem
Sea $f: [a,b] \to \mathbb R$ una [[función acotada]].

$f \in \mathcal R[a,b]$ ([[integral de Riemann]]) $\iff \forall \varepsilon > 0, \exists P_\varepsilon \in \mathcal P([a,b])$ ([[partición de un intervalo]]) $: U(f, P_\varepsilon)$ ([[suma superior de Riemann]]) $- L(f, P_\varepsilon)$ ([[suma inferior de Riemann]]) $< \varepsilon$.

$$f \in \mathcal R[a,b] \iff \forall \varepsilon > 0, \exists P_\varepsilon \in \mathcal P([a,b]) : U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon.$$

```

```ad-proof
$\rightarrow$.
Suponemos que $f \in R[a,b]$. Fijamos $\varepsilon > 0$. Tenemos que:
$$\int_a^b f(x) \, dx = \inf\{U(f, Q) : Q \in \mathcal P([a,b]) \} = \sup \{L(f, Q) : Q \in \mathcal P([a,b]) \}.$$
Luego,
$$\int_a^b f(x) \, dx - \frac{\varepsilon}{2} < L(f, Q_1) \land \int_a^b f(x) \, dx + \frac{\varepsilon}{2} > U(f, Q_2),$$
para algunos $Q_1, Q_2 \in \mathcal P([a,b])$.
Tomamos $P_\varepsilon = Q_1 \cup Q_2$. Entonces,
$$\int_a^b f(x) \, dx - \frac{\varepsilon}{2} < L(f, Q_1) \le L(f, P_\varepsilon) \le U(f, P_\varepsilon) \le U(f, Q_2) < \int_a^b f(x) \, dx + \frac{\varepsilon}{2}.$$
Por tanto,
$$U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon.$$

$\leftarrow$.
Fijamos $\varepsilon > 0$ y tomamos $P_\varepsilon \in \mathcal P([a,b])$ tal que $U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon$. Entonces,
$$L(f, P_\varepsilon) \le \underline{\int_a^b} f(x) \, dx \le \overline{\int_a^b} f(x) \, dx < U(f, P_\varepsilon)$$
([[integrales de Darboux]]), lo que implica que
$$0 \le \left | \overline{\int_a^b} f(x) \, dx - \underline{\int_a^b} f(x) \, dx \right | < \varepsilon, \quad \forall \varepsilon > 0.$$
Por tanto,
$$\overline{\int_a^b} f(x) \, dx = \underline{\int_a^b} f(x) \, dx,$$
es decir, $f \in \mathcal R[a,b].$
```

**Tema:** [[Integración de funciones de una variable real#1. Integral de Riemann]]
**Demostrado por:**
**Consecuencias:** [[Teorema monotonía implica integrabilidad]], [[Teorema continuidad implica integrabilidad]]

---
### Anki

START
Básico
Anverso: Qué dice el criterio de integrabilidad?
Reverso:Sea $f: [a,b] \to \mathbb R$ una [[función acotada]].

$f \in \mathcal R[a,b]$ ([[integral de Riemann]]) $\iff \forall \varepsilon > 0, \exists P_\varepsilon \in \mathcal P([a,b])$ ([[partición de un intervalo]]) $: U(f, P_\varepsilon)$ ([[suma superior de Riemann]]) $- L(f, P_\varepsilon)$ ([[suma inferior de Riemann]]) $< \varepsilon$.

$$f \in \mathcal R[a,b] \iff \forall \varepsilon > 0, \exists P_\varepsilon \in \mathcal P([a,b]) : U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon.$$
Tags: proposición/teorema análisisI
<!--ID: 1714669443825-->
END

START
Básico
Anverso: Demostración del criterio de integrabilidad
Reverso: $\rightarrow$.
Suponemos que $f \in R[a,b]$. Fijamos $\varepsilon > 0$. Tenemos que:
$$\int_a^b f(x) \, dx = \inf\{U(f, Q) : Q \in \mathcal P([a,b]) \} = \sup \{L(f, Q) : Q \in \mathcal P([a,b]) \}.$$
Luego,
$$\int_a^b f(x) \, dx - \frac{\varepsilon}{2} < L(f, Q_1) \land \int_a^b f(x) \, dx + \frac{\varepsilon}{2} > U(f, Q_2),$$
para algunos $Q_1, Q_2 \in \mathcal P([a,b])$.
Tomamos $P_\varepsilon = Q_1 \cup Q_2$. Entonces,
$$\int_a^b f(x) \, dx - \frac{\varepsilon}{2} < L(f, Q_1) \le L(f, P_\varepsilon) \le U(f, P_\varepsilon) \le U(f, Q_2) < \int_a^b f(x) \, dx + \frac{\varepsilon}{2}.$$
Por tanto,
$$U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon.$$

$\leftarrow$.
Fijamos $\varepsilon > 0$ y tomamos $P_\varepsilon \in \mathcal P([a,b])$ tal que $U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon$. Entonces,
$$L(f, P_\varepsilon) \le \underline{\int_a^b} f(x) \, dx \le \overline{\int_a^b} f(x) \, dx < U(f, P_\varepsilon)$$
([[integrales de Darboux]]), lo que implica que
$$0 \le \left | \overline{\int_a^b} f(x) \, dx - \underline{\int_a^b} f(x) \, dx \right | < \varepsilon, \quad \forall \varepsilon > 0.$$
Por tanto,
$$\overline{\int_a^b} f(x) \, dx = \underline{\int_a^b} f(x) \, dx,$$
es decir, $f \in \mathcal R[a,b].$
Tags: demostración análisisI
<!--ID: 1714669443829-->
END