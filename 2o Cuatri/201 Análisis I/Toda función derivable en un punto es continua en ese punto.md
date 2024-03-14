
---
mathLink: $f$ derivable en $a \implies f$ continua en $a$
---
### Contenido Principal

**Fecha:** 2024-02-25, 11:30

Sea $a \in A, f : A \to \mathbb R$. Entonces,

```ad-proposition
$f$ derivable en $a$ ([[Función derivable en un punto]]) $\implies f$ continua en $a$ ([[Función continua en un punto]])
```


```ad-proof
Por la [[Formulación de Weierstrass (1861)]], si $f$ es derivable en $a$, entonces
$$f(x) = f(a) + r(x-a) + H(x)(x-a)$$
Sin embargo, $f(a)$ es una constante, r(x-a)$ es un polinomio, $H(x)$ es continua en $a$ por la [[Formulación de Weierstrass (1861)]], y $(x-a)$ es un polinomio. Por tanto, por ser $f(x)$ combinación lineal de funciones continuas, entonces es continua.

Ver [[(POR DEMOSTRAR) Suma de funciones continuas es continua]], [[(POR DEMOSTRAR) Producto de funciones continuas es continua]].


Sin embargo, el recíproco no es cierto por el [[Teorema de Weierstrass (1872)]].
```

**Tema:** [[Funciones derivables#1. Derivabilidad y continuidad]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Qué relación tiene que una función sea derivable en un punto con que sea continua?
Reverso: Sea $a \in A, f : A \to \mathbb R$. Entonces, $f$ derivable en $a$ ([[Función derivable en un punto]]) $\implies f$ continua en $a$ ([[Función continua en un punto]])
Tags: proposición/teorema análisisI
<!--ID: 1708973800338-->
END

START
Básico
Anverso: Demuestra que sea $a \in A, f : A \to \mathbb R$. Entonces, $f$ derivable en $a$ ([[Función derivable en un punto]]) $\implies f$ continua en $a$ ([[Función continua en un punto]]).
Reverso: Por la [[Formulación de Weierstrass (1861)]], si $f$ es derivable en $a$, entonces
$$f(x) = f(a) + r(x-a) + H(x)(x-a)$$
Sin embargo, $f(a)$ es una constante, r(x-a)$ es un polinomio, $H(x)$ es continua en $a$ por la [[Formulación de Weierstrass (1861)]], y $(x-a)$ es un polinomio. Por tanto, por ser $f(x)$ combinación lineal de funciones continuas, entonces es continua.

Ver [[(POR DEMOSTRAR) Suma de funciones continuas es continua]], [[(POR DEMOSTRAR) Producto de funciones continuas es continua]].


Sin embargo, el recíproco no es cierto por el [[Teorema de Weierstrass (1872)]].
Tags: demostración análisisI
<!--ID: 1708973800343-->
END