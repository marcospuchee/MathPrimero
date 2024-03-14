
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-04, 17:18

```ad-theorem
Sean $I$ un [[Intervalo]] en $\mathbb R$ y $f: I \to \mathbb R$, continua en $I$ ([[Función continua en un conjunto]]), y derivable ([[Función derivable en un punto]]) en su [[Interior]]. Entonces:
1. $f$ es creciente (respectivamente decreciente) en $I \iff f'(x) \ge 0, \forall x \in I^o$  (respectivamente $f'(x) \le 0, \forall x \in I^o$).
2. Si $f'(x) > 0, \forall x \in I^o$ (respectivamente $f'(x) < 0, \forall x \in I^o$), entonces $f$ es estrictamente creciente (respectivamente estrictamente decreciente) en $I$.
```


```ad-proof
**(i).**
Si $f$ es creciente en $I$ y $a \in I^o$, tendremos:
$$\frac{f(x) - f(a)}{x-a} \ge 0 \quad x \in I - \{a\};$$
ahora, las propiedades de los límites nos permiten afirmar que $f'(a) \ge 0$. Recíprocamente, dados $x,y \in I, x<y$, de acuerdo con el [[Teorema del valor medio de Cauchy (1821)]], $\exists \xi \in ]x,y[ \subset I^o$ tal que $f(y)-f(x) = f'(\xi)(y-x) \ge 0$.

**(ii).**
La prueba es similar a la segunda parte de (i).
```


**Tema:** [[Funciones derivables#5. El teorema fundamental del cálculo diferencial]]
**Demostrado por:** [[Teorema del valor medio de Cauchy (1821)]]
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sean $I$ un [[Intervalo]] en $\mathbb R$ y $f: I \to \mathbb R$, continua en $I$ ([[Función continua en un conjunto]]), y derivable ([[Función derivable en un punto]]) en su [[Interior]]. Entonces:
1. {{c1::$f$ es creciente (respectivamente decreciente) en $I$}} $\iff${{c2::$f'(x) \ge 0, \forall x \in I^o$  (respectivamente $f'(x) \le 0, \forall x \in I^o$)}}.
2. Si {{c3::$f'(x) > 0, \forall x \in I^o$ (respectivamente $f'(x) < 0, \forall x \in I^o$)}}, entonces {{c4::$f$ es estrictamente creciente (respectivamente estrictamente decreciente) en $I$.}}
Tags: proposición/teorema análisisI
<!--ID: 1709571902633-->
END

START
Básico
Anverso: Demostración de que sean $I$ un [[Intervalo]] en $\mathbb R$ y $f: I \to \mathbb R$, continua en $I$ ([[Función continua en un conjunto]]), y derivable ([[Función derivable en un punto]]) en su [[Interior]]. Entonces:
1. $f$ es creciente (respectivamente decreciente) en $I \iff f'(x) \ge 0, \forall x \in I^o$  (respectivamente $f'(x) \le 0, \forall x \in I^o$).
2. Si $f'(x) > 0, \forall x \in I^o$ (respectivamente $f'(x) < 0, \forall x \in I^o$), entonces $f$ es estrictamente creciente (respectivamente estrictamente decreciente) en $I$.
Reverso: **(i).**
Si $f$ es creciente en $I$ y $a \in I^o$, tendremos:
$$\frac{f(x) - f(a)}{x-a} \ge 0 \quad x \in I - \{a\};$$
ahora, las propiedades de los límites nos permiten afirmar que $f'(a) \ge 0$. Recíprocamente, dados $x,y \in I, x<y$, de acuerdo con el [[Teorema del valor medio de Cauchy (1821)]], $\exists \xi \in ]x,y[ \subset I^o$ tal que $f(y)-f(x) = f'(\xi)(y-x) \ge 0$.

**(ii).**
La prueba es similar a la segunda parte de (i).
Tags: análisisI demostración
<!--ID: 1709571902644-->
END
