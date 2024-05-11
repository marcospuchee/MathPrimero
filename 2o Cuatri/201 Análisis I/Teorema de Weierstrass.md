
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-01-26, 09:40

Sea $C$ un [[Subconjunto sucesionalmente compacto]] de $\mathbb R$
> [!theorem]
> $f : C \to \mathbb R$ [[Función continua en un conjunto]] $C \implies f$ es [[Función acotada]].

> [!proof]
> En caso contrario, por definición de [[Función acotada]], existiría una sucesión $x_n \in C$ tal que $|f(x_n)| \ge n, \forall n \in \mathbb N$.
>
> Puesto que $C$ es compacto, ha de existir una [[subsucesión]] $(x_{n_k})_{k = 1}^\infty$ convergente a un punto $\xi \in C$. El [[Teorema de caracterización de la continuidad por sucesiones]] nos dice que $(f(x_{n_k}))_{k = 1}^\infty$ converge, por tanto $(f(x_{n_k}))_{k = 1}^\infty$ es acotada.
>
> Por otra parte, tenemos $|f(x_{n_k})| \ge n_k \ge k, \forall k \in \mathbb N$, por tanto $(f(x_{n_k}))_{k=1}^\infty$ no es acotada, **contradicción**.

**Tema:** [[Funciones continuas#2. Funciones continuas en ciertos conjuntos]]
**Demostrado por:** [[Teorema de caracterización de la continuidad por sucesiones]]
**Consecuencias:** [[Teorema principal de Weierstrass (1861)]], [[Teorema continuidad implica integrabilidad]]

---
### Anki

START
Básico
Anverso: Qué dice el Teorema de Weierstrass?
Reverso: Sea $C$ un [[Subconjunto sucesionalmente compacto]] de $\mathbb R$
> $f : C \to \mathbb R$ [[Función continua en un conjunto]] $C \implies f$ es [[Función acotada]].

Tags: proposición/teorema
<!--ID: 1706259997766-->
END

START
Básico
Anverso: Demostración del Teorema de Weierstrass
Reverso: En caso contrario, por definición de [[Función acotada]], existiría una sucesión $x_n \in C$ tal que $|f(x_n)| \ge n, \forall n \in \mathbb N$.

Puesto que $C$ es compacto, ha de existir una [[subsucesión]] $(x_{n_k})_{k = 1}^\infty$ convergente a un punto $\xi \in C$. El [[Teorema de caracterización de la continuidad por sucesiones]] nos dice que $(f(x_{n_k}))_{k = 1}^\infty$ converge, por tanto $(f(x_{n_k}))_{k = 1}^\infty$ es acotada.

Por otra parte, tenemos $|f(x_{n_k})| \ge n_k \ge k, \forall k \in \mathbb N$, por tanto $(f(x_{n_k}))_{k=1}^\infty$ no es acotada, **contradicción**.
Tags: demostración
<!--ID: 1706259997771-->
END