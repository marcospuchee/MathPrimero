
---
mathLink: $\vec t(s)$ es unitario
---
### Contenido Principal

**Fecha:** 2024-02-23, 14:16

Sea $\vec t(s)$ el [[Vector tangente unitario]] a $\vec r(s)$, entonces

```ad-proposition
$\vec t(s)$ es un [[Vector unitario]]
```


```ad-proof
Tenemos que $s(t) = \int^t_{t_0} v(t) dt$ ([[Camino recorrido]]), entonces $s'(t) = v(t) > 0 \implies$ $s(t)$ es estrictamente creciente $\implies$ $s(t)$ inyectiva $\implies$ $s^{-1}(t) = t(s) \implies$ $\vec r(t(s)) = \vec r(s)$, luego tenemos la trayectoria parametrizada con $s$.

Como tenemos también $s(t)$, podemos calcular $\vec r(s(t)) = (\vec r \circ s)(t)$. Así, gracias a las [[Fórmulas de derivación]], sabemos que 
$$
\begin{eqnarray}
\dot{(\vec r \circ s)}(t) &=& r'(s(t)) · \dot s(t) \\
&=& r'(s(t)) · v(t).
\end{eqnarray}
$$
Así, tenemos que
$$\vec v(t) = \vec r'(s(t)) v(t) \implies r'(s(t)) = \frac{\vec v(t)}{v(t)},$$
y como $\vec t(s) \equiv r'(s(t))$, entonces tenemos que es unitario.
```

**Tema:** [[Cinemática clásica#3.a Elementos básicos de cinemática]]
**Corolarios:** [[El vector curvatura y el vector tangente unitario son ortogonales]]

---
### Anki

START
Básico
Anverso: Demostración de que el vector tangente unitario es unitario
Reverso: Tenemos que $s(t) = \int^t_{t_0} v(t) dt$ ([[Camino recorrido]]), entonces $s'(t) = v(t) > 0 \implies$ $s(t)$ es estrictamente creciente $\implies$ $s(t)$ inyectiva $\implies$ $s^{-1}(t) = t(s) \implies$ $\vec r(t(s)) = \vec r(s)$, luego tenemos la trayectoria parametrizada con $s$.

Como tenemos también $s(t)$, podemos calcular $\vec r(s(t)) = (\vec r \circ s)(t)$. Así, gracias a las [[Fórmulas de derivación]], sabemos que 
$$
\begin{eqnarray}
\dot{(\vec r \circ s)}(t) &=& r'(s(t)) · \dot s(t) \\
&=& r'(s(t)) · v(t).
\end{eqnarray}
$$
Así, tenemos que
$$\vec v(t) = \vec r'(s(t)) v(t) \implies r'(s(t)) = \frac{\vec v(t)}{v(t)},$$
y como $\vec t(s) \equiv r'(s(t))$, entonces tenemos que es unitario.
Tags: demostración Física
<!--ID: 1708971255661-->
END
