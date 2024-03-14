
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-06, 17:32

Sean $V$ un $K$-espacio vectorial, $\vec a, \vec b, \vec c \in V$, $\lambda, \mu \in K$,

```ad-proposition
Se cumplen las siguientes propiedades sobre el [[Producto vectorial]]:
- Bilineal: $\vec a \land (\lambda \vec b + \mu \vec c) = \lambda \vec a \land\vec b + \mu \vec a \land \vec c$.
- Anti-conmutativo: $\vec a \land \vec b = -\vec b \land \vec a$.
- $\vec a \land \vec b \iff \vec a = \lambda \vec b$.
- $\vec a · (\vec a \land \vec b) = \vec b · (\vec a \land \vec b) = 0$.
- $\vec a \land \vec b \not = 0 \implies \{\vec a, \vec b, \vec a \land \vec b\}$ es una [[Base]].
- No asociativo: $\vec a \land (\vec b \land \vec c) = (\vec a · \vec c)\vec b - (\vec a · \vec b)\vec c$

_Añadidas tras el producto mixto:_
- $(\vec a, \vec b, \vec c) = (\vec c, \vec a, \vec b) = (\vec b, \vec c, \vec a) = -(\vec a, \vec c, \vec b) = -(\vec c, \vec b, \vec a) = -(\vec b, \vec a, \vec c)$ 
- Si $\alpha = \angle (\vec a, \vec b)$, entonces $|\vec a \land \vec b| = |\vec a| |\vec b| \sin(\alpha)$.
- Si $\vec a \land \vec b \not = 0$, entonces $\{\vec a, \vec b, \vec a \land \vec b\}$ es una base orientada.
- $\{\vec e_i\}$ [[Base ortonormal]] orientada $\implies \vec e_1 \land \vec e_2 = \vec e_3, \vec e_2 \land \vec e_3 = \vec e_1, \vec e_3 \land \vec e_1 = \vec e_2$.
- $\{\vec e_i\}$ [[Base ortonormal]] orientada, $\vec a = a^i \vec e_i, \vec b = b^i \vec e_i, \vec c = c^i \vec e_i$ tres vectores $\implies (\vec a, \vec b, \vec c)$ ([[Producto mixto de tres vectores]]) $= |\vec a, \vec b, \vec c|$.
- $\{\vec a, \vec b, \vec c\}$ es una base orientada $\iff (\vec a, \vec b, \vec c) > 0$

```


```ad-proof
(POR DEMOSTRAR)
```

**Tema:** [[Cinemática clásica#1. El espacio y el tiempo de la física clásica. Cálculo vectorial.]]
**Corolarios:** [[La derivada del binormal unitario y el normal principal unitario son colineales sii el producto vectorial es 0]]

---
### Anki

START
Respuesta anidada
Sean $V$ un $K$-espacio vectorial, $\vec a, \vec b, \vec c \in V$, $\lambda, \mu \in K$, se cumplen las siguientes propiedades sobre el [[Producto vectorial]]:
{{c1::
- Bilineal: $\vec a \land (\lambda \vec b + \mu \vec c) = \lambda \vec a \land\vec b + \mu \vec a \land \vec c$.
- Anti-conmutativo: $\vec a \land \vec b = -\vec b \land \vec a$.
- $\vec a \land \vec b \iff \vec a = \lambda \vec b$.
- $\vec a · (\vec a \land \vec b) = \vec b · (\vec a \land \vec b) = 0$.
- $\vec a \land \vec b \not = 0 \implies \{\vec a, \vec b, \vec a \land \vec b\}$ es una [[Base]].
- No asociativo: $\vec a \land (\vec b \land \vec c) = (\vec a · \vec c)\vec b - (\vec a · \vec b)\vec c$.}}

_Añadidas tras el producto mixto:_
{{c2::
- $(\vec a, \vec b, \vec c) = (\vec c, \vec a, \vec b) = (\vec b, \vec c, \vec a) = -(\vec a, \vec c, \vec b) = -(\vec c, \vec b, \vec a) = -(\vec b, \vec a, \vec c)$ 
- Si $\alpha = \angle (\vec a, \vec b)$, entonces $|\vec a \land \vec b| = |\vec a| |\vec b| \sin(\alpha)$.
- Si $\vec a \land \vec b \not = 0$, entonces $\{\vec a, \vec b, \vec a \land \vec b\}$ es una base orientada.
- $\{\vec e_i\}$ [[Base ortonormal]] orientada $\implies \vec e_1 \land \vec e_2 = \vec e_3, \vec e_2 \land \vec e_3 = \vec e_1, \vec e_3 \land \vec e_1 = \vec e_2$.
- $\{\vec e_i\}$ [[Base ortonormal]] orientada, $\vec a = a^i \vec e_i, \vec b = b^i \vec e_i, \vec c = c^i \vec e_i$ tres vectores $\implies (\vec a, \vec b, \vec c)$ ([[Producto mixto de tres vectores]]) $= |\vec a, \vec b, \vec c|$.
- $\{\vec a, \vec b, \vec c\}$ es una base orientada $\iff (\vec a, \vec b, \vec c) > 0$.}}
Tags: proposición/teorema
<!--ID: 1707241941223-->
END
