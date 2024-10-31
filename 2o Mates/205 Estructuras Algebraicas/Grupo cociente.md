### Contenido Principal

```ad-theorem
Sea $G$ un grupo y $N \unlhd G$. Entonces el conjunto cociente $G/N = \{xN : x \in G \}$ tiene estructura de grupo con la operación
$$\begin{matrix}
\cdot : & G / N \times G / N & \to & G/N \\
& (xN, yN) & \to & (xy)N
\end{matrix}$$
llamado grupo cociente de $G$ sobre $N$.
```

^9efc40

```ad-proof
Veamos que la operación está bien definida: sean $xN = x'N$ y $yN = y'N$, hay que ver que $(xy)N = (x'y')N$. Notemos que
$$(xN)(yN) = x(Ny)N = x(yN)N = (xy)NN = (xy)N = (xN) \cdot (yN).$$
Podemos aplicar esto a
$$(xN) \cdot (yN) = (xy)N = (xN)(yN) = (x'N)(y'N) = (x'y')N = (x'N) \cdot (y'N),$$
luego la operación $\cdot$ está bien definida.

Veamos ahora que tiene estructura de grupo:
1. El neutro es $1_G = N$.
2. Dado $xN \in G/N$, entonces $(xN)^{-1} = x^{-1}N$.
```

**Tema:** [[Teoría de grupos#12. Grupos cociente.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Definición de grupo cociente
Reverso: Sea $G$ un grupo y $N \unlhd G$. Entonces el conjunto cociente $G/N = \{xN : x \in G \}$ tiene estructura de grupo con la operación
$$\begin{matrix}
\cdot : & G / N \times G / N & \to & G/N \\
& (xN, yN) & \to & (xy)N
\end{matrix}$$
llamado grupo cociente de $G$ sobre $N$.
Tags: est
<!--ID: 1729160606412-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo y $N \unlhd G$. Entonces el conjunto cociente $G/N = \{xN : x \in G \}$ tiene estructura de grupo con la operación
$$\begin{matrix}
\cdot : & G / N \times G / N & \to & G/N \\
& (xN, yN) & \to & (xy)N
\end{matrix}$$
llamado grupo cociente de $G$ sobre $N$.
Reverso: Veamos que la operación está bien definida: sean $xN = x'N$ y $yN = y'N$, hay que ver que $(xy)N = (x'y')N$. Notemos que
$$(xN)(yN) = x(Ny)N = x(yN)N = (xy)NN = (xy)N = (xN) \cdot (yN).$$
Podemos aplicar esto a
$$(xN) \cdot (yN) = (xy)N = (xN)(yN) = (x'N)(y'N) = (x'y')N = (x'N) \cdot (y'N),$$
luego la operación $\cdot$ está bien definida.

Veamos ahora que tiene estructura de grupo:
1. El neutro es $1_G = N$.
2. Dado $xN \in G/N$, entonces $(xN)^{-1} = x^{-1}N$.
Tags: est dem
<!--ID: 1729160606415-->
END

