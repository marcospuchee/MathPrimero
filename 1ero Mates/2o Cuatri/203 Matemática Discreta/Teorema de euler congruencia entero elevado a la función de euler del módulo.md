
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-31, 17:34

```ad-theorem
Sea $a \in \mathbb Z$ tal que $\textrm{mcd}(a,n) = 1$, entonces
$$a^{\Phi (n)} \equiv 1 \pmod n.$$
```

```ad-proof
Sea $R = \{x \in \{1,2, \dots, n-1\}$ tal que $\textrm{mcd}(x,n) = 1 \}$. Notar que $R$ es el grupo de unidades de $\mathbb Z_n$ y que su cardinal es $|R| = \Phi(n)$ ([[función de Euler]]). Construyamos dos conjuntos de clases en $\mathbb Z_n$:
$$C_1 = \{\overline{ax} : x \in \mathbb R \}, \quad C_2 = \{\overline x : x \in \mathbb R \}.$$
Demostramos que ambos conjuntos son iguales, ante todo notemos que tanto $a$ como cualquier $x \in \mathbb R$ son elementos invertibles ([[elemento de congruencia invertible]]) en el anillo $\mathbb Z_n$, y llamemos a estos inversos $a^{-1}$ y $x^{-1}$ respectivamente.

$C_1 \subseteq C_2$: sea $\overline{ax} \in C_1$, entonces podemos elegir como representante de esta clase $y$ entre $0$ y $n-1$, de manera que $ax \equiv y \pmod n$. Multiplicando esta relación por $x^{-1}x^{-1}$ obtenemos $x^{-1} a^{-1} y \equiv 1 \pmod n$, es decir $y$ es invertible por lo que $\textrm{mcd}(y,n) = 1$. Por tanto $y \in R$, esto tanto como decir que $\overline{ax} = \overline y$ por lo que $\overline{ax} \in C_2$.

$C_2 \subseteq C_1$: sea $x \in R$, veamos que $\overline x \in C_1$. Para ello sea $\alpha \in \{0,1, \dots, n-1 \}$ tal que $a^{-1}x \equiv \alpha \pmod n$. Claramente $\alpha$ es invertible ya que $x^{-1}a\alpha \equiv 1 \pmod n$, lo cual nos permite afirmar que $\alpha \in \{0,1,\dots, n-1\}$. Además, $\overline{a\alpha} = \overline x$ por tanto $\overline x \in C_1$. Multiplicando los elementos de ambos conjuntos se obtiene, llamando $P$ al producto de los elementos en $C_2$:
$$a^{\Phi(n)}P \equiv P \pmod n.$$
Como también $P$ es invertible, $a^{\Phi(n)} \equiv 1 \pmod n$. El teorema queda demostrado.
```

**Tema:** [[Aritmética modular#5. Primer teorema de Fermat - Teorema de Euler]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sea $a \in \mathbb Z$ tal que $\textrm{mcd}(a,n) = 1$, entonces
$${{c1::a^{\Phi (n)}}} \equiv {{c2::1 \pmod n}}.$$
Tags: proposición/teorema MatDiscreta
<!--ID: 1717176517172-->
END

START
Básico
Anverso: Demostración de que sea $a \in \mathbb Z$ tal que $\textrm{mcd}(a,n) = 1$, entonces
$$a^{\Phi (n)} \equiv 1 \pmod n.$$
Reverso: Sea $R = \{x \in \{1,2, \dots, n-1\}$ tal que $\textrm{mcd}(x,n) = 1 \}$. Notar que $R$ es el grupo de unidades de $\mathbb Z_n$ y que su cardinal es $|R| = \Phi(n)$ ([[Función de Euler]]). Construyamos dos conjuntos de clases en $\mathbb Z_n$:
$$C_1 = \{\overline{ax} : x \in \mathbb R \}, \quad C_2 = \{\overline x : x \in \mathbb R \}.$$
Demostramos que ambos conjuntos son iguales, ante todo notemos que tanto $a$ como cualquier $x \in \mathbb R$ son elementos invertibles ([[Elemento de congruencia invertible]]) en el anillo $\mathbb Z_n$, y llamemos a estos inversos $a^{-1}$ y $x^{-1}$ respectivamente.

$C_1 \subseteq C_2$: sea $\overline{ax} \in C_1$, entonces podemos elegir como representante de esta clase $y$ entre $0$ y $n-1$, de manera que $ax \equiv y \pmod n$. Multiplicando esta relación por $x^{-1}x^{-1}$ obtenemos $x^{-1} a^{-1} y \equiv 1 \pmod n$, es decir $y$ es invertible por lo que $\textrm{mcd}(y,n) = 1$. Por tanto $y \in R$, esto tanto como decir que $\overline{ax} = \overline y$ por lo que $\overline{ax} \in C_2$.

$C_2 \subseteq C_1$: sea $x \in R$, veamos que $\overline x \in C_1$. Para ello sea $\alpha \in \{0,1, \dots, n-1 \}$ tal que $a^{-1}x \equiv \alpha \pmod n$. Claramente $\alpha$ es invertible ya que $x^{-1}a\alpha \equiv 1 \pmod n$, lo cual nos permite afirmar que $\alpha \in \{0,1,\dots, n-1\}$. Además, $\overline{a\alpha} = \overline x$ por tanto $\overline x \in C_1$. Multiplicando los elementos de ambos conjuntos se obtiene, llamando $P$ al producto de los elementos en $C_2$:
$$a^{\Phi(n)}P \equiv P \pmod n.$$
Como también $P$ es invertible, $a^{\Phi(n)} \equiv 1 \pmod n$. El teorema queda demostrado.
Tags: demostración MatDiscreta
<!--ID: 1717176517177-->
END
