
---
mathLink: $\vec a = \dot v \vec t + v^2 \vec k$
---
### Contenido Principal

**Fecha:** 2024-02-23, 14:40

Sea $\vec a$ el vector [[Aceleración]], $v$ el módulo ([[Módulo de un vector]]) del vector [[Velocidad]], $\vec t$ el [[Vector tangente unitario]], $\vec k$ el [[Vector curvatura]]. Entonces,

```ad-proposition
$$\vec a = \dot v \vec t + v^2 \vec k$$
```


```ad-proof
Por definición de vector tangente unitario, sabemos que $\vec v(t) = v(t) · \vec t(t)$. Así, derivando según el tiempo, obtenemos:
$$
\begin{eqnarray}
\vec a(t) = \dot{\vec v}(t) &=& \dot v(t) \vec t (t) + v(t) \vec t'(s(t)) \dot s(t) \\
&=& \dot v(t) \vec t(t) + v(t) \vec k(s(t)) v(t) \\
&=& \dot v(t) \vec t(t) + v^2(t) \vec k(s(t)),
\end{eqnarray}
$$
dado que sabemos que $t'(s(t)) = \vec k(s(t))$ por definición de [[Vector curvatura]], y también que $\dot s(t) = \vec v(t)$ por definición de [[Camino recorrido]].
```



**Tema:** [[Cinemática clásica#3.a Elementos básicos de cinemática]]
**Corolarios:** [[Fórmula curvatura a partir de la velocidad y aceleración]]

---
### Anki

START
Básico
Anverso: Demuestra que sea $\vec a$ el vector [[Aceleración]], $v$ el módulo ([[Módulo de un vector]]) del vector [[Velocidad]], $\vec t$ el [[Vector tangente unitario]], $\vec k$ el [[Vector curvatura]]. Entonces,
$$\vec a = \dot v \vec t + v^2 \vec k$$
Reverso: Por definición de vector tangente unitario, sabemos que $\vec v(t) = v(t) · \vec t(t)$. Así, derivando según el tiempo, obtenemos:
$$
\begin{eqnarray}
\vec a(t) = \dot{\vec v}(t) &=& \dot v(t) \vec t (t) + v(t) \vec t'(s(t)) \dot s(t) \\
&=& \dot v(t) \vec t(t) + v(t) \vec k(s(t)) v(t) \\
&=& \dot v(t) \vec t(t) + v^2(t) \vec k(s(t)),
\end{eqnarray}
$$
dado que sabemos que $t'(s(t)) = \vec k(s(t))$ por definición de [[Vector curvatura]], y también que $\dot s(t) = \vec v(t)$ por definición de [[Camino recorrido]].
Tags: demostración Física
<!--ID: 1708971255652-->
END


START
Respuesta anidada
Sea $\vec a$ el vector [[Aceleración]], $v$ el módulo ([[Módulo de un vector]]) del vector [[Velocidad]], $\vec t$ el [[Vector tangente unitario]], $\vec k$ el [[Vector curvatura]]. Entonces,
$${{c1::\vec a}} ={{c2::\dot v \vec t + v^2 \vec k}}$$
Tags: proposición/teorema Física
<!--ID: 1708971255656-->
END
