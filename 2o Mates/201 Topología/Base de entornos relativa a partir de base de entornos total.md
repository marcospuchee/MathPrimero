### Contenido Principal

```ad-proposition
Sean $(X, \mathcal T)$ espacio topológico, $x \in H \subseteq X$, $\mathcal B(x)$ base de entornos de $x$. Entonces, $\mathcal B_H(x) = \{B \cap H : B \in \mathcal B(x) \}$ es base de entornos de $x$ en la topología inducida.
```

```ad-note
title: Corollarium
$(X, \mathcal T)$ espacio topológico $1\textrm{AN}$ y $H \subseteq X$, entonces $(H, \mathcal T_H) \, \, 1 \textrm{AN}$.
```

```ad-proof
Vamos a comprobar que se cumpla la definición de base de entornos:
1. $B \cap H \in \mathcal E_H(x)$.
2. Sea $U \in \mathcal E_H(x)$, entonces $\exists U' \in \mathcal E(x)$ tal que $U = U' \cap H$. Como $\mathcal B(x)$ es base de entornos, entonces $\exists B \in \mathcal B(x)$ tal que $x \in B \subseteq U'$, luego $x \in B \cap H \subseteq U' \cap H = U$, donde $B \cap H \in \mathcal B_H(x)$. 

Así, $\mathcal B_H(x)$ es base de entornos en la topología relativa.
```

**Tema:** [[Subespacios topológicos#1. Definición.]]

**Definiciones referenciadas:** [$\mathcal T_H$](Topología inducida), [[Base de entornos]], [[Entorno]], [[Espacio topológico 1 AN]]
**Resultados referenciados:** [$U \in \mathcal E_H(x) \iff \exists U' \in \mathcal E(x) : U = U' \cap H$](Caracterización entorno en topología inducida (entorno topología padre))

---
### Anki
