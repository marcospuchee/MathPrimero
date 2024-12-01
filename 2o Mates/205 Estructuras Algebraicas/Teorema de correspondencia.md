### Contenido Principal

```ad-theorem
Sea $G$ un grupo y $N \unlhd G$. Entonces la aplicación
$$\begin{array}{c c c c}
(\cdot)^*: & \{H : N \le H \le G \} & \to & \{H^* : H^* \le G/N \} \\
& H & \mapsto & H/N
\end{array}$$
Además, si $N \le H,K \le G$,
1. $K \le H \iff K^* \le H^*$.
2. $K \unlhd H \iff K^* \unlhd H^*$. Además, $H/K \cong H^* / K^*$.
```

^dfe652

```ad-proof
Para simplificar notación, para $N \le X \le G$, escribiremos $X^* = X /N$.

En primer lugar notamos que
$$X^* = X/N = \{xN : x \in X \} = \{\pi(x) : x \in X \} = \pi(X) \le G/N,$$
donde $\pi: G \to G/N$ con $g \mapsto gN$ es el homomorfismo proyección (sobreyectivo). Por tanto, $(\cdot)^*$ está bien definida.

**Inyectividad:** sean $N \le H, K \le G$ tales que $H^*  = K^*$. Vemos que $H = K$.
$\subseteq$. Sea $h \in H$. Demostramos que $h \in K$. Como $h \in H$, entonces $hN \in H^* = K^*$. Por tanto, $\exists k \in K$ tal que $hN = kN$. Así, $k^{-1}h \in N \le K$. Por tanto, como $k \in K$ y $k^{-1}h \in K$, tenemos que $h = k(k^{-1}h) \in K$.
$\supseteq$. Similar.

**Sobreyectividad:** sea $Y \le G/N$, demostramos que $\exists N \le X \le G$ tal que $X^* = Y$. Consideramos $X = \pi^{-1}(Y) = \{g \in G : \pi(g) \in Y\}$. Demostramos que: $X \le G$, $N \le X$ y $X^* = Y$.
1. Como $Y \le G/N$ y $\pi: G \to G/N$ es homomorfismo, entonces $\pi^{-1}(Y) \le G$.
2. Sea $n \in N$. Vemos que $n \in \pi^{-1}(Y)$, esto es, $\pi(n) \in Y$. Notamos que $\pi(n)$ $=$ $nN$ $=$ $N$ $=$ $1_{G/N} \in Y$ por ser $Y \le G/N$.
3. Tenemos que:
$$\begin{eqnarray}
\pi^{-1}(Y)^* &=& \pi(\pi^{-1}(Y)) = \{\pi(x) : x \in \pi^{-1}(Y) \} = \{\pi(x) : \pi(x) \in Y \} \\
&=&  \{xN : xN \in Y \} = Y
\end{eqnarray}$$
En particular, para un subgrupo $Y \le G/N$ su preimagen es $\pi^{-1}(Y)$.



Falta demostrar que:
- $K \le H \iff K^* \le H^*$.
$\Rightarrow$. Suponemos que $K \le H$. Como $\pi: G \to G/N$ es homomorfismo, 
$$K^* = \pi(K) \le \pi(H) = H^*.$$
$\Leftarrow$. Suponemos que $K^* \le H^*$. Como $\pi: G \to G/N$ es homomorfismo,
$$K = \pi^{-1}(K^*) \le \pi^{-1}(H^*) = H.$$

- $K \unlhd H \iff K^* \unlhd H^*$.
$\Rightarrow$. Suponemos que $K \unlhd H$. Como $\pi : G \to G/N$ homomorfismo sobreyectivo,
$$K^* = \pi(K) \unlhd \pi(H) = H^*.$$
$\Leftarrow$. Suponemos que $K^* \unlhd H^*$. Como $\pi:G \to G/N$ homomorfismo,
$$K = \pi^{-1}(K^*) \unlhd \pi^{-1}(H^*) = H$$

- El isomorfismo $H/K \cong H^*/K^*$ es el tercer teorema de isomorfía.

```


