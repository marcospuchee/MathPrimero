### Contenido Principal

```ad-proposition
Sea $G \curvearrowright \Omega$. Entonces
1. $\forall \alpha \in \Omega$, $\textrm{Stab}_\alpha \le G$.
2. $\forall \alpha \in \Omega$ y todo $g \in G$, $\textrm{Stab}_{g \cdot \alpha} = g \textrm{Stab}_\alpha g^{-1}$.
3. La familia $\{\textrm{Orb}_\alpha \, | \, \alpha \in \Omega \}$ forma una partición de $\Omega$.
```

```ad-proof
1. Sea $\alpha \in \Omega$. Demostramos que $\textrm{Stab}_\alpha \le G$. En primer lugar, $1_G \in \textrm{Stab}_\alpha$ ya que, por la definición de acción, $1_G \cdot \alpha = \alpha$. Sean $g,h \in \textrm{Stab}_\alpha$, esto es, $g \cdot \alpha = \alpha$ y $h \cdot \alpha = \alpha$. Vemos que $gh \in \textrm{Stab}_\alpha$:
$$(gh) \cdot \alpha = g \cdot (h \cdot \alpha) = g \cdot \alpha = \alpha.$$
Sea $g \in \textrm{Stab}_\alpha$, esto es, $g \cdot \alpha = \alpha$. Demostramos que $g^{-1} \in \textrm{Stab}_\alpha$.
$$g^{-1} \cdot \alpha = g^{-1} \cdot (g \cdot \alpha) = (g^{-1}g) \cdot \alpha = 1_G \cdot \alpha = \alpha.$$

2. Sean $g \in G$ y $\alpha \in \Omega$. Demostramos que $g \textrm{Stab}_\alpha g^{-1} = \textrm{Stab}_{g \cdot \alpha}$.
$\subseteq$. Sea $x \in g \textrm{Stab}_\alpha g^{-1}$, por tanto, $\exists y \in \textrm{Stab}_\alpha$ tal que $x = gyg^{-1}$. Vemos que $x \in \textrm{Stab}_{g \cdot \alpha}$:
$$x \cdot (g \cdot \alpha) = (xg) \cdot \alpha = (gyg^{-1}g) \cdot \alpha = (gy) \cdot \alpha = g \cdot (y \cdot \alpha) = g \cdot \alpha.$$
$\supseteq$. Sea $x \in \textrm{Stab}_{g \cdot \alpha}$, esto es, $x \cdot (g \cdot \alpha) = g \cdot \alpha$. Demostramos que $x \in g \textrm{Stab}_\alpha g^{-1}$, equivalentemente: $g^{-1}xg \in \textrm{Stab}_\alpha$.
$$(g^{-1}xg) \cdot \alpha =  g^{-1} \cdot (x \cdot (g \cdot \alpha)) = g^{-1} \cdot (g \cdot \alpha) = (g^{-1}g) \cdot \alpha = 1_G \cdot \alpha = \alpha.$$

3. Demostramos que $\{\textrm{Orb}_\alpha : \alpha \in \Omega \}$ forma una partición de $\Omega$. En primer lugar, como $\forall \alpha \in \Omega$, $\alpha = 1_G \cdot \alpha \in \textrm{Orb}_\alpha$. Por tanto,
$$\Omega = \bigcup_{\alpha \in \Omega} \{\alpha \} \subseteq \bigcup_{\alpha \in \Omega} \textrm{Orb}_\alpha \subseteq \Omega \implies \bigcup_{\alpha \in \Omega} \textrm{Orb}_\alpha = \Omega.$$
Ahora demostramos que, $\forall \alpha, \beta \in \Omega$, si $\textrm{Orb}_\alpha \neq \textrm{Orb}_\beta$, entonces $\textrm{Orb}_\alpha \cap \textrm{Orb}_\beta = \emptyset$. Lo demostramos por contrarrecíproco, esto es, demostramos que, si $\textrm{Orb}_\alpha \cap \textrm{Orb}_\beta \neq \emptyset$ entonces $\textrm{Orb}_\alpha = \textrm{Orb}_\beta$. Suponemos que $\gamma \in \textrm{Orb}_\alpha \cap \textrm{Orb}_\beta$, esto es, $\exists g_1, g_2 \in G$ tales que $\gamma = g_1 \cdot \alpha = g_2 \cdot \beta$. Veamos que $\textrm{Orb}_\alpha = \textrm{Orb}_\beta$.
$\subseteq$. Sea $\omega \in \textrm{Orb}_\alpha$, esto es, $\exists h \in G$ tal que $\omega = h \cdot \alpha$. Consideramos $hg_1^{-1}g_2 \in G$ y notamos que
$$(hg_1^{-1}g_2) \cdot \beta = (hg_1^{-1}) \cdot (g_2 \cdot \beta) = (hg_1^{-1}) \cdot (g_1 \cdot \alpha) = (hg_1^{-1}g_1) \cdot \alpha = h \cdot \alpha = \omega.$$
$\supseteq$. Similar.
```

**Tema:** [[Acciones de grupos#2. Teorema Órbita-Estabilizador.]]

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo), [$\textrm{Stab} \\_ \alpha$](Estabilizador), [$\textrm{Orb} \\_ \alpha$](Órbita), [[Subgrupo]], [[Partición de un conjunto]]
**Resultados referenciados:** *ninguno.*

---
### Anki
