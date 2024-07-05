
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-15, 19:36

```ad-proposition
La [[energía mecánica total]] de una partícula que se mueve bajo la acción de una [[fuerza conservativa]] $\vec{F}(\vec{r})$ se conserva, es decir, $\dot{E} = 0$.
```

```ad-proof
Tenemos que
$$\frac{dE}{dt} = \frac{d}{dt} (T + U).$$
La derivada de la energía cinética es:
$$\frac{dT}{dt} = \frac{d}{dt} \left ( \frac{1}{2} m v^2 \right ) = m \vec v \frac{d \vec v}{dt} = m \vec v \vec a.$$
Sin embargo, por la [[segunda ley de Newton]], $\vec F(\vec r) = m \vec a$, por tanto:
$$\frac{dT}{dt} = \vec F(\vec r) \cdot \vec v.$$
Por otra parte,
$$\frac{dU(x)}{dt} = \frac{dU(x)}{dx} \frac{dx}{dt} = - \vec F(\vec r) \cdot \vec v.$$
Sumando ambas, obtenemos que $\dot E = 0$.
```

```ad-note
title: Consecuencia
La energía de una partícula puede calcularse dadas unas condiciones
iniciales $(\vec{r}_0, \vec{v}_0)$. Por tanto, la posición $\vec{r}$ y el módulo de la velocidad $v$ de una partícula satisfacen la siguiente relación implícita:
$$
\frac{1}{2}mv^2 + U(\vec{r}) = E , \quad E = \frac{1}{2}mv_0^2 + U(\vec{r}_0)
$$
```


**Tema:** [[Fuerzas conservativas. Campo central.#b) Conservación de la energía.]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Teorema conservación de la energía provocada por una fuerza conservativa
Reverso: La [[energía mecánica total]] de una partícula que se mueve bajo la acción de una [[fuerza conservativa]] $\vec{F}(\vec{r})$ se conserva, es decir, $\dot{E} = 0$.
Tags: proposición/teorema Física
<!--ID: 1718442849536-->
END

START
Básico
Anverso: Demostración de que sa [[energía mecánica total]] de una partícula que se mueve bajo la acción de una [[fuerza conservativa]] $\vec{F}(\vec{r})$ se conserva, es decir, $\dot{E} = 0$.
Reverso: Tenemos que
$$\frac{dE}{dt} = \frac{d}{dt} (T + U).$$
La derivada de la energía cinética es:
$$\frac{dT}{dt} = \frac{d}{dt} \left ( \frac{1}{2} m v^2 \right ) = m \vec v \frac{d \vec v}{dt} = m \vec v \vec a.$$
Sin embargo, por la [[segunda ley de Newton]], $\vec F(\vec r) = m \vec a$, por tanto:
$$\frac{dT}{dt} = \vec F(\vec r) \cdot \vec v.$$
Por otra parte,
$$\frac{dU(x)}{dt} = \frac{dU(x)}{dx} \frac{dx}{dt} = - \vec F(\vec r) \cdot \vec v.$$
Sumando ambas, obtenemos que $\dot E = 0$.
Tags: Física demostración
<!--ID: 1718442849538-->
END
