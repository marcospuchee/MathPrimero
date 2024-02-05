
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-27, 11:57

Sea $K \subset \mathbb R, f : K \to \mathbb R$
```ad-theorem
Si $K$ es compacto ([[Subconjunto sucesionalmente compacto]]) y $f \in C(K)$ ([[Función continua en un conjunto]]), entonces $f$ es uniformemente continua ([[Función uniformemente continua]]) en $K$.

```


```ad-proof
Razonaremos por reducción al absurdo, suponiendo la existencia de un compacto $C$ y una función $f: C \to \mathbb R$ continua en $C$, que no es uniformemente continua. 

De acuerdo con [[Definición alternativa de función uniformemente continua]], $\exists \epsilon_0 > 0$ y sucesiones $(x_n)_{n=1}^\infty$ y $(y_n)_{n=1}^\infty$ verificando que $\forall n \in \mathbb N$ se cumple que  $|f(x_n) - f(y_n)| \ge \epsilon_0 \land |x_n - y_n < 1/n|$. Puesto que $C$ es compacto, ha de existir una subsucesión $(x_{n_k})_{k=1}^\infty$ estrictamente creciente, convergente a un $x_0 \in C$. Observemos que
$$0 \le |y_{n_k}- x_0| \le |y_{n_k} - x_{n_k}| + |x_{n_k} - x_0| \le 1/n_k + |x_{n_k} - x_0|$$
Puesto que $1/n$ es convergente a cero, la subsucesión $(1/n_k)_{n=1}^\infty$ ha de converger también a cero; además $(x_{n_k})_{n=1}^\infty$ es convergente a $x_0$, por tanto $|x_{n_k} - x_0|$ converge a cero. De acuerdo con el criterio del emparedado, de la observación deducimos que $|y_{n_k} - x_0|$ converge también a cero, es decir, $(y_{n_k})_{k=1}^\infty$ es convergente a $x_0$.

Por la elección de sucesiones tenemos $|f(x_n) - f(y_n)| \ge \epsilon_0, n \in \mathbb N$, por tanto
$$|f(x_{n_k}) - f(y_{n_k})|\ge \epsilon_0, k \in \mathbb N$$
Puesto que $f$ es continua, según el [[Teorema de caracterización de la continuidad por sucesiones]], tendremos que $\lim f(x_{n_k}) = \lim f(y_{n_k}) = \lim f(x_0)$; las últimas igualdades y la última observación (el resultado apartado entre párrafos) muestras que $0 = |f(x_0) - f(x_0)| \ge \epsilon_0$. **Contradicción**.

```


**Tema:** [[Funciones continuas#3. Funciones uniformemente continuas]]
**Demostrado por:** [[Definición alternativa de función uniformemente continua]], [[Teorema de caracterización de la continuidad por sucesiones]].
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué dice el Teorema de Heine (1872)?
Reverso: Sea $K \subset \mathbb R, f : K \to \mathbb R$,
- Si $K$ es compacto ([[Subconjunto sucesionalmente compacto]]) y $f \in C(K)$ ([[Función continua en un conjunto]]), entonces $f$ es uniformemente continua ([[Función uniformemente continua]]) en $K$.
Tags: proposición/teorema
<!--ID: 1706355204100-->
END

START
Básico
Anverso:Demostración del Teorema de Heine (1872)
Reverso: Razonaremos por reducción al absurdo, suponiendo la existencia de un compacto $C$ y una función $f: C \to \mathbb R$ continua en $C$, que no es uniformemente continua. 

De acuerdo con [[Definición alternativa de función uniformemente continua]], $\exists \epsilon_0 > 0$ y sucesiones $(x_n)_{n=1}^\infty$ y $(y_n)_{n=1}^\infty$ verificando que $\forall n \in \mathbb N$ se cumple que  $|f(x_n) - f(y_n)| \ge \epsilon_0 \land |x_n - y_n < 1/n|$. Puesto que $C$ es compacto, ha de existir una subsucesión $(x_{n_k})_{k=1}^\infty$ estrictamente creciente, convergente a un $x_0 \in C$. Observemos que
$$0 \le |y_{n_k}- x_0| \le |y_{n_k} - x_{n_k}| + |x_{n_k} - x_0| \le 1/n_k + |x_{n_k} - x_0|$$
Puesto que $1/n$ es convergente a cero, la subsucesión $(1/n_k)_{n=1}^\infty$ ha de converger también a cero; además $(x_{n_k})_{n=1}^\infty$ es convergente a $x_0$, por tanto $|x_{n_k} - x_0|$ converge a cero. De acuerdo con el criterio del emparedado, de la observación deducimos que $|y_{n_k} - x_0|$ converge también a cero, es decir, $(y_{n_k})_{k=1}^\infty$ es convergente a $x_0$.

Por la elección de sucesiones tenemos $|f(x_n) - f(y_n)| \ge \epsilon_0, n \in \mathbb N$, por tanto
$$|f(x_{n_k}) - f(y_{n_k})|\ge \epsilon_0, k \in \mathbb N$$
Puesto que $f$ es continua, según el [[Teorema de caracterización de la continuidad por sucesiones]], tendremos que $\lim f(x_{n_k}) = \lim f(y_{n_k}) = \lim f(x_0)$; las últimas igualdades y la última observación (el resultado apartado entre párrafos) muestras que $0 = |f(x_0) - f(x_0)| \ge \epsilon_0$. **Contradicción**.
Tags: demostración
<!--ID: 1706355204105-->
END

