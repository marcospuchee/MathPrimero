
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-13, 12:15

```ad-proposition
Sean $a,b \in \mathbb R, a \le b$ y $f \in C[a,b]$. Si $\lambda \in f([a,b])$, el conjunto $\{x \in [a,b]: f(x) = \lambda \}$ tiene máximo y mínimo.
```


```ad-proof
Haremos la prueba, por ejemplo, para el máximo. Sabemos que $\{x \in [a,b]: f(x) = \lambda \}$ es acotado y no vacío, por tanto tiene sentido considerar $s := \sup \{x \in [a,b]: f(x) = \lambda \}$. Por definición de supremo, para cada $n \in \mathbb N$, $\exists x_n \in [a,b] \cap ]s-1/n, s]$. Entonces $\lim x_n = s$, la continuidad de $f$ en $s$ nos da que $f(s) = \lim f(x_n) = \lambda$, lo que muestra que $s \in \{x \in [a,b]: f(a) = \lambda \}$ y $s = \max \{x \in [a,b]: f(x) = \lambda \}.$
```

**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Corolarios:** [[Teorema función es convexa sii la gráfica de f está por encima de su tangente]]

---
### Anki

START
Básico
Anverso: Cuál es la proposición que determina la existencia de un máximo y mínimo en el conjunto de imágenes de una función con un determinado valor?
Reverso: Sean $a,b \in \mathbb R, a \le b$ y $f \in C[a,b]$. Si $\lambda \in f([a,b])$, el conjunto $\{x \in [a,b]: f(x) = \lambda \}$ tiene máximo y mínimo.
Tags: proposición/teorema análisisI
<!--ID: 1713093070080-->
END

START
Básico
Anverso: Demostración de que sean $a,b \in \mathbb R, a \le b$ y $f \in C[a,b]$. Si $\lambda \in f([a,b])$, el conjunto $\{x \in [a,b]: f(x) = \lambda \}$ tiene máximo y mínimo.
Reverso: Haremos la prueba, por ejemplo, para el máximo. Sabemos que $\{x \in [a,b]: f(x) = \lambda \}$ es acotado y no vacío, por tanto tiene sentido considerar $s := \sup \{x \in [a,b]: f(x) = \lambda \}$. Por definición de supremo, para cada $n \in \mathbb N$, $\exists x_n \in [a,b] \cap ]s-1/n, s]$. Entonces $\lim x_n = s$, la continuidad de $f$ en $s$ nos da que $f(s) = \lim f(x_n) = \lambda$, lo que muestra que $s \in \{x \in [a,b]: f(a) = \lambda \}$ y $s = \max \{x \in [a,b]: f(x) = \lambda \}.$
Tags: demostración análisisI
<!--ID: 1713093070086-->
END