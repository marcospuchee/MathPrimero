### Contenido Principal

```ad-proposition
Las siguientes condiciones son equivalentes.
1. $N \unlhd G$.
2. $\forall g \in G$, $\alpha_g (N) = N$.
3. $\forall g \in G$, $gN = Ng$.
4. $\forall g \in G$ y $\forall n \in N$, $gng^{-1} \in N$.
5. $\forall g \in G$, $gNg^{-1} \subseteq N$.
```

^0dc1bb

```ad-proof
Está claro que $(1) \equiv (2) \equiv (3)$ y $(4) \equiv (5)$. $(1) \implies (5)$ es evidente, veamos que $(5) \implies (1)$:

Supongamos que $\forall g \in G$, $gNg^{-1} \subseteq N$. Sea $g \in G$, demostramos que $gNg^{-1} = N$.
$\subseteq$. Por hipótesis de $(5)$.
$\supseteq$. Por hipótesis de $(5)$, para $g^{-1} \in G$, $g^{-1}Ng \subseteq N$, lo que implica que $N = g(g^{-1}Ng)g^{-1} \subseteq gNg^{-1}$.
```

**Tema:** [[Teoría de grupos#11. Subgrupos normales.]]

---
### Anki

START
Básico
Anverso: Definiciones equivalentes a subgrupo normal
Reverso: Las siguientes condiciones son equivalentes.
1. $N \unlhd G$.
2. $\forall g \in G$, $\alpha_g (N) = N$.
3. $\forall g \in G$, $gN = Ng$.
4. $\forall g \in G$ y $\forall n \in N$, $gng^{-1} \in N$.
5. $\forall g \in G$, $gNg^{-1} \subseteq N$.
Tags: est
<!--ID: 1728820185263-->
END

START
Básico
Anverso: Demostración de que las siguientes condiciones son equivalentes.
1. $N \unlhd G$.
2. $\forall g \in G$, $\alpha_g (N) = N$.
3. $\forall g \in G$, $gN = Ng$.
4. $\forall g \in G$ y $\forall n \in N$, $gng^{-1} \in N$.
5. $\forall g \in G$, $gNg^{-1} \subseteq N$.
Reverso: 
Está claro que $(1) \equiv (2) \equiv (3)$ y $(4) \equiv (5)$. $(1) \implies (5)$ es evidente, veamos que $(5) \implies (1)$:

Supongamos que $\forall g \in G$, $gNg^{-1} \subseteq N$. Sea $g \in G$, demostramos que $gNg^{-1} = N$.
$\subseteq$. Por hipótesis de $(5)$.
$\supseteq$. Por hipótesis de $(5)$, para $g^{-1} \in G$, $g^{-1}Ng \subseteq N$, lo que implica que $N = g(g^{-1}Ng)g^{-1} \subseteq gNg^{-1}$.
Tags: dem est
<!--ID: 1728820185266-->
END
