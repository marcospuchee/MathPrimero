
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-15, 19:33

```ad-proposition
El trabajo ([[trabajo de una fuerza]]) $\vec{F}(\vec{r})$ entre dos puntos $\vec{r}_1$ y $\vec{r}_2$ es igual a la pérdida de energía potencial, es decir,

$$
\int_{\vec{r}_1}^{\vec{r}_2} \vec{F} \cdot d\vec{r} = U(\vec{r}_1) - U(\vec{r}_2) = -\Delta U.
$$
```

```ad-proof
Por definición de [[potencial]], podemos definir $U(\vec r)$ como:
$$U(\vec r) = - \int_{\vec r_0}^{\vec r} \vec F \cdot d \vec r.$$
Para dos puntos $\vec r_1$ y $\vec r_2$, consideramos la [[integral curvilínea de un campo vectorial]] $\vec F$ desde $\vec r_1$ hasta $\vec r_2$:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r.$$
Usando la definición de $U(\vec r)$, tenemos:
$$U(\vec r_1) = - \int_{\vec r_0}^{\vec r_1} \vec F \cdot d \vec r, \quad U(\vec r_2) = - \int_{\vec r_0}^{\vec r_2} \vec F \cdot d \vec r.$$
El trabajo realizado por $\vec F$ ([[trabajo de una fuerza]]) para mover una partícula $\vec r_1$ a $\vec r_2$ es:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r.$$
Esto puede ser expresado en términos de $U(\vec r)$ como:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r = \left ( - \int_{\vec r_0}^{\vec r_1} \vec F \cdot d \vec r \right ) - \left ( - \int_{\vec r_0}^{\vec r_2} \vec F \cdot d \vec r  \right ) = \left ( \int_{\vec r_0}^{\vec r_2} \vec F \cdot d \vec r  - \int_{\vec r_0}^{\vec r_1} \vec F \cdot d \vec r \right ),$$
que, aplicando la definición de potencial tenemos:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r = U(\vec r_1) - U(\vec r_2).$$
```

**Tema:** [[Fuerzas conservativas. Campo central.#b) Conservación de la energía.]] 
**Corolarios:**

---
### Anki

START
Básico
Anverso: Qué relación hay entre el trabajo realizado y la energía potencial?
Reverso: El trabajo ([[trabajo de una fuerza]]) $\vec{F}(\vec{r})$ entre dos puntos $\vec{r}_1$ y $\vec{r}_2$ es igual a la pérdida de energía potencial, es decir,
$$
\int_{\vec{r}_1}^{\vec{r}_2} \vec{F} \cdot d\vec{r} = U(\vec{r}_1) - U(\vec{r}_2) = -\Delta U.
$$
Tags: proposición/teorema Física
<!--ID: 1718442849523-->
END

START
Básico
Anverso: Demostración de que el trabajo ([[trabajo de una fuerza]]) $\vec{F}(\vec{r})$ entre dos puntos $\vec{r}_1$ y $\vec{r}_2$ es igual a la pérdida de energía potencial, es decir,
$$
\int_{\vec{r}_1}^{\vec{r}_2} \vec{F} \cdot d\vec{r} = U(\vec{r}_1) - U(\vec{r}_2) = -\Delta U.
$$
Reverso: Por definición de [[potencial]], podemos definir $U(\vec r)$ como:
$$U(\vec r) = - \int_{\vec r_0}^{\vec r} \vec F \cdot d \vec r.$$
Para dos puntos $\vec r_1$ y $\vec r_2$, consideramos la [[integral curvilínea de un campo vectorial]] $\vec F$ desde $\vec r_1$ hasta $\vec r_2$:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r.$$
Usando la definición de $U(\vec r)$, tenemos:
$$U(\vec r_1) = - \int_{\vec r_0}^{\vec r_1} \vec F \cdot d \vec r, \quad U(\vec r_2) = - \int_{\vec r_0}^{\vec r_2} \vec F \cdot d \vec r.$$
El trabajo realizado por $\vec F$ ([[trabajo de una fuerza]]) para mover una partícula $\vec r_1$ a $\vec r_2$ es:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r.$$
Esto puede ser expresado en términos de $U(\vec r)$ como:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r = \left ( - \int_{\vec r_0}^{\vec r_1} \vec F \cdot d \vec r \right ) - \left ( - \int_{\vec r_0}^{\vec r_2} \vec F \cdot d \vec r  \right ) = \left ( \int_{\vec r_0}^{\vec r_2} \vec F \cdot d \vec r  - \int_{\vec r_0}^{\vec r_1} \vec F \cdot d \vec r \right ),$$
que, aplicando la definición de potencial tenemos:
$$\int_{\vec r_1}^{\vec r_2} \vec F \cdot d \vec r = U(\vec r_1) - U(\vec r_2).$$
Tags: demostración Física
<!--ID: 1718442849526-->
END
