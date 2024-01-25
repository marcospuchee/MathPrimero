### Proposición

El [[Límite funcional]] en un punto, si existe, es único.

---
### Demostración

Sea $f: A \rightarrow \mathbb R$ con $x_0 \in ac(A)$ ([[Punto de acumulación]]). Supongamos que $\lim_{x \to x_0} f(x) = l_1$ y que $\lim_{x \to x_0} f(x) = l_2$. 
Sea $\frac{\epsilon}{2} > 0$, como $\lim_{x \to x_0} f(x) = l_1, \exists \delta_1 > 0$ tal que si $0 < |x-x_0| < \delta_1$ y $x \in A$, entonces $|f(x) - l_1| < \frac{\epsilon}{2}$.
Como $\lim_{x \to x_0} f(x) = l_2, \exists \delta_2 > 0$ tal que si $0 < |x-x_0| < \delta_2$ y $x \in A$, entonces $|f(x) - l_2| < \frac{\epsilon}{2}$.
Sea $\delta := min\{\delta_1, \delta_2\} > 0$, si $x \in A$ con $0 < |x-x_0| < \delta$, entonces $0 \le |l_1 - l_2| = |l_1 - f(x) + f(x) - l_2 \le$ $|l_1 - f(x)| + |f(x) - l_2| < \frac{\epsilon}{2} + \frac{\epsilon}{2} = \epsilon$. Como $\epsilon > 0$ es arbitrario, concluimos que $l_1 = l_2$.


---
### Referencias

[[Función]]