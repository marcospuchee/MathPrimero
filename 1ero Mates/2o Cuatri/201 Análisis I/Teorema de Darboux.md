
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-07, 08:45

```ad-theorem
Sean $I$ un intervalo abierto, $a,b \in I, a<b$ y $f: I \to \mathbb R$ una función derivable en $I$ ([[Función derivable en un punto]]). Si $\lambda$ verifica que $f'(a) < \lambda < f'(b)$, o $f'(a) > \lambda > f'(b)$, entonces $\exists \xi \in ]a,b[$ tal que $f'(\xi) = \lambda$.
```

```ad-proof
Supongamos por ejemplo que $f'(a) < \lambda < f'(b)$ y sean $g(x) := f(x) - \lambda x$, $x \in I$ y $h:=g \restriction_{[a,b]}$. El [[Teorema principal de Weierstrass (1861)]], nos asegura que $h$ tiene un mínimo $c$ en $[a,b]$. Puesto que $g'(a) < 0$, de acuerdo con la nota [[Teorema derivada de un extremo relativo]], la función $h$ no tiene un mínimo en $a$. Puesto que $g'(b) > 0$ la función $h$ no tiene un mínimo en $b$. Por tanto $c \in ]a,b[$. El [[Teorema derivada de un extremo relativo]], nos da que $h'(c) = f'(c) - \lambda = 0$.
```


**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:** [[Teorema principal de Weierstrass (1861)]], [[Teorema derivada de un extremo relativo]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Darboux?
Reverso: Sean $I$ un intervalo abierto, $a,b \in I, a<b$ y $f: I \to \mathbb R$ una función derivable en $I$ ([[Función derivable en un punto]]). Si $\lambda$ verifica que $f'(a) < \lambda < f'(b)$, o $f'(a) > \lambda > f'(b)$, entonces $\exists \xi \in ]a,b[$ tal que $f'(\xi) = \lambda$.
Tags: análisisI proposición/teorema
<!--ID: 1709836068083-->
END

START
Básico
Anverso: Demostración del teorema de Darboux?
Reverso: Supongamos por ejemplo que $f'(a) < \lambda < f'(b)$ y sean $g(x) := f(x) - \lambda x$, $x \in I$ y $h:=g \restriction_{[a,b]}$. El [[Teorema principal de Weierstrass (1861)]], nos asegura que $h$ tiene un mínimo $c$ en $[a,b]$. Puesto que $g'(a) < 0$, de acuerdo con la nota [[Teorema derivada de un extremo relativo]], la función $h$ no tiene un mínimo en $a$. Puesto que $g'(b) > 0$ la función $h$ no tiene un mínimo en $b$. Por tanto $c \in ]a,b[$. El [[Teorema derivada de un extremo relativo]], nos da que $h'(c) = f'(c) - \lambda = 0$.
Tags: análisisI demostración
<!--ID: 1709836068094-->
END