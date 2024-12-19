### Contenido Principal

```ad-theorem
Consideremos un problema de PLE en formato estándar con región factible
$$\mathcal F = \{x \in \mathbb Z^n : Ax = b, x \ge 0_n \},$$
donde $A \in \mathbb Z^{m \times n}$ es totalmente unimodular y $b \in \mathbb Z^m$. Sea $\mathcal S$ el conjunto factible de su relajación lineal
$$\mathcal S = \{x \in \mathbb R^n: Ax = b, x \ge 0_n \}.$$
Entonces todos los puntos extremos (SBP) de $\mathcal S$ tienen componentes enteras.
```

```ad-proof
Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T \in \mathbb R^n$ una SBP de $\mathcal S$ asociada a la base $B$. Como,
$$\overline x_B = B^{-1}b = \frac{(\textrm{adj}(B))^t}{|B|}b \in \mathbb Z^m,$$
dado que $\textrm{adj}(B)$ está formado por $\{-1,0,1\}$, $|B|$ también, y $b \in \mathbb Z^m$. Entonces, se tiene que $\overline x \in \mathbb Z^n$.
```

**Tema:** [[Programación lineal entera#2. Combinatoria poliédrica.]]

**Definiciones referenciadas:** [[Matriz totalmente unimodular]], [[Relajación lineal]].
**Resultados referenciados:** -.

---

```ad-cor
title: Corollarium
Consideremos un porblema de PLE en formato canónico con región factible
$$\mathcal F = \{x \in \mathbb Z^n : Ax \le b, \, x \ge 0_n \},$$
donde $A \in \mathbb Z^{m \times n}$ es totalmente unimodular y $b \in \mathbb Z^m$. Sea $\mathcal S$ el conjunto factible de su relajación lineal
$$\mathcal S = \{x \in \mathbb R^n : Ax \le b, \, x \ge 0_n \}.$$
Entonces todos los puntos extremos (SBP) de $\mathcal S$ tienen componentes enteras.
```

```ad-proof
Basta comprobar que la matriz $[A \quad I_m]$ es totalmente unimodular y aplicar el teorema de las soluciones enteras bajo unimodularidad en formato estándar.
```


---
### Anki

START
Básico
Anverso: Soluciones enteras bajo unimodularidad en formato estándar
Reverso: Consideremos un problema de PLE en formato estándar con región factible
$$\mathcal F = \{x \in \mathbb Z^n : Ax = b, x \ge 0_n \},$$
donde $A \in \mathbb Z^{m \times n}$ es totalmente unimodular y $b \in \mathbb Z^m$. Sea $\mathcal S$ el conjunto factible de su relajación lineal
$$\mathcal S = \{x \in \mathbb R^n: Ax = b, x \ge 0_n \}.$$
Entonces todos los puntos extremos (SBP) de $\mathcal S$ tienen componentes enteras.
Tags: prm
<!--ID: 1733328768615-->
END

START
Básico
Anverso: Demostración de que consideremos un problema de PLE en formato estándar con región factible
$$\mathcal F = \{x \in \mathbb Z^n : Ax = b, x \ge 0_n \},$$
donde $A \in \mathbb Z^{m \times n}$ es totalmente unimodular y $b \in \mathbb Z^m$. Sea $\mathcal S$ el conjunto factible de su relajación lineal
$$\mathcal S = \{x \in \mathbb R^n: Ax = b, x \ge 0_n \}.$$
Entonces todos los puntos extremos (SBP) de $\mathcal S$ tienen componentes enteras.
Reverso: Sea $\overline x = (\overline x_B^T, 0_{n-m}^T)^T \in \mathbb R^n$ una SBP de $\mathcal S$ asociada a la base $B$. Como,
$$\overline x_B = B^{-1}b = \frac{\textrm{adj}(B)}{|B|}b \in \mathbb Z^m,$$
dado que $\textrm{adj}(B)$ está formado por $\{-1,0,1\}$, $|B|$ también, y $b \in \mathbb Z^m$. Entonces, se tiene que $\overline x \in \mathbb Z^n$.
Tags: dem prm
<!--ID: 1733328768618-->
END

