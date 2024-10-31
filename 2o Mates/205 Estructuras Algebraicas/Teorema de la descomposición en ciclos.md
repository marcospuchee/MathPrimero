### Contenido Principal


```ad-theorem
Sea $X \neq \emptyset$ finito y $\sigma \in S_X$. Entonces $\exists c_1, c_2, \dots, c_r \in S_X$ ([[r-ciclo]]) disjuntos ([[permutaciones disjuntas]]) tales que
$$\sigma = c_1 \circ c_2 \circ \dots \circ c_r.$$
Además, esta descomposición es única salvo el orden.
```

^4e6fc9

```ad-proof
Vamos a proceder por inducción fuerte sobre $|X|$.

**Caso base: $|X| = 1$.** Entonces $\sigma = id_X = (x_1)$.

**Paso inductivo.**
- Existencia. $\sigma \in S_X$, $X = \{x_1, \dots, x_n\}$. El conjunto $\{x_1, \sigma(x_1), \sigma^2(x_1), \dots\} \subseteq X$, por tanto es finito. Esto implica que $\exists r \in \mathbb N$ mínimo tal que $\sigma^{r+1}(x_1) \in \{x_1, \sigma(x_1), \dots, \sigma^r(x_1)\}$. Queremos demostrar que $\sigma^{r+1}(x_1) = x_1$. Supongamos que $\sigma^{r+1}(x_1) = \sigma^i(x_1)$ para algún $1 \le i \le r$. Entonces, $\sigma(\sigma^r(x_1)) = \sigma(\sigma^{i-1}(x_1))$, luego como $\sigma$ es biyectiva, $\sigma^r (x_1) = \sigma^{i-1}(x)$, lo cual es una contradicción porque $r$ era mínimo.
Entonces, $\sigma^{r+1}(x_1) = x_1$ y, denotando $Y = \{x_1, \sigma(x_1), \dots, \sigma^{r}(x_1)\}$, podemos definir $\sigma_{\restriction Y} = (x_1, \sigma(x_1), \dots, \sigma^r(x_1)) = c_1$.
Como $\sigma_{\restriction X \textrm{\\} Y} \in S_{X \textrm{\\} Y}$, podemos aplicar la hipótesis inductiva y $\sigma_{X \textrm{\\} Y} = c_2 \circ c_3 \circ \dots \circ c_r$. Por tanto, $\sigma = c_1 \circ c_2 \circ \dots \circ c_r$.
- Unicidad: supongamos que $\sigma = c_1 \circ \dots \circ c_n = d_1 \circ \dots \circ d_s$. Sea $x_1 \in X$. Como los $r$-ciclos son disjuntos entre sí, $\exists 1 \le 1 \le n$ tal que $x_1 \in c_i$ y $\exists 1 \le j \le s$ tal que $x_1 \in d_j$. Podemos asumir sin pérdida de generalidad que $x_1 \in c_1$ y $x_1 \in d_1$. Entonces, $c_1 = (x_1, \sigma(x_1), \dots, \sigma^r(x_1)) = d_1$. Por tanto, $c_2 \circ \dots \circ c_n = d_2 \circ \dots \circ d_s$ por hipótesis de inducción, y $n=s$ y $c_2 = d_2, \dots, c_n = d_s$.
```

**Tema:** [[Teoría de grupos#3. Estructura de ciclos.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la descomposición en ciclos?
Reverso: Sea $X \neq \emptyset$ finito y $\sigma \in S_X$. Entonces $\exists c_1, c_2, \dots, c_r \in S_X$ ([[r-ciclo]]) disjuntos ([[permutaciones disjuntas]]) tales que
$$\sigma = c_1 \circ c_2 \circ \dots \circ c_r.$$
Además, esta descomposición es única salvo el orden.
Tags: 
<!--ID: 1727083427903-->
END

START
Básico
Anverso: Demostración de que sea $X \neq \emptyset$ finito y $\sigma \in S_X$. Entonces $\exists c_1, c_2, \dots, c_r \in S_X$ ([[r-ciclo]]) disjuntos ([[permutaciones disjuntas]]) tales que
$$\sigma = c_1 \circ c_2 \circ \dots \circ c_r.$$
Además, esta descomposición es única salvo el orden.
Reverso: Vamos a proceder por inducción fuerte sobre $|X|$.

**Caso base: $|X| = 1$.** Entonces $\sigma = id_X = (x_1)$.

**Paso inductivo.**
- Existencia. $\sigma \in S_X$, $X = \{x_1, \dots, x_n\}$. El conjunto $\{x_1, \sigma(x_1), \sigma^2(x_1), \dots\} \subseteq X$, por tanto es finito. Esto implica que $\exists r \in \mathbb N$ mínimo tal que $\sigma^{r+1}(x_1) \in \{x_1, \sigma(x_1), \dots, \sigma^r(x_1)\}$. Queremos demostrar que $\sigma^{r+1}(x_1) = x_1$. Supongamos que $\sigma^{r+1}(x_1) = \sigma^i(x_1)$ para algún $1 \le i \le r$. Entonces, $\sigma(\sigma^r(x_1)) = \sigma(\sigma^{i-1}(x_1))$, luego como $\sigma$ es biyectiva, $\sigma^r (x_1) = \sigma^{i-1}(x)$, lo cual es una contradicción porque $r$ era mínimo.
Entonces, $\sigma^{r+1}(x_1) = x_1$ y, denotando $Y = \{x_1, \sigma(x_1), \dots, \sigma^{r}(x_1)\}$, podemos definir $\sigma_{\restriction Y} = (x_1, \sigma(x_1), \dots, \sigma^r(x_1)) = c_1$.
Como $\sigma_{\restriction X \textrm{\\} Y} \in S_{X \textrm{\\} Y}$, podemos aplicar la hipótesis inductiva y $\sigma_{X \textrm{\\} Y} = c_2 \circ c_3 \circ \dots \circ c_r$. Por tanto, $\sigma = c_1 \circ c_2 \circ \dots \circ c_r$.
- Unicidad: supongamos que $\sigma = c_1 \circ \dots \circ c_n = d_1 \circ \dots \circ d_s$. Sea $x_1 \in X$. Como los $r$-ciclos son disjuntos entre sí, $\exists 1 \le 1 \le n$ tal que $x_1 \in c_i$ y $\exists 1 \le j \le s$ tal que $x_1 \in d_j$. Podemos asumir sin pérdida de generalidad que $x_1 \in c_1$ y $x_1 \in d_1$. Entonces, $c_1 = (x_1, \sigma(x_1), \dots, \sigma^r(x_1)) = d_1$. Por tanto, $c_2 \circ \dots \circ c_n = d_2 \circ \dots \circ d_s$ por hipótesis de inducción, y $n=s$ y $c_2 = d_2, \dots, c_n = d_s$.
Tags: dem est
<!--ID: 1727083427905-->
END
