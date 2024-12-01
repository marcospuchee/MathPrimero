### Contenido principal

```ad-Formal
Sea $G$ un grupo. Definimos $G \curvearrowright \textrm{Sub}(G)$ como sigue: $g \cdot H = {}^g H = gHg^{-1}$.
1. $\textrm{Orb}_H = \{gHg^{-1} : g \in G \} = \{ {}^gH : g \in G \}$.
2. $\textrm{Stab}_H = \{g \in G : gHg^{-1} = H \} = \{g \in G : gH = Hg \} =: N_G(H) \le G$. A este subgrupo se le llama normalizador de $H$ en $G$.
3. $H$ es un punto fijo $\iff$ $H \unlhd G$.
```

^7132fc

```ad-note
1. $|\{{}^gH : g \in G \}| = |G: N_G(H)|$.
```

^bcde6a

```ad-proof
Veamos primero que es una acción:
1. $\forall H \le G$, $1_G \cdot H = {}^{1_G} H = H$.
2. $\forall g,h \in G, \, \forall H \le G$,
$$\begin{eqnarray}
(gh) \cdot H &=& {}^{gh}H = (gh)H(gh)^{-1} = (gh)H(h^{-1}g^{-1}) = g(hHh^{-1})g^{-1} \\
&=& g \cdot (h \cdot H)
\end{eqnarray}$$

Estudiamos la acción:
1. $\textrm{Orb}_H = \{^gH \le G : g \in G \}$.
2. $\textrm{Stab}_H = \{g \in G : gHg^{-1} = H \} = \{g \in G : gH = Hg \} = N_G(H) \le G$. Este subgrupo es el normalizador de $H$ en $G$.
3. Notamos que $H \in \Omega_\textrm{fix} \iff \textrm{Orb}_H = \{^g H\le G : g \in G \} = \{H \}$. Esto es, si $\forall g \in G$, $^g H = H$. Por tanto, $H \in \Omega_\textrm{fix} \iff H \unlhd G$.

Por el teorema órbita-estabilizador, $|\{{}^gH : g \in G \}| = |G: N_G(H)|$.
```


**Tema:** [[Acciones de grupos#6. La acción sobre los subgrupos.]]

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo), [$\textrm{Orb} \\_ \alpha$](Órbita), [$\textrm{Stab} \\_ \alpha$](Estabilizador), [Punto fijo](Estabilizador), [$\Omega \\_ \textrm{fix}$](Órbita), [[Subgrupo normal]]
**Resultados referenciados:** [$|\textrm{Orb} \\_ \alpha | = |G: \textrm{Stab} \\_ \alpha |$](Teorema órbita-estabilizador)

---
### Anki

START
Básico
Anverso: Definición de acción sobre los subgrupos
Reverso: Sea $G$ un grupo. Definimos $G \curvearrowright \textrm{Sub}(G)$ como sigue: $g \cdot H = {}^g H = gHg^{-1}$. Tras el estudio de la acción:
1. $\textrm{Orb}_H = \{gHg^{-1} : g \in G \} = \{ {}^gH : g \in G \}$.
2. $\textrm{Stab}_H = \{g \in G : gHg^{-1} = H \} = \{g \in G : gH = Hg \} =: N_G(H) \le G$. A este subgrupo se le llama normalizador de $H$ en $G$.
3. $H$ es un punto fijo $\iff$ $H \unlhd G$.
Tags: est
<!--ID: 1731931805075-->
END

START
Básico
Anverso: Estudio de la acción sobre los subrupos
Reverso: Veamos primero que es una acción:
1. $\forall H \le G$, $1_G \cdot H = {}^{1_G} H = H$.
2. $\forall g,h \in G, \, \forall H \le G$,
$$\begin{eqnarray}
(gh) \cdot H &=& {}^{gh}H = (gh)H(gh)^{-1} = (gh)H(h^{-1}g^{-1}) = g(hHh^{-1})g^{-1} \\
&=& g \cdot (h \cdot H)
\end{eqnarray}$$

Estudiamos la acción:
1. $\textrm{Orb}_H = \{^gH \le G : g \in G \}$.
2. $\textrm{Stab}_H = \{g \in G : gHg^{-1} = H \} = \{g \in G : gH = Hg \} = N_G(H) \le G$. Este subgrupo es el normalizador de $H$ en $G$.
3. Notamos que $H \in \Omega_\textrm{fix} \iff \textrm{Orb}_H = \{^g H\le G : g \in G \} = \{H \}$. Esto es, si $\forall g \in G$, $^g H = H$. Por tanto, $H \in \Omega_\textrm{fix} \iff H \unlhd G$.

Por el teorema órbita-estabilizador, $|\{{}^gH : g \in G \}| = |G: N_G(H)|$.
Tags: dem est
<!--ID: 1731931805085-->
END

