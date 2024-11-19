### Contenido Principal

```ad-theorem
Sea $G$ un grupo finito, $p \in \mathbb P$ y $k \in \mathbb N$. Si $p^k \mid |G|$, entonces $\exists H \le G$ tal que $|H|=p^k$.
```

```ad-proof
Por inducción fuerte sobre $|G|$.

**Caso base:** $|G| = 1$.
Notamos que si $p^k \mid |G| = 1$, entonces $k = 0$ y podemos considerar $H = 1 \le G$ con $|1| = 1 = p^0$.

**Hipótesis inductiva.**
Suponemos que para todo grupo $G'$ con $|G'| < |G|$, para todo $p \in \mathbb P$ y todo $k \in \mathbb N$, si $p^k \mid |G'|$, entonces $\exists H' \le G'$ con $|H'| = p^k$. Demostramos el resultado para $G:$ para el caso $k = 0$, entonces cogemos $H = 1 \le G$. Si $k > 0$, distinguimos dos casos:
1. Suponemos que $\exists K < G$ con $p^k \mid |K|$. Entonces, por hipótesis de inducción, sabemos que $\exists H \le K < G$ con $|H| = p^k$.
2. Suponemos que $\forall K < G$, $p ^k \nmid |K|$. Por la ecuación de las clases, $\exists x_{t+1}, \dots, x_n \in G \textrm{\\} Z(G)$ tales que
$$|G| = |Z(G)| + \sum_{i = t+1}^n |G: C_G(x_i)|.$$
Notemos que $\forall t+1 \le i \le n$, como $x_i \notin Z(G)$, $C_G(x_i) < G$ (es subgrupo estricto). En particular, $p^k \nmid |C_G(x_i)|$. Sin embargo, como
$$p^k \mid |G| = |C_G(x_i)| \, |G: C_G(x_i)|,$$
entonces $p \mid |G: C_G(x_i)|$, $\forall t+1 \le i \le n$. Además, como $k > 0$, $p \mid p^k \mid |G|$. Así, $p \mid |G| - \sum_{i = t+1}^n |G:C_G(x_i)| = |Z(G)|$. Por el teorema de Cauchy para grupos abelianos, $\exists N \le Z(G)$ con $|N| = p$. Además, $N \unlhd G$. Consideramos $G' = G/N$ y notamos que: $|G'| = |G/N| = |G|/p < |G|$ y, por otro lado, $p^k \mid |G|$ $\implies$ $p^{k-1} \mid |G'| = |G|/p$.
Por tanto, por hipótesis de inducción, $\exists H' \le G/N$ con $|H'| = p^{k-1}$. Por el teorema de correspondencia, $H' = H/N$ para algún $N \le H \le G$. Así,
$$p^{k-1} = |H'| = |H/N| = |H|/p \quad \land \quad |H| = p^k.$$
```

**Tema:** [[Teorema de Sylow (referencia)]]
**Corolario:** [$|G| = p^k m$ donde $p \in \mathbb P$ y $p \nmid m \implies \textrm{Syl} \\_ p(G) \neq \emptyset$](Corolario teorema de Cauchy generalizado)

**Definiciones referenciadas:** [$C_G(x)$](Acción por conjugación), [[Grupo cociente]]
**Resultados referenciados:** [[Ecuación de las clases]], [$|G| = |Z(G)| + \sum \\_ {i = t+1}^n |G:C_G(x_i)|$](Ecuación de las clases), [$|G| = |C_G(x_i)| \, |G: C_G(x_i)|$](Teorema de Lagrange (cardinal de un grupo)), [[Teorema de Cauchy para grupos abelianos]], [[Teorema de correspondencia]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de Cauchy generalizado
Reverso: Sea $G$ un grupo finito, $p \in \mathbb P$ y $k \in \mathbb N$. Si $p^k \mid |G|$, entonces $\exists H \le G$ tal que $|H|=p^k$.
Tags: est
<!--ID: 1731931804911-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo finito, $p \in \mathbb P$ y $k \in \mathbb N$. Si $p^k \mid |G|$, entonces $\exists H \le G$ tal que $|H|=p^k$.
Reverso: Por inducción fuerte sobre $|G|$.

**Caso base:** $|G| = 1$.
Notamos que si $p^k \mid |G| = 1$, entonces $k = 0$ y podemos considerar $H = 1 \le G$ con $|1| = 1 = p^0$.

**Hipótesis inductiva.**
Suponemos que para todo grupo $G'$ con $|G'| < |G|$, para todo $p \in \mathbb P$ y todo $k \in \mathbb N$, si $p^k \mid |G'|$, entonces $\exists H' \le G'$ con $|H'| = p^k$. Demostramos el resultado para $G:$ para el caso $k = 0$, entonces cogemos $H = 1 \le G$. Si $k > 0$, distinguimos dos casos:
1. Suponemos que $\exists K < G$ con $p^k \mid |K|$. Entonces, por hipótesis de inducción, sabemos que $\exists H \le K < G$ con $|H| = p^k$.
2. Suponemos que $\forall K < G$, $p ^k \nmid |K|$. Por la ecuación de las clases, $\exists x_{t+1}, \dots, x_n \in G \textrm{\\} Z(G)$ tales que
$$|G| = |Z(G)| + \sum_{i = t+1}^n |G: C_G(x_i)|.$$
Notemos que $\forall t+1 \le i \le n$, como $x_i \notin Z(G)$, $C_G(x_i) < G$ (es subgrupo estricto). En particular, $p^k \nmid |C_G(x_i)|$. Sin embargo, como
$$p^k \mid |G| = |C_G(x_i)| \, |G: C_G(x_i)|,$$
entonces $p \mid |G: C_G(x_i)|$, $\forall t+1 \le i \le n$. Además, como $k > 0$, $p \mid p^k \mid |G|$. Así, $p \mid |G| - \sum_{i = t+1}^n |G:C_G(x_i)| = |Z(G)|$. Por el teorema de Cauchy para grupos abelianos, $\exists N \le Z(G)$ con $|N| = p$. Además, $N \unlhd G$. Consideramos $G' = G/N$ y notamos que: $|G'| = |G/N| = |G|/p < |G|$ y, por otro lado, $p^k \mid |G|$ $\implies$ $p^{k-1} \mid |G'| = |G|/p$.
Por tanto, por hipótesis de inducción, $\exists H' \le G/N$ con $|H'| = p^{k-1}$. Por el teorema de correspondencia, $H' = H/N$ para algún $N \le H \le G$. Así,
$$p^{k-1} = |H'| = |H/N| = |H|/p \quad \land \quad |H| = p^k.$$
Tags: dem est
<!--ID: 1731931804920-->
END

