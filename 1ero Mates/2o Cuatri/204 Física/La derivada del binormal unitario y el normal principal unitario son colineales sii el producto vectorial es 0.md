
---
mathLink: $b'(s)$ colineal con $\vec n(s) \iff \vec n(s) \land \vec b'(s) = 0$
---
### Contenido Principal

**Fecha:** 2024-02-23, 15:42

Sea $\vec b = \vec b(s)$ el [[Vector binormal unitario]], y sea $\vec n(s)$ el [[Vector normal principal unitario]]. Entonces,

```ad-proposition
$$b'(s) \textrm{ colineal con } \vec n(s) \iff \vec n(s) \land \vec b'(s) = 0$$
([[Vectores colineales]], [[Producto vectorial]])
```


```ad-proof
Por definición de $\vec b$,
$$\vec b' = (\vec t \land \vec n)' = \vec t' \land \vec n + \vec t \land \vec n' = \vec t \land \vec n',$$
dado que $\vec t' \land \vec n = 0$ porque $\vec t' \land \vec n = \vec k \land (\vec k / k)$.

Así, 
$$
\begin{eqnarray}
\vec n \land \vec b' &=& \vec n \land (\vec t \land \vec n') \\
&=& (\vec n · \vec n')\vec t - (\vec n · \vec t)\vec n \\
&=& 0
\end{eqnarray}
$$
Por [[(POR DEMOSTRAR) Propiedades del producto vectorial y producto mixto]], $\vec n · \vec n' = 0$ (por ser [[Vector unitario]], de donde deducimos que el módulo es constante y [[Función vectorial de módulo constante es ortogonal a su derivada]]), poruqe $\vec n · \vec t = 0$ por ser ortogonales ([[La base intrínseca es ortonormal orientada]])
```

**Tema:** [[Cinemática clásica#3.a Elementos básicos de cinemática]]
**Corolarios:** [[Torsión]]

---
### Anki

START
Respuesta anidada
Sea $\vec b = \vec b(s)$ el [[Vector binormal unitario]], y sea $\vec n(s)$ el [[Vector normal principal unitario]]. Entonces,
$${{c1::b'(s) \textrm{ colineal con } \vec n(s)}} \iff {{c2::\vec n(s) \land \vec b'(s) = 0}}$$
([[Vectores colineales]], [[Producto vectorial]])
Tags: proposición/teorema Física
<!--ID: 1708971255628-->
END

START
Básico
Anverso: Demuestra que sea $\vec b = \vec b(s)$ el [[Vector binormal unitario]], y sea $\vec n(s)$ el [[Vector normal principal unitario]]. Entonces,
$$b'(s) \textrm{ colineal con } \vec n(s) \iff \vec n(s) \land \vec b'(s) = 0$$
([[Vectores colineales]], [[Producto vectorial]])
Reverso: Por definición de $\vec b$,
$$\vec b' = (\vec t \land \vec n)' = \vec t' \land \vec n + \vec t \land \vec n' = \vec t \land \vec n',$$
dado que $\vec t' \land \vec n = 0$ porque $\vec t' \land \vec n = \vec k \land (\vec k / k)$.

Así, 
$$
\begin{eqnarray}
\vec n \land \vec b' &=& \vec n \land (\vec t \land \vec n') \\
&=& (\vec n · \vec n')\vec t - (\vec n · \vec t)\vec n \\
&=& 0
\end{eqnarray}
$$
Por [[(POR DEMOSTRAR) Propiedades del producto vectorial y producto mixto]], $\vec n · \vec n' = 0$ (por ser [[Vector unitario]], de donde deducimos que el módulo es constante y [[Función vectorial de módulo constante es ortogonal a su derivada]]), poruqe $\vec n · \vec t = 0$ por ser ortogonales ([[La base intrínseca es ortonormal orientada]])
Tags: demostración Física
<!--ID: 1708971255633-->
END
