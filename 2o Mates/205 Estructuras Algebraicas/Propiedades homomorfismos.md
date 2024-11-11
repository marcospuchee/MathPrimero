### Contenido Principal

```ad-proposition
Sea $f: G \to H$ un [[homomorfismo]]. Entonces
1. $f(1_G) = 1_H$.
2. $\forall x \in G$, $\quad f(x^{-1}) = f(x)^{-1}$.
3. $\forall x \in G, n \in \mathbb Z, \quad f(x^n) = f(x)^n$. En particular,
$$f(\langle x \rangle) = \langle f(x) \rangle.$$
4. $\forall x \in G$, si $x$ tiene orden finito, entonces $o(f(x)) | o(x)$.
```

^0fa7e7

```ad-proof
1. $f(1_G) = f(1_G 1_G) = f(1_G) f(1_G) \implies f(1_G) = 1_H$.
2. $f(x)f(x^{-1}) = f(xx^{-1}) = f(1_G) = 1_H$.
$f(x^{-1}) f(x) = f(x^{-1} x) = f(1_G) = 1_H$.
Así, $f(x)^{-1} = f(x^{-1})$.
3. Por inducción sobre $n$. El caso base está claro. Supongamos el resultado cierto para $n$. Entonces, 
$$f(x^{n+1}) = f(x^n x) = f(x^n)f(x) = f(x)^n f(x) = f(x)^{n+1}.$$
Si $n<0$, utilizamos $(2)$. Además,
$$f(\langle x \rangle) = \{f(x^n) : n \in \mathbb Z \} = \{f(x)^n : n \in \mathbb Z \} = \langle f(x) \rangle.$$
4. $f(x)^{o(x)} = f(x^{o(x)}) = f(1_G) = 1_H$.
```

**Tema:** [[Teoría de grupos#9. Homomorfismos.]]

---
### Anki

START
Básico
Anverso: Propiedades de los homomorfismos
Reverso: Sea $f: G \to H$ un [[Homomorfismo]]. Entonces
1. $f(1_G) = 1_H$.
2. $\forall x \in G$, $\quad f(x^{-1}) = f(x)^{-1}$.
3. $\forall x \in G, n \in \mathbb Z, \quad f(x^n) = f(x)^n$. En particular,
$$f(\langle x \rangle) = \langle f(x) \rangle.$$
4. $\forall x \in G$, si $x$ tiene orden finito, entonces $o(f(x)) | o(x)$.
<!--ID: 1727966477203-->
END

START
Básico
Anverso: Demostración de que sea $f: G \to H$ un [[Homomorfismo]]. Entonces
1. $f(1_G) = 1_H$.
2. $\forall x \in G$, $\quad f(x^{-1}) = f(x)^{-1}$.
3. $\forall x \in G, n \in \mathbb Z, \quad f(x^n) = f(x)^n$. En particular,
$$f(\langle x \rangle) = \langle f(x) \rangle.$$
4. $\forall x \in G$, si $x$ tiene orden finito, entonces $o(f(x)) | o(x)$.
Reverso: 
1. $f(1_G) = f(1_G 1_G) = f(1_G) f(1_G) \implies f(1_G) = 1_H$.
2. $f(x)f(x^{-1}) = f(xx^{-1}) = f(1_G) = 1_H$.
$f(x^{-1}) f(x) = f(x^{-1} x) = f(1_G) = 1_H$.
Así, $f(x)^{-1} = f(x^{-1})$.
3. Por inducción sobre $n$. El caso base está claro. Supongamos el resultado cierto para $n$. Entonces, 
$$f(x^{n+1}) = f(x^n x) = f(x^n)f(x) = f(x)^n f(x) = f(x)^{n+1}.$$
Si $n<0$, utilizamos $(2)$. Además,
$$f(\langle x \rangle) = \{f(x^n) : n \in \mathbb Z \} = \{f(x)^n : n \in \mathbb Z \} = \langle f(x) \rangle.$$
4. $f(x)^{o(x)} = f(x^{o(x)}) = f(1_G) = 1_H$.
Tags: dem est
<!--ID: 1727966477219-->
END
