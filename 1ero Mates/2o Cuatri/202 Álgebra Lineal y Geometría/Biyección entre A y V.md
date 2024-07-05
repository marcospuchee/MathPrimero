
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 16:18

```ad-lemma
Sea $(A, V, +)$ un [[espacio afín]], y sea $P \in A$. Entonces la aplicación no lineal $\varphi_P: V \to A$ con $v \to \varphi_P(v) = P+V$ es una biyección. En particular, $|V| = |A|$.
```


```ad-proof
Veamos que $\varphi_P$ es inyectiva. Sean $u,w \in V$ tales que $\varphi_P(u) = \varphi_P(w)$. Es decir, $P + v = P + w$. Por tanto:
$$(P+v) + (-v) = (P+w) + (-v) \implies P = P + (w-v) \implies w-v = \vec{PP} = 0,$$
por las [[propiedades del espacio afín]].
Por tanto $w = v$. Concluimos que $\varphi_P$ es inyectiva.

$\varphi$ sobreyectiva ejercicio.
```

**Tema:** [[Espacios afines]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $(A, V, +)$ un [[Espacio afín]], y sea $P \in A$. Entonces {{c1::la aplicación no lineal $\varphi_P: V \to A$ con $v \to \varphi_P(v) = P+V$}} es {{c2::una biyección}}.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060761164-->
END

START
Básico
Anverso: Demostración de que sea $(A, V, +)$ un [[Espacio afín]], y sea $P \in A$. Entonces la aplicación no lineal $\varphi_P: V \to A$ con $v \to \varphi_P(v) = P+V$ es una biyección. En particular, $|V| = |A|$.
Reverso: Veamos que $\varphi_P$ es inyectiva. Sean $u,w \in V$ tales que $\varphi_P(u) = \varphi_P(w)$. Es decir, $P + v = P + w$. Por tanto:
$$(P+v) + (-v) = (P+w) + (-v) \implies P = P + (w-v) \implies w-v = \vec{PP} = 0,$$
por las [[Propiedades del espacio afín]].
Por tanto $w = v$. Concluimos que $\varphi_P$ es inyectiva.

$\varphi$ sobreyectiva ejercicio.
Tags: demostración ÁlgebraI
<!--ID: 1714060761175-->
END

