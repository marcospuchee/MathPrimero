### Proposición

Sea $f: A \rightarrow \mathbb R, x_0 \in ac(A\cap[x_0, +\infty))\cap ac(A \cap(-\infty, x_0])$ entonces $\exists \lim_{x \to x_0} f(x) \iff \exists \lim_{x \to x_0^+} f(x)$ y $\exists \lim_{x \to x_0^-} f(x)$ y coinciden.

---
### Demostración

$\rightarrow$. Trivial.
$\leftarrow$. Supongamos que $\exists \lim_{x \to x_0^+} f(x) = L = \lim_{x \to x_0^-} f(x)$. Como $\lim_{x \to x_0^+} f(x) = L$, $\exists \delta_1 > 0$ tal que si $x \in A$ $x_0 < x < x_0 + \delta_1$ entonces $|f(x) - L| < \epsilon$. Como $\lim_{x \to x_0^-} f(x) = L, \exists \delta_2 > 0$ tal que si $x \in A$, $x_0 - \delta_2 < x < x_0$.
Sea $\delta := min\{\delta_1, \delta_2\}$ si $x \in A$ con $0 < |x-x_0| < \delta$, entonces $x_0 < x <x_0 + \delta \le x_0 + \delta_1 \implies$ $|f(x) - L| < \epsilon$  si $x_0 - \delta_2 \le x_0 - \delta < x < x_0 \implies |f(x) - L| < \epsilon$ por lo que $\exists \lim_{x \to x_0} f(x) = L$.

---
### Referencias

[[Límite funcional]]
[[Límite lateral]]
[[Función]]