### Contenido principal

```ad-Formal
Sea $G$ un grupo y $H \le G$. Definimos $G \curvearrowright \mathcal L_H$ como sigue
1. $g \cdot xH = (gx)H$.
2. $\textrm{Orb}_{xH} = \{(gx)H : g \in G \} = \mathcal L_H$. La acción es transitiva.
3. $\textrm{Stab}_{xH} = \{g \in G : (gx)H = xH \} = \{g \in G : x^{-1}gx \in H \} = xHx^{-1} \le G$.
4. No hay puntos fijos (si $H \neq G$).
```

```ad-note
1. $|G: {}^xH| = |\mathcal L_H| = |G:H|$.
2. El núcleo de la acción es
$$\textrm{Ker}(\rho) = \bigcap_{x \in G} \textrm{Stab}_{xH} = \bigcap_{x \in G} {}^xH \unlhd G.$$
En particular, al núcleo de esta acción se le llama core de $H$ en $G$, denotado $\textrm{Core}_G(H)$.
```

**Tema:** [[Acciones de grupos#4. La acción sobre clases]]

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo), [$\textrm{Orb} \\_ \alpha$](Órbita), [[Acción transitiva]], [$\textrm{Stab} \\_ \alpha$](Estabilizador), [Punto fijo](Estabilizador), [$\textrm{Ker}(\rho)$](Núcleo de la acción)
**Resultados referenciados:** [$|\textrm{Orb} \\_ \alpha | = |G: \textrm{Stab} \\_ \alpha |$](Teorema órbita-estabilizador).

---
### Anki

START
Básico
Anverso: Acción sobre clases
Reverso: Sea $G$ un grupo y $H \le G$. Definimos $G \curvearrowright \mathcal L_H$ como sigue
1. $g \cdot xH = (gx)H$.
2. $\textrm{Orb}_{xH} = \{(gx)H : g \in G \} = \mathcal L_H$. La acción es transitiva.
3. $\textrm{Stab}_{xH} = \{g \in G : (gx)H = xH \} = \{g \in G : x^{-1}gx \in H \} = xHx^{-1} \le G$.
4. No hay puntos fijos (si $H \neq G$).
Tags: est
END

START
Básico
Anverso: Definición de $\textrm{Core}_G(H)$
Reverso: El núcleo de la acción es
$$\textrm{Ker}(\rho) = \bigcap_{x \in G} \textrm{Stab}_{xH} = \bigcap_{x \in G} {}^xH \unlhd G.$$
En particular, al núcleo de esta acción se le llama core de $H$ en $G$, denotado $\textrm{Core}_G(H)$.
Tags: est
END

