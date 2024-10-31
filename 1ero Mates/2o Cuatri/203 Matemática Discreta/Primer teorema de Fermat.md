
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-19, 17:11

```ad-theorem
Sea $p$ un [[número primo]]. Para cualquier entero $a$
$$a^p \equiv a \pmod p$$
y para cualquier entero $a$ no divisible por $p$ ($p \nmid a$), tenemos que
$$a^{p-1} \equiv 1 \pmod p.$$
```


```ad-proof
Suponemos primero que $p \nmid a$. En $\mathbb Z / p \mathbb Z$ consideramos las clases de congruencia:
$$\overline{0a}, \overline{1a}, \overline{2a}, \dots, \overline{(p-1)a}$$
y demostremos que todas ellas son diferentes. Como $a$ y $p$ son [[coprimos]], $\exists u,v \in \mathbb Z$, tal que $au + pv = 1$ ([[identidad de Bezout]]), luego $au \equiv 1 \pmod p$, por la proposición [[elemento de congruencia invertible]], $a$ es invertible en $\mathbb Z / p \mathbb Z$, es decir $a^{-1} \in \mathbb Z / p \mathbb Z$. Ahora si $\overline{ia} = \overline{ja}$ con $i \neq j$, entonces $ia = ja$ en $\mathbb Z / p \mathbb Z$, por tanto $iaa^{-1} = jaa^{-1}$, implica que $i = j$, lo que es una contradicción.

Por otro lado, ningún elemento de $\{\overline{0a}, \overline{1a}, \overline{2a}, \dots, \overline{(p-1)a} \}$ puede ser $0$ módulo $p$, ya que si $k$ es uno de los número $\{1,2,3, \dots, p-1\}$, $k$ no es divisible por $p$ y tampoco $a$. Entonces $ka$ no es divisible por $p$. Así pues se tiene que el conjunto de clases $\{\overline{0a}, \overline{1a}, \overline{2a}, \dots, \overline{(p-1)a}\}$ está formado por $p$ clases distintas y coincide con $\mathbb Z / p \mathbb Z = \{\overline 0, \overline 1, \overline 2, \dots, \overline{(p-1)} \}$. Evidentemente $\overline{0a} = \overline 0$, luego tenemos la siguiente igualdad entre conjuntos:
$$\{1,2,3, \dots, p-1 \} = \{a,2a,3a, \dots, (p-1)a \}.$$
Multiplicando los elementos de la izquierda y de la derecha obtenemos
$$(p-1)! \equiv (p-1)!a^{p-1} \pmod p.$$
Es decir,
$$p | [(p-1)!(a^{p-1}-1)].$$
Como todos los factores de $(p-1)!$ son menores de $p$, ninguno tiene a $p$ como factor, y por otro lado, si el producto de elementos de $(p-1)!$ diera como resultado un múltiplo de $p$, (o el mismo $p$), entonces $p$ no sería primo. Todo esto nos lleva a que $\textrm{mcd}((p-1)!, p) = 1$, y por [[proposición divisibilidad de un producto]] (si $a|bc$ y $\textrm{mcd}(a,b) = 1$, entonces $a|c$) $p|a^{p-1}-1$ y en consecuencia $a^{p-1} \equiv 1 \pmod p$. Y el segundo resultado queda demostrado.

Ahora si $p \nmid a$, por el resultado anterior $a^{p-1} \equiv 1 \pmod p$. Multiplicando por $a$ se obtiene $a^p \equiv a \pmod p$.
Si $p | a$ entonces $a \equiv 0 \pmod p$, luego $a^p \equiv 0^p \pmod p$, y por tanto $a^p \equiv 0 \pmod 0$ y $a^p \equiv a \pmod p$.
```

**Tema:** [[Aritmética modular#5. Primer teorema de Fermat - Teorema de Euler]]
**Demostrado por:** [[Identidad de Bezout]], [[Elemento de congruencia invertible]], [[Proposición divisibilidad de un producto]]
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Cuál es el primer teorema de Fermat?
Reverso: Sea $p$ un [[Número primo]]. Para cualquier entero $a$
$$a^p \equiv a \pmod p$$
y para cualquier entero $a$ no divisible por $p$ ($p \nmid a$), tenemos que
$$a^{p-1} \equiv 1 \pmod p.$$
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517303-->
END

START
Básico
Anverso: Demostración del primer teorema de Fermat
Reverso: Suponemos primero que $p \nmid a$. En $\mathbb Z / p \mathbb Z$ consideramos las clases de congruencia:
$$\overline{0a}, \overline{1a}, \overline{2a}, \dots, \overline{(p-1)a}$$
y demostremos que todas ellas son diferentes. Como $a$ y $p$ son [[Coprimos]], $\exists u,v \in \mathbb Z$, tal que $au + pv = 1$ ([[Identidad de Bezout]]), luego $au \equiv 1 \pmod p$, por la proposición [[Elemento de congruencia invertible]], $a$ es invertible en $\mathbb Z / p \mathbb Z$, es decir $a^{-1} \in \mathbb Z / p \mathbb Z$. Ahora si $\overline{ia} = \overline{ja}$ con $i \neq j$, entonces $ia = ja$ en $\mathbb Z / p \mathbb Z$, por tanto $iaa^{-1} = jaa^{-1}$, implica que $i = j$, lo que es una contradicción.

Por otro lado, ningún elemento de $\{\overline{0a}, \overline{1a}, \overline{2a}, \dots, \overline{(p-1)a} \}$ puede ser $0$ módulo $p$, ya que si $k$ es uno de los número $\{1,2,3, \dots, p-1\}$, $k$ no es divisible por $p$ y tampoco $a$. Entonces $ka$ no es divisible por $p$. Así pues se tiene que el conjunto de clases $\{\overline{0a}, \overline{1a}, \overline{2a}, \dots, \overline{(p-1)a}\}$ está formado por $p$ clases distintas y coincide con $\mathbb Z / p \mathbb Z = \{\overline 0, \overline 1, \overline 2, \dots, \overline{(p-1)} \}$. Evidentemente $\overline{0a} = \overline 0$, luego tenemos la siguiente igualdad entre conjuntos:
$$\{1,2,3, \dots, p-1 \} = \{a,2a,3a, \dots, (p-1)a \}.$$
Multiplicando los elementos de la izquierda y de la derecha obtenemos
$$(p-1)! \equiv (p-1)!a^{p-1} \pmod p.$$
Es decir,
$$p | [(p-1)!(a^{p-1}-1)].$$
Como todos los factores de $(p-1)!$ son menores de $p$, ninguno tiene a $p$ como factor, y por otro lado, si el producto de elementos de $(p-1)!$ diera como resultado un múltiplo de $p$, (o el mismo $p$), entonces $p$ no sería primo. Todo esto nos lleva a que $\textrm{mcd}((p-1)!, p) = 1$, y por [[Proposición divisibilidad de un producto]] (si $a|bc$ y $\textrm{mcd}(a,b) = 1$, entonces $a|c$) $p|a^{p-1}-1$ y en consecuencia $a^{p-1} \equiv 1 \pmod p$. Y el segundo resultado queda demostrado.

Ahora si $p \nmid a$, por el resultado anterior $a^{p-1} \equiv 1 \pmod p$. Multiplicando por $a$ se obtiene $a^p \equiv a \pmod p$.
Si $p | a$ entonces $a \equiv 0 \pmod p$, luego $a^p \equiv 0^p \pmod p$, y por tanto $a^p \equiv 0 \pmod 0$ y $a^p \equiv a \pmod p$.
Tags: demostración MatDiscreta
<!--ID: 1717176517306-->
END