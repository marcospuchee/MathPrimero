### Contenido Principal

```ad-proposition
Si $f: \mathbb R^n \to \mathbb R$ es continua, $f(x) \ge 0$, $\forall x \in \mathbb R^n$ y $\lim \limits_{||x|| \to +\infty} f(x) = 0$, entonces, $f$ tiene un máximo absoluto.
```

```ad-proof
Si $f(x) = 0$, $\forall x \in \mathbb R^n$, entonces está claro que $0$ es máximo absoluto.

Si $\exists y_0 \in \mathbb R^n$ tal que $f(y_0) = \alpha > 0$. Como $\lim \limits_{||x|| \to + \infty} f(x)  = 0$, entonces $\exists M > 0$ tal que si $||x|| > M$, entonces $f(x) < \frac{\alpha}{2}$. Consideramos el conjunto $K$ $=$ $\{x \in \mathbb R^n : f(x) \ge \frac{\alpha}{2} \}$ $\subset$ $B(0; M)$, el cual es no vacío, porque $y_0 \in K$, cerrado y acotado. Por tanto, $K$ es compacto, y como $f$ es continua en $K$, por el teorema de Weierstrass, $f$ tiene máximo absoluto en $K$. Es decir, $\exists x_0 \in K$ tal que $f(x) \le f(x_0)$, $\forall x \in K$.

Si $x \notin K$, entonces $f(x) < \frac{\alpha}{2} \le f(x_0)$, luego $f(x) \le f(x_0)$, $\forall x \in \mathbb R^n$, luego $f$ tiene un máximo absoluto en $x_0$.
```

**Tema:** [[Derivadas de orden superior y extremos relativos#3. Extremos relativos y absolutos.]]

**Definiciones referenciadas:**  [[Extremos absoluto]], [[Norma]], [[Conjunto compacto]]
**Resultados referenciados:** [[Teorema de Weierstrass (R^n)]]

---
### Anki
