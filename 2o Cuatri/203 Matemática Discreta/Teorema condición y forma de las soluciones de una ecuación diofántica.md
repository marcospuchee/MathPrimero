
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-19, 16:35

```ad-theorem
Sean $a,b,c \in \mathbb Z$. Se tiene que:
1. La [[ecuación diofántica]] $ax + by = c$ tiene soluciones $\iff \textrm{mcd}(a,b)$ ([[Máximo común divisor]]) es un divisor de $c$.
2. Si se cumple la condición anterior y $x_0, y_0$ es una solución, entonces todas las soluciones son de la forma
$$x = x_0 + \lambda b, \quad y = y_0 - \lambda a,$$
para algún $\lambda \in \mathbb Q$.
```

```ad-proof
Tomamos $d = \textrm{mcd}(a,b)$. Si existe una solución $(x_0, y_0) \in \mathbb Z$, entonces como $d$ es divisor de $a$ y $b$, necesariamente dividirá a la combinación lineal $ax_0 + by_0 = c$, por lo tanto $d | c$.
Recíprocamente, por la [[identidad de Bezout]], se sabe que $\exists \alpha, \beta \in \mathbb Z$ tales que $a \alpha + b \beta = d$. Como $d | c$, entonces $c = dn$ para algún $n \in \mathbb Z$, y multiplicando la expresión anterior por $n$:
$$a (n \alpha) + b (n \beta) = c$$
se obtiene que $n \alpha$ y $n \beta$ es una solución. Esto prueba el primer apartado.

Es fácil ver que toda pareja de números de la forma
$$x = x_0 + \lambda b, \quad y = y_0 - \lambda a, \quad \textrm{con } \lambda \in \mathbb Q$$
es solución. Supongamos que la pareja $(x,y)$ es una solución, probemos que tiene que ser de la forma que dice el teorema. Tenemos por una parte $ax_0 + by_0 = c$ y por otra parte $ax + by = c$. Restando las ecuaciones obtenemos
$$a(x-x_0)+ b(y-y_0) = 0 \iff a(x-x_0) = b(y_0-y).$$
Llamemos $a_1 = \frac{a}{d}$ y $b_1 = \frac{b}{d}$, entonces $\textrm{mcd}(a_1, b_1) = 1$ puesto que hemos dividido $a$ y $b$ por su máximo común divisor. Así pues, $a_1(x - x_0) = b_1 (y_0 -y)$, es decir $a_1(x-x_0)|b_1(y_0-y)$; pero como $a_1$ y $b_1$ son [[coprimos]], se tiene por [[proposición divisibilidad de un producto]] que $a_1 | (y_0-y)$, luego $\exists \lambda_1 \in \mathbb Z$ cumpliendo $y_0 - y = a_1 \lambda_1$. Razonando análogamente, $\exists \lambda_2$ cumpliendo $x-x_0 = b_1 \lambda_2$. Si $ab \neq 0$ entonces $\lambda_1 = \lambda_2$. En efecto

$$
\begin{eqnarray}
c &=& ax + by = a(x_0 + \lambda_2b_1) + b(y_0 - \lambda_1 a_1) = ax_0 + by_0 + a\lambda_2 b_1 - b \lambda_1 a_1 = \\ &=& c + a \lambda_2 b_1 - b \lambda_1 a_1.
\end{eqnarray}
$$
Por tanto, $a\lambda_2 b_1 = b \lambda_1 a_1$ y multiplicando por $d$ se tiene que
$$ab \lambda_2 = ab \lambda_1.$$
Si $ab \neq 0$ entonces $\lambda_1 = \lambda_2$ y el teorema está probado. Si $ab = 0$, pongamos que $b = 0$, la ecuación es $ax = c$. Por hipótesis $a|c$ porque $\textrm{mcd}(a, 0) = a$, las solución es $x = \frac{c}{a} = \frac{c}{a} + 0\lambda$. El valor de $y$ es arbitrario y podemos suponer que tiene la forma indicada. Con lo que hemos concluido la demostración.
```

**Tema:** [[Aritmética modular#4. Ecuaciones diofánticas lineales]]
**Demostrado por:** [[Identidad de Bezout]], [[Proposición divisibilidad de un producto]]
**Consecuencias:**

---
### Anki
