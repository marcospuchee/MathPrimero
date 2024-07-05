
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-14, 12:20

```ad-theorem
Sea $V$ un $\mathbb R$-[[Espacio vectorial euclídeo]] y sean $x,y \in V$. Entonces,
$$|x · y| \le ||x|| · ||y||.$$
[[Norma de un vector]].

Además la igualdad se satisface si y sólo si $x,y$ son proporcionales.
```


```ad-proof
Podemos suponer $x,y$ no nulos (de serlo es trivial). En particular $\langle x \rangle \le V$ es [[subespacio regular]] y por tanto $V = \langle x \rangle \bigoplus \langle x \rangle^\perp$.
Podemos escribir $y = \lambda x + u$, donde $\lambda \in \mathbb R, u \in \langle x \rangle^\perp$. Tenemos:
$$||y||^2 = y · y = (\lambda x + u)(\lambda x + u) = \lambda^2(x · x) + 2\lambda (x·u) + u·u = \lambda^2||x||^2 + ||u||^2 \ge \lambda^2 ||x||^2$$
Ahora,
$$(x·y)^2 = (x·(\lambda x + u))^2$$
Por $u \in \langle x \rangle^\perp$, tenemos
$$(x·(\lambda x + u))^2 = \lambda^2 (x·x)^2 = \lambda^2(||x||^2)^2 = \lambda^2 ||x||^2 ||x||^2 \le ||x||^2 · ||y||^2.$$
Por tanto, $|x·y| \le ||x|| · ||y||$.

Las desigualdades anteriores son igualdades si y sólo si $||v||^2 = 0 \iff$ $v = 0$ $\iff \lambda x = y$.
```


**Tema:** [[Espacios vectoriales euclídeos]]
**Demostrado por:**
**Consecuencias:** [[Propiedades de la norma]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Cauchy-Schwartz?
Reverso: Sea $V$ un $\mathbb R$-[[Espacio vectorial euclídeo]] y sean $x,y \in V$. Entonces,
$$|x · y| \le ||x|| · ||y||.$$
[[Norma de un vector]].

Además la igualdad se satisface si y sólo si $x,y$ son proporcionales.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060760762-->
END

START
Básico
Anverso: Demostración del teorema de Cauchy-Schwartz
Reverso: Podemos suponer $x,y$ no nulos (de serlo es trivial). En particular $\langle x \rangle \le V$ es [[Subespacio regular]] y por tanto $V = \langle x \rangle \bigoplus \langle x \rangle^\perp$.
Podemos escribir $y = \lambda x + u$, donde $\lambda \in \mathbb R, u \in \langle x \rangle^\perp$. Tenemos:
$$||y||^2 = y · y = (\lambda x + u)(\lambda x + u) = \lambda^2(x · x) + 2\lambda (x·u) + u·u = \lambda^2||x||^2 + ||u||^2 \ge \lambda^2 ||x||^2$$
Ahora,
$$(x·y)^2 = (x·(\lambda x + u))^2$$
Por $u \in \langle x \rangle^\perp$, tenemos
$$(x·(\lambda x + u))^2 = \lambda^2 (x·x)^1 = \lambda^2(||x||^2)^2 = \lambda^2 ||x||^2 ||x||^2 \le ||x||^2 · ||y||^2.$$
Por tanto, $|x·y| \le ||x|| · ||y||$.

Las desigualdades anteriores son igualdades si y sólo si $||v||^2 = 0 \iff$ $v = 0$ $\iff \lambda x = y$.
Tags: demostración ÁlgebraI
<!--ID: 1714060760774-->
END