### Contenido Principal

```ad-cor
Sean $d,d'$ [[métrica]]s en $X$. Si $\exists m, M > 0$ tales que $\forall x,y \in X$
$$md(x,y) \le d'(x,y) \le Md(x,y).$$
Entonces $d,d'$ son [[métricas equivalentes]].
```

```ad-proof
Sea $x \in X$ y $\varepsilon > 0$. Tomamos $\delta = \frac{\varepsilon}{M}$.
$$d(x,y) \le \delta \implies d'(x,y) \le Md(x,y) \le M \delta = \varepsilon \implies B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon).$$

Si tomamos $\delta' = \varepsilon m$,
$$d'(x,y) \le \delta' \implies md(x,y) \le d'(x,y) \le \delta' \implies d(x,y) \le \varepsilon \implies B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon).$$
```

**Tema:** [[2o Mates/201 Topología/Espacios topológicos#Métricas equivalentes.|Espacios topológicos]]

---
### Anki

START
Básico
Anverso: Proposición métricas son equivalentes si existen constantes tales que una envuelve a la otra
Reverso: Sean $d,d'$ [[métrica]]s en $X$. Si $\exists m, M > 0$ tales que $\forall x,y \in X$
$$md(x,y) \le d'(x,y) \le Md(x,y).$$
Entonces $d,d'$ son [[métricas equivalentes]].
<!--ID: 1728138052354-->
END

START
Básico
Anverso: Demostración de que sean $d,d'$ [[métrica]]s en $X$. Si $\exists m, M > 0$ tales que $\forall x,y \in X$
$$md(x,y) \le d'(x,y) \le Md(x,y).$$
Entonces $d,d'$ son [[métricas equivalentes]].
Reverso: Sea $x \in X$ y $\varepsilon > 0$. Tomamos $\delta = \frac{\varepsilon}{M}$.
$$d(x,y) \le \delta \implies d'(x,y) \le Md(x,y) \le M \delta = \varepsilon \implies B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon).$$

Si tomamos $\delta' = \varepsilon m$,
$$d'(x,y) \le \delta' \implies md(x,y) \le d'(x,y) \le \delta' \implies d(x,y) \le \varepsilon \implies B_{d'}(x; \delta') \subseteq B_d(x; \varepsilon).$$
Tags: dem top
<!--ID: 1728138052356-->
END