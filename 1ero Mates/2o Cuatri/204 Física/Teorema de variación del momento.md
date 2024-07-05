
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-15, 16:42

```ad-theorem
Si las fuerzas internas de un sistema de partículas no aislado son newtonianas ([[fuerza newtoniana]]),

$$
\dot{\vec{P}}(t) = \vec{F}_E
$$
[[Resultante de las fuerzas externas]].
```


```ad-proof
Consideremos un sistema de $N$ partículas, donde la $i$-ésima partícula tiene masa $m_i$ y posición $\vec r_i(t)$. La velocidad de la $i$-ésima partícula es $\vec v_i (t) = \dot{\vec r_i}(t)$. El momento lineal de la $i$-ésima partícula ([[momento lineal de una partícula]]) es $\vec{p_i}(t) = m_i \vec{v_i}(t)$.

El momento lineal total del sistema de partículas es:
$$\vec P(t) = \sum_{i = 1}^N \vec p_i(t) = \sum_{i = 1}^N m_i \vec v_i(t).$$

Sabemos por la [[segunda ley de Newton]] que la fuerza total que actúa sobre la $i$-ésima partícula es:
$$\vec F_i = m_i \dot{\vec v_i} = \vec F_{i, \textrm{ext}} + \sum^N_{j=1, j \neq i} \vec F_{ij}.$$
Sumando las ecuaciones del movimiento para todas las partículas, obtenemos:
$$\sum_{i = 1}^N m_i \dot{\vec v_i} = \sum_{i = 1}^N \vec F_{i, \textrm{ext}} + \sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij}.$$
El término de la izquierda es la derivada del momento lineal total:
$$\sum_{i = 1}^N m_i \dot{\vec v_i} = \frac{d}{dt} \left ( \sum_{i = 1}^N m_i \vec v_i \right ) = \dot{\vec P(t)}.$$
Por lo tanto, tenemos
$$\dot{\vec P}(t) = \sum_{i = 1}^N \vec F_{i, \textrm{ext}} + \sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij}.$$
Usando la [[ley de acción-reacción (tercera ley de Newton)]], podemos reorganizar la suma doble:
$$\sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij} = \sum_{i = 1}^N \sum_{j = 1, j \neq i}^N (-\vec F_{ji}) = - \sum_{j = 1}^N \sum_{i = 1, i \neq j}^N \vec F_{ji}.$$
Luego cada par de fuerzas internas $\vec F_{ij}$ y $\vec F_{ji}$ se cancela mutuamente, lo que da como resultado cero:
$$\sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij} = 0.$$
Por lo tanto, la ecuación del movimiento lineal total se reduce a:
$$\dot{\vec P}(t) = \sum_{i = 1}^N \vec F_{i, \textrm{ext}} = \vec F_E.$$
```

**Tema:** [[Mecánica Newtoniana#c) Teoremas de variación de los momentos lineal y angular.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de variación del momento?
Reverso: Si las fuerzas internas de un sistema de partículas son newtonianas ([[fuerza newtoniana]]),

$$
\dot{\vec{P}}(t) = \vec{F}_E
$$
[[Resultante de las fuerzas externas]].
Tags: proposición/teorema Física
<!--ID: 1718033660683-->
END

START
Básico
Anverso: Demostración de que si las fuerzas internas de un sistema de partículas son newtonianas ([[fuerza newtoniana]]),

$$
\dot{\vec{P}}(t) = \vec{F}_E
$$
[[Resultante de las fuerzas externas]].
Reverso: Consideremos un sistema de $N$ partículas, donde la $i$-ésima partícula tiene masa $m_i$ y posición $\vec r_i(t)$. La velocidad de la $i$-ésima partícula es $\vec v_i (t) = \dot{\vec r_i}(t)$. El momento lineal de la $i$-ésima partícula ([[momento lineal de una partícula]]) es $\vec{p_i}(t) = m_i \vec{v_i}(t)$.

El momento lineal total del sistema de partículas es:
$$\vec P(t) = \sum_{i = 1}^N \vec p_i(t) = \sum_{i = 1}^N m_i \vec v_i(t).$$

Sabemos por la [[segunda ley de Newton]] que la fuerza total que actúa sobre la $i$-ésima partícula es:
$$\vec F_i = m_i \dot{\vec v_i} = \vec F_{i, \textrm{ext}} + \sum^N_{j=1, j \neq i} \vec F_{ij}.$$
Sumando las ecuaciones del movimiento para todas las partículas, obtenemos:
$$\sum_{i = 1}^N m_i \dot{\vec v_i} = \sum_{i = 1}^N \vec F_{i, \textrm{ext}} + \sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij}.$$
El término de la izquierda es la derivada del momento lineal total:
$$\sum_{i = 1}^N m_i \dot{\vec v_i} = \frac{d}{dt} \left ( \sum_{i = 1}^N m_i \vec v_i \right ) = \dot{\vec P(t)}.$$
Por lo tanto, tenemos
$$\dot{\vec P}(t) = \sum_{i = 1}^N \vec F_{i, \textrm{ext}} + \sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij}.$$
Usando la [[ley de acción-reacción (tercera ley de Newton)]], podemos reorganizar la suma doble:
$$\sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij} = \sum_{i = 1}^N \sum_{j = 1, j \neq i}^N (-\vec F_{ji}) = - \sum_{j = 1}^N \sum_{i = 1, i \neq j}^N \vec F_{ji}.$$
Luego cada par de fuerzas internas $\vec F_{ij}$ y $\vec F_{ji}$ se cancela mutuamente, lo que da como resultado cero:
$$\sum_{i = 1}^N \sum_{j = 1, j \neq i}^N \vec F_{ij} = 0.$$
Por lo tanto, la ecuación del movimiento lineal total se reduce a:
$$\dot{\vec P}(t) = \sum_{i = 1}^N \vec F_{i, \textrm{ext}} = \vec F_E.$$
Tags: Física demostración
<!--ID: 1718623070247-->
END

