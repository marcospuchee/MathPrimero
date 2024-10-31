### Contenido principal

```ad-Formal
Sean $\Omega$ un abierto de $\mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Decimos que $f$ es diferenciable en $a$ si $\exists T \in \mathcal L(\mathbb R^n, \mathbb R^m)$ continua tal que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} = 0.$$

A la aplicación $T$ la llamamos diferencial, la denotamos $Df(a)$. 
```

^e04077

```ad-note
Notemos que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} \equiv \lim_{x \to a} \frac{||f(x) - f(a) - T(x-a)||}{||x-a||} \equiv \lim_{h \to 0} \frac{f(a+h) - f(a) - T(h)}{||h||}.$$
```


**Tema:** [[Diferenciabilidad de funciones de varias variables#1. Derivadas direccionales y diferencial.]]

---
### Anki

START
Básico
Anverso: Definición de función diferenciable
Reverso: Sean $\Omega$ un abierto de $\mathbb R^n$, $f: \Omega \to \mathbb R^m$, $a \in \Omega$. Decimos que $f$ es diferenciable en $a$ si $\exists T \in \mathcal L(\mathbb R^n, \mathbb R^m)$ continua tal que
$$\lim_{x \to a} \frac{f(x) - f(a) - T(x-a)}{||x-a||} = 0.$$

A la aplicación $T$ la llamamos diferencial, la denotamos $Df(a)$.
Tags: anII
<!--ID: 1728549801646-->
END