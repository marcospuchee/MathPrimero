### Contenido Principal

```ad-theorem
El método iterativo $Mx^k = b-Nx^{k-1}$ converge a la solución del sistema $(M+N)x = b$ $\iff$ $\rho(Q) < 1$ con $Q = M^{-1}N$.
```

```ad-proof
Vamos a demostrarlo para $Q$ diagonalizable.

Por definición de diagonalizable, $\exists P \in \mathbb C^{n \times n}$ tal que $P^{-1}QP$ $=$ $D$ $=$ $\textrm{diag}(d_1, \dots, d_n)$. Entonces, los valores propios de $Q$ son los valores propios de $D$, por tanto, $$\rho(Q) = \rho(D) = \max \limits_{1 \le i \le n} |d_i|.$$

Notemos que como $Q^k = PD^kP^{-1}$, entonces $$\lim \limits_{k \to \infty} Q^k = P \left ( \lim \limits_{k \to \infty} D^k \right ) P = 0,$$ con $D^k = \textrm{diag}(d_1^k, d_2^k, \dots, d_n^k)$.

Como $P, P^{-1}$ son lineales, la expresión anterior es equivalente a $\lim \limits_{k \to \infty} D^k = 0$, que se cumple $\iff$ $|d_i| < 1$, $\forall i$ $\iff$ $\rho(Q) < 1$.
```

**Tema:** [[Métodos iterativos para resolver sistemas de ecuaciones lineales#2. Estudio de la convergencia.]]

**Definiciones referenciadas:** [$Mx^k = b-Nx^{k-1}$](Método iterativo), [[Método iterativo convergente]], [$Q := -M^{-1}N$](Matriz de iteración), [$\rho(Q)$](Radio espectral), [[Matriz diagonalizable]]
**Resultados referenciados:** -.

---
### Anki

START
Básico
Anverso: Caracterización de convergencia de método iterativo de sistemas de ecuaciones lineales
Reverso: El método iterativo $Mx^k = b-Nx^{k-1}$ converge a la solución del sistema $(M+N)x = b$ $\iff$ $\rho(Q) < 1$ con $Q = M^{-1}N$.
Tags: met
<!--ID: 1735044171489-->
END

START
Básico
Anverso: Demostración de que el método iterativo $Mx^k = b-Nx^{k-1}$ converge a la solución del sistema $(M+N)x = b$ $\iff$ $\rho(Q) < 1$ con $Q = M^{-1}N$.
Reverso: Vamos a demostrarlo para $Q$ diagonalizable.

Por definición de diagonalizable, $\exists P \in \mathbb C^{n \times n}$ tal que $P^{-1}QP$ $=$ $D$ $=$ $\textrm{diag}(d_1, \dots, d_n)$. Entonces, los valores propios de $Q$ son los valores propios de $D$, por tanto, $$\rho(Q) = \rho(D) = \max \limits_{1 \le i \le n} |d_i|.$$

Notemos que como $Q^k = PD^kP^{-1}$, entonces $$\lim \limits_{k \to \infty} Q^k = P \left ( \lim \limits_{k \to \infty} D^k \right ) P = 0,$$ con $D^k = \textrm{diag}(d_1^k, d_2^k, \dots, d_n^k)$.

Como $P, P^{-1}$ son lineales, la expresión anterior es equivalente a $\lim \limits_{k \to \infty} D^k = 0$, que se cumple $\iff$ $|d_i| < 1$, $\forall i$ $\iff$ $\rho(Q) < 1$.
Tags: dem met
<!--ID: 1735044171491-->
END

