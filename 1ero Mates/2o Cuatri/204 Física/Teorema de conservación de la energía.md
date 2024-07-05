
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-15, 17:07

```ad-theorem
La [[energía mecánica total]] de una partícula en movimiento unidimensional bajo la acción de una fuerza $F(x)$ se conserva, es decir, $\dot{E} = 0$.
```


```ad-proof
Tenemos que
$$\dot E = \frac{dE}{dt} = \frac{d}{dt} \left (\frac{1}{2}mv^2 + U(x) \right ) = \frac{d}{dt} \left (\frac{1}{2} m v^2 \right ) + \frac{d}{dt} U(x).$$
Está claro que la derivada de la [[energía cinética]] es:
$$\frac{d}{dt} \left ( \frac{1}{2} m v^2 \right ) = mv \frac{dv}{dt} = mva.$$
La derivada de la energía potencial es:
$$\frac{dU}{dt} = \frac{dU}{dx} \frac{dx}{dt} = \frac{dU}{dx} v = - F(x) v.$$
La suma de la derivadas es, por tanto:
$$\dot E = mva - F(x)v.$$

Aplicando la [[segunda ley de Newton]], tenemos que $F(x) = ma$, por tanto, podemos sustituirlo en la suma de las derivadas y tenemos:
$$\dot E = F(x)v - F(x)v = 0.$$
```

```ad-note
title: Corolario
La energía de una partícula puede calcularse para unas condiciones iniciales dadas, $(x_0, v_0)$. Por tanto, la posición $x$ y la velocidad $v$ de una partícula satisfacen la siguiente relación implícita:
$$
E = \frac{1}{2}mv^2 + U(x) \quad , \quad E = \frac{1}{2}mv_0^2 + U(x_0)
$$
```


**Tema:** [[Sistemas conservativos unidimensionales#c) Energía mecánica total. Conservación.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de conservación de la energía?
Reverso: La [[energía mecánica total]] de una partícula en movimiento unidimensional bajo la acción de una fuerza $F(x)$ se conserva, es decir, $\dot{E} = 0$.
Tags: proposición/teorema Física
<!--ID: 1718442849516-->
END

START
Básico
Anverso: Demostración del teorema de la conservación de la energía
Reverso: Tenemos que
$$\dot E = \frac{dE}{dt} = \frac{d}{dt} \left (\frac{1}{2}mv^2 + U(x) \right ) = \frac{d}{dt} \left (\frac{1}{2} m v^2 \right ) + \frac{d}{dt} U(x).$$
Está claro que la derivada de la [[energía cinética]] es:
$$\frac{d}{dt} \left ( \frac{1}{2} m v^2 \right ) = mv \frac{dv}{dt} = mva.$$
La derivada de la energía potencial es:
$$\frac{dU}{dt} = \frac{dU}{dx} \frac{dx}{dt} = \frac{dU}{dx} v = - F(x) v.$$
La suma de la derivadas es, por tanto:
$$\dot E = mva - F(x)v.$$

Aplicando la [[segunda ley de Newton]], tenemos que $F(x) = ma$, por tanto, podemos sustituirlo en la suma de las derivadas y tenemos:
$$\dot E = F(x)v - F(x)v = 0.$$
Tags: demostración Física
<!--ID: 1718442849518-->
END
