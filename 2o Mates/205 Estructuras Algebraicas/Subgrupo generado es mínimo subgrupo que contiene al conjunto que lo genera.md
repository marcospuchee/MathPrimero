### Contenido Principal

```ad-proposition
Sea $G$ [[grupo]], $X \subseteq G$. Si $H \le G$ tal que $X \subseteq H$, entonces $\langle X \rangle \le H$.
```

^51fd98

```ad-proof
Sea $x_1^{n_1}, \dots x_r^{n_r} \in \langle X \rangle$. Veamos que $x_1^{n_1} \dots x_r^{n_r} \in H$. Procederemos por inducción sobre $r$:
- $r = 0$. $1_G \in H$.
- $r+1$. $x_1^{n_1} \dots x_{r+1}^{n_{r+1}} = (x_1^{n_1} x_2^{n_2} \dots x_r^{n_r})x_{r+1}^{n_{r+1}} \in H$, porque $(x_1^{n_1} x_2^{n_2} \dots x_r^{n_r}) \in H$ y $x_{r+1}^{n_{r+1}} \in H$.

```

**Tema:** [[Teoría de grupos#7. Subgrupo generado.]]

---
### Anki

START
Básico
Anverso: Proposición subgrupo generado es el mínimo subgrupo que contiene al conjunto que lo genera
Reverso: Sea $G$ [[grupo]], $X \subseteq G$. Si $H \le G$ tal que $X \subseteq H$, entonces $\langle X \rangle \le H$.
<!--ID: 1727966478069-->
END

START
Básico
Anverso: Demostración de que sea $G$ [[grupo]], $X \subseteq G$. Si $H \le G$ tal que $X \subseteq H$, entonces $\langle X \rangle \le H$.
Reverso: Sea $x_1^{n_1}, \dots x_r^{n_r} \in \langle X \rangle$. Veamos que $x_1^{n_1} \dots x_r^{n_r} \in H$. Procederemos por inducción sobre $r$:
- $r = 0$. $1_G \in H$.
- $r+1$. $x_1^{n_1} \dots x_{r+1}^{n_{r+1}} = (x_1^{n_1} x_2^{n_2} \dots x_r^{n_r})x_{r+1}^{n_{r+1}} \in H$, porque $(x_1^{n_1} x_2^{n_2} \dots x_r^{n_r}) \in H$ y $x_{r+1}^{n_{r+1}} \in H$.
Tags: dem est
<!--ID: 1727966478116-->
END
