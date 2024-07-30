
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-12, 12:47

```ad-theorem
Sea $G$ un [[grupo]] y $a \in G$ un elemento de orden finito $m > 0$ ([[orden de un elemento de un grupo]]). Entonces,
1. $m$ es el menor entero positivo tal que $a^m = e$.
2. $a^k = e \iff m | k$.
3. $a^r = a^s \iff r \equiv s \pmod m$.
4. $\langle a \rangle = \{a, a^2, \dots, a^{m-1}, a^m = e \}$.
5. Para cada $k$ tal que $k | m$, $|a^k| = m/k$.
```


```ad-proof
Sea $H = \langle a \rangle$.
1. Por el [[teorema grupo cíclico de orden m isomorfo a Zm]], $\exists g: \mathbb Z_m \to H$ con $\overline k \to a^k$ [[isomorfismo]]. Como $\overline m = \overline 0$, entonces $a^m = a^0 = e$. Como $\mathbb Z_m = \{\overline 0, \overline 1, \dots, \overline{m-1} \}$, está claro que $m$ es el menor entero tal que $\overline m = \overline 0$.
2. Por el razonamiento de $(1)$, $a^k = e \iff \overline k = \overline 0 \iff \overline x = \overline m$, y como $m$ es el menor entero positivo tal que $\overline m = \overline 0$, entonces $m/k$.
3. $\rightarrow$. Como $g$ isomorfismo, $g$ [[monomorfismo]]. Es decir, sean $\overline r, \overline s \in \mathbb Z_m$ tales que $g(\overline r) = g(\overline s)$, entonces $\overline r = \overline s$, lo que se cumple si y sólo si $r \equiv s \pmod m$. $\leftarrow$. Si $r \equiv s \pmod m$, entonces $\overline r = \overline s$. Está claro, pues, que $a^r = a^s$.
4. Sabemos que $\mathbb Z_m = \{\overline 0, \overline 1, \dots, \overline{m-1} \}$. Como $g$ isomorfo, sea $x \in H, \, \exists \overline k \in \mathbb Z_m$ tal que $g(\overline k) = x$. Por tanto, $H = \{g(\overline 0), g(\overline 1), \dots, g(\overline{m-1}) \}$. Esto es, $H = \{a^0, a^1, \dots, a^{m-1} \}$.
5. Está claro que $a^{k(\frac{m}{k})} = a^m = e$ y $a^{kr} \neq e$, $\forall 0 < r < \frac{m}{k}$, porque en caso de que $a^{kr} = e$, estaríamos contradiciendo $(3)$ porque $a^{kr} = e$ y $kr < m$.
```

**Tema:** [[Grupos#3. Grupos cíclicos.]]
**Demostrado por:** [[Teorema grupo cíclico de orden m isomorfo a Zm]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué propiedades cumple un elemento de orden finito?
Reverso: Sea $G$ un [[grupo]] y $a \in G$ un elemento de orden finito $m > 0$ ([[orden de un elemento de un grupo]]). Entonces,
1. $m$ es el menor entero positivo tal que $a^m = e$.
2. $a^k = e \iff m | k$.
3. $a^r = a^s \iff r \equiv s \pmod m$.
4. $\langle a \rangle = \{a, a^2, \dots, a^{m-1}, a^m = e \}$.
5. Para cada $k$ tal que $k | m$, $|a^k| = m/k$.
Tags: proposición/teorema hungerford
<!--ID: 1721211802937-->
END