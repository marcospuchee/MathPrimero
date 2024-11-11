### Contenido Principal

```ad-proposition
Sea $G$ un [[grupo]] y $H \le G$. Entonces la aplicación
$$\begin{matrix*}
\alpha_H : & \mathcal R_H & \to & \mathcal L_H \\
& Hx & \to & x^{-1}H
\end{matrix*}$$
es una biyección.
```

^3ee799

```ad-proof
- Inyectiva: supongamos que $x^{-1}H = \alpha_H(Hx) = \alpha_H (Hy) = y^{-1}H$. Esto ocurre sii 
$$(x^{-1}H)^{-1} = (y^{-1}H)^{-1} \iff H^{-1}(x^{-1})^{-1} = H^{-1}(y^{-1})^{-1} \iff Hx = Hy.$$
- Sobreyectiva: sea $xH \in \mathcal L_H$, $\alpha_H(Hx^{-1}) = (x^{-1})^{-1}H = xH$.
```

**Tema:** [[Teoría de grupos#6. Teorema de Lagrange.]]

---
### Anki

START
Básico
Anverso: Biyección entre conjuntos de coclases
Reverso: Sea $G$ un [[Grupo]] y $H \le G$. Entonces la aplicación
$$\begin{matrix*}
\alpha_H : & \mathcal R_H & \to & \mathcal L_H \\
& Hx & \to & x^{-1}H
\end{matrix*}$$
es una biyección.
<!--ID: 1727339263731-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]] y $H \le G$. Entonces la aplicación
$$\begin{matrix*}
\alpha_H : & \mathcal R_H & \to & \mathcal L_H \\
& Hx & \to & x^{-1}H
\end{matrix*}$$
es una biyección.
Reverso: 
- Inyectiva: supongamos que $x^{-1}H = \alpha_H(Hx) = \alpha_H (Hy) = y^{-1}H$. Esto ocurre sii 
$$(x^{-1}H)^{-1} = (y^{-1}H)^{-1} \iff H^{-1}(x^{-1})^{-1} = H^{-1}(y^{-1})^{-1} \iff Hx = Hy.$$
- Sobreyectiva: sea $xH \in \mathcal L_H$, $\alpha_H(Hx^{-1}) = (x^{-1})^{-1}H = xH$.
Tags: dem est
<!--ID: 1727339263733-->
END
