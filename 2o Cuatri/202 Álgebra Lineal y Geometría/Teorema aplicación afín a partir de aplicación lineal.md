
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-29, 17:55

```ad-theorem
Sean $(A, V, +), (A', V', +)$ espacios afines ([[espacio afín]]), y sean $P \in A, Q \in A'$ y $g: V \to V'$ [[aplicación lineal]].

Entonces $\exists ! f: A \to A'$ [[aplicación afín]] cuya aplicación lineal subyacente es $g$ y tal que $f(P) = Q$.
```


```ad-proof
Consideramos $f: A \to A'$, con $X \to f(X) = Q+g(\vec{PX})$.

1. Primero, veamos que $f$ es afín con aplicación lineal subyacente $g$. Sean $Y \in A, v \in V$ cualesquiera. Entonces:
$$f(Y+v) = Q+g(\overrightarrow{P(Y+v)}).$$
Sin embargo, tenemos que $\overrightarrow{P(Y+v)} = \vec{PY} + \overrightarrow{Y(Y+v)} = \vec{PY} + v$. Por tanto, seguimos la cadena de igualdades con 
$$Q+g(\overrightarrow{P(Y+v)}) = Q + g(\vec{PY} + v) = Q + g(\vec{PY}) + g(v) = f(Y) + g(v).$$
Luego hemos comprobado que $f(Y+v) = f(Y) + g(v)$.

2. Notemos que $f(P) = Q + g(\vec{PP}) = Q + g(0) = Q + 0 = Q$.

3. Para demostrar la unicidad, supongamos que $f': A \to A'$ afín tal que $f'(P) = Q$ y $g$ es la aplicación lineal subyacente a $f'$. Sea $X \in A$ arbitrario, tenemos:
$$f'(X) = f'(P + \vec{PX}) = f'(P) + g(\vec{PX}) = Q+g(\vec{PX}) = f(X) \implies f=f'.$$
```

**Tema:** [[Aplicaciones afines]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema que garantiza la existencia y la unicidad de una aplicación afín a partir de una aplicación lineal?
Reverso: Sean $(A, V, +), (A', V', +)$ espacios afines ([[espacio afín]]), y sean $P \in A, Q \in A'$ y $g: V \to V'$ [[aplicación lineal]].

Entonces $\exists ! f: A \to A'$ [[aplicación afín]] cuya aplicación lineal subyacente es $g$ y tal que $f(P) = Q$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714669443536-->
END

START
Básico
Anverso: Demostración de que sean $(A, V, +), (A', V', +)$ espacios afines ([[espacio afín]]), y sean $P \in A, Q \in A'$ y $g: V \to V'$ [[aplicación lineal]].

Entonces $\exists ! f: A \to A'$ [[aplicación afín]] cuya aplicación lineal subyacente es $g$ y tal que $f(P) = Q$.
Reverso: Consideramos $f: A \to A'$, con $X \to f(X) = Q+g(\vec{PX})$.

1. Primero, veamos que $f$ es afín con aplicación lineal subyacente $g$. Sean $Y \in A, v \in V$ cualesquiera. Entonces:
$$f(Y+v) = Q+g(\overrightarrow{P(Y+v)}).$$
Sin embargo, tenemos que $\overrightarrow{P(Y+v)} = \vec{PY} + \overrightarrow{Y(Y+v)} = \vec{PY} + v$. Por tanto, seguimos la cadena de igualdades con 
$$Q+g(\overrightarrow{P(Y+v)}) = Q + g(\vec{PY} + v) = Q + g(\vec{PY}) + g(v) = f(Y) + g(v).$$
Luego hemos comprobado que $f(Y+v) = f(Y) + g(v)$.

2. Notemos que $f(P) = Q + g(\vec{PP}) = Q + g(0) = Q + 0 = Q$.

3. Para demostrar la unicidad, supongamos que $f': A \to A'$ afín tal que $f'(P) = Q$ y $g$ es la aplicación lineal subyacente a $f'$. Sea $X \in A$ arbitrario, tenemos:
$$f'(X) = f'(P + \vec{PX}) = f'(P) + g(\vec{PX}) = Q+g(\vec{PX}) = f(X) \implies f=f'.$$
Tags: demostración ÁlgebraI
<!--ID: 1714669443540-->
END