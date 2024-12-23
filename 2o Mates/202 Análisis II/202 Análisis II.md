## Tema 0: Introducción.
**Referencia:** [[Introducción - Análisis II]]

- [[Norma]]
- [[Producto escalar]]
- [[Sucesión (Rn)]]
- [[Convergencia sucesión (Rn)]]
- [[Bola abierta]]
- [[Bola cerrada]]
- [[Esfera]]
- [[Conjunto abierto]]
- [[Entorno]]
- [[Conjunto cerrado]]
- [[Punto de acumulación]]
- [[Clausura]]
- [[Punto interior]]
- [[(por demostrar) Conjunto es abierto sii es igual a su interior]]
- [[(por demostrar) Conjunto es cerrado sii es igual a su clausura sii toda sucesión convergente converge a un punto del cojunto]]
- [[Frontera topológica]]
- [[Conjunto acotado]]
- [[(por demostrar) Caracterización de conjuntos acotados]]
- [[(por demostrar) Toda sucesión acotada tiene una subsucesión convergente]]
- [[Conjunto compacto]]
- [[(por demostrar) Conjunto compacto sii cerrado y acotado]]
---
## Tema 1: Funciones de varias variables.
**Referencia:** [[Funciones de varias variables]]
### 1. Introducción.
- [[Función de varias variables]]
- [[Límite de una función de varias variables]]
- [[(ejercicio) Teorema caracterización sucesional de límite multivariable]]
- [[(ejercicio) Límite función vectorial igual al límite de cada vector]]
- [[(ejercicio) Propiedades cálculo de límites multivariables]]
### 2. Dos variables.
- [[Límites por curvas]]
- [[Límite de una función con función que tiende a 0 como epsilon]]
- [[Límites iterados]]
- [[(ejercicio) Límite de una función a través de coordenadas polares]]
### 3. Continuidad.
- [[Función multivariable continua]]
- [[(por hacer) Operaciones sobre funciones continuas son continuas]]
- [[(por hacer) La composición de funciones continuas es continua]]
- [[Caracterización continuidad función multivariable con entornos]]
- [[Caracterización continuidad función multivariable con antiimagen abierta y cerrada]]
- [[Función continua sobre conjunto compacto entonces imagen compacta]]
- [[Teorema de Weierstrass (R^n)]]
- [[Función uniformemente continua]]
- [[Teorema de Heine (R^n)]]
- [[Función lipschitziana]]
- [[Aplicación lineal es uniformemente continua (lipschitziana)]]
--- 
## Tema 2: Diferenciabilidad de funciones de varias variables.
**Referencia:** [[Diferenciabilidad de funciones de varias variables]]
### 1. Derivadas direccionales y diferencial.
- [[Derivada direccional]]
- [[Derivada parcial]]
- [[Función diferenciable]]
- [[Diferencial es único]]
- [[(ejercicio) Diferenciable implica que existen todas las derivadas direccionales]]
- [[Diferenciable implica continua]]
- [[Derivada direccional a partir de parciales]]
- [[Propiedades función diferenciable]]
### 2. Matrices jacobianas y vector gradiente.
- [[Matriz jacobiana]]
- [[Vector gradiente]]
- [[Caracterización de función diferenciable]]
- [[Derivada direccional es máxima en la dirección del gradiente]]
### 4. Condición suficiente de  diferenciabilidad.
- [[Condición suficiente de diferenciabilidad]]
- [$C^1$](Función de clase C1)
### 5. Regla de la cadena.
- [[Regla de la cadena (Rn)]]
### 6. Teorema del valor medio. 
- [[Teorema del valor medio]]
- [[Todas las derivadas parciales acotadas implica que la función es lipschitziana]]
- [[Derivadas parciales nulas implican que la función es constante]]
---
## Tema 3: Derivadas de orden superior y extremos relativos.
**Referencia:** [[Derivadas de orden superior y extremos relativos]]
### 1. Derivada de orden dos.
- [$D_if(a)$](Derivada de orden dos)
- [$\exists D_if(a), D_jf(a)$ y son diferenciables $\implies$ $\exists D_{ij}f(a), D_{ji}f(a)$ y $D_{ij}f(a) = D_{ji}f(a)$](Teorema de Young)
- [[Corolario teorema de Young]]
- [$C^2$](Función de clase C2)
- [$\exists D_if(a), D_jf(a), D_{ij}f(a)$ y son continuas $\implies \exists D_{ji}f(a) = D_{ij}f(a)$](Teorema de Schwarz)
### 2. Fórmula de Taylor.
- [$P_2(x)$](Polinomio de Taylor de orden dos)
- [$\lim \limits_{x \to a} \frac{f(x)-P_2(x)}{||x-a||^2} = 0$](Teorema de Taylor para varias variables)
### 3. Extremos relativos y absolutos.
- [[Extremos absoluto]]
- [[Extremos relativos]]
- [$a$ extremo relativo $\implies$ $D_if(a) = 0$, $\forall i$](Teorema de derivadas nulas en extremos relativos)
- [Punto crítico](Teorema de derivadas nulas en extremos relativos), [Punto de silla](Teorema de derivadas nulas en extremos relativos)
- [$H_f(a)$](Matriz Hessiana),[[Matriz Hessiana]]
- [$D^2f(a)$](Forma cuadrática), [[Forma cuadrática]]
- [$D^2f(a)$ definida positiva $\implies$ $f$ mínimo relativo estricto en $a$](Existencia extremos relativos estrictos según matriz Hessiana)
- [$D^2f(a)$ definida negativa $\implies$ $f$ máximo relativo estricto en $a$](Existencia extremos relativos estrictos según matriz Hessiana)
- [$D^2f(a)$ toma valores positivos y negativos $\implies$ $a$ es punto de silla en $f$](Existencia extremos relativos estrictos según matriz Hessiana)
- [[Criterio de Sylvester]]
- [Corolario criterio de Sylvester](Criterio de Sylvester)
- [[Teorema de Weierstrass (R^n)]]
- [$(f(x) \ge 0$, $\forall x \in \mathbb R^n \land \lim \limits_{||x|| \to +\infty} f(x) = 0) \implies f$ tiene máximo absoluto](Función positiva con límite cuando la norma tiende a infinito cero tiene máximo absoluto)
---
## Tema 4: Los teoremas de la función inversa y de la función implícita. 
**Referencia:** [[Los teoremas de la función inversa y de la función implícita]]
### 1. Teorema de la función inversa.
- [[Determinante jacobiano]], [$J_f(x)$](Determinante jacobiano)
- [[Teorema de la inyectividad local]]
- [[Función abierta]]
- [$B(a; r) : J_f(x) \neq 0 \land f(x) \neq f(a), \, \forall x \in S(a;r) \implies f(B(a;r)) \in \mathcal E(f(a))$](Imagen bola con jacobiano no trivial es entorno)
- [$f$ diferenciable e inyectiva en $\Omega$ con $J_f(x) \neq 0, \forall x \in \Omega \implies f(\Omega)$ es un abierto](Función de clase C1 con jacobiano no nulo es abierta)
- [$f \in C^1(\Omega, \mathbb R^n) : J_f(x) \neq 0, \forall x \in \Omega \implies f$ aplicación abierta](Función de clase C1 con jacobiano no nulo es abierta)
- [$f \in C^1(\Omega, \mathbb R^n)$ inyectiva $: J_f(x) \neq 0, \forall x \in \Omega \implies f^{-1}: f(\Omega) \to \Omega$ es continua ](Función inversa es continua)
- [[Teorema de la función inversa]]
- [$f \in C^1(\Omega)$ biyección $\implies (f^{-1} \in C^1 \iff J_f(x) \neq 0, \forall x \in \Omega)$](Teorema de la función inversa)
### 2. Cambios de variable.
- [[Cambio de variable]]
- [Cambio a coordenadas polares](Cambio de variable)
- [Cambio a coordenadas cilíndricas](Cambio de variable)
- [Cambio a coordenadas esféricas](Cambio de variable)
### 3. El teorema de la función implícita.
- [[Teorema de la función implícita]]
---
## Tema 5: Extremos condicionados y multiplicadores de Lagrange.
**Referencia:** [[Extremos condicionados y multiplicadores de Lagrange]]

- [[Variedad diferenciable]]
- [[Extremo condicionado]]
- [[Teorema de los multiplicadores de Lagrange]]
