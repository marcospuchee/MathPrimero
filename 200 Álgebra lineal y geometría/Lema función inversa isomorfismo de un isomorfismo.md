### Lema

Supongamos que $\exists f: V \rightarrow V'$  isomorfismo. Como $f$ es biyectiva ([[Aplicaciones inyectivas, sobreyectivas y biyectivas]]), $\exists f^{-1} : V' \rightarrow V$ [[Isomorfismo]].

---
### Demostración

Hay que ver que $f^{-1}$ es lineal. Sean $u', v' \in V', \lambda, \mu \in K$.

¿$f^{-1}(\lambda u' + \mu v') = \lambda f^{-1}(u') + \mu f^{-1}(v')$? Como $f$ es sobreyectiva, y $u' \in V', \exists u \in V$ tal que $f(u) = u'$. Análogamente, $\exists v \in V$ tal que $f(v) = v'$.

Así, $f^{-1}(\lambda u' + \mu v') = f^{-1}(\lambda f(u) + \mu f(v))$. Como $f$ es lineal, eso es lo mismo que $f^{-1}(f(\lambda u + \mu v)) =  (f^{-1} \circ f)(\lambda u + \mu v) = id_V(\lambda u + \mu v) = \lambda u + \mu v$.

Como $f(u) = u' \iff (f^{-1} \circ f)(u) =f^{-1}(u')$.
Como $f(v) = v' \iff v = f^{-1}(v')$.

Tras esta aclaración, retomamos lo anterior, $\lambda u + \mu v = \lambda f^{-1}(u') + \mu f^{-1}(v') = f^{-1}(\lambda u' + \mu v')$.

---
### Referencias

[[Aplicación lineal]]