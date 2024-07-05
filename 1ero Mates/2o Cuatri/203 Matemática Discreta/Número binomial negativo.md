
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-07, 14:05

Sea $n, k \in \mathbb N$, entonces

```ad-proposition
$${-n \choose k} =(-1)^k {n+k-1 \choose k}$$
```


```ad-proof
Según [[Número binomial generalizado]],
$${-n \choose k} = \frac{-n(-n-1)(-n-2) \dots (-n-k+1)}{k!}$$
Desarrollamos esto de tal manera que:
$$\frac{-n(-n-1)(-n-2) \dots (-n-k+1)}{k!} = \frac{(-1)^k n(n+1)(n+2)\dots (n+k-1)}{k!}$$
Ahora, buscamos transformar esto en un número binomial, dado que esto es igual a:
$$(-1)^k \frac{1 · 2 · \dots (n-1)n(n+1) \dots (n+k-1)}{k!} = (-1)^k \frac{(n+k-1)!}{(n-1)! k!} = (-1)^k {n+k-1 \choose n-1} = (-1)^k {n+k-1 \choose k}$$
```



**Tema:** [[Métodos de enumeración y combinatoria#5. Funciones generatrices.]]
**Consecuencias:** [[Función generatriz de 1+x elevado a -n]]

---
### Anki

START
Básico
Anverso: Definición de número binomial negativo
Reverso: Sea $n, k \in \mathbb N$, entonces
$${-n \choose k} =(-1)^k {n+k-1 \choose k}$$
Tags: proposición/teorema MatDiscreta
<!--ID: 1707764224994-->
END

START
Básico
Anverso: Demuestra que sea $n, k \in \mathbb N$, entonces
$${-n \choose k} =(-1)^k {n+k-1 \choose k}$$
Reverso: Según [[Número binomial generalizado]],
$${-n \choose k} = \frac{-n(-n-1)(-n-2) \dots (-n-k+1)}{k!}$$
Desarrollamos esto de tal manera que:
$$\frac{-n(-n-1)(-n-2) \dots (-n-k+1)}{k!} = \frac{(-1)^k n(n+1)(n+2)\dots (n+k-1)}{k!}$$
Ahora, buscamos transformar esto en un número binomial, dado que esto es igual a:
$$(-1)^k \frac{1 · 2 · \dots (n-1)n(n+1) \dots (n+k-1)}{k!} = (-1)^k \frac{(n+k-1)!}{(n-1)! k!} = (-1)^k {n+k-1 \choose n-1} = (-1)^k {n+k-1 \choose k}$$
Tags: demostración MatDiscreta
<!--ID: 1707764225009-->
END