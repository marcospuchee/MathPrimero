
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-13, 11:08

```ad-theorem
Sea $G = \langle a \rangle$ un [[grupo cíclico]]. Si $G$ es infinito, entonces $a$ y $a^{-1}$ son los únicos generadores de $G$ ([[subgrupo generado]]). Si $G$ es finito de orden $m$, entonces $a^k$ es un generador de $G$ si y sólo si $\textrm{mcd}(k,m) = 1$.
```

```ad-proof
1. $G$ infinito. Gracias a que $G$ y $\mathbb Z$ son isomorfos, podemos asumir sin pérdida de generalidad que $G = \mathbb Z$ ([[teorema grupo cíclico infinito isomorfo a Z]]). Veamos que $\langle 1 \rangle = \langle -1 \rangle \neq \langle x \rangle$ para cualquier $x \in \mathbb Z$ con $|x| > 1$. Está claro que $\mathbb Z = \langle 1 \rangle$ porque
$$\langle 1 \rangle = \{1m \, | \, m \in \mathbb Z \} = \{m | \in \mathbb Z \} = \mathbb Z.$$
Por definición, $\langle -1 \rangle = \{-1n \, | \, n \in \mathbb Z \}$. Si tomamos $n = -m$, $\langle -1 \rangle = \langle 1 \rangle = \mathbb Z$. Sea $x \in \mathbb Z$ tal que $|x| > 1$. Está claro que $x+1 \notin \langle x \rangle$, pero $x+1 \in \mathbb Z$.

2. Gracias a que $G$ y $\mathbb Z_m$ son isomorfos, podemos asumir sin pérdida de generalidad que $G = \mathbb Z_m$ ([[teorema grupo cíclico de orden m isomorfo a Zm]]).
$\leftarrow$. Como $\textrm{mcd}(m,k) = 1$, por la [[identidad de Bezout]], $\exists x,y \in \mathbb Z$ tales que $mx + ky = 1$. Esto es, $\overline{mx} + \overline{ky} = \overline 1$, lo que implica que $\overline{ky} = \overline{1}$ y $\langle \overline k \rangle = \langle \overline 1 \rangle$.
$\rightarrow$. Supongamos que $\textrm{mcd}(m,k) = r>1$. Sea $m/r = n$. $n \overline k = \overline{nk} = \overline 0$ por tanto, $\overline k$ no es generador de $\mathbb Z_m$, ya que tiene un orden menor a $m$.
```

**Tema:** [[Grupos#3. Grupos cíclicos.]]
**Demostrado por:** [[Teorema grupo cíclico infinito isomorfo a Z]], [[Teorema grupo cíclico de orden m isomorfo a Zm]], [[Teorema caracterización subgrupo generado]], [[Identidad de Bezout]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que da forma a los generadores de un grupo cíclico?
Reverso: Sea $G = \langle a \rangle$ un [[Grupo cíclico]]. Si $G$ es infinito, entonces $a$ y $a^{-1}$ son los únicos generadores de $G$ ([[subgrupo generado]]). Si $G$ es finito de orden $m$, entonces $a^k$ es un generador de $G$ si y sólo si $\textrm{mcd}(k,m) = 1$.
Tags: proposición/teorema hungerford
<!--ID: 1721211802892-->
END
