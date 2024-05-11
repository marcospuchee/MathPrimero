
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-22, 19:55

```ad-proposition
Sea $f: [a,b] \to \mathbb R$ acotada, $a<c<b$.
$$f \in R[a,b] \iff f \in R[a,c] \land f \in  R[c,b].$$
En particular, $\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_c^b f(x) \, dx$.
```


```ad-proof
$\rightarrow$.
Sea $f \in R[a,b]$. Fijamos $\varepsilon > 0$, por el [[criterio de integrabilidad]], $\exists P \in \mathcal P [a,b]$ tal que $U(f, P) - L(f, P) < \varepsilon$. Podemos suponer que si $c \in P$, $Q_1 = P \cap [a,c]$ es partición de $[a,c]$ y $Q_2 = P \cap [c,b]$ es partición de $[c,b]$.

Se cumple que
$$L(f, P) = L(f, Q_1) + L(f, Q_2), \quad U(f, P)= U(f, Q_1) + U(f, Q_2).$$
Por tanto,
$$(U(f, Q_1) - L(f, Q_1)) + (U(f, Q_2) - L(f, Q_2)) = U(f, P) - L(f, P) < \varepsilon.$$
Sin embargo, como $(U(f, Q_1) - L(f, Q_1)), (U(f, Q_2) - L(f, Q_2)) \ge 0$, entonces tenemos que
$$U(f, Q_1) - L(f, Q_1) < \varepsilon, \quad U(f, Q_2) - L(f, Q_2) < \varepsilon.$$
Luego, $f \in R[a,c]$ y $f \in R[c,b]$.

$\leftarrow$.
Fijamos $\varepsilon > 0$. Por el criterio de integrabilidad,
$$\begin{array}{l}
\exists Q_1 > 0 \in \mathcal P[a,c]: U(f, Q_1) - L(f, Q_1) < \frac{\varepsilon}{2} \\
\exists Q_2 > 0 \in \mathcal P[c,b]: U(f, Q_2) - L(f, Q_2) < \frac{\varepsilon}{2}
\end{array}$$
Tomando $P = Q_1 \cup Q_2 \in \mathcal P[a,b]$, tenemos $U(f, P) - L(f, P) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon$. Luego $f \in R[a,b]$.

Veamos que $\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_a^b f(x) \,dx$.
Fijamos $\varepsilon > 0$, $\exists Q_1 \in P[a,b], Q_2 \in P[a,b]$ tales que $P_\varepsilon Q_1 \cup Q_2$ cumple que $U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon$.
Se sabe que:
1. $L(f, P_\varepsilon) \le \int_a^b f(x) \,dx \le U(f, P_\varepsilon)$.
2. $L(f, Q_1) \le \int_a^c f(x) \, dx \le U(f, Q_1) \land L(f, Q_2) \le \int_c^b f(x) \, dx \le U(f, Q_2).$

Sumando (2) queda:
$$L(f, P_\varepsilon) \le \int_a^c f(x) \, dx + \int_c^b f(x) \, dx \le U(f, P_\varepsilon).$$
Luego: 
$$|\int_a^b f(x) \, dx - (\int_a^c f(x) \, dx + \int_c^b f(x) \, dx)| \le U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon.$$
Esto implica que
$$\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_c^b f(x) \, dx.$$
```

**Tema:** [[Integración de funciones de una variable real#1. Integral de Riemann]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la proposición que permite dividir una integral en dos?
Reverso: Sea $f: [a,b] \to \mathbb R$ acotada, $a<c<b$.
$$f \in R[a,b] \iff f \in R[a,c] \land f \in  R[c,b].$$
En particular, $\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_c^b f(x) \, dx$.
Tags: proposición/teorema análisisI
<!--ID: 1714669443787-->
END

START
Básico
Anverso: Demostración de que sea $f: [a,b] \to \mathbb R$ acotada, $a<c<b$.
$$f \in R[a,b] \iff f \in R[a,c] \land f \in  R[c,b].$$
En particular, $\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_c^b f(x) \, dx$.
Reverso: $\rightarrow$.
Sea $f \in R[a,b]$. Fijamos $\varepsilon > 0$, por el [[criterio de integrabilidad]], $\exists P \in \mathcal P [a,b]$ tal que $U(f, P) - L(f, P) < \varepsilon$. Podemos suponer que si $c \in P$, $Q_1 = P \cap [a,c]$ es partición de $[a,c]$ y $Q_2 = P \cap [c,b]$ es partición de $[c,b]$.

Se cumple que
$$L(f, P) = L(f, Q_1) + L(f, Q_2), \quad U(f, P)= U(f, Q_1) + U(f, Q_2).$$
Por tanto,
$$(U(f, Q_1) - L(f, Q_1)) + (U(f, Q_2) - L(f, Q_2)) = U(f, P) - L(f, P) < \varepsilon.$$
Sin embargo, como $(U(f, Q_1) - L(f, Q_1)), (U(f, Q_2) - L(f, Q_2)) \ge 0$, entonces tenemos que
$$U(f, Q_1) - L(f, Q_1) < \varepsilon, \quad U(f, Q_2) - L(f, Q_2) < \varepsilon.$$
Luego, $f \in R[a,c]$ y $f \in R[c,b]$.

$\leftarrow$.
Fijamos $\varepsilon > 0$. Por el criterio de integrabilidad,
$$\begin{array}{l}
\exists Q_1 > 0 \in \mathcal P[a,c]: U(f, Q_1) - L(f, Q_1) < \frac{\varepsilon}{2} \\
\exists Q_2 > 0 \in \mathcal P[c,b]: U(f, Q_2) - L(f, Q_2) < \frac{\varepsilon}{2}
\end{array}$$
Tomando $P = Q_1 \cup Q_2 \in \mathcal P[a,b]$, tenemos $U(f, P) - L(f, P) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon$. Luego $f \in R[a,b]$.

Veamos que $\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_a^b f(x) \,dx$.
Fijamos $\varepsilon > 0$, $\exists Q_1 \in P[a,b], Q_2 \in P[a,b]$ tales que $P_\varepsilon Q_1 \cup Q_2$ cumple que $U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon$.
Se sabe que:
1. $L(f, P_\varepsilon) \le \int_a^b f(x) \,dx \le U(f, P_\varepsilon)$.
2. $L(f, Q_1) \le \int_a^c f(x) \, dx \le U(f, Q_1) \land L(f, Q_2) \le \int_c^b f(x) \, dx \le U(f, Q_2).$

Sumando (2) queda:
$$L(f, P_\varepsilon) \le \int_a^c f(x) \, dx + \int_c^b f(x) \, dx \le U(f, P_\varepsilon).$$
Luego: 
$$|\int_a^b f(x) \, dx - (\int_a^c f(x) \, dx + \int_c^b f(x) \, dx)| \le U(f, P_\varepsilon) - L(f, P_\varepsilon) < \varepsilon.$$
Esto implica que
$$\int_a^b f(x) \, dx = \int_a^c f(x) \, dx + \int_c^b f(x) \, dx.$$
Tags: demostración análisisI
<!--ID: 1714669443792-->
END
