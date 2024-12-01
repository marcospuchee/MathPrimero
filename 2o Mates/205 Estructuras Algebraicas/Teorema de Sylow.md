### Contenido Principal

```ad-theorem
Sea $|G| = p^km$ donde $p \in \mathbb P$ y $p \nmid m$ y $S \in \textrm{Syl}_p(G)$. Entonces
1. $\textrm{Syl}_p(G) = \{{}^g S : g \in G\}$.
2. $n_p(G) = |G: N_G(S)| \equiv 1 \pmod p$. En particular, $n_p(G) \mid m$.
3. Dado un $p$-subgrupo $P \le G$,
$$|\{S \in \textrm{Syl}_p(G) : P \le S \}| \equiv 1 \pmod p.$$
En particular, todo $p$-subgrupo está contenido en un $p$-subgrupo de Sylow.
```

^3f3c00

```ad-proof
Denotamos $\Omega = \{ {}^g S \le G : g \in G \}$. Dado $K \le G$, vamos a considerar la restricción de la acción $G \curvearrowright \textrm{Sub}(G)$ a $K$ y $\Omega = \textrm{Orb}_S$, $k \cdot {}^gS = {}^{kg}S \in \Omega$. Así, si $S' \in \Omega$, $S' \in \Omega_\textrm{fix}$ $\iff$ $\{{}^k S' \in \Omega : k \in K \} = \{S'\}$ $\iff$ $K \le N_G(S')$.
1. Demostramos que $\textrm{Syl}_p(G) = \Omega$.
$\supseteq$. Sea $^gS \in \Omega$. Como $\alpha_g$ es un automorfismo (biyección), tenemos que
$$|^gS| = |\alpha_g(S)| = |S| = p^k.$$
Por tanto, $^gS \in \textrm{Syl}_p(G)$.
$\subseteq$. Sea $S' \in \textrm{Syl}_p(G)$. Consideremos la acción $S' \curvearrowright \Omega$ por conjugación de subgrupos. Como $S'$ es un $p$-grupo, $|\Omega| \equiv |\Omega_\textrm{fix}| \pmod p$. Notamos que $S \le N_G(S)$. Así, $|\Omega| = |G:N_G(S)| \mid |G:S| = m$. Así, $p \nmid |\Omega|$. Entonces $\Omega_\textrm{fix} \neq \emptyset$ y consideremos $^g S \in \Omega_\textrm{fix}$. 
Por lo que hemos visto antes de empezar, $S' \le N_G(^gS)$. Ahora bien, $S', {}^gS \in \textrm{Syl}_p(G)$ y $S', {}^gS \le N_G(^gS)$, por tanto, $S', {}^gS \in \textrm{Syl}_p(N_G(^gS))$. Como $^gS \unlhd N_G(^gS)$, luego $S' = {}^gS \in \Omega$.
2. Demostramos que $n_p(G) = |G:N_G(S)| \equiv 1 \pmod p$. La primera igualdad se deduce del primer punto
$$n_p(G) = |\textrm{Syl}_p(G)| = |\Omega| = |G: N_G(S)|.$$
Para demostrar que $|\Omega| \equiv 1 \pmod p$ consideremos la acción $S \curvearrowright \Omega$ por conjugación de subgrupos. Como $S$ es un $p$-grupo, $|\Omega| \equiv |\Omega_\textrm{fix}| \pmod p$. Demostremos que $|\Omega_\textrm{fix}| = 1$.
$\ge$. Notamos que $S \le N_G(S)$. Por tanto, $S \in \Omega_\textrm{fix}$ y $|\Omega_\textrm{fix}| \ge 1$.
$\le$. Sea $S' \in \Omega_\textrm{fix}$. Entonces, por lo que hemos comentado antes de empezar la demostración, $S \le N_G(S')$. Igual que antes, como $S, S' \in \Omega = \textrm{Syl}_p(G)$ y $S,S' \le N_G(S')$, entonces $S,S' \in \textrm{Syl}_p(N_G(S'))$. Así, $S=S'$ y $|\Omega_\textrm{fix}| \le 1$.

3. Sea $P \le G$ un $p$-subgrupo. Demostremos $|\{k \in \textrm{Syl}_p(G) : P \le K\}| \equiv 1 \pmod p$. Consideremos la acción $P \curvearrowright \Omega$ por conjugación de subgrupos. Como $P$ $p$-grupo, $|\Omega| \equiv |\Omega_\textrm{fix}| \pmod p$, y por el punto 2, $|\Omega| \equiv 1 \pmod p$. Por tanto, $|\Omega_\textrm{fix}| \equiv 1 \pmod p$.
Demostramos que $\Omega_\textrm{fix} = \{K \in \textrm{Syl}_p(G) : P \le K\}$.
Notamos que, por lo que hemos notado antes de empezar la demostración, $K \in \Omega_\textrm{fix}$. Veamos que $P \le N_G(K) \iff P \le K$.
$\Leftarrow$. $P \le K \le N_G(K)$.
$\Rightarrow$. Como $K \in \Omega_\textrm{fix} \subseteq \Omega = \textrm{Syl}_p(G)$, tenemos que $K \in \textrm{Syl}_p(N_G(K))$. Como $K \unlhd N_G(K)$ y $P \le N_G(K)$ $p$-subgrupos, por la demostración de la unicidad de los $p$-subgrupos de Sylow de $G$.
```

