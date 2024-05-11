
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-19, 13:49

```ad-theorem
Sean $p_1, p_2, \dots, p_n$ números enteros positivos [[coprimos]] dos a dos. Es decir, $\textrm{mcd}(p_i, p_j) = 1, \quad \forall i,j = 1, \dots, n$. Si $\forall i = 1, \dots, n$ llamamos
$$M_i = \frac{\prod_{j = 1}^n p_j}{p_i},$$
entonces existen $n$ enteros $N_i$ que cumplen $M_i N_i \equiv 1 \pmod{p_i}$.

Supongamos que tenemos el sistema de congruencias ([[relación de congruencia]]):
$$ \left \{
\begin{array}
xx \equiv a_1 \pmod{p_1} \\
x \equiv a_2 \pmod{p_2} \\
\dots \\
x \equiv a_n \pmod{p_n}.
\end{array}
\right .
$$
Entonces el número $s = \sum_{i = 1}^n a_i M_i N_i$ es una solución y cuaqluier otra solución es congruente con $s$ módulo $M$, siendo $M = \prod_{i = 1}^n p_i$.
```

```ad-proof
Como se cumple que $\textrm{mcd}(M_i, p_i) = 1$, ya que justamente $M_i = \frac{M}{p_i}$, y ningún número $p_j$ tiene factores comunes con otro $p_l$ distinto de él, entonces por la proposición [[Elemento de congruencia invertible]] en $\mathbb Z/p_i \mathbb Z$, tenemos que $M_i$ es invertible en $\mathbb Z/p_i \mathbb Z$, por tanto la existencia de $N_i$ cumpliendo que $M_i N_i \equiv 1 \pmod{p_i}$ está garantizada. En la práctica se usa el [[algoritmo de Euclides]] para hallarlo.

Por otro lado, vamos a comprobar que $s$ cumple las ecuaciones anteriores. Probemos por ejemplo $s \equiv a_1 \pmod{p_1}$.
$$s - a_1 = \sum_{i = 1}^n a_i M_i N_i - a_1 = a_1(M_1 N_1 - 1) + \sum_{i = 2}^n a_i M_i N_i.$$
El primer sumando es $a_1(M_1 N_1 - 1) \equiv 0 \pmod{p_1}$ y como el segundo sumando es mútliplo de $p_1$, porque el factor $p_1$ está en todos los $M_i$ con $i \neq 1$, se tiene que $s-a_1 \equiv 0 \pmod{p_1}$. Razonando análogamente se prueban el resto de congruencias.

Supongamos ahora que $u$ es otra solución. Se cumple que $u \equiv x \pmod{p_i}$,  $\forall i = 1, \dots, n$. Es decir, todos los $p_i$ dividen $x-u$. Como entre los $p_i$ no hay factores comunes, entonces $M$ divide $x-u$.
```


**Tema:** [[Aritmética modular#3. Teorema chino del resto]]
**Demostrado por:** [[Algoritmo de Euclides]], [[Elemento de congruencia invertible]]
**Consecuencias:**

---
### Anki
