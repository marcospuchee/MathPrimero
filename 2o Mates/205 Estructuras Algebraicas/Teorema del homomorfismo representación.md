### Contenido Principal

```ad-theorem
Sea $G \curvearrowright \Omega$. Entonces:
1. $\forall g \in G$, la aplicación
$$\begin{array}{c c c l}
\rho_g: & \Omega & \to & \Omega \\
& \alpha & \mapsto & g \cdot \alpha
\end{array}$$
es una biyección.
2. La aplicación
$$\begin{array}{c c c l}
\rho: & G & \to & S_\Omega \\
& g & \mapsto & \rho_g
\end{array}$$
es un homomorfismo llamado homomorfismo representación.
```

```ad-proof
1. En primer lugar, demostramos que $\rho_g$ es inyectiva. Sean $\alpha, \beta \in \Omega$ tales que $\rho_g(\alpha) = \rho_g(\beta)$. Veamos que $\alpha = \beta$. Notamos la siguiente cadena de igualdades:
$$\begin{eqnarray}
\alpha = 1_G \cdot \alpha &=& (g^{-1}g) \cdot \alpha = g^{-1} \cdot (g \cdot \alpha) \\
&=& g^{-1}\cdot (g \cdot \beta) = (g^{-1}g) \cdot \beta = 1_G \cdot \beta = \beta.
\end{eqnarray}$$
Sea $\beta \in \Omega$. Demostramos que $\exists \alpha \in \Omega$ tal que $\rho_g (\alpha) = \beta$. Consideramos $\alpha = g^{-1} \cdot \beta$ y notamos que
$$\rho_g(\alpha) = \rho_g(g^{-1} \cdot \beta) = g \cdot (g^{-1} \cdot \beta) = (gg^{-1}) \cdot \beta = 1_G \cdot \beta = \beta.$$

2. Demostramos que $\rho$ es un homomorfismo. Sean $g,h \in G$. Demostramos que $\rho_{gh} = \rho_g \circ \rho_h$. Notamos la siguiente cadena de igualdades: $\forall \alpha \in \Omega$,
$$\rho_{gh}(\alpha) = (gh) \cdot \alpha = g \cdot(h \cdot \alpha) = g \cdot (\rho_h(\alpha)) = \rho_g(\rho_h(\alpha)) = \rho_g \circ \rho_h(\alpha).$$
```

**Tema:** [[Acciones de grupos#1. Definición.]]
**Corolario:**

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo)
**Resultados referenciados:** *ninguna.*

---
### Anki

START
Básico
Anverso: Definición de homomorfismo representación
Reverso: Sea $G \curvearrowright \Omega$. Entonces:
1. $\forall g \in G$, la aplicación
$$\begin{array}{c c c l}
\rho_g: & \Omega & \to & \Omega \\
& \alpha & \mapsto & g \cdot \alpha
\end{array}$$
es una biyección.
2. La aplicación
$$\begin{array}{c c c l}
\rho: & G & \to & S_\Omega \\
& g & \mapsto & \rho_g
\end{array}$$
es un homomorfismo llamado homomorfismo representación.
Tags: est
<!--ID: 1731931804892-->
END

START
Básico
Anverso: Demostración de que sea $G \curvearrowright \Omega$. Entonces:
1. $\forall g \in G$, la aplicación
$$\begin{array}{c c c l}
\rho_g: & \Omega & \to & \Omega \\
& \alpha & \mapsto & g \cdot \alpha
\end{array}$$
es una biyección.
2. La aplicación
$$\begin{array}{c c c l}
\rho: & G & \to & S_\Omega \\
& g & \mapsto & \rho_g
\end{array}$$
es un homomorfismo llamado homomorfismo representación.
Reverso: 1. En primer lugar, demostramos que $\rho_g$ es inyectiva. Sean $\alpha, \beta \in \Omega$ tales que $\rho_g(\alpha) = \rho_g(\beta)$. Veamos que $\alpha = \beta$. Notamos la siguiente cadena de igualdades:
$$\begin{eqnarray}
\alpha = 1_G \cdot \alpha &=& (g^{-1}g) \cdot \alpha = g^{-1} \cdot (g \cdot \alpha) \\
&=& g^{-1}\cdot (g \cdot \beta) = (g^{-1}g) \cdot \beta = 1_G \cdot \beta = \beta.
\end{eqnarray}$$
Sea $\beta \in \Omega$. Demostramos que $\exists \alpha \in \Omega$ tal que $\rho_g (\alpha) = \beta$. Consideramos $\alpha = g^{-1} \cdot \beta$ y notamos que
$$\rho_g(\alpha) = \rho_g(g^{-1} \cdot \beta) = g \cdot (g^{-1} \cdot \beta) = (gg^{-1}) \cdot \beta = 1_G \cdot \beta = \beta.$$

2. Demostramos que $\rho$ es un homomorfismo. Sean $g,h \in G$. Demostramos que $\rho_{gh} = \rho_g \circ \rho_h$. Notamos la siguiente cadena de igualdades: $\forall \alpha \in \Omega$,
$$\rho_{gh}(\alpha) = (gh) \cdot \alpha = g \cdot(h \cdot \alpha) = g \cdot (\rho_h(\alpha)) = \rho_g(\rho_h(\alpha)) = \rho_g \circ \rho_h(\alpha).$$
Tags: dem est
<!--ID: 1731931804901-->
END