**Tema:** [[Teorema de Sylow (referencia)]]

**Definiciones referenciadas:** [$\textrm{Syl} \\_ p(G)$](p-subgrupo de Sylow), [$n_p(G)$](p-subgrupo de Sylow), [$p$-subgrupo](p-grupo), [[Acción sobre los subgrupos]]
**Resultados referenciados:** [$|\Omega| = |G: N_G(S)|$](Acción sobre los subgrupos), [$p$-grupo $\implies$ $|\Omega| \equiv |\Omega \\_ \textrm{fix}| \pmod p$](Teorema cardinal conjunto con acción sobre p-grupo), [$|G| = p^km$, $p \in \mathbb P : p \nmid m$, $S \in \textrm{Syl} \\_ p(G) : S \unlhd G \implies S$ es el único $p$-subgrupo de Sylow de $G$](Condición suficiente para la unicidad de los p-subgrupos de Sylow de un grupo)

---
### Corolario 1

```ad-cor
Sea $G$ un grupo finito y $S \in \textrm{Syl}_p(G)$. Son equivalentes:
1. $\textrm{Syl}_p(G) = \{S\}$.
2. $S \unlhd G$.
```

```ad-proof
$2 \implies 1$.
$S \unlhd G$ $\implies$ la unicidad de $p$-subgrupos de Sylow.

$1 \implies 2$.
Suponemos que $\textrm{Syl}_p(G) = \{S\}$, por el teorema de Sylow,
$$\{S\} = \textrm{Syl}_p(G) = \{{}^gS \le G : g \in G \}.$$
Así, $\forall g \in G$, $^gS = S$, esto es, $S \unlhd G$.
```

**Tema:** [[Teorema de Sylow (referencia)]]

**Definiciones referenciadas:** [$\textrm{Syl} \\_ p(G)$](p-subgrupo de Sylow), [[Subgrupo normal]]
**Resultados referenciados:** [$|G| = p^km$, $p \in \mathbb P : p \nmid m$, $S \in \textrm{Syl} \\_ p(G) : S \unlhd G \implies S$ es el único $p$-subgrupo de Sylow de $G$](Condición suficiente para la unicidad de los p-subgrupos de Sylow de un grupo)

---
### Corolario 2

```ad-cor
Sea $G$ un grupo finito y $S \in \textrm{Syl}_p(G)$. Son equivalentes:
1. $\textrm{Syl}_p(G) = \{S\}$.
2. $S \textrm{ car } G$.
```

^62c19f

