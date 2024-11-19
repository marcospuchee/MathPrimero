### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ espacio topológico, $x \in H \subseteq X$, $U \subseteq H$. Entonces, $U \in \mathcal E_H(x)$ $\iff$ $\exists U' \in \mathcal E(x)$ tal que $U = U' \cap H$. 
```

```ad-proof
$\Rightarrow$.
Si $U \in \mathcal E_H(x)$, entonces $\exists A \in \mathcal T_H$ tal que $x \in A \subseteq U$. Por definición de $\mathcal T_H$, $\exists A' \in \mathcal T$ tal que $A = A' \cap H$. Definimos $U' := U \cup A' \in \mathcal E(x)$ porque $x \in U'$ y $x \in A' \subseteq U'$. Tenemos que
$$U' \cap H = (A' \cup U) \cap H = (A' \cap H) \cup (U \cap H) = A \cup U = U.$$

$\Leftarrow$.
Dado que $U' \in \mathcal E(x)$, entonces $\exists A \in \mathcal T$ tal que $x \in A \subseteq U'$. Además, por hipótesis $U = U' \cap H$. Luego,
$$x \in A \cap H \subseteq U' \cap H = U \in \mathcal E_H(x),$$
porque $A \cap H \in \mathcal T_H$.
```

**Tema:** [[Subespacios topológicos#1. Definición.]]

**Definiciones referenciadas:** [[Entorno]], [$\mathcal T_H$](Topología inducida).
**Resultados referenciados:** *-*.

---
### Anki

START
Básico
Anverso: Caracterización de entorno en topología inducida (entorno en topología padre)
Reverso: Sean $(X, \mathcal T)$ espacio topológico, $x \in H \subseteq X$, $U \subseteq H$. Entonces, $U \in \mathcal E_H(x)$ $\iff$ $\exists U' \in \mathcal E(x)$ tal que $U = U' \cap H$.
Tags: top
<!--ID: 1731931805282-->
END

START
Básico
Anverso: Demostración de que sean $(X, \mathcal T)$ espacio topológico, $x \in H \subseteq X$, $U \subseteq H$. Entonces, $U \in \mathcal E_H(x)$ $\iff$ $\exists U' \in \mathcal E(x)$ tal que $U = U' \cap H$.
Reverso: $\Rightarrow$.
Si $U \in \mathcal E_H(x)$, entonces $\exists A \in \mathcal T_H$ tal que $x \in A \subseteq U$. Por definición de $\mathcal T_H$, $\exists A' \in \mathcal T$ tal que $A = A' \cap H$. Definimos $U' := U \cup A' \in \mathcal E(x)$ porque $x \in U'$ y $x \in A' \subseteq U'$. Tenemos que
$$U' \cap H = (A' \cup U) \cap H = (A' \cap H) \cup (U \cap H) = A \cup U = U.$$

$\Leftarrow$.
Dado que $U' \in \mathcal E(x)$, entonces $\exists A \in \mathcal T$ tal que $x \in A \subseteq U'$. Además, por hipótesis $U = U' \cap H$. Luego,
$$x \in A \cap H \subseteq U' \cap H = U \in \mathcal E_H(x),$$
porque $A \cap H \in \mathcal T_H$.
Tags: dem top
<!--ID: 1731931805291-->
END

