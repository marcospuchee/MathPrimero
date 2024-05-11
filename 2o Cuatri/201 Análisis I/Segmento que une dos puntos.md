### Contenido principal

**Fecha:** 2024-04-12, 19:29

```ad-formal
title: Formal definition
Si $A = \{a,b\} \subset \mathbb R^n$, llamaremos segmento que une $a$ con $b$ al conjunto $\{\lambda b + (1-\lambda)a : \lambda \in [0,1] \}$.
```

```ad-note
Observemos que si $a \neq b$, entonces $\{\lambda b + (1-\lambda)a : \lambda \in \mathbb R \}$ es la recta que pasa por $a$ y $b$.

Para $n = 1$, si $a,b \in \mathbb R, a \le b$, tendremos que si $\lambda \in [0,1]$, entonces
$$a = \lambda a + (1-\lambda)a \le \lambda a + (1-\lambda)b \le \lambda b + (1-\lambda)b = b.$$
Por tanto, $\{\lambda a + (1-\lambda)b : \lambda \in [0,1] \} \subset [a,b]$. Está claro que si $a = b$, tendremos la igualdad entre los conjuntos. Veamos que esta igualdad también se cumple si $a \neq b.$ En efecto, si $c \in [a,b]$ tendremos
$$c = \frac{c-a}{b-a}b + \frac{b-c}{b-a}a = \frac{c-a}{b-a}b + \left ( 1-\frac{c-a}{b-a} \right ) a;$$
con lo que si $\lambda = (c-a)/(b-a)$, resulta que $c = \lambda b + (1-\lambda)a$ y $\lambda \in [0,1]$. Por tanto, $[a,b] \subset \{\lambda a + (1-\lambda)b : \lambda \in [0,1] \}$.
```

**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Referencias:**
**Proposiciones:**
**Teoremas:**

---
### Anki

START
Básico
Anverso: Cómo podemos definir el segmento que une dos puntos?
Reverso: Si $A = \{a,b\} \subset \mathbb R^n$, llamaremos segmento que une $a$ con $b$ al conjunto $\{\lambda b + (1-\lambda)a : \lambda \in [0,1] \}$.
Tags: definición análisisI
<!--ID: 1713093069948-->
END

START
Básico
Anverso: Cuál es la interpretación geométrica de tomar el segmento que une $a$ con $b$ al conjunto $\{\lambda b + (1-\lambda)a : \lambda \in [0,1] \}$?
Reverso: Observemos que si $a \neq b$, entonces $\{\lambda b + (1-\lambda)a : \lambda \in \mathbb R \}$ es la recta que pasa por $a$ y $b$.

Para $n = 1$, si $a,b \in \mathbb R, a \le b$, tendremos que si $\lambda \in [0,1]$, entonces
$$a = \lambda a + (1-\lambda)a \le \lambda a + (1-\lambda)b \le \lambda b + (1-\lambda)b = b.$$
Por tanto, $\{\lambda a + (1-\lambda)b : \lambda \in [0,1] \} \subset [a,b]$. Está claro que si $a = b$, tendremos la igualdad entre los conjuntos. Veamos que esta igualdad también se cumple si $a \neq b.$ En efecto, si $c \in [a,b]$ tendremos
$$c = \frac{c-a}{b-a}b + \frac{b-c}{b-a}a = \frac{c-a}{b-a}b + \left ( 1-\frac{c-a}{b-a} \right ) a;$$
con lo que si $\lambda = (c-a)/(b-a)$, resulta que $c = \lambda b + (1-\lambda)a$ y $\lambda \in [0,1]$. Por tanto, $[a,b] \subset \{\lambda a + (1-\lambda)b : \lambda \in [0,1] \}$.
Tags: definición análisisI
<!--ID: 1713093069952-->
END

