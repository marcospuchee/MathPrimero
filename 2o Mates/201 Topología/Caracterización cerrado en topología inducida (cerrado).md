### Contenido Principal

```ad-proposition
$(X, \mathcal T)$ espacio topológico. $H \subseteq X$. Entonces, $C \subseteq H$ es cerrado en $\mathcal T_H$ $\iff$ $\exists C'$ cerrado en $\mathcal T$ tal que $C = C' \cap H$.
```

```ad-proof
$\Rightarrow$. Sea $C$ cerrado en $\mathcal T_H$, entonces $H \textrm{\\} C \in \mathcal T_H$. Por definición, $\exists A' \in \mathcal T$ tal que $H \textrm{\\} C = A' \cap H$. Definimos $C' := X \textrm{\\} A$ cerrado en $\mathcal T$ y tenemos:
$$C = H \textrm{\\} (H \textrm{\\} C) = H \textrm{\\} (A' \cap H) = H \textrm{\\} A' = H \cap (X \textrm{\\} A') = H \cap C'.$$
$\Leftarrow$. Sea $C = C' \cap H$ con $C'$ cerrado en $\mathcal T$. Entonces,
$$H \textrm{\\} C = H \textrm{\\} (C' \cap H) = H \textrm{\\} C' = H \cap (X \textrm{\\} C'),$$
donde $X \textrm{\\} C' \in \mathcal T$. Por tanto, $H \textrm{\\} C \in \mathcal T_H$, y $C$ es cerrado en $\mathcal T_H$.
```

**Tema:** [[Subespacios topológicos#1. Definición.]]

**Definiciones referenciadas:** [$\mathcal T_H$](Topología inducida)
**Resultados referenciados:**  -.

---
### Anki

START
Básico
Anverso: Caracterización cerrado en topología inducida (cerrado en topología padre)
Reverso: $(X, \mathcal T)$ espacio topológico. $H \subseteq X$. Entonces, $C \subseteq H$ es cerrado en $\mathcal T_H$ $\iff$ $\exists C'$ cerrado en $\mathcal T$ tal que $C = C' \cap H$.
Tags: top
<!--ID: 1731931805338-->
END

START
Básico
Anverso: Demostración de que sea $(X, \mathcal T)$ espacio topológico. $H \subseteq X$. Entonces, $C \subseteq H$ es cerrado en $\mathcal T_H$ $\iff$ $\exists C'$ cerrado en $\mathcal T$ tal que $C = C' \cap H$.
Reverso: $\Rightarrow$. Sea $C$ cerrado en $\mathcal T_H$, entonces $H \textrm{\\} C \in \mathcal T_H$. Por definición, $\exists A' \in \mathcal T$ tal que $H \textrm{\\} C = A' \cap H$. Definimos $C' := X \textrm{\\} A$ cerrado en $\mathcal T$ y tenemos:
$$C = H \textrm{\\} (H \textrm{\\} C) = H \textrm{\\} (A' \cap H) = H \textrm{\\} A' = H \cap (X \textrm{\\} A') = H \cap C'.$$
$\Leftarrow$. Sea $C = C' \cap H$ con $C'$ cerrado en $\mathcal T$. Entonces,
$$H \textrm{\\} C = H \textrm{\\} (C' \cap H) = H \textrm{\\} C' = H \cap (X \textrm{\\} C'),$$
donde $X \textrm{\\} C' \in \mathcal T$. Por tanto, $H \textrm{\\} C \in \mathcal T_H$, y $C$ es cerrado en $\mathcal T_H$.
Tags: dem top
<!--ID: 1731931805347-->
END

