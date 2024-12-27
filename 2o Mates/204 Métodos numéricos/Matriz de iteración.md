### Contenido principal

```ad-Formal
Dado un método iterativo $Mx^{k+1} = b-Nx^k$, la matriz $Q:= -M^{-1}N$ se llama matriz de iteración del método.
```

```ad-note
Notemos entonces que, por definición, un método es convergente si $\forall x^0$, la sucesión de iteraciones producidas por el método satsiface que $x^k \to x$, o equivalentemente $\forall z$, $\lim \limits_{k \to \infty} Q^k z = 0$:
$$\lim_{k \to \infty} x^k = x \iff \lim_{k \to \infty} e^k = 0 \iff \lim_{k \to \infty} Q^k e^0 = 0.$$
```

**Tema:** [[Métodos iterativos para resolver sistemas de ecuaciones lineales#3. Error.]]

**Definiciones referenciadas:** [$Mx^k = b-Nx^{k-1}$](Método iterativo)

---
### Anki

START
Básico
Anverso: Definición de matriz de iteración
Reverso: Dado un método iterativo $Mx^{k+1} = b-Nx^k$, la matriz $Q:= -M^{-1}N$ se llama matriz de iteración del método.

Notemos entonces que, por definición, un método es convergente si $\forall x^0$, la sucesión de iteraciones producidas por el método satsiface que $x^k \to x$, o equivalentemente $\forall z$, $\lim \limits_{k \to \infty} Q^k z = 0$:
$$\lim_{k \to \infty} x^k = x \iff \lim_{k \to \infty} e^k = 0 \iff \lim_{k \to \infty} Q^k e^0 = 0.$$
Tags: met
<!--ID: 1735044171439-->
END
