### Contenido principal

```ad-Formal
Una norma matricial subordinada a una norma vectorial $|| \cdot ||_\alpha$ se define como:
$$A \in \mathbb R^{n \times n}, \quad ||A||_\alpha := \textrm{sup}_{x \neq 0} \frac{||Ax||_\alpha}{||x||_\alpha}.$$
En esta definición $\alpha \in \mathbb N \cup \{ \infty \}$.
```

```ad-note
Para $A \in \mathbb R^{n \times n}$, son equivalentes:
$$||A||_\alpha = \sup \limits_{x \neq 0} \frac{||Ax||_\alpha}{||x||_\alpha} = \max \limits_{x \neq 0} \frac{||Ax||_\alpha}{||x||_\alpha} = \max \limits_{||x||_\alpha = 1} ||Ax||_\alpha.$$
```

```ad-note
De la definición se puede deducir:
1. $D = \textrm{diag}(d_1, \dots, d_n) \in \mathbb R^{n \times n} \implies ||D||_2 = \max \limits_{1 \le i \le n} |d_i|$.
2. $Q \in \mathbb R^{n \times n}$ ortogonal $\implies$ $||Q||_2 = 1$.
```


**Tema:** [[Sistemas lineales y su solución numérica#1. Normas de vectores y de matrices.]]

**Definiciones referenciadas:** [$|| \cdot ||$](Norma matricial), [$||\cdot||_ \alpha$](Norma matricial), [[Matriz ortogonal]]

---
### Anki

START
Básico
Anverso: Definición de norma matricial subordinada a una norma vectorial
Reverso: Una norma matricial subordinada a una norma vectorial $|| \cdot ||_\alpha$ se define como:
$$A \in \mathbb R^{n \times n}, \quad ||A||_\alpha := \textrm{sup}_{x \neq 0} \frac{||Ax||_\alpha}{||x||_\alpha}.$$
En esta definición $\alpha \in \mathbb N \cup \{ \infty \}$. Además, para $A \in \mathbb R^{n \times n}$, son equivalentes:
$$||A||_\alpha = \sup \limits_{x \neq 0} \frac{||Ax||_\alpha}{||x||_\alpha} = \max \limits_{x \neq 0} \frac{||Ax||_\alpha}{||x||_\alpha} = \max \limits_{||x||_\alpha = 1} ||Ax||_\alpha.$$
Tags: met
<!--ID: 1735044171392-->
END
