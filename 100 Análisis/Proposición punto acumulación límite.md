### Proposición

Sea $A \subseteq \mathbb R, x \in \mathbb R$. Entonces $x \in ac(A) \iff \exists (a_n)_{n=1}^{+\infty}$ en $A$ con $a_n \not = x, \forall n \in \mathbb N$ tal que $lim_{n \to +\infty} a_n = x$.

---
### Demostración

$\rightarrow$. Supongamos que $x \in ac(A)$ ([[Punto de acumulación]]). Para cada $n \in \mathbb N, I_x = \{x-\frac{1}{n}, x + \frac{1}{n}\}$. $\exists a_n \in ((x-\frac{1}{n}, x + \frac{1}{n}) - \{x\})\cap A$. Esto es, $a_n \not = x$ y $a_n \in A, \forall n \in \mathbb N$. Así, $|x-a_n| < \frac{1}{n} \rightarrow_{n \to + \infty} 0$. Por tanto, $\exists lim_{n \to +\infty} a_n = x$.

$\leftarrow$. Supongamos que $\exists(a_n)_{n=1}^{+\infty} \subseteq A$ con $a_n \not = x, \forall n \in \mathbb N$ y $lim_{n \to + \infty} a_n = x$. Sea $I_x$ un intervalo abierto que contiene a $x$, $I_x = (\alpha, \beta)$ con $\alpha < x < \beta$. Sea $\epsilon := min(\beta - x, x - \alpha)$. Como $lim_{n \to +\infty} a_n = x$, $\exists n_0 : |a_{n_0} - x| < \epsilon$, por tanto, $a_{n_0} \in (x-\epsilon, x + \epsilon) \subseteq (\alpha, \beta)$, y $a_{n_0} \in ((\alpha, \beta) - \{x\})\cap A$.

---
### Referencias

[[Función]]
[[Límite de una sucesión]]