```ad-proof
$2 \implies 1$.
$S \textrm{ car } C \implies S \unlhd G \implies$ la unicidad de los $p$-subgrupos de Sylow de $G$.

$1 \implies 2$.
Suponemos $\textrm{Syl}_p(G) = \{S\}$. Sea $\varphi \in \textrm{Aut}(G)$. Notamos que $|\varphi(S)| = |S| = p^k$, por tanto, $\varphi(S) \in \textrm{Syl}_p(G)$. Así, $\forall \varphi \in \textrm{Aut}(G)$, $\varphi(S) = S$ y $S \textrm{ car } G$.
```

**Tema:** [[Teorema de Sylow (referencia)]]

**Definiciones referenciadas:** [$\textrm{Syl} \\_ p(G)$](p-subgrupo de Sylow), [$S \textrm{ car } G$](Subgrupo característico)
[$|G| = p^km$, $p \in \mathbb P : p \nmid m$, $S \in \textrm{Syl} \\_ p(G) : S \unlhd G \implies S$ es el único $p$-subgrupo de Sylow de $G$](Condición suficiente para la unicidad de los p-subgrupos de Sylow de un grupo)

---
### Anki

START
Básico
Anverso: Teorema de Sylow
Reverso: Sea $|G| = p^km$ donde $p \in \mathbb P$ y $p \nmid m$ y $S \in \textrm{Syl}_p(G)$. Entonces
1. $\textrm{Syl}_p(G) = \{{}^g S : g \in G\}$.
2. $n_p(G) = |G: N_G(S)| \equiv 1 \pmod p$. En particular, $n_p(G) \mid m$.
3. Dado un $p$-subgrupo $P \le G$,
$$|\{S \in \textrm{Syl}_p(G) : P \le S \}| \equiv 1 \pmod p.$$
En particular, todo $p$-subgrupo está contenido en un $p$-subgrupo de Sylow.
Tags: est
<!--ID: 1733051328646-->
END

