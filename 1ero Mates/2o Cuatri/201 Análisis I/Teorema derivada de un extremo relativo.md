
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-29, 18:22

Sean $a,b \in \mathbb R, a<b$ y $f: ]a,b[ \to \mathbb R$.

```ad-theorem
Si $f$ es derivable en $c \in ]a,b[$ ([[Función derivable en un punto]]) y $c$ es un extremo relativo ([[Extremos relativos (estrictos)]]) de $f$, entonces $f'(c) = 0$.
```

```ad-proof
Supongamos, por ejemplo, que $c$ es un máximo relativo y que $f'(c) > 0$, es decir
$$\lim_{x \to c} \frac{f(x) - f(c)}{x-c} > 0.$$
De acuerdo con [[Lema valor del límite en un punto a]], $\exists \delta_0 > 0$ tal que
$$\frac{f(x) -f(c)}{x-c} > 0, \quad \forall x \in ]c-\delta_0, c + \delta_0[ \cap ]a,b[ - \{c\}.$$
Ahora si $x \in ]c,c + \delta_0[ \cap ]c,b[$, tendremos $f(x) > f(c)$, por tanto $c$ no es un máximo relativo.
```

```ad-note
Lo que esto demuestra es que si $a < c < d < b$ y si $f:]a,b[ \to \mathbb R$ es derivable en $c$ ([[Función derivable en un punto]]), entonces:
1. Si $f'(c) > 0 \implies c$ no es máximo relativo ([[Extremos relativos (estrictos)]]) de $f \restriction_{[c,d]};$
2. Si $f'(c) < 0 \implies c$ no es mínimo relativo de $f \restriction_{[c,d]}$.

Si $f$ es derivable en $d$ entonces
1. Si $f'(d) > 0 \implies d$ no es mínimo relativo de $f \restriction_{[c,d]};$
2. Si $f'(d) < 0 \implies d$ no es máximo relativo de $f \restriction_{[c,d]}.$
```


**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:** [[Lema valor del límite en un punto a]]
**Consecuencias:** [[Teorema de Rolle (1690)]], [[Teorema de Darboux]]

---
### Anki

START
Básico
Anverso: Cuál es la derivada de un extremo relativo?
Reverso: Sean $a,b \in \mathbb R, a<b$ y $f: ]a,b[ \to \mathbb R$. Si $f$ es derivable en $c \in ]a,b[$ ([[Función derivable en un punto]]) y $c$ es un extremo relativo ([[Extremos relativos (estrictos)]]) de $f$, entonces $f'(c) = 0$.
Tags: proposición/teorema análisisI
<!--ID: 1709231331188-->
END

START
Básico
Anverso: Demostración de que sean $a,b \in \mathbb R, a<b$ y $f: ]a,b[ \to \mathbb R$. Si $f$ es derivable en $c \in ]a,b[$ ([[Función derivable en un punto]]) y $c$ es un extremo relativo ([[Extremos relativos (estrictos)]]) de $f$, entonces $f'(c) = 0$.
Reverso: Supongamos, por ejemplo, que $c$ es un máximo relativo y que $f'(c) > 0$, es decir
$$\lim_{x \to c} \frac{f(x) - f(c)}{x-c} > 0.$$
De acuerdo con [[Lema valor del límite en un punto a]], $\exists \delta_0 > 0$ tal que
$$\frac{f(x) -f(c)}{x-c} > 0, \quad \forall x \in ]c-\delta_0, c + \delta_0[ \cap ]a,b[ - \{c\}.$$
Ahora si $x \in ]c,c + \delta_0[ \cap ]c,b[$, tendremos $f(x) > f(c)$, por tanto $c$ no es un máximo relativo.
Tags: demostración análisisI
<!--ID: 1709231331193-->
END

START
Respuesta anidada
Sean $a,b \in \mathbb R, a<b$ y $f: ]a,b[ \to \mathbb R$. Si $f$ es derivable en $c \in ]a,b[$ ([[Función derivable en un punto]]) y $c$ es un extremo relativo ([[Extremos relativos (estrictos)]]) de $f$, entonces $f'(c) = 0$.

Lo que esto demuestra es que si $a < c < d < b$ y si $f:]a,b[ \to \mathbb R$ es derivable en $c$ ([[Función derivable en un punto]]), entonces:
1. Si {{c1::$f'(c) > 0$}} $\implies$ {{c2::$c$ no es máximo relativo ([[Extremos relativos (estrictos)]]) de $f \restriction_{[c,d]};$}}
2. Si {{c1::$f'(c) < 0$}} $\implies$ {{c2::$c$ no es mínimo relativo de $f \restriction_{[c,d]}$.}}

Si $f$ es derivable en $d$ entonces
1. Si {{c1::$f'(d) > 0$}} $\implies$ {{c2::$d$ no es mínimo relativo de $f \restriction_{[c,d]};$}}
2. Si {{c1::$f'(d) < 0$}} $\implies$ {{c2::$d$ no es máximo relativo de $f \restriction_{[c,d]}.$}}
Tags: proposición/teorema análisisI
<!--ID: 1709231331198-->
END
