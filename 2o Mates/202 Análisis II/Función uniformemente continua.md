### Definición $(X, d)$.

```ad-Formal
$f: (X, d) \to (X, d')$ aplicación entre espacios métricos es uniformemente continua si $\forall \varepsilon > 0$, $\exists \delta> 0$ tal que si $d(x_1, x_2) < \delta$, entonces $d'(f(x_1), f(x_2)) < \varepsilon$.
```

**Tema:** [[Continuidad#3. Continuidad uniforme e isometrias.]]

**Definiciones referenciadas:** [[Espacio métrico]], [[Métrica]]

---
### Definición $\mathbb R^n$.

```ad-Formal
Diremos que $f: A \subseteq \mathbb R^n \to \mathbb R^m$ es uniformemente continua si
$$\forall \varepsilon > 0, \, \exists \delta > 0 : x,y \in A, \, ||x-y|| < \delta \implies ||f(x) - f(y)|| < \varepsilon.$$
```

^360b26

**Tema:** [[Funciones de varias variables#3. Continuidad.]]

---
### Definición $\mathbb R$.

Sea $A$ un subconjunto no vacío de $\mathbb R$ y $f: A \to \mathbb R$,
> [!formal] Formal definition
> Diremos que $f$ es uniformemente continua en $A$ si
> $$\forall \epsilon > 0, \exists \delta > 0 : \forall x,y \in A \textrm{ con } |x-y| < \delta \implies |f(x)-f(y)| < \epsilon$$

**Ejemplos:** la función $f : ]0,1] \to \mathbb R, f(x) := 1/x$ no es uniformemente continua en $]0,1]$ aunque es continua en $]0,1]$.

**Tema:** [[Funciones continuas#3. Funciones uniformemente continuas]]


---
### Anki

START
Básico
Anverso: Cuándo decimos que una función es uniformemente continua?
Reverso: Sea $A$ un subconjunto no vacío de $\mathbb R$ y $f: A \to \mathbb R$,

> Diremos que $f$ es uniformemente continua en $A$ si
> $$\forall \epsilon > 0, \exists \delta > 0 : \forall x,y \in A \textrm{ con } |x-y| < \delta \implies |f(x)-f(y)| < \epsilon$$

Tags: definición
<!--ID: 1706355204109-->
END

START
Básico
Anverso: Definición de función uniformemente continua $\mathbb R^n$.
Reverso: Diremos que $f: A \subseteq \mathbb R^n \to \mathbb R^m$ es uniformemente continua si
$$\forall \varepsilon > 0, \, \exists \delta > 0 : x,y \in A, \, ||x-y|| < \delta \implies ||f(x) - f(y)|| < \varepsilon.$$
<!--ID: 1728138052349-->
END

START
Básico
Anverso: Definición de función uniformemente continua $(X, \mathcal T)$.
Reverso: $f: (X, d) \to (X, d')$ aplicación entre espacios métricos es uniformemente continua si $\forall \varepsilon > 0$, $\exists \delta> 0$ tal que si $d(x_1, x_2) < \delta$, entonces $d'(f(x_1), f(x_2)) < \varepsilon$.
Tags: top
<!--ID: 1731446305326-->
END