**Tema:** [[Teoría de grupos#16. Teorema de correspondencia.]]
**Corolario:**

**Definiciones referenciadas:**
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Teorema de correspondencia
Reverso: Sea $G$ un grupo y $N \unlhd G$. Entonces la aplicación
$$\begin{array}{c c c c}
(\cdot)^*: & \{H : N \le H \le G \} & \to & \{H^* : H^* \le G/N \} \\
& H & \mapsto & H/N
\end{array}$$
Además, si $N \le H,K \le G$,
1. $K \le H \iff K^* \le H^*$.
2. $K \unlhd H \iff K^* \unlhd H^*$. Además, $H/K \cong H^* / K^*$.
Tags: est
<!--ID: 1731446305183-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo y $N \unlhd G$. Entonces la aplicación
$$\begin{array}{c c c c}
(\cdot)^*: & \{H : N \le H \le G \} & \to & \{H^* : H^* \le G/N \} \\
& H & \mapsto & H/N
\end{array}$$
Además, si $N \le H,K \le G$,
1. $K \le H \iff K^* \le H^*$.
2. $K \unlhd H \iff K^* \unlhd H^*$. Además, $H/K \cong H^* / K^*$.
Reverso: Para simplificar notación, para $N \le X \le G$, escribiremos $X^* = X /N$.

En primer lugar notamos que
$$X^* = X/N = \{xN : x \in X \} = \{\pi(x) : x \in X \} = \pi(X) \le G/N,$$
donde $\pi: G \to G/N$ con $g \mapsto gN$ es el homomorfismo proyección (sobreyectivo). Por tanto, $(\cdot)^*$ está bien definida.

**Inyectividad:** sean $N \le H, K \le G$ tales que $H^*  = K^*$. Vemos que $H = K$.
$\subseteq$. Sea $h \in H$. Demostramos que $h \in K$. Como $h \in H$, entonces $hN \in H^* = K^*$. Por tanto, $\exists k \in K$ tal que $hN = kN$. Así, $k^{-1}h \in N \le K$. Por tanto, como $k \in K$ y $k^{-1}h \in K$, tenemos que $h = k(k^{-1}h) \in K$.
$\supseteq$. Similar.

**Sobreyectividad:** sea $Y \le G/N$, demostramos que $\exists N \le X \le G$ tal que $X^* = Y$. Consideramos $X = \pi^{-1}(Y) = \{g \in G : \pi(g) \in Y\}$. Demostramos que: $X \le G$, $N \le X$ y $X^* = Y$.
1. Como $Y \le G/N$ y $\pi: G \to G/N$ es homomorfismo, entonces $\pi^{-1}(Y) \le G$.
2. Sea $n \in N$. Vemos que $n \in \pi^{-1}(Y)$, esto es, $\pi(n) \in Y$. Notamos que $\pi(n)$ $=$ $nN$ $=$ $N$ $=$ $1_{G/N} \in Y$ por ser $Y \le G/N$.
3. Tenemos que:
$$\begin{eqnarray}
\pi^{-1}(Y)^* &=& \pi(\pi^{-1}(Y)) = \{\pi(x) : x \in \pi^{-1}(Y) \} = \{\pi(x) : \pi(x) \in Y \} \\
&=&  \{xN : xN \in Y \} = Y
\end{eqnarray}$$
En particular, para un subgrupo $Y \le G/N$ su preimagen es $\pi^{-1}(Y)$.



Falta demostrar que:
- $K \le H \iff K^* \le H^*$.
$\Rightarrow$. Suponemos que $K \le H$. Como $\pi: G \to G/N$ es homomorfismo, 
$$K^* = \pi(K) \le \pi(H) = H^*.$$
$\Leftarrow$. Suponemos que $K^* \le H^*$. Como $\pi: G \to G/N$ es homomorfismo,
$$K = \pi^{-1}(K^*) \le \pi^{-1}(H^*) = H.$$

- $K \unlhd H \iff K^* \unlhd H^*$.
$\Rightarrow$. Suponemos que $K \unlhd H$. Como $\pi : G \to G/N$ homomorfismo sobreyectivo,
$$K^* = \pi(K) \unlhd \pi(H) = H^*.$$
$\Leftarrow$. Suponemos que $K^* \unlhd H^*$. Como $\pi:G \to G/N$ homomorfismo,
$$K = \pi^{-1}(K^*) \unlhd \pi^{-1}(H^*) = H$$

- El isomorfismo $H/K \cong H^*/K^*$ es el tercer teorema de isomorfía.
Tags: est dem
<!--ID: 1731446305195-->
END
