### Lema

(Partimos de que sabemos que la composición de aplicaciones biyectivas es biyectiva)

Sean $f: V \rightarrow V', g: V' \rightarrow V''$, aplicaciones lineales, entonces $g \circ f$ ([[Composición de aplicaciones]]) es lineal.

---
### Demostración

Sean $u, v \in V, \lambda, \mu \in K$, hay que ver que $(g \circ f)(\lambda u + \mu v) = \lambda (g \circ f)(u) + \mu (g \circ f)(v)$.

Tenemos que $(g \circ f)(\lambda u + \mu v) = g(f(\lambda u + \mu v))$. Como $f$ es lineal, eso es igual a $g(\lambda f(u) + \mu f(v))$. Como $g$ también es lineal, eso es igual a $\lambda g(f(u)) + \mu g(f(v)) = \lambda (g \circ f)(u) + \mu (g \circ f)(v)$.

---
### Referencias

[[Aplicación lineal]]