
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-02, 16:38

```ad-proposition
Si $f, g: [a,b] \to \mathbb R$ son integrables Riemann ([[Integral de Riemann]]) y admiten [[función primitiva]] $F,G$. Entonces,
$$\int_a^b F(x) g(x) \, dx = F(b) G(b) - F(a)G(a) - \int_a^b f(x) G(x) \, dx.$$
```


```ad-proof
Tomamos $H: [a,b] \to \mathbb R$, $H(x) = F(x)G(x)$. Tenemos que $H$ es continua en $[a,b]$ por ser producto de continuas.
Además, si $a<x<b$, entonces $H'(x) = f(x)G(x) + F(x)g(x)$, y además, $fG + gF$ es integrable en $[a,b]$.

Por la [[regla de Barrow]]:
$$\int_a^b f(g) G(x) \, dx + \int_a^b F(g) g(x) \, dx = H(b) - H(a) = F(b)G(b) - F(a)G(a).$$
```

**Tema:** [[Integración de funciones de una variable real]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la proposición que permite la integración por partes?
Reverso: Si $f, g: [a,b] \to \mathbb R$ son integrables Riemann ([[Integral de Riemann]]) y admiten [[Función primitiva]] $F,G$. Entonces,
$$\int_a^b F(x) g(x) \, dx = F(b) G(b) - F(a)G(a) - \int_a^b f(x) G(x) \, dx.$$
Tags: proposición/teorema análisisI
<!--ID: 1714669443634-->
END

START
Básico
Anverso: Demostración de que si $f, g: [a,b] \to \mathbb R$ son integrables Riemann ([[Integral de Riemann]]) y admiten [[Función primitiva]] $F,G$. Entonces,
$$\int_a^b F(x) g(x) \, dx = F(b) G(b) - F(a)G(a) - \int_a^b f(x) G(x) \, dx.$$
Reverso: Tomamos $H: [a,b] \to \mathbb R$, $H(x) = F(x)G(x)$. Tenemos que $H$ es continua en $[a,b]$ por ser producto de continuas.
Además, si $a<x<b$, entonces $H'(x) = f(x)G(x) + F(x)g(x)$, y además, $fG + gF$ es integrable en $[a,b]$.

Por la [[Regla de Barrow]]:
$$\int_a^b f(g) G(x) \, dx + \int_a^b F(g) g(x) \, dx = H(b) - H(a) = F(b)G(b) - F(a)G(a).$$
Tags: demostración análisisI
<!--ID: 1714669443640-->
END