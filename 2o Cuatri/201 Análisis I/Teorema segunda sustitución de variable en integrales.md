
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-02, 17:10

```ad-theorem
Sea $\varphi: [a,b] \to \mathbb R$ derivable con derivada continua tal que $\varphi'(t) \neq 0, \forall t \in [a,b]$. Sea $\Psi =$ inversa de $f$ continua en $\varphi([a,b])$. Entonces,
$$\int_a^b f(\varphi(t)) \, dt = \int_{\varphi(a)}^{\varphi(b)} f(x) \Psi (x) \, dx.$$
```


```ad-proof
Dado que $\varphi'$ tiene signo constante, entonces $\varphi$ es estrictamente monótona. Así, $\varphi: [a,b] \to [c,d]$ es biyección, siendo $[c,d] = \varphi([a,b])$.

Tenemos que $\Psi$ es derivable y $\Psi'(\varphi(t)) = 1/\varphi'(t), \forall t \in [a,b]$ ([[teorema de la función inversa]])
Entonces,
$$\int_a^b f(\varphi(t)) \, dt = \int_a^b f(\varphi(t)) \Psi (\varphi(t)) \varphi'(t) \,dt = \int_{\varphi(a)}^{\varphi(t)} f(x) \Psi(x) \, dx,$$
donde la última igualdad se extrae del [[teorema primera sustitución de variable en integrales]].
```


**Tema:** [[Integración de funciones de una variable real]]
**Demostrado por:** [[Teorema primera sustitución de variable en integrales]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la segunda sustitución de variable en integrales?
Reverso: Sea $\varphi: [a,b] \to \mathbb R$ derivable con derivada continua tal que $\varphi'(t) \neq 0, \forall t \in [a,b]$. Sea $\Psi =$ inversa de $f$ continua en $\varphi([a,b])$. Entonces,
$$\int_a^b f(\varphi(t)) \, dt = \int_{\varphi(a)}^{\varphi(b)} f(x) \Psi (x) \, dx.$$
Tags: proposición/teorema análisisI
<!--ID: 1714669443611-->
END

START
Básico
Anverso: Demostración de que sea $\varphi: [a,b] \to \mathbb R$ derivable con derivada continua tal que $\varphi'(t) \neq 0, \forall t \in [a,b]$. Sea $\Psi =$ inversa de $f$ continua en $\varphi([a,b])$. Entonces,
$$\int_a^b f(\varphi(t)) \, dt = \int_{\varphi(a)}^{\varphi(b)} f(x) \Psi (x) \, dx.$$
Reverso: Dado que $\varphi'$ tiene signo constante, entonces $\varphi$ es estrictamente monótona. Así, $\varphi: [a,b] \to [c,d]$ es biyección, siendo $[c,d] = \varphi([a,b])$.

Tenemos que $\Psi$ es derivable y $\Psi'(\varphi(t)) = 1/\varphi'(t), \forall t \in [a,b]$.
Entonces,
$$\int_a^b f(\varphi(t)) \, dt = \int_a^b f(\varphi(t)) \Psi (\varphi(t)) \varphi'(t) \,dt = \int_{\varphi(a)}^{\varphi(t)} f(x) \Psi(x) \, dx,$$
donde la última igualdad se extrae del [[teorema primera sustitución de variable en integrales]].
Tags: demostración análisisI
<!--ID: 1714669443616-->
END