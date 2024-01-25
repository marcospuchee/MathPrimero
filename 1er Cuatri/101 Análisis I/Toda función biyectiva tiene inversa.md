### Proposición

Una función $f$ tiene inversa ([[Función inversa]]) $\iff f$ es biyectiva.

---
### Demostración
$\rightarrow$. Supongamos que $\exists f^{-1}: B \rightarrow A$ inversa de $f$. Si $x,y \in A$ tales que $f(x) = f(y)$, podemos aplicar que $f^{-1}(f(x)) = f^{-1}(f(y))$, ambas son la composición de aplicaciones: $x = f \circ f^{-1}(x) = f \circ f^{-1}(y) = y$. Esto implica que la aplicación es inyectiva. Si tomo $z \in B, \exists f^{-1}(z) \in A$, que es la antimagen de $z$, luego es sobreyectiva. Como es sobreyectiva e inyectiva, entonces es biyectiva.

$\leftarrow$. Supongamos que $f$ es biyectiva, definimos $g: B \rightarrow A$ dada por: a cada $x \in B, g(x)$ es el único $z \in A$ tal que $f(z) = x$. Entonces, $f \circ g(x) = f(g(x)) = f(z) = x$. Igualmente, $g \circ f(z) = g(f(z)) = g(x) = z$.

---
### Referencias

[[Aplicaciones inyectivas, sobreyectivas y biyectivas]]
[[Función]]