
---
mathLink: La trayectoria es rectilínea $\iff k = 0$
---
### Contenido Principal

**Fecha:** 2024-02-23, 14:59

Sean $\vec r(s)$ la [[Función vectorial]] que nos devuelve el [[Vector de posición]] de una partícula respecto al [[Camino recorrido]], $k$ la curvatura (definición en [[Vector curvatura]]). Entonces

```ad-proposition
$$\textrm{La trayectoria es rectilínea } \iff k=0,$$
es decir,
$$\vec r(s) = \vec r_0 + s \vec t \iff k(s) = 0$$
```


```ad-proof
$\rightarrow$.
Vamos a calcular primero la derivada de $\vec r(s)$ respecto de $s$:
$$\frac{d\vec r}{ds} = \frac{d}{ds} \left ( \vec r_0 + s \vec t \right ) = \vec t.$$
Sin embargo, sabemos que $\vec r'(s) = \vec t$, siendo $\vec t$, el [[vector tangente unitario]], que es constante. Además, $\frac{d \vec t}{ds} = k(s)$, sin embargo, como $\vec t$ es constante, $k(s) = 0$.

$\leftarrow$.
Como $k(s) = 0$, tenemos que $\vec t$ es constante. Sin embargo, $\vec t(s)$ está definido como:
$$\vec t(s) = \frac{\vec r'(s)}{||\vec r'(s)||} \implies \vec r'(s) = ||\vec r'(s)|| \vec t.$$
Como $||\vec r'(s)||$ es constante, vamos a denotarlo por $c$. Tenemos:
$$\vec r'(s) = c\vec t.$$
Integrando con respecto a $s$, obtenemos:
$$\vec r(s) = c\vec t s + \vec r_0,$$
donde $\vec r_0$ es un vector constante de integración. Podemos ajustar $c$ para que $\vec t$ sea un vector unitario. Sin pérdida de generalidad, tomamos $c= 1$. Así, obtenemos:
$$\vec r(s) = \vec r_0 + s \vec t.$$
```

**Tema:** [[Cinemática clásica#3.a Elementos básicos de cinemática]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sean $\vec r(s)$ la [[Función vectorial]] que nos devuelve el [[Vector de posición]] de una partícula respecto al [[Camino recorrido]], $k$ la curvatura (definición en [[Vector curvatura]]). Entonces,
$${{c1::\textrm{La trayectoria es rectilínea }}} \iff {{c2::k=0}},$$
es decir,
$${{c1::\vec r(s) = \vec r_0 + s \vec t }}\iff {{c2::k(s) = 0}}$$
Tags: proposición/teorema Física
<!--ID: 1708971255621-->
END

START
Básico
Anverso: Demostración de que
$$\textrm{La trayectoria es rectilínea } \iff k=0,$$
es decir,
$$\vec r(s) = \vec r_0 + s \vec t \iff k(s) = 0$$
Reverso: $\rightarrow$.
Vamos a calcular primero la derivada de $\vec r(s)$ respecto de $s$:
$$\frac{d\vec r}{ds} = \frac{d}{ds} \left ( \vec r_0 + s \vec t \right ) = \vec t.$$
Sin embargo, sabemos que $\vec r'(s) = \vec t$, siendo $\vec t$, el [[vector tangente unitario]], que es constante. Además, $\frac{d \vec t}{ds} = k(s)$, sin embargo, como $\vec t$ es constante, $k(s) = 0$.

$\leftarrow$.
Como $k(s) = 0$, tenemos que $\vec t$ es constante. Sin embargo, $\vec t(s)$ está definido como:
$$\vec t(s) = \frac{\vec r'(s)}{||\vec r'(s)||} \implies \vec r'(s) = ||\vec r'(s)|| \vec t.$$
Como $||\vec r'(s)||$ es constante, vamos a denotarlo por $c$. Tenemos:
$$\vec r'(s) = c\vec t.$$
Integrando con respecto a $s$, obtenemos:
$$\vec r(s) = c\vec t s + \vec r_0,$$
donde $\vec r_0$ es un vector constante de integración. Podemos ajustar $c$ para que $\vec t$ sea un vector unitario. Sin pérdida de generalidad, tomamos $c= 1$. Así, obtenemos:
$$\vec r(s) = \vec r_0 + s \vec t.$$
Tags: demostración Física
<!--ID: 1718623070253-->
END
