### Contenido Principal

```ad-proposition
El diferencial $T$ (definición en [[función diferenciable]]) es único.
```

^165e12

```ad-proof
Como $\Omega$ abierto, entonces $\exists \delta > 0$ tal que $B(a, \delta) \subseteq \Omega$. Sea $u \in \mathbb R^n \textrm{\\} \{0\}$, $t \in \mathbb R$ con $0 < |t| < \frac{\delta}{||u||}$, entonces
$$||a+tu - a|| = |t| \, ||u|| < \delta,$$
luego $a+tu \in B(a, \delta) \subseteq \Omega$. Como $\lim_{t \to 0} (a+tu) = a$, puedo hacer el cambio $x = a+tu$ en el límite de la diferenciabilidad:
$$\begin{eqnarray}
0 = \lim_{t \to 0} \frac{||f(a+tu) - f(a) - T(tu)||}{||tu||} &=& \frac{1}{||u||} \lim_{t \to 0} \left | \left | \frac{f(a+tu) - f(a) - tT(u)}{t} \right | \right | \\

&=& \frac{1}{||u||} \lim_{t \to 0} \left | \left | \frac{f(a+tu) - f(a)}{t}  - T(u) \right | \right |.
\end{eqnarray}$$

Sin embargo, esto último implica que
$$T(u) = \lim_{t \to 0} \frac{f(a+tu) - f(a)}{t}, \quad \forall u \in \mathbb R^n.$$

Si $\exists T_1, T_2 \in \mathcal L(\mathbb R^n, \mathbb R^m)$ cumpliendo la hipótesis de diferenciabilidad, entonces cumplen esta última igualdad, luego $T_1 = T_2$.
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#1. Derivadas direccionales y diferencial.]]

---
### Anki

START
Básico
Anverso: Proposición diferencial único
Reverso: Sean $\Omega$ un abierto de $\mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Decimos que $f$ es diferenciable en $a$ si $\exists T \in \mathcal L(\mathbb R^n, \mathbb R^m)$ continua tal que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} = 0.$$

A la aplicación $T$ la llamamos diferencial, la denotamos $Df(a)$. Este diferencial es único
Tags: anII
<!--ID: 1728549801700-->
END

START
Básico
Anverso: Demostración de que sean $\Omega$ un abierto de $\mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Decimos que $f$ es diferenciable en $a$ si $\exists T \in \mathcal L(\mathbb R^n, \mathbb R^m)$ continua tal que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} = 0.$$

A la aplicación $T$ la llamamos diferencial, la denotamos $Df(a)$. Este diferencial es único
Reverso: Como $\Omega$ abierto, entonces $\exists \delta > 0$ tal que $B(a, \delta) \subseteq \Omega$. Sea $u \in \mathbb R^n \textrm{\\} \{0\}$, $t \in \mathbb R$ con $0 < |t| < \frac{\delta}{||u||}$, entonces
$$||a+tu - a|| = |t| \, ||u|| < \delta,$$
luego $a+tu \in B(a, \delta) \subseteq \Omega$. Como $\lim_{t \to 0} (a+tu) = a$, puedo hacer el cambio $x = a+tu$ en el límite de la diferenciabilidad:
$$\begin{eqnarray}
0 = \lim_{t \to 0} \frac{||f(a+tu) - f(a) - T(tu)||}{||tu||} &=& \frac{1}{||u||} \lim_{t \to 0} \left | \left | \frac{f(a+tu) - f(a) - tT(u)}{t} \right | \right | \\

&=& \frac{1}{||u||} \lim_{t \to 0} \left | \left | \frac{f(a+tu) - f(a)}{t}  - T(u) \right | \right |.
\end{eqnarray}$$

Sin embargo, esto último implica que
$$T(u) = \lim_{t \to 0} \frac{f(a+tu) - f(a)}{t}, \quad \forall u \in \mathbb R^n.$$

Si $\exists T_1, T_1 \in \mathcal L(\mathbb R^n, \mathbb R^m)$ cumpliendo la hipótesis de diferenciabilidad, entonces cumplen esta última igualdad, luego $T_1 = T_2$.
Tags: anII dem
<!--ID: 1728549801732-->
END
