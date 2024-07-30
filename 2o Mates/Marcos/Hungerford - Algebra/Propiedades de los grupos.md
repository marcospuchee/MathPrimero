
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-05, 13:46

```ad-theorem
Si $G$ es un [[monoide]], entonces el elemento identidad $e$ es único. Si $G$ es un [[grupo]], entonces
1. $c \in G$ y $cc = c \implies c = e$.
2. $\forall a, b, c \in G, \, ab = ac \implies b = c$ y $ba = ca \implies b = c$.
3. Para cada $a \in G$, el elemento inverso $a^{-1}$ es único.
4. Para cada $a \in G, \, (a^{-1})^{-1} = a$.
5. Dados $a,b \in G, (ab)^{-1} = b^{-1}a^{-1}$.
6. Dados $a,b \in G$, las ecuaciones $ax = b$ y $ya = b$ tienen soluciones únicas en $G: x = a^{-1}b$ y $y = ba^{-1}$.
```

```ad-proof
Podemos suponer por reducción al absurdo que el elemento identidad no es único. Luego suponemos que $\exists u \in G$ con $u \neq e$ tal que $u$ es elemento unidad. Sin embargo, $e = eu = u$, lo cual es una contradicción.

1. $cc = c \implies ccc^{-1} = cc^{-1} \implies c = e$.
2. $ab = ac \implies a^{-1}ab = a^{-1}ac \implies b = c$. Análogamente se resuelve el segundo resultado.
3. Supongamos por reducción al absurdo que $\exists b \in G$ tal que $ab = e$. Sin embargo, $a^{-1} = a^{-1}(ab) = (a^{-1}a)b = b$, lo cual es una contradicción.
4. $(a^{-1})^{-1} = (a^{-1})^{-1}(a^{-1}a) = \left ( (a^{-1})^{-1} a^{-1} \right )a = a$.
5. $(ab)^{-1} = (ab)^{-1}abb^{-1}a^{-1} = \left [ (ab)^{-1} ab \right ] b^{-1} a^{-1} = b^{-1} a^{-1}$.
6. Trivial.
```

**Tema:** [[Grupos#1. Semigrupos, monoides y grupos]]
**Demostrado por:** propiedades básicas de [[Monoide]] y [[Grupo]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué propiedades cumplen los grupos?
Reverso: Si $G$ es un [[monoide]], entonces el elemento identidad $e$ es único. Si $G$ es un [[grupo]], entonces
1. $c \in G$ y $cc = c \implies c = e$.
2. $\forall a, b, c \in G, \, ab = ac \implies b = c$ y $ba = ca \implies b = c$.
3. Para cada $a \in G$, el elemento inverso $a^{-1}$ es único.
4. Para cada $a \in G, \, (a^{-1})^{-1} = a$.
5. Dados $a,b \in G, (ab)^{-1} = b^{-1}a^{-1}$.
6. Dados $a,b \in G$, las ecuaciones $ax = b$ y $ya = b$ tienen soluciones únicas en $G: x = a^{-1}b$ y $y = ba^{-1}$.
Tags: hungerford proposición/teorema
<!--ID: 1721211802962-->
END