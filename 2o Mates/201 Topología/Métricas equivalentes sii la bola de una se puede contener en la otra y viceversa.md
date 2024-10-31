### Contenido Principal

```ad-proposition
Dos [[métrica]]s $d,d'$ son equivalentes ([[métricas equivalentes]]) $\iff$ $\forall x \in X$, $\forall \varepsilon > 0$, se cumple:
1. $\exists \delta > 0$ tal que $B_d(x; \delta) \subseteq B_{d'}(x; \varepsilon)$.
2. $\exists \delta' > 0$ tal que $B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon)$.
```

```ad-proof
$\rightarrow$. Sean $d,d'$ métricas equivalentes. Sea $B_{d'}(x; \varepsilon)$ una bola cualquiera. Como $\mathcal T_d = \mathcal T_{d'}$, $B_{d'}(x; \varepsilon) \in \mathcal T_{d'} = \mathcal T_d$. Por tanto, $\exists \delta > 0$ tal que $x \in B_d (x; \delta) \subseteq B_{d'}(x; \varepsilon)$. El apartado $(2)$ se cumple de manera análoga.

$\leftarrow$. Supongamos que se cumplen $(1)$ y $(2)$. Sean $A \in \mathcal T_d, x \in A$, entonces $\exists \varepsilon > 0$ tal que $x \in B_d(x; \varepsilon) \subseteq A$. Por $(2)$, sabemos que $\exists \delta' > 0$ tal que $B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon)$, lo que impica que $x \in B_{d'}(x; \delta') \subseteq A$, lo que implica que $A \in \mathcal T_{d'}$, lo que implica que $\mathcal T_d \subseteq \mathcal T_{d'}$. Por un razonamiento análogo, con $(1)$, $\mathcal T_{d'} \subseteq \mathcal T_d$.
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos#Métricas equivalentes.|Espacios topológicos]]

---
### Anki

START
Básico
Anverso: Proposición métricas son equivalentes sii la bola de una se puede contener en la otra y viceversa
Reverso: Dos [[métrica]]s $d,d'$ son equivalentes ([[métricas equivalentes]]) $\iff$ $\forall x \in X$, $\forall \varepsilon > 0$, se cumple:
1. $\exists \delta > 0$ tal que $B_d(x; \delta) \subseteq B_{d'}(x; \varepsilon)$.
2. $\exists \delta' > 0$ tal que $B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon)$.
<!--ID: 1728138052361-->
END

START
Básico
Anverso: Demostración de que sos [[métrica]]s $d,d'$ son equivalentes ([[métricas equivalentes]]) $\iff$ $\forall x \in X$, $\forall \varepsilon > 0$, se cumple:
1. $\exists \delta > 0$ tal que $B_d(x; \delta) \subseteq B_{d'}(x; \varepsilon)$.
2. $\exists \delta' > 0$ tal que $B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon)$.
Reverso: $\rightarrow$. Sean $d,d'$ métricas equivalentes. Sea $B_{d'}(x; \varepsilon)$ una bola cualquiera. Como $\mathcal T_d = \mathcal T_{d'}$, $B_{d'}(x; \varepsilon) \in \mathcal T_{d'} = \mathcal T_d$. Por tanto, $\exists \delta > 0$ tal que $x \in B_d (x; \delta) \subseteq B_{d'}(x; \varepsilon)$. El apartado $(2)$ se cumple de manera análoga.

$\leftarrow$. Supongamos que se cumplen $(1)$ y $(2)$. Sean $A \in \mathcal T_d, x \in A$, entonces $\exists \varepsilon > 0$ tal que $x \in B_d(x; \varepsilon) \subseteq A$. Por $(2)$, sabemos que $\exists \delta' > 0$ tal que $B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon)$, lo que impica que $x \in B_{d'}(x; \delta') \subseteq A$, lo que implica que $A \in \mathcal T_{d'}$, lo que implica que $\mathcal T_d \subseteq \mathcal T_{d'}$. Por un razonamiento análogo, con $(1)$, $\mathcal T_{d'} \subseteq \mathcal T_d$.
Tags: dem top
<!--ID: 1728138052363-->
END