START
Básico
Anverso: Demostración de que sea $|G| = p^km$ donde $p \in \mathbb P$ y $p \nmid m$ y $S \in \textrm{Syl}_p(G)$. Entonces
1. $\textrm{Syl}_p(G) = \{{}^g S : g \in G\}$.
2. $n_p(G) = |G: N_G(S)| \equiv 1 \pmod p$. En particular, $n_p(G) \mid m$.
3. Dado un $p$-subgrupo $P \le G$,
$$|\{S \in \textrm{Syl}_p(G) : P \le S \}| \equiv 1 \pmod p.$$
En particular, todo $p$-subgrupo está contenido en un $p$-subgrupo de Sylow.
Reverso: Denotamos $\Omega = \{ {}^g S \le G : g \in G \}$. Dado $K \le G$, vamos a considerar la restricción de la acción $G \curvearrowright \textrm{Sub}(G)$ a $K$ y $\Omega = \textrm{Orb}_S$, $k \cdot {}^gS = {}^{kg}S \in \Omega$. Así, si $S' \in \Omega$, $S' \in \Omega_\textrm{fix}$ $\iff$ $\{{}^k S' \in \Omega : k \in K \} = \{S'\}$ $\iff$ $K \le N_G(S')$.
1. Demostramos que $\textrm{Syl}_p(G) = \Omega$.
$\supseteq$. Sea $^gS \in \Omega$. Como $\alpha_g$ es un automorfismo (biyección), tenemos que
$$|^gS| = |\alpha_g(S)| = |S| = p^k.$$
Por tanto, $^gS \in \textrm{Syl}_p(G)$.
$\subseteq$. Sea $S' \in \textrm{Syl}_p(G)$. Consideremos la acción $S' \curvearrowright \Omega$ por conjugación de subgrupos. Como $S'$ es un $p$-grupo, $|\Omega| \equiv |\Omega_\textrm{fix}| \pmod p$. Notamos que $S \le N_G(S)$. Así, $|\Omega| = |G:N_G(S)| \mid |G:S| = m$. Así, $p \nmid |\Omega|$. Entonces $\Omega_\textrm{fix} \neq \emptyset$ y consideremos $^g S \in \Omega_\textrm{fix}$. 
Por lo que hemos visto antes de empezar, $S' \le N_G(^gS)$. Ahora bien, $S', {}^gS \in \textrm{Syl}_p(G)$ y $S', {}^gS \le N_G(^gS)$, por tanto, $S', {}^gS \in \textrm{Syl}_p(N_G(^gS))$. Como $^gS \unlhd N_G(^gS)$, luego $S' = {}^gS \in \Omega$.
2. Demostramos que $n_p(G) = |G:N_G(S)| \equiv 1 \pmod p$. La primera igualdad se deduce del primer punto
$$n_p(G) = |\textrm{Syl}_p(G)| = |\Omega| = |G: N_G(S)|.$$
Para demostrar que $|\Omega| \equiv 1 \pmod p$ consideremos la acción $S \curvearrowright \Omega$ por conjugación de subgrupos. Como $S$ es un $p$-grupo, $|\Omega| \equiv |\Omega_\textrm{fix}| \pmod p$. Demostremos que $|\Omega_\textrm{fix}| = 1$.
$\ge$. Notamos que $S \le N_G(S)$. Por tanto, $S \in \Omega_\textrm{fix}$ y $|\Omega_\textrm{fix}| \ge 1$.
$\le$. Sea $S' \in \Omega_\textrm{fix}$. Entonces, por lo que hemos comentado antes de empezar la demostración, $S \le N_G(S')$. Igual que antes, como $S, S' \in \Omega = \textrm{Syl}_p(G)$ y $S,S' \le N_G(S')$, entonces $S,S' \in \textrm{Syl}_p(N_G(S'))$. Así, $S=S'$ y $|\Omega_\textrm{fix}| \le 1$.

3. Sea $P \le G$ un $p$-subgrupo. Demostremos $|\{k \in \textrm{Syl}_p(G) : P \le K\}| \equiv 1 \pmod p$. Consideremos la acción $P \curvearrowright \Omega$ por conjugación de subgrupos. Como $P$ $p$-grupo, $|\Omega| \equiv |\Omega_\textrm{fix}| \pmod p$, y por el punto 2, $|\Omega| \equiv 1 \pmod p$. Por tanto, $|\Omega_\textrm{fix}| \equiv 1 \pmod p$.
Demostramos que $\Omega_\textrm{fix} = \{K \in \textrm{Syl}_p(G) : P \le K\}$.
Notamos que, por lo que hemos notado antes de empezar la demostración, $K \in \Omega_\textrm{fix}$. Veamos que $P \le N_G(K) \iff P \le K$.
$\Leftarrow$. $P \le K \le N_G(K)$.
$\Rightarrow$. Como $K \in \Omega_\textrm{fix} \subseteq \Omega = \textrm{Syl}_p(G)$, tenemos que $K \in \textrm{Syl}_p(N_G(K))$. Como $K \unlhd N_G(K)$ y $P \le N_G(K)$ $p$-subgrupos, por la demostración de la unicidad de los $p$-subgrupos de Sylow de $G$.
Tags: dem est
<!--ID: 1733051328652-->
END

START
Respuesta anidada
Sea $G$ un grupo finito y $S \in \textrm{Syl}_p(G)$. Son equivalentes:
1. {{c1::$\textrm{Syl}_p(G) = \{S\}$}}.
2. {{c2::$S \textrm{ car } G$.}}
Tags: est
<!--ID: 1733051328655-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo finito y $S \in \textrm{Syl}_p(G)$. Son equivalentes:
1. $\textrm{Syl}_p(G) = \{S\}$.
2. $S \textrm{ car } G$.
Reverso: $2 \implies 1$.
$S \textrm{ car } C \implies S \unlhd G \implies$ la unicidad de los $p$-subgrupos de Sylow de $G$.

$1 \implies 2$.
Suponemos $\textrm{Syl}_p(G) = \{S\}$. Sea $\varphi \in \textrm{Aut}(G)$. Notamos que $|\varphi(S)| = |S| = p^k$, por tanto, $\varphi(S) \in \textrm{Syl}_p(G)$. Así, $\forall \varphi \in \textrm{Aut}(G)$, $\varphi(S) = S$ y $S \textrm{ car } G$.
Tags: dem est
<!--ID: 1733051328657-->
END

