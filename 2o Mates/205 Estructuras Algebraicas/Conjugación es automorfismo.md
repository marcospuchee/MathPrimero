### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]] y $g \in G$. Entonces la aplicación
$$\begin{matrix}
\alpha_g: & G & \to & G \\
& x & \to & gxg^{-1}
\end{matrix}$$
es un automorfismo de $G$. Para $x \in G$, su imagen $\alpha_g(x) = gxg^{-1}$ es el elemento conjugado de $x$ por $g$ y lo dentamos por $^g x = gxg^{-1}$.
```

^691f17

```ad-proof
Para ver que sea homomorfismo, sean $x,y \in G$. Tenemos que
$$\alpha_g(xy) = gxyg^{-1} = gx1_gyg^{-1} = gxg^{-1}gyg^{-1} = \alpha_g(x) \alpha_g(y).$$

Para ver que es biyectiva, basta con recordar que $\alpha_g = L_g \circ R_{g^{-1}}$, por tanto $\alpha_g$ es biyectiva.
```

**Tema:** [[Teoría de grupos#9. Homomorfismos.]]

---
### Anki

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]] y $g \in G$. Entonces la aplicación
$$\begin{matrix}
\alpha_g: & G & \to & G \\
& x & \to & gxg^{-1}
\end{matrix}$$
es un automorfismo de $G$. Para $x \in G$, su imagen $\alpha_g(x) = gxg^{-1}$ es el elemento conjugado de $x$ por $g$ y lo dentamos por $^g x = gxg^{-1}$.
Reverso: Para ver que sea homomorfismo, sean $x,y \in G$. Tenemos que
$$\alpha_g(xy) = gxyg^{-1} = gx1_gyg^{-1} = gxg^{-1}gyg^{-1} = \alpha_g(x) \alpha_g(y).$$

Para ver que es biyectiva, basta con recordar que $\alpha_g = L_g \circ R_{g^{-1}}$, por tanto $\alpha_g$ es biyectiva.
Tags: dem est
<!--ID: 1728549801410-->
END
