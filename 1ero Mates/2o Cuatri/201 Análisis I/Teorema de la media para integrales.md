
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-23, 17:08

```ad-theorem
Sean $f$ continua en $[a,b]$ ([[función continua en un conjunto]]) y $g \in R[a,b]$ ([[integral de Riemann]]) con $g(x) \ge 0, \forall x \in [a,b]$. Entonces, $\exists c \in [a,b]$ tal que
$$\int_a^b f(x)g(x) \, dx = f(c) \int_a^b g(x) \, dx.$$
```

```ad-proof
Sabemos que el [[producto de integrables es integrable]], $fg \in R[a,b]$. Sean
$$m := \min \{f(x): x \in [a,b] \}, \quad M := \max \{f(x): x \in [a,b] \},$$
que existen por la continuidad de $f$ en $[a,b]$. Por [[Relaciones de orden se mantienen en las integrales]],
$$m \int_a^b g(x) \, dx \le \int_a^b f(x) g(x) \, dx \le M \int_a^b g(x) \, dx,$$
ya que $mg(x) \le f(x) g(x) \le Mg(x)$. Si $\int_a^b g(x) \, dx = 0$, cogemos $c \in [a,b]$ arbitrario y la igualdad es obvia. Si $\int_a^b g(x) \, dx \neq 0$, obtenemos
$$ m \le \frac{\displaystyle \int_a^b f(x) g(x) \, dx}{\displaystyle \int_a^b g(x) \, dx} \le M.$$
Debido a que $f$ es continua, $f$ toma todos los valores entre $m$ y $M$, por lo tanto, $\exists c \in [a,b]$ con
$$f(c) = \frac{\displaystyle \int_a^b f(x) g(x) \, dx}{\displaystyle \int_a^b g(x) \, dx}.$$
```

```ad-note
title: Corolario
Si escogemos $g(x) = 1, \forall x \in [a,b]$ obtenemos el siguiente resultado:
- Si $f$ es continua en $[a,b]$, $\exists c \in [a,b]$ tal que
$$\int_a^b f(x) \, dx = f(c)(a-b).$$
```


**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la media para integrales?
Reverso: Sean $f$ continua en $[a,b]$ ([[Función continua en un conjunto]]) y $g \in R[a,b]$ ([[Integral de Riemann]]) con $g(x) \ge 0, \forall x \in [a,b]$. Entonces, $\exists c \in [a,b]$ tal que
$$\int_a^b f(x)g(x) \, dx = f(c) \int_a^b g(x) \, dx.$$
Tags: proposición/teorema análisisI
<!--ID: 1716477603196-->
END

START
Básico
Anverso: Demostración de que sean $f$ continua en $[a,b]$ ([[Función continua en un conjunto]]) y $g \in R[a,b]$ ([[Integral de Riemann]]) con $g(x) \ge 0, \forall x \in [a,b]$. Entonces, $\exists c \in [a,b]$ tal que
$$\int_a^b f(x)g(x) \, dx = f(c) \int_a^b g(x) \, dx.$$
Reverso: Sabemos que el [[Producto de integrables es integrable]], $fg \in R[a,b]$. Sean
$$m := \min \{f(x): x \in [a,b] \}, \quad M := \max \{f(x): x \in [a,b] \},$$
que existen por la continuidad de $f$ en $[a,b]$. Por [[Relaciones de orden se mantienen en las integrales]],
$$m \int_a^b g(x) \, dx \le \int_a^b f(x) g(x) \, dx \le M \int_a^b g(x) \, dx,$$
ya que $mg(x) \le f(x) g(x) \le Mg(x)$. Si $\int_a^b g(x) \, dx = 0$, cogemos $c \in [a,b]$ arbitrario y la igualdad es obvia. Si $\int_a^b g(x) \, dx \neq 0$, obtenemos
$$ m \le \frac{\displaystyle \int_a^b f(x) g(x) \, dx}{\displaystyle \int_a^b g(x) \, dx} \le M.$$
Debido a que $f$ es continua, $f$ toma todos los valores entre $m$ y $M$, por lo tanto, $\exists c \in [a,b]$ con
$$f(c) = \frac{\displaystyle \int_a^b f(x) g(x) \, dx}{\displaystyle \int_a^b g(x) \, dx}.$$
Tags: demostración análisisI
<!--ID: 1716477603199-->
END

START
Básico
Anverso: Corolario del teorema de la media para integrales cuando $g(x) = 1, \forall x \in [a,b]$
Reverso: Si escogemos $g(x) = 1, \forall x \in [a,b]$ obtenemos el siguiente resultado:
- Si $f$ es continua en $[a,b]$, $\exists c \in [a,b]$ tal que
$$\int_a^b f(x) \, dx = f(c)(a-b).$$
Tags: proposición/teorema análisisI
<!--ID: 1716477603202-->
END
