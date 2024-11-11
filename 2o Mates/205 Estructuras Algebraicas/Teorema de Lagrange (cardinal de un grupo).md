### Contenido Principal


```ad-theorem
Sea $G$ un [[grupo]] finito y $H \le G$. Entonces
$$|G| = |H||G: H|.$$
```

^f49735

```ad-proof
Como $G = \bigcup_{x \in G} \{x\}$, $\mathcal L_H$ es una partición, $G$ finito, entonces podemos definir $\mathcal L_H = \{x_1H_1, x_2H_2, \dots, x_nH_n\}$, donde $n = |\mathcal L_H| = |G:H|$ porque $G$ finito.

Como $G = \bigcup_{x \in G} xH = \dot{\bigcup}_{i = 1}^n x_i H$, entonces,
$$|G| = |x_1H| + |x_2H| + \dots + |x_nH|.$$
Veamos que $|x_iH| = |H|$: tenemos que $x_iH = \{x_ih \, | \, h \in H \} = L_{x_i}(H)$, donde $L_{x_i}: G \to G$ con $x \to x_i * x$. Por ser esta función biyectiva, $|H| = |Lx_i(H)| = |x_iH|$.

Así, tenemos que
$$|G| = n|H| = |H||G:H|.$$
```

**Tema:** [[Teoría de grupos#6. Teorema de Lagrange.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Teorema de Lagrange sobre el cardinal de un grupo a partir del subíndice de un subgrupo suyo
Reverso: Sea $G$ un [[Grupo]] finito y $H \le G$. Entonces
$$|G| = |H||G: H|.$$
<!--ID: 1727339263707-->
END

START
Básico
Anverso: Demostración de que sea $G$ un [[Grupo]] finito y $H \le G$. Entonces
$$|G| = |H||G: H|.$$
Reverso: Como $G = \bigcup_{x \in G} \{x\}$, $\mathcal L_H$ es una partición, $G$ finito, entonces podemos definir $\mathcal L_H = \{x_1H_1, x_2H_2, \dots, x_nH_n\}$, donde $n = |\mathcal L_H| = |G:H|$ porque $G$ finito.

Como $G = \bigcup_{x \in G} xH = \dot{\bigcup}_{i = 1}^n x_i H$, entonces,
$$|G| = |x_1H| + |x_2H| + \dots + |x_nH|.$$
Veamos que $|x_iH| = |H|$: tenemos que $x_iH = \{x_ih \, | \, h \in H \} = L_{x_i}(H)$, donde $L_{x_i}: G \to G$ con $x \to x_i * x$. Por ser esta función biyectiva, $|H| = |Lx_i(H)| = |x_iH|$.

Así, tenemos que
$$|G| = n|H| = |H||G:H|.$$
Tags: dem est
<!--ID: 1727339263710-->
END
