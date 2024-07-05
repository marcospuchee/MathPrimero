
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-16, 10:09

```ad-lemma
$(E, V, +)$ [[espacio afín euclídeo]]. $P \in E, W_Q \subseteq E$ [[variedad afín]]. Entonces,
$$d(P, W_Q) = d(P, P_{W_Q}(P)).$$
```

```ad-proof
Sea $Y \in W_Q$ arbitrario, y sea $R = P_{W_Q}(P)$. Queremos ver $d(P, Y) \ge d(P, R)$.

Tenemos: $\forall Y \in W_Q, \vec{PY} = \vec{PR} + \vec{RY}$. Ahora $\vec{PR} \in W^\perp$ (por [[Existencia y unicidad proyección ortogonal de un punto en una variedad afín]]) y $\vec{RY} \in W$ (porque $R,Y \in W_Q$). Así, $\vec{PR} \perp \vec{RY}$, es decir $(\vec{PR})(\vec{RY}) = 0$.

Tenemos:
$$\begin{eqnarray}
||\vec{PY}||^2 &=& (\vec{PY})(\vec{PY}) = (\vec{PR}+\vec{RY})(\vec{PR}+\vec{RY}) = (\vec{PR})(\vec{PR}) + 2(\vec{PR})(\vec{RY}) + (\vec{RY}\vec{RY}) \\
&=& ||\vec{PR}||^2 + ||\vec{RY}||^2 \ge ||\vec{PR}||^2 \implies ||\vec{PY}|| \ge ||\vec{PR}||,
\end{eqnarray}$$
es decir, $d(P, Y) \ge d(P, R)$.

Conclusión: $d(P, W_Q) = d(P, P_{W_Q}(P))$.
```

**Tema:** [[Espacios afines euclídeos]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
$(E, V, +)$ [[Espacio afín euclídeo]]. $P \in E, W_Q \subseteq E$ [[Variedad afín]]. Entonces,
$${{c1::d(P, W_Q)}} = {{c2::d(P, P_{W_Q}(P))}}.$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1715864620189-->
END

START
Básico
Anverso: Demostración de que sea $(E, V, +)$ [[Espacio afín euclídeo]]. $P \in E, W_Q \subseteq E$ [[Variedad afín]]. Entonces,
$$d(P, W_Q) = d(P, P_{W_Q}(P)).$$
Reverso: Sea $Y \in W_Q$ arbitrario, y sea $R = P_{W_Q}(P)$. Queremos ver $d(P, Y) \ge d(P, R)$.

Tenemos: $\forall Y \in W_Q, \vec{PY} = \vec{PR} + \vec{RY}$. Ahora $\vec{PR} \in W^\perp$ (por [[Existencia y unicidad proyección ortogonal de un punto en una variedad afín]]) y $\vec{RY} \in W$ (porque $R,Y \in W_Q$). Así, $\vec{PR} \perp \vec{RY}$, es decir $(\vec{PR})(\vec{RY}) = 0$.

Tenemos:
$$\begin{eqnarray}
||\vec{PY}||^2 &=& (\vec{PY})(\vec{PY}) = (\vec{PR}+\vec{RY})(\vec{PR}+\vec{RY}) = (\vec{PR})(\vec{PR}) + 2(\vec{PR})(\vec{RY}) + (\vec{RY}\vec{RY}) \\
&=& ||\vec{PR}||^2 + ||\vec{RY}||^2 \ge ||\vec{PR}||^2 \implies ||\vec{PY}|| \ge ||\vec{PR}||,
\end{eqnarray}$$
es decir, $d(P, Y) \ge d(P, R)$.

Conclusión: $d(P, W_Q) = d(P, P_{W_Q}(P))$.
Tags: demostración ÁlgebraI
<!--ID: 1715864620195-->
END

