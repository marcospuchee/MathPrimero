
---
mathLink: Función generatriz de $(1+x)^{-n}$
---
### Contenido Principal

**Fecha:** 2024-02-10, 22:46

```ad-proposition
$f(x) = (1+x)^{-n}$ es la [[Función generatriz]] de la sucesión de término general $a_i = {-n \choose i}, \forall i \in \mathbb N$.
```


```ad-proof
Aplicamos el [[desarrollo de Taylor]] de  $f(x) = (1+x)^{-n}$ en $x = 0$. Para ello, calculamos:
$$\sum_{n = 0}^{+\infty} \frac{f^{(n)} (x_0)}{n!} (x-x_0)^n = \sum_{n=0}^{+\infty} \frac{f^{(n)}(0)}{n!}(x)^n$$

Primero, calculemos la derivada $i$-ésima de $f(x)$. Nos damos cuenta de que:
$$\begin{gather} f'(x) = -n(1+x)^{-n-1} \\ f''(x) = -n(-n-1)(1+x)^{n-2} \\ \dots \\ f^{(i)}(x) = (-n)(-n-1) \dots (-n-i+1)(1+x)^{-n-i} \end{gather}$$
Por tanto, el desarrollo de Taylor queda:
$$\frac{1}{0!}(x)^0 + \frac{-N}{1!} x + \frac{-N(-N-1)}{2!} x^2 + \dots + \frac{-N(-N-1)\dots (-2N +1)}{N!} x^N$$
Así, el coeficiente de $x^i$ en el desarrollo de Taylor de $f(x) = (1+x)^{-n}$ en $x_0 = 0$ es $\frac{f^{(i)}(0)}{i!} = {-n \choose i}$ ([[Número binomial negativo]]), y por definición de [[Función generatriz]] de una una sucesión, $f(x) = (1+x)^{-n}$ es la función generatriz de la sucesión de término general $a_i = {-n \choose i}$.
```

Gracias a este resultado podemos calcular los coeficientes de los monomios en $(1+x)^{-n}, \forall n \in \mathbb N$. Por ejemplo, el coeficiente de $x^{10}$ en $(1+x)^{-20}$. A través de este resultado, sabemos que es ${-20 \choose 10} = (-1)^{10} {20+10-1 \choose 10} = {29 \choose 10}$.

**Tema:** [[Métodos de enumeración y combinatoria#5. Funciones generatrices.]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la función generatriz de la sucesión de término general $a_i = {-n \choose i}$?
Reverso: $f(x) = (1+x)^{-n}$ es la [[Función generatriz]] de la sucesión de término general $a_i = {-n \choose i}, \forall i \in \mathbb N$.
Tags: proposición/teorema MatDiscreta
<!--ID: 1707764224946-->
END

START
Básico
Anverso: Demostración de que $f(x) = (1+x)^{-n}$ es la [[Función generatriz]] de la sucesión de término general $a_i = {-n \choose i}, \forall i \in \mathbb N$.
Reverso: Aplicamos el [[Desarrollo de Taylor]] de  $f(x) = (1+x)^{-n}$ en $x = 0$. Para ello, calculamos:
$$\sum_{n = 0}^{+\infty} \frac{f^{(n)} (x_0)}{n!} (x-x_0)^n = \sum_{n=0}^{+\infty} \frac{f^{(n)}(0)}{n!}(x)^n$$

Primero, calculemos la derivada $i$-ésima de $f(x)$. Nos damos cuenta de que:
$$\begin{gather} f'(x) = -n(1+x)^{-n-1} \\ f''(x) = -n(-n-1)(1+x)^{n-2} \\ \dots \\ f^{(i)}(x) = (-n)(-n-1) \dots (-n-i+1)(1+x)^{-n-i} \end{gather}$$
Por tanto, el desarrollo de Taylor queda:
$$\frac{1}{0!}(x)^0 + \frac{-N}{1!} x + \frac{-N(-N-1)}{2!} x^2 + \dots + \frac{-N(-N-1)\dots (-2N +1)}{N!} x^N$$
Así, el coeficiente de $x^i$ en el desarrollo de Taylor de $f(x) = (1+x)^{-n}$ en $x_0 = 0$ es $\frac{f^{(i)}(0)}{i!} = {-n \choose i}$ ([[Número binomial negativo]]), y por definición de [[Función generatriz]] de una una sucesión, $f(x) = (1+x)^{-n}$ es la función generatriz de la sucesión de término general $a_i = {-n \choose i}$.
Tags: demostración MatDiscreta
<!--ID: 1707764224957-->
END