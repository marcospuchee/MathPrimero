
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-29, 17:40

Sea $f: ]u,v[ \to ]s, t[$ estrictamente monótona ([[Función monótona]], o inyectiva), sobreyectiva y continua en $]u,v[$ ([[Función continua en un conjunto]]), denotemos por $g : ]s,t[ \to ]u,v[$ a su [[Función inversa]].

```ad-theorem
Si $f$ es derivable en $a \in ]u,v[$ ([[Función derivable en un punto]]) y $f'(a) \neq 0$, entonces $g$ es derivable en $b = f(a)$ y
$$g'(b) = 1/f'(a).$$
```


```ad-proof
Puesto que $f$ es derivable en $a$, sea $H$ la función continua en $a$ que cumple con la [[Formulación de Weierstrass (1861)]], es decir, $H(a) = 0$ y
$$f(x) = f(a) + f'(a)(x-a) + H(x)(x-a), \quad x \in ]u,v[.$$
En particular
$$y = f(g(y)) = b + f'(a)(g(y) - g(b)) + H(g(y))(g(y)-g(b)), \quad y \in ]s,t[;$$
así
$$y - b = (f'(a)+H(g(y)))(g(y) - g(b)), \quad y \in ]s,t[.$$
De acuerdo con la igualdad anterior, si $y \neq b$ tendremos que $f'(a) + H(g(y)) \neq 0$, y podemos escribir
$$\frac{g(y) - g(b)}{y-b} = \frac{1}{f'(a) + H(g(y))}, \quad y \in ]s,t[ - \{b\}. \tag{*}$$
Según el [[Teorema función inversa mantiene continuidad y monotonía]],  la función $g$ es continua, entonces $H(g(y))$ también lo es en $b$. Existirá por tanto el límite $\lim_{y \to b} H(g(y)) = H(g(b)) = H(a) = 0$. Esta observación y (*) nos dan que
$$\exists \lim_{y \to b} \frac{g(y)-g(b)}{y-b} = 1/f'(a).$$
```


**Tema:** [[Funciones derivables#4. Teorema de la función inversa]]
**Demostrado por:** [[Formulación de Weierstrass (1861)]], [[Teorema función inversa mantiene continuidad y monotonía]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la función inversa?
Reverso: Sea $f: ]u,v[ \to ]s, t[$ estrictamente monótona ([[Función monótona]], o inyectiva), sobreyectiva y continua en $]u,v[$ ([[Función continua en un conjunto]]), denotemos por $g : ]s,t[ \to ]u,v[$ a su [[Función inversa]]. Si $f$ es derivable en $a \in ]u,v[$ ([[Función derivable en un punto]]) y $f'(a) \neq 0$, entonces $g$ es derivable en $b = f(a)$ y
$$g'(b) = 1/f'(a).$$
Tags: proposición/teorema análisisI
<!--ID: 1709231331288-->
END

START
Básico
Anverso: Demostración de que sea $f: ]u,v[ \to ]s, t[$ estrictamente monótona ([[Función monótona]], o inyectiva), sobreyectiva y continua en $]u,v[$ ([[Función continua en un conjunto]]), denotemos por $g : ]s,t[ \to ]u,v[$ a su [[Función inversa]]. Si $f$ es derivable en $a \in ]u,v[$ ([[Función derivable en un punto]]) y $f'(a) \neq 0$, entonces $g$ es derivable en $b = f(a)$ y
$$g'(b) = 1/f'(a).$$
(Teorema de la función inversa)
Reverso: Puesto que $f$ es derivable en $a$, sea $H$ la función continua en $a$ que cumple con la [[Formulación de Weierstrass (1861)]], es decir, $H(a) = 0$ y
$$f(x) = f(a) + f'(a)(x-a) + H(x)(x-a), \quad x \in ]u,v[.$$
En particular
$$y = f(g(y)) = b + f'(a)(g(y) - g(b)) + H(g(y))(g(y)-g(b)), \quad y \in ]s,t[;$$
así
$$y - b = (f'(a)+H(g(y)))(g(y) - g(b)), \quad y \in ]s,t[.$$
De acuerdo con la igualdad anterior, si $y \neq b$ tendremos que $f'(a) + H(g(y)) \neq 0$, y podemos escribir
$$\frac{g(y) - g(b)}{y-b} = \frac{1}{f'(a) + H(g(y))}, \quad y \in ]s,t[ - \{b\}. \tag{*}$$
Según el [[Teorema función inversa mantiene continuidad y monotonía]],  la función $g$ es continua, entonces $H(g(y))$ también lo es en $b$. Existirá por tanto el límite $\lim_{y \to b} H(g(y)) = H(g(b)) = H(a) = 0$. Esta observación y (*) nos dan que
$$\exists \lim_{y \to b} \frac{g(y)-g(b)}{y-b} = 1/f'(a).$$
Tags: demostración análisisI
<!--ID: 1709231331296-->
END