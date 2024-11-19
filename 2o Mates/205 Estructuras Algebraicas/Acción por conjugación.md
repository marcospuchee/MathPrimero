### Contenido principal

```ad-Formal
Sea $G$ un grupo. Definimos $G \curvearrowright G$ como sigue: $g \cdot x = {}^g x = gxg^{-1}$. Tras el estudio de la acción:
1. $\textrm{Orb}_x = \{gxg^{-1} : g \in G \} = \textrm{Cl}_G(x)$. La clase de conjugación de $x$.
2. $\textrm{Stab}_x = \{g \in G : gxg^{-1} = x \} = \{g \in G : gx = xg \} = C_G(x) \le G$. A este subgrupo se le llama centralizador de $x$ en $G$.
3. $x$ es un punto fijo $\iff$ $x \in Z(G)$:
```

```ad-note
1. $|\textrm{Cl}_G(x)| = |G: C_G(x)|$.
2. El homomorfismo representación viene dado por
$$\begin{array}{c c c l}
\rho: & G & \to & S_G \\
& g & \mapsto & \alpha_g
\end{array}$$
y el núcleo de la acción es $\textrm{Ker}(\rho) = Z(G)$.
```

```ad-proof
Verificamos que es una acción:
1. $\forall x \in G$, 
$$1_G \cdot x = {}^{1_G}x = 1_G x 1_G^{-1} = x.$$

2. $\forall g,h \in G, x \in G$:
$$\begin{eqnarray}
(gh) \cdot x &=& {}^{gh}x = (gh)x(gh)^{-1} = (gh)x(h^{-1}g^{-1}) = g(hxh^{-1})g^{-1} = g \cdot (hxh^{-1}) \\
&=& g \cdot (h \cdot x).
\end{eqnarray}$$

Estudiamos la acción:
1. $\textrm{Orb}_x = \{gxg^{-1} \in G : g \in G \} =: \textrm{Cl}_G(x)$. La clase de conjugación de $x$ en $G$.
2. $\textrm{Stab}_x = \{g \in G : gxg^{-1} = x \} = \{g \in G : gx = xg \} =: C_G(x)$. Centralizador de $x$ en $G$.
3. Notamos que $\Omega_\textrm{fix} = Z(G)$:
$$\begin{eqnarray}
x \in \Omega_\textrm{fix} &\iff& \textrm{Orb}_x = \{gxg^{-1} \in G : g \in G \} = \{x\} \\ &\iff& \forall g \in G, \, \, gxg^{-1} = x \\ &\iff& \forall g \in G, \, \, gx = xg \\
&\iff& x \in Z(G).
\end{eqnarray}$$

Por el teorema órbita-estabilizador, $|\textrm{Cl}_G(x)| = |G: C_G(x)|$. Además, calculamos su homomorfismo representación: para $g \in G$,
$$\begin{array}{c c c l}
\rho_g: & G & \to & G \\
& x & \mapsto & gxg^{-1}.
\end{array}$$
Es decir, $\rho_g = \alpha_g$ el automorfismo conjugación. Así,
$$\begin{array}{c c c l}
\rho: & G & \to & S_G \\
& g & \mapsto & \alpha_g,
\end{array}$$
que tiene como núcleo $\textrm{Ker}(\rho) = Z(G)$.
```


**Tema:** [[Acciones de grupos#5. La acción por conjugación.]]

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo), [$\textrm{Orb} \\_ \alpha$](Órbita), [$\textrm{Stab} \\_ \alpha$](Estabilizador), [Punto fijo](Estabilizador), [Homomorfismo representación](Teorema del homomorfismo representación), [$\textrm{Ker}(\rho)$](Núcleo de la acción)
**Resultados referenciados:** [$|\textrm{Cl}_ G(x)| = |G: C_G(x)|$](Teorema órbita-estabilizador), [$|G| = |Z(G)| + \sum_{i = t+1}^n |\textrm{Cl}_ G(x_i)|$](Corolario 2 teorema órbita-estabilizador), [$|\textrm{Cl}_ G(x_i)| = |G: C_G(x_I)|$](Teorema órbita-estabilizador)

---
### Anki

START
Básico
Anverso: Definición de acción por conjugación
Reverso: Sea $G$ un grupo. Definimos $G \curvearrowright G$ como sigue: $g \cdot x = {}^g x = gxg^{-1}$. Tras el estudio de la acción:
1. $\textrm{Orb}_x = \{gxg^{-1} : g \in G \} = \textrm{Cl}_G(x)$. La clase de conjugación de $x$.
2. $\textrm{Stab}_x = \{g \in G : gxg^{-1} = x \} = \{g \in G : gx = xg \} = C_G(x) \le G$. A este subgrupo se le llama centralizador de $x$ en $G$.
3. $x$ es un punto fijo $\iff$ $x \in Z(G)$:
Tags: est
<!--ID: 1731931805093-->
END

START
Básico
Anverso:  Estudio de la acción por conjugación
Reverso: Verificamos que es una acción:
1. $\forall x \in G$, 
$$1_G \cdot x = {}^{1_G}x = 1_G x 1_G^{-1} = x.$$

2. $\forall g,h \in G, x \in G$:
$$\begin{eqnarray}
(gh) \cdot x &=& {}^{gh}x = (gh)x(gh)^{-1} = (gh)x(h^{-1}g^{-1}) = g(hxh^{-1})g^{-1} = g \cdot (hxh^{-1}) \\
&=& g \cdot (h \cdot x).
\end{eqnarray}$$

Estudiamos la acción:
1. $\textrm{Orb}_x = \{gxg^{-1} \in G : g \in G \} =: \textrm{Cl}_G(x)$. La clase de conjugación de $x$ en $G$.
2. $\textrm{Stab}_x = \{g \in G : gxg^{-1} = x \} = \{g \in G : gx = xg \} =: C_G(x)$. Centralizador de $x$ en $G$.
3. Notamos que $\Omega_\textrm{fix} = Z(G)$:
$$\begin{eqnarray}
x \in \Omega_\textrm{fix} &\iff& \textrm{Orb}_x = \{gxg^{-1} \in G : g \in G \} = \{x\} \\ &\iff& \forall g \in G, \, \, gxg^{-1} = x \\ &\iff& \forall g \in G, \, \, gx = xg \\
&\iff& x \in Z(G).
\end{eqnarray}$$

Por el teorema órbita-estabilizador, $|\textrm{Cl}_G(x)| = |G: C_G(x)|$. Además, calculamos su homomorfismo representación: para $g \in G$,
$$\begin{array}{c c c l}
\rho_g: & G & \to & G \\
& x & \mapsto & gxg^{-1}.
\end{array}$$
Es decir, $\rho_g = \alpha_g$ el automorfismo conjugación. Así,
$$\begin{array}{c c c l}
\rho: & G & \to & S_G \\
& g & \mapsto & \alpha_g,
\end{array}$$
que tiene como núcleo $\textrm{Ker}(\rho) = Z(G)$.
Tags: dem est
<!--ID: 1731931805103-->
END
