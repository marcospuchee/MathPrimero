### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]] y $N \unlhd G$.
1. Si $G$ es conmutativo, entonces $G/N$ es conmutativo.
2. Si $G$ es finito, entonces $G/N$ es finito.
3. Si $G$ es cíclico, entonces $G/N$ es cíclico.
```

^180157

```ad-proof
1. $(xN)(yN) = (xy)N = (yx)N = (yN)(xN)$.
2. Como $G$ finito, por el [[teorema de Lagrange (cardinal de un grupo)]], tenemos que $|G/N| \le |G|$.
3. Supongamos que $G = \langle x \rangle$. Vamos a demostrar que $G/N = \langle xN \rangle$.
$\supseteq$. Trivial.
$\subseteq$. Sea $gN \in G/N$. En particular, $g \in G = \langle x \rangle$. Por tanto, $\exists n \in \mathbb Z$ tal que $g = x^n$. Así, $gN = x^n N = (xN)^n \in \langle xN \rangle$.
```

**Tema:** [[Teoría de grupos#12. Grupos cociente.]]

---
### Anki

START
Básico
Anverso: Qué propiedades respeta el grupo cociente
Reverso: Sea $G$ un [[Grupo]] y $N \unlhd G$.
1. Si $G$ es conmutativo, entonces $G/N$ es conmutativo.
2. Si $G$ es finito, entonces $G/N$ es finito.
3. Si $G$ es cíclico, entonces $G/N$ es cíclico.
Tags: est
<!--ID: 1729160606417-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]] y $N \unlhd G$.
1. Si $G$ es conmutativo, entonces $G/N$ es conmutativo.
2. Si $G$ es finito, entonces $G/N$ es finito.
3. Si $G$ es cíclico, entonces $G/N$ es cíclico.
Reverso: 
1. $(xN)(yN) = (xy)N = (yx)N = (yN)(xN)$.
2. Como $G$ finito, por el [[teorema de Lagrange (cardinal de un grupo)]], tenemos que $|G/N| \le |G|$.
3. Supongamos que $G = \langle x \rangle$. Vamos a demostrar que $G/N = \langle xN \rangle$.
$\supseteq$. Trivial.
$\subseteq$. Sea $gN \in G/N$. En particular, $g \in G = \langle x \rangle$. Por tanto, $\exists n \in \mathbb Z$ tal que $g = x^n$. Así, $gN = x^n N = (xN)^n \in \langle xN \rangle$.
Tags: dem est
<!--ID: 1729160606419-->
END

