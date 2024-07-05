### Contenido principal

**Fecha:** 2024-04-12, 19:40

```ad-formal
title: Formal definition
Sea $I \subset \mathbb R$ un [[Intervalo]] no vacío y $f : I \to \mathbb R$, diremos que $f$ es convexa si $\forall a,b \in I$, tenemos que
$$f(\lambda b + (1-\lambda)a) \le \lambda f(b) + (1-\lambda)f(a).$$
[[Segmento que une dos puntos]]
```

```ad-note
Observemos que el segmento que une los puntos $(a, f(a))$ y $(b, f(b))$ es
$$
\begin{array}
\{\lambda(b, f(b)) + (1-\lambda)(a, f(a)) : \lambda \in [0,1] \} = \\
= \{(\lambda b + (1-\lambda)a, \lambda f(b) + (1-\lambda)f(a) ) : \lambda \in [0,1] \}.
\end{array}
$$

Entonces, la definición de función convexa nos dice que la gráfica de $f$ está por debajo del segmento que une los puntos $(a, f(a))$ y $(b, f(b))$.
```


**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Referencias:** [[Función cóncava]]
**Proposiciones:** [[Lema desigualdades de una función convexa]]
**Teoremas:** [[Convexidad de f sii derivada de f creciente]], [[Teorema función es convexa sii la gráfica de f está por encima de su tangente]]

---
### Anki

START
Básico
Anverso: Cuándo decimos que una función es convexa?
Reverso: Sea $I \subset \mathbb R$ un [[Intervalo]] no vacío y $f : I \to \mathbb R$, diremos que $f$ es convexa si $\forall a,b \in I$, tenemos que
$$f(\lambda b + (1-\lambda)a) \le \lambda f(b) + (1-\lambda)f(a).$$
[[Segmento que une dos puntos]]
Tags: definición análisisI
<!--ID: 1713093070066-->
END

START
Básico
Anverso: Interpretación geométrica de decir que una función $f$ es convexa si $\forall a,b \in I$, tenemos que 
$$f(\lambda b + (1-\lambda)a) \le \lambda f(b) + (1-\lambda)f(a).$$
Reverso: Observemos que el segmento que une los puntos $(a, f(a))$ y $(b, f(b))$ es
$$
\begin{array}
\{\lambda(b, f(b)) + (1-\lambda)(a, f(a)) : \lambda \in [0,1] \} = \\
= \{(\lambda b + (1-\lambda)a, \lambda f(b) + (1-\lambda)f(a) ) : \lambda \in [0,1] \}.
\end{array}
$$

Entonces, la definición de función convexa nos dice que la gráfica de $f$ está por debajo del segmento que une los puntos $(a, f(a))$ y $(b, f(b))$.
Tags: definición análisisI
<!--ID: 1713093070072-->
END
