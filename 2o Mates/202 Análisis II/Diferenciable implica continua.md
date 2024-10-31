### Contenido Principal

```ad-proposition
Sea $\Omega \subseteq \mathbb R^n$ abierto. Si $f: \Omega \to \mathbb R^m$ es [[función diferenciable]] en $a \in \Omega$, entonces $f$ es continua en $a$.
```

^13b2f7

```ad-proof
Sea $x \in \Omega$.

$$f(x) - f(a) = \frac{f(x) - f(a) - Df(a)(x-a)}{||x-a||}||x-a|| + Df(a)(x-a).$$

Cuando $x \to a$, lo de la derecha tiende todo a $0$, luego $\lim_{x \to a} f(x) = f(a)$.
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#1. Derivadas direccionales y diferencial.]]

---
### Anki

START
Básico
Anverso: Proposición diferenciable impica continuidad
Reverso: Sea $\Omega \subseteq \mathbb R^n$ abierto. Si $f: \Omega \to \mathbb R^m$ es [[función diferenciable]] en $a \in \Omega$, entonces $f$ es continua en $a$.
Tags: anII
<!--ID: 1728549801785-->
END

START
Básico
Anverso: Demostración de que sea $\Omega \subseteq \mathbb R^n$ abierto. Si $f: \Omega \to \mathbb R^m$ es [[función diferenciable]] en $a \in \Omega$, entonces $f$ es continua en $a$.
Reverso: Sea $x \in \Omega$.

$$f(x) - f(a) = \frac{f(x) - f(a) - Df(a)(x-a)}{||x-a||}||x-a|| + Df(a)(x-a).$$

Cuando $x \to a$, lo de la derecha tiende todo a $0$, luego $\lim_{x \to a} f(x) = f(a)$.
Tags: anII dem
<!--ID: 1728549801838-->
END
