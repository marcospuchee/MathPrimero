### Contenido Principal

```ad-theorem
Sea $G$ un grupo finito. Entonces $\exists x_{t+1}, \dots, x_n \in G$ tales que
$$|G| = |Z(G)| + \sum_{i = t+1}^n |G:C_G(x_i)|.$$
```

^8d7b24

```ad-proof
Tomando la acción por conjugación,
$$\begin{eqnarray}
|G| &=& |Z(G)| + \sum_{i = t+1}^n |\textrm{Cl}_G(x_i)| \\
&=& |Z(G)| + \sum_{i = t+1}^n |G: C_G(x_i)|,
\end{eqnarray}$$
donde $x_{t+1}, \dots x_n \in G \textrm{\\} Z(G)$.
```

**Tema:** [[Acciones de grupos#5. La acción por conjugación.]]
**Corolario:** [$G$ $p$-grupo no trivial $\implies$ $Z(G) \neq 1$](Corolario ecuación de las clases)

**Definiciones referenciadas:** [[Acción por conjugación]], [$C_G(x)$](Acción por conjugación)
**Resultados referenciados:** [$|G| = |Z(G)| + \sum_{i = t+1}^n |\textrm{Cl}_ G(x_i)|$](Corolario 2 teorema órbita-estabilizador), [$|\textrm{Cl}_ G(x_i)| = |G: C_G(x_I)|$](Teorema órbita-estabilizador)

---
### Anki

START
Básico
Anverso: Cuál es la ecuación de las clases?
Reverso: Sea $G$ un grupo finito. Entonces $\exists x_{t+1}, \dots, x_n \in G$ tales que
$$|G| = |Z(G)| + \sum_{i = t+1}^n |G:C_G(x_i)|.$$
Tags: est
<!--ID: 1731931805001-->
END

START
Básico
Anverso: Demostración de la ecuación de las clases
Reverso: Tomando la acción por conjugación,
$$\begin{eqnarray}
|G| &=& |Z(G)| + \sum_{i = t+1}^n |\textrm{Cl}_G(x_i)| \\
&=& |Z(G)| + \sum_{i = t+1}^n |G: C_G(x_i)|,
\end{eqnarray}$$
donde $x_{t+1}, \dots x_n \in G \textrm{\\} Z(G)$.
Tags: dem est
<!--ID: 1731931805009-->
END

