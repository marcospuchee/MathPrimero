
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-15, 19:25

```ad-theorem
$\vec{F}(\vec{r})$ es un [[campo de fuerzas conservativo]] sii la integral curvilínea ([[integral curvilínea de un campo vectorial]]) a lo largo de cualquier curva cerrada es cero,

$$
\oint \vec{F} \cdot d\vec{r} = 0
$$

$\oint \vec F \cdot d \vec r$ representa a la [[integral curvilínea de un campo vectorial]] sobre una curva cerrada.
```

```ad-proof
$\rightarrow$.
Consideramos una curva cerrada $C$, que empieza y termina en el mismo punto $\vec r_0$. Si dividimos $C$ en dos partes, $\gamma_1$ y $\gamma_2$, tales que $\gamma_1$ va de $\vec r_0$ a $\vec r_1$ y $\gamma_2$ regresa de $\vec r_1$ a $\vec r_0$, entonces:
$$\oint_c \vec F \cdot d\vec r = \int_{\gamma_1} \vec F \cdot d \vec r + \int_{\gamma_2} \vec F \cdot d \vec r.$$
Como $\vec F$ es conservativo:
$$\int_{\gamma_1} \vec F \cdot d \vec r = f(\vec r_0, \vec r_1), \quad \int_{\gamma_2} \vec F \cdot d \vec r = f(\vec r_1, \vec r_0),$$
pero como $\gamma_2$ es la misma curva que $\gamma_1$ pero en sentido contrario, tenemos:
$$\int_{\gamma_2} \vec F \cdot d \vec r = -f(\vec r_0, \vec r_1).$$
Sumando ambas, tenemos:
$$\oint_C \vec F \cdot d \vec r = f(\vec r_0, \vec r_1) - f(\vec r_0, \vec r_1) = 0.$$

$\leftarrow$.
Supongamos que $\oint_C \vec F \cdot d \vec r = 0$ para cualquier curva cerrada $C$. Para demostrar que $\vec F(\vec r)$ es conservativo, debemos demostrar que el trabajo realizado por $\vec F$ entre dos puntos $\vec r_1$ y $\vec r_2$ no depende del camino tomado.
Consideremos dos curvas $\gamma$ y $\gamma'$ que van de $\vec r_1$ a $\vec r_2$. Formamos una curva cerrada uniendo $\gamma$ y $-\gamma'$ (la curva $\gamma'$ recorrida en sentido inverso), denotada por $C$.
Por hipótesis, tenemos:
$$\oint_C \vec F \cdot d \vec r = \int_\gamma \vec F \cdot d \vec r + \int_{-\gamma'} \vec F \cdot d \vec r = \int_\gamma \vec F \cdot d \vec r - \int_{\gamma'} \vec F \cdot d \vec r = 0.$$
Por lo tanto,
$$\int_\gamma \vec F \cdot \vec r = \int_{\gamma'} \vec F \cdot d \vec r.$$
Esto demuestra que la integral de $\vec F$ entre $\vec r_1$ y $\vec r_2$ es independiente del camino tomado.
```

```ad-note
title: Notación
Si $\vec{F}(\vec{r})$ es conservativo, escribiremos
$$
\int_{\gamma} \vec{F} \cdot d\vec{r} = \int_{\vec{r}_1}^{\vec{r}_2} \vec{F} \cdot d\vec{r}
$$
```


**Tema:** [[Fuerzas conservativas. Campo central.#a) Campos de fuerzas conservativos. Función potencial.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de caracterización de un campo de fuerzas conservativo?
Reverso: $\vec{F}(\vec{r})$ es un [[campo de fuerzas conservativo]] sii la integral curvilínea ([[integral curvilínea de un campo vectorial]]) a lo largo de cualquier curva cerrada es cero,

$$
\oint \vec{F} \cdot d\vec{r} = 0
$$
Tags:
ENaD
