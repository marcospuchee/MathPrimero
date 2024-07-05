
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-15, 19:14

```ad-theorem
Si $\vec{r}(t)$ es solución de la ecuación del movimiento $m\ddot{\vec{r}} = \vec{F}(\vec{r})$, entonces

$$
T(t_2) - T(t_1) = \int_{\gamma} \vec{F} \cdot d\vec{r}
$$

siendo $\gamma$ la trayectoria de la partícula entre $t_1$ y $t_2$.

Es decir, el incremento de [[energía cinética]] de la partícula es igual al trabajo realizado por la fuerza a lo largo de la trayectoria,

$$
\Delta T = W_{\vec{F}}(\gamma)
$$
```

```ad-proof
Sabemos que
$$T(t) = \frac{1}{2} m |\vec v (t)|^2 = \frac{1}{2}m\dot{\vec r}(t) \cdot \dot{\vec r}(t).$$
Vamos a calcular la derivada:
$$\frac{dT}{dt} = \frac{d}{dt} \left ( \frac{1}{2}m \dot{\vec r}(t) \cdot \dot{\vec r}(t) \right ) = \frac{1}{2}m \frac{d}{dt} (\dot{\vec r}(t) \cdot \dot{\vec r}(t)) = m \dot{\vec r}(t) \cdot \ddot{\vec r}(t).$$
Ahora utilizamos la ecuación del movimiento:
$$m \ddot{\vec r} = \vec F(\vec r(t)) \implies \frac{dT}{dt} = \dot{\vec r}(t) \cdot \vec F(\vec r(t)).$$
Para encontrar el cambio en la energía cinética entre los tiempos $t_1$ y $t_2$, integramos la derivada de la energía cinética respecto al tiempo desde $t_1$ hasta $t_2$.
$$T(t_2) - T(t_1) = \int_{t_1}^{t_2} \frac{dT}{dt} dt = \int_{t_1}^{t_2} \dot{\vec r(t)} \cdot \vec F(\vec r(t)) dt = \int_\gamma \vec F \cdot d \vec r.$$
```

**Tema:** [[Fuerzas conservativas. Campo central.#c) Teorema de variación de la energía cinética.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que relaciona la energía cinética con el trabajo de una fuerza?
Reverso: Si $\vec{r}(t)$ es solución de la ecuación del movimiento $m\ddot{\vec{r}} = \vec{F}(\vec{r})$, entonces

$$
T(t_2) - T(t_1) = \int_{\gamma} \vec{F} \cdot d\vec{r}
$$

siendo $\gamma$ la trayectoria de la partícula entre $t_1$ y $t_2$.

Es decir, el incremento de [[energía cinética]] de la partícula es igual al trabajo realizado por la fuerza a lo largo de la trayectoria,

$$
\Delta T = W_{\vec{F}}(\gamma)
$$
Tags: proposición/teorema Física
<!--ID: 1718442849511-->
END

START
Básico
Anverso: Demostración de que si $\vec{r}(t)$ es solución de la ecuación del movimiento $m\ddot{\vec{r}} = \vec{F}(\vec{r})$, entonces

$$
T(t_2) - T(t_1) = \int_{\gamma} \vec{F} \cdot d\vec{r}
$$

siendo $\gamma$ la trayectoria de la partícula entre $t_1$ y $t_2$.

Es decir, el incremento de [[energía cinética]] de la partícula es igual al trabajo realizado por la fuerza a lo largo de la trayectoria,
$$
\Delta T = W_{\vec{F}}(\gamma)
$$
Reverso: Sabemos que
$$T(t) = \frac{1}{2} m |\vec v (t)|^2 = \frac{1}{2}m\dot{\vec r}(t) \cdot \dot{\vec r}(t).$$
Vamos a calcular la derivada:
$$\frac{dT}{dt} = \frac{d}{dt} \left ( \frac{1}{2}m \dot{\vec r}(t) \cdot \dot{\vec r}(t) \right ) = \frac{1}{2}m \frac{d}{dt} (\dot{\vec r}(t) \cdot \dot{\vec r}(t)) = m \dot{\vec r}(t) \cdot \ddot{\vec r}(t).$$
Ahora utilizamos la ecuación del movimiento:
$$m \ddot{\vec r} = \vec F(\vec r(t)) \implies \frac{dT}{dt} = \dot{\vec r}(t) \cdot \vec F(\vec r(t)).$$
Para encontrar el cambio en la energía cinética entre los tiempos $t_1$ y $t_2$, integramos la derivada de la energía cinética respecto al tiempo desde $t_1$ hasta $t_2$.
$$T(t_2) - T(t_1) = \int_{t_1}^{t_2} \frac{dT}{dt} dt = \int_{t_1}^{t_2} \dot{\vec r(t)} \cdot \vec F(\vec r(t)) dt = \int_\gamma \vec F \cdot d \vec r.$$
Tags: demostración Física
<!--ID: 1718442849513-->
END
