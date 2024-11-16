### Contenido Principal

```ad-theorem
Sea $G \curvearrowright \Omega$ y $\alpha \in \Omega$. Entonces
$$|\textrm{Orb}_\alpha| = |G: \textrm{Stab}_\alpha|.$$
```

```ad-proof
Consideramos la aplicación $f: \mathcal L_{\textrm{Stab}_\alpha} \to \textrm{Orb}_\alpha$, donde $f(g \textrm{Stab}_\alpha) = g \cdot \alpha$. Demostramos que $f$ es biyectiva, y por tanto,
$$|\mathcal L_{\textrm{Stab}_\alpha}| = |G: \textrm{Stab}_\alpha| = |\textrm{Orb}_\alpha|.$$

Notamos que: $g \textrm{Stab}_\alpha = h \textrm{Stab}_\alpha$ $\iff$ $h^{-1}g  \in \textrm{Stab}_\alpha$ $\iff$ $(h^{-1}g) \cdot \alpha = \alpha$ $\iff$ $g \cdot \alpha = h \cdot \alpha$ $\iff$ $f(g \textrm{Stab}_\alpha) = f(h \textrm{Stab}_\alpha)$. Donde "$\Rightarrow$" demuestra que $f$ está bien definida, y "$\Leftarrow$" demuestra que $f$ es inyectiva.

**$f$ sobreyectiva.**
Sea $\beta \in \textrm{Orb}_\alpha$. Entonces, $\exists g \in G$ tal que $\beta = g \cdot \alpha$. Así, $f(g\textrm{Stab}_\alpha) = g \cdot \alpha = \beta$.
```

**Tema:** [[Acciones de grupos#2. Teorema Órbita-Estabilizador.]]
**Corolario:** [$|\Omega| = \sum^n_ {i = 1} |\textrm{Orb}_ {\alpha_ i}| = \sum^n_ {i = 1} |G: \textrm{Stab} \\_ {\alpha \\_ i}|$](Corolario teorema órbita-estabilizador), [$|\Omega| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb} \\_ {\alpha \\_ i}|$](Corolario 2 teorema órbita-estabilizador)

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo), [$\textrm{Stab} \\_ \alpha$](Estabilizador), [$\textrm{Orb} \\_ \alpha$](Órbita), [$|G:\textrm{Stab}_ \alpha|$](Índice de un subgrupo).
**Resultados referenciados:** [$g \textrm{Stab}_ \alpha = h \textrm{Stab}_ \alpha$ $\iff$ $h^{-1}g  \in \textrm{Stab}_ \alpha$](Propiedades coclases)

---
### Anki
