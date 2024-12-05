### Contenido Principal

```ad-theorem
Sea $G$ un [[grupo abeliano]] y $p \in \mathbb P$ tal que $p \mid |g|$. Entonces $\exists H \le G$ tal que $|H| = p$. 
```

	^09cab8

```ad-proof
Procederemos por inducción sobre $|G|$.

**Caso base: $|G| = 1$.**
Entonces $\not \exists p \in \mathbb P$ tal que $p|1$. Por tanto, la condición se cumple trivialmente.

**Paso inductivo.**
Sea $x \in G \textrm{\\} \{1_G\}$, consideremos $\langle x \rangle \le G$. Por casos:
1. $p \mid |\langle x \rangle |  = o(x) = n$. Por [[grupo cíclico finito tiene un único subgrupo del orden de cada uno de sus divisores]], $\langle x^{n/p} \rangle$ tiene orden $p$. $\langle x^{n/p} \rangle \le \langle x \rangle \le G$.
2. $p \not \mid | \langle x \rangle | = o(x)$. Como $G$ abeliano, $\langle x \rangle \unlhd G$. Consideremos $G/\langle x \rangle$. Notemos que se cumple:
	1. Por [[grupo cociente respeta propiedades]], $G / \langle x \rangle$ es abeliano.
	2. Como $x \neq 1_G$, $| \langle x \rangle | \neq 1$. Por [[teorema de Lagrange (cardinal de un grupo)]], $|G: \langle x \rangle | = |G/\langle x \rangle | = \frac{|G|}{\langle x \rangle } < |G|$.
	3. Como $p \mid |G|$ y $p \not \mid \langle x \rangle$, entonces $p \mid |G/\langle x \rangle | = |G| / | \langle x \rangle |$.
Por hipótesis de inducción, $\exists H' \le G/ \langle x \rangle$ con $|H'| = p \in \mathbb P$. Por [[G grupo de orden primo entonces G es cíclico]], $H'$ es cíclico, entonces, $H' = \langle y \langle x \rangle \rangle$ para algún $y \in G$. Pero notemos que:
$$(y \langle x \rangle)^{o(y)} = y^{o(y)} \langle x \rangle = 1_G \langle x \rangle = 1_{G/ \langle x \rangle}.$$
Por [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], entonces $o(y \langle x \rangle) \mid o(y)$, pero como
$$o(y\langle x \rangle) = | \langle y \langle x \rangle \rangle| = |H'| = p,$$ 
entonces concluimos como en el primer paso
```

**Tema:** [[Teoría de grupos#12. Grupos cociente.]]
**Generalización:** [[Teorema de Cauchy generalizado]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Cauchy para grupos abelianos
Reverso: Sea $G$ un [[Grupo abeliano]] y $p \in \mathbb P$ tal que $p \mid |g|$. Entonces $\exists H \le G$ tal que $|H| = p$.
Tags: est
<!--ID: 1729160606408-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo abeliano]] y $p \in \mathbb P$ tal que $p \mid |g|$. Entonces $\exists H \le G$ tal que $|H| = p$.
Reverso: Procederemos por inducción sobre $|G|$.

**Caso base: $|G| = 1$.**
Entonces $\not \exists p \in \mathbb P$ tal que $p|1$. Por tanto, la condición se cumple trivialmente.

**Paso inductivo.**
Sea $x \in G \textrm{\\} \{1_G\}$, consideremos $\langle x \rangle \le G$. Por casos:
1. $p \mid |\langle x \rangle |  = o(x) = n$. Por [[grupo cíclico finito tiene un único subgrupo del orden de cada uno de sus divisores]], $\langle x^{n/p} \rangle$ tiene orden $p$. $\langle x^{n/p} \rangle \le \langle x \rangle \le G$.
2. $p \not \mid | \langle x \rangle | = o(x)$. Como $G$ abeliano, $\langle x \rangle \unlhd G$. Consideremos $G/\langle x \rangle$. Notemos que se cumple:
	1. Por [[grupo cociente respeta propiedades]], $G / \langle x \rangle$ es abeliano.
	2. Como $x \neq 1_G$, $| \langle x \rangle | \neq 1$. Por [[teorema de Lagrange (cardinal de un grupo)]], $|G: \langle x \rangle | = |G/\langle x \rangle | = \frac{|G|}{\langle x \rangle } < |G|$.
	3. Como $p \mid |G|$ y $p \not \mid \langle x \rangle$, entonces $p \mid |G/\langle x \rangle | = |G| / | \langle x \rangle |$.
Por hipótesis de inducción, $\exists H' \le G/ \langle x \rangle$ con $|H'| = p \in \mathbb P$. Por [[G grupo de orden primo entonces G es cíclico]], $H'$ es cíclico, entonces, $H' = \langle y \langle x \rangle \rangle$ para algún $y \in G$. Pero notemos que:
$$(y \langle x \rangle)^{o(y)} = y^{o(y)} \langle x \rangle = 1_G \langle x \rangle = 1_{G/ \langle x \rangle}.$$
Por [[exponente de un elemento de un grupo es neutro sii su orden divide al exponente]], entonces $o(y \langle x \rangle) \mid o(y)$, pero como
$$o(y\langle x \rangle) = | \langle y \langle x \rangle \rangle| = |H'| = p,$$ 
entonces concluimos como en el primer paso
Tags: dem est
<!--ID: 1729160606410-->
END

