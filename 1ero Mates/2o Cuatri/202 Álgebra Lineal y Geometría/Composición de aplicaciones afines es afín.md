
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 18:08

```ad-proposition
Sean $f: A \to A', g: A' \to A''$  aplicaciones afines ([[aplicación afín]]) donde $(A, V, +), (A', V', +), (A'', V'', +)$ son espacios afines ([[espacio afín]]). Supongamos que $\hat f: V \to V', \hat g: V' \to V''$ son las aplicaciones subyacentes a $f,g$. Entonces, $g \circ f$ es afín.
```


```ad-proof
$\forall P \in A, \forall v \in V$, se cumple que:
$$(g \circ f)(P+v) = g(f(P+v)) = g(f(P) + \hat f(v)) = g(f(P)) + \hat g( \hat f(v)) = (g \circ f)(P) + (\hat g \circ \hat f)(v).$$
```

**Tema:** [[Aplicaciones afines]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Cuál es la proposición que garantiza que la composición de aplicaciones afines es afín?
Reverso: Sean $f: A \to A', g: A' \to A''$  aplicaciones afines ([[Aplicación afín]]) donde $(A, V, +), (A', V', +), (A'', V'', +)$ son espacios afines ([[Espacio afín]]). Supongamos que $\hat f: V \to V', \hat g: V' \to V''$ son las aplicaciones subyacentes a $f,g$. Entonces, $g \circ f$ es afín.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714669443588-->
END

START
Básico
Anverso: Demostración de que sean $f: A \to A', g: A' \to A''$  aplicaciones afines ([[Aplicación afín]]) donde $(A, V, +), (A', V', +), (A'', V'', +)$ son espacios afines ([[Espacio afín]]). Supongamos que $\hat f: V \to V', \hat g: V' \to V''$ son las aplicaciones subyacentes a $f,g$. Entonces, $g \circ f$ es afín.
Reverso: $\forall P \in A, \forall v \in V$, se cumple que:
$$(g \circ f)(P+v) = g(f(P+v)) = g(f(P) + \hat f(v)) = g(f(P)) + \hat g( \hat f(v)) = (g \circ f)(P) + (\hat g \circ \hat f)(v).$$
Tags: demostración ÁlgebraI
<!--ID: 1714669443593-->
END