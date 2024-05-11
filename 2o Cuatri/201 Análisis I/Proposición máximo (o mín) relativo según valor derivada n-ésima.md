
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-13, 12:41

```ad-proposition
Sea $I$ un [[Intervalo]] abierto no vacío en $\mathbb R$, $f: I \to \mathbb R, f \in C^{(n)}(I)$, supondremos que $a \in I$ y que $n \in \mathbb N, n \ge 2$, verifica que $f^{(k)}(a) = 0, 1 \le k < n, f^{(n)}(a) \neq 0$.
Si $n$ es impar entonces $a$ no es ni un máximo ni un mínimo relativo, si $n$ es par y si $f^{(n)}(a)>0$ (resp. $f^{(n)}(a)<0$) entonces $a$ es un mínimo (resp. máximo) relativo estricto.
```


```ad-proof
La expresión del [[Teorema de Lagrange (1797)]] del resto de Taylor y las hipótesis respecto a las derivadas, nos dan que $\forall x \in I, \exists \xi_x \in I(x,a)$ de extremos $a$ y $x$, tal que
$$f(x) = \sum_{k = 0}^{n-1} \frac{f^{(k)}(a)}{k!}(x-a)^k + \frac{f^{(n)}(\xi_x)}{n!}(x-a)^n = f(a) + \frac{f^{(k)}(\xi_x)}{n!}(x-a)^n.$$
Por tanto
$$\tag{*} f(x)-f(a) = \frac{f^{(n)}(\xi_x)}{n!}(x-a)^n.$$
Sabemos que $f^{(n)}$ es continua en $I$ ([[Función continua en un conjunto]]), y en particular en $a$. Suopngamos, por ejemplo, que $f^{(n)}(a) > 0$. Aplicando [[Lema valor del límite en un punto a]] a $f^{(n)}$ en $a$ obtendremos un $\delta > 0$ tal que
$$f^{(n)}(x) > 0, \quad \forall x \in ]a-\delta, a+\delta[.$$
Esta observación y $(*)$ nos dicen que el signo de $f(x) - f(a)$ es el mismo que el de $(x-a)^n$.

**Supongamos que $n$ es par.**
El signo de $(x-a)^n$ es positivo, por tanto $f(x)-f(a) > 0$ si $x \in ]a-\delta, a+\delta[$, luego $a$ es un mínimo relativo estricto.

**Supongamos que $n$ es impar.**
Tendremos que $(x-a)^n > 0$ (resp. $(x-a)^n < 0$) $\iff x-a > 0$ (resp. $x-a < 0$), la discusión anterior muestra que esto equivale a $f(x)-f(a) > 0$ (resp. $f(x)-f(a) < 0$), por tanto no es ni máximo ni mínimo relativo.

```



**Tema:** [[Funciones derivables#8. Concavidad, convexidad, inflexión, máximos y mínimos]]
**Corolarios:**

---
### Anki



START
Respuesta anidada
{{c3::Sea $I$ un [[Intervalo]] abierto no vacío en $\mathbb R$, $f: I \to \mathbb R, f \in C^{(n)}(I)$, supondremos que $a \in I$ y que $n \in \mathbb N, n \ge 2$, verifica que $f^{(k)}(a) = 0, 1 \le k < n, f^{(n)}(a) \neq 0$.}}
Si {{c1::$n$ es impar}} entonces{{c2:: $a$ no es ni un máximo ni un mínimo relativo}}, si {{c1::$n$ es par}} y si {{c1::$f^{(n)}(a)>0$ (resp. $f^{(n)}(a)<0$)}} entonces {{c2::$a$ es un mínimo (resp. máximo) relativo estricto}}.
Tags: proposición/teorema análisisI
<!--ID: 1714839016687-->
END

START
Básico
Anverso: Demostración de que sea $I$ un [[Intervalo]] abierto no vacío en $\mathbb R$, $f: I \to \mathbb R, f \in C^{(n)}(I)$, supondremos que $a \in I$ y que $n \in \mathbb N, n \ge 2$, verifica que $f^{(k)}(a) = 0, 1 \le k < n, f^{(n)}(a) \neq 0$.
Si $n$ es impar entonces $a$ no es ni un máximo ni un mínimo relativo, si $n$ es par y si $f^{(n)}(a)>0$ (resp. $f^{(n)}(a)<0$) entonces $a$ es un mínimo (resp. máximo) relativo estricto.
Reverso: La expresión del [[Teorema de Lagrange (1797)]] del resto de Taylor y las hipótesis respecto a las derivadas, nos dan que $\forall x \in I, \exists \xi_x \in I(x,a)$ de extremos $a$ y $x$, tal que
$$f(x) = \sum_{k = 0}^{n-1} \frac{f^{(k)}(a)}{k!}(x-a)^k + \frac{f^{(n)}(\xi_x)}{n!}(x-a)^n = f(a) + \frac{f^{(k)}(\xi_x)}{n!}(x-a)^n.$$
Por tanto
$$\tag{*} f(x)-f(a) = \frac{f^{(n)}(\xi_x)}{n!}(x-a)^n.$$
Sabemos que $f^{(n)}$ es continua en $I$ ([[Función continua en un conjunto]]), y en particular en $a$. Suopngamos, por ejemplo, que $f^{(n)}(a) > 0$. Aplicando [[Lema valor del límite en un punto a]] a $f^{(n)}$ en $a$ obtendremos un $\delta > 0$ tal que
$$f^{(n)}(x) > 0, \quad \forall x \in ]a-\delta, a+\delta[.$$
Esta observación y $(*)$ nos dicen que el signo de $f(x) - f(a)$ es el mismo que el de $(x-a)^n$.

**Supongamos que $n$ es par.**
El signo de $(x-a)^n$ es positivo, por tanto $f(x)-f(a) > 0$ si $x \in ]a-\delta, a+\delta[$, luego $a$ es un mínimo relativo estricto.

**Supongamos que $n$ es impar.**
Tendremos que $(x-a)^n > 0$ (resp. $(x-a)^n < 0$) $\iff x-a > 0$ (resp. $x-a < 0$), la discusión anterior muestra que esto equivale a $f(x)-f(a) > 0$ (resp. $f(x)-f(a) < 0$), por tanto no es ni máximo ni mínimo relativo.

Tags: demostración análisisI
<!--ID: 1713093069995-->
END


