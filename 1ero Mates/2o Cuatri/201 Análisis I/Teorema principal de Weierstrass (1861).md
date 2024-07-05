
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-26, 09:51

Sean $C$ un [[Subconjunto sucesionalmente compacto]] de $\mathbb R$ y $f: C \to \mathbb R$ una función continua en $C$ ([[Función continua en un conjunto]])
> [!theorem]
> $\exists a, b \in C$ tales que
> $$f(a) = max\{f(x) : x \in C\} \quad \quad f(b) = min\{f(x) : x \in C\}$$

> [!proof]
> Es suficiente hacer la prueba para el máximo. Según el [[Teorema de Weierstrass]], el conjunto $f(C)$ es acotado, por tanto, tiene sentido considerar $\xi := sup(f(C))$. Si $\xi \in f(C)$, entonces $\exists a \in C$ tal que $f(a) = \xi$, luego $f(a) = max\{f(x), x \in C\}$.
>
>Veamos que suponer que $\xi \notin f(C)$ nos lleva a una contradicción, con lo que la prueba estará terminada. Si $\xi \notin f(C)$, la función $h(x) := \xi - f(x), x \in C$, es continua en $C$ y no se anula en ningún punto de ese conjunto. De acuerdo con [[(POR DEMOSTRAR)División de funciones continuas es continua]], $g: C \to \mathbb R$ con $g(x) = (\xi - f(x))^{-1}$, $x \in C$, es continua en $C$. Dado $n \in \mathbb N$, por definición de supremo, debe existir un $c_n \in C$ tal que $f(c_n) > \xi - 1/n$. Luego $g(c_n) > n$, es decir $g$ es continua y no acotada ([[Función acotada]]) en $C$, lo que contradice al [[Teorema de Weierstrass]].

**Tema:** [[Funciones continuas#2. Funciones continuas en ciertos conjuntos]]
**Demostrado por:** [[Teorema de Weierstrass]]
**Corolarios:** [[Teorema de Rolle (1690)]], [[Teorema de Darboux]]

---
### Anki

START
Básico
Anverso: Qué dice el Teorema principal de Weierstrass (1861)?
Reverso: Sean $C$ un [[Subconjunto sucesionalmente compacto]] de $\mathbb R$ y $f: C \to \mathbb R$ una función continua en $C$ ([[Función continua en un conjunto]])

> $\exists a, b \in C$ tales que
> $$f(a) = max\{f(x) : x \in C\} \quad \quad f(b) = min\{f(x) : x \in C\}$$

Tags: proposición/teorema
<!--ID: 1706259997757-->
END

START
Básico
Anverso: Demostración  del Teorema principal de Weierstrass (1861)?
Reverso: Es suficiente hacer la prueba para el máximo. Según el [[Teorema de Weierstrass]], el conjunto $f(C)$ es acotado, por tanto, tiene sentido considerar $\xi := sup(f(C))$. Si $\xi \in f(C)$, entonces $\exists a \in C$ tal que $f(a) = \xi$, luego $f(a) = max\{f(x), x \in C\}$.

Veamos que suponer que $\xi \notin f(C)$ nos lleva a una contradicción, con lo que la prueba estará terminada. Si $\xi \notin f(C)$, la función $h(x) := \xi - f(x), x \in C$, es continua en $C$ y no se anula en ningún punto de ese conjunto. De acuerdo con [[(POR DEMOSTRAR)División de funciones continuas es continua]], $g: C \to \mathbb R$ con $g(x) = (\xi - f(x))^{-1}$, $x \in C$, es continua en $C$. Dado $n \in \mathbb N$, por definición de supremo, debe existir un $c_n \in C$ tal que $f(c_n) > \xi - 1/n$. Luego $g(c_n) > n$, es decir $g$ es continua y no acotada ([[Función acotada]]) en $C$, lo que contradice al [[Teorema de Weierstrass]].
Tags: demostración
<!--ID: 1706298709216-->
END

