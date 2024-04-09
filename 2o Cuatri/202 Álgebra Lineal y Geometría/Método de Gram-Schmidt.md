
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-03-27, 17:28

```ad-theorem
Sea $V$ un $\mathbb R$-espacio vectorial (de dimensión $\dim V = n$), y sea $B = \{v_1, \dots, v_n\}$ base de $V$. Entonces $\exists B' = \{e_1, \dots, e_n\}$ [[Base ortonormal]] de $V$ tal que
$$\langle v_1, \dots, v_k \rangle = \langle e_1, \dots, e_k \rangle, \quad \forall k = 1, \dots, n.$$
```

```ad-proof
Tomamos $u_1 = v_1$. Supongamos que tenemos $u_1, \dots, u_{k-1} \in V$ ortogonales entre sí, y tales que $\langle u_1, \dots, u_{k-1} \rangle = \langle v_1, \dots, v_{k-1} \rangle$. Consideramos:
$$u_k := v_k - \frac{v_k · u_1}{||u_1||^2}u_1 - \frac{v_k · u_2}{||u_2||^2} u_2 - \dots - \frac{v_k · u_{k-1}}{||u_{k-1}||^2} u_{k-1} \in \langle v_k, u_1, \dots, u_{k-1} \rangle \subseteq \langle v_1, v_2, \dots, v_k \rangle.$$
Veamos que $u_k · u_j = 0, \forall i = 1, \dots, k-1$. Tenemos:
$$u_k · u_j = v_k · u_j - (\sum_{i = 1}^{k-1} \frac{v_k · u_i}{||u_1i||^2} u_i) u_j = v_k · u_j - \frac{v_k · u_j}{||u_j||^2} · u_j u_j = 0.$$
La razón por la que el sumatorio desaparece es porque $i \neq j \implies u_i · u_j$. Luego hemos visto que $\{u_1, \dots, u_{k-1}, u_k\}$ es ortogonal ([[Conjunto F-ortogonal]]). 

Notemos que $\{u_1, \dots, u_{k-1}\}$ es linealmente independiente, ya que $\dim \langle u_1, \dots, u_{k-1} \rangle = \dim \langle v_1, \dots, v_{k-1} \rangle = k-1$. Luego $u_j \neq 0, \forall j = 1, \dots, k-1$. Además, $u_k \neq 0$. Efectivamente, encontramos la siguiente contradicción:
$$u_k = 0 \implies v_k = \sum_{i = 1}^{k-1} \frac{v_k · u_i}{||u_i||^2} u_1 \in \langle u_1, \dots, u_{k-1} \rangle = \langle v_1, \dots, v_{k-1} \rangle,$$
lo cual es una contradicción porque $B$ es base. Por el [[Lema vectores ortogonales son linealmente independientes]], deducimos que $\{u_1, \dots, u_{k-1}, u_k\}$ es linealmente independiente. Además, por construcción, $\langle u_1, \dots, u_k \rangle \subseteq \langle v_1, \dots, v_k \rangle \implies$ $\langle u_1, \dots, u_k \rangle = \langle v_1, \dots, v_k \rangle$, dado que sus dimensiones son iguales ([[Prop 5. EV]]).

Después de un número finito de pasos, obtenemos una base ortogonal $\{u_1, \dots, u_n\}$ de $V$ tal que $\langle u_1, \dots, u_k \rangle = \langle v_1, \dots, v_k \rangle$, $\forall k = 1, \dots, n$.

Finalmente, si definimos $e_j = \frac{u_j}{||u_j||}, \forall j = 1, \dots, n$, entonces $B' = \{e_1, \dots, e_n\}$ es base ortonormal de $V$ y $\langle e_1, \dots, e_k \rangle = \langle v_1, \dots, v_k \rangle, \forall k = 1, \dots, n$.
```


**Tema:** [[Espacios vectoriales euclídeos]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Básico
Anverso: Qué dice el método de Gram-Schmidt?
Reverso: Sea $V$ un $\mathbb R$-espacio vectorial (de dimensión $\dim V = n$), y sea $B = \{v_1, \dots, v_n\}$ base de $V$. Entonces $\exists B' = \{e_1, \dots, e_n\}$ [[Base ortonormal]] de $V$ tal que
$$\langle v_1, \dots, v_k \rangle = \langle e_1, \dots, e_k \rangle, \quad \forall k = 1, \dots, n.$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1712235233599-->
END

START
Básico
Anverso: Demostración del método de Gram-Schmidt
Reverso: Tomamos $u_1 = v_1$. Supongamos que tenemos $u_1, \dots, u_{k-1} \in V$ ortogonales entre sí, y tales que $\langle u_1, \dots, u_{k-1} \rangle = \langle v_1, \dots, v_{k-1} \rangle$. Consideramos:
$$u_k := v_k - \frac{v_k · u_1}{||u_1||^2}u_1 - \frac{v_k · u_2}{||u_2||^2} u_2 - \dots - \frac{v_k · u_{k-1}}{||u_{k-1}||^2} u_{k-1} \in \langle v_k, u_1, \dots, u_{k-1} \rangle \subseteq \langle v_1, v_2, \dots, v_k \rangle.$$
Veamos que $u_k · u_j = 0, \forall i = 1, \dots, k-1$. Tenemos:
$$u_k · u_j = v_k · u_j - (\sum_{i = 1}^{k-1} \frac{v_k · u_i}{||u_1i||^2} u_i) u_j = v_k · u_j - \frac{v_k · u_j}{||u_j||^2} · u_j u_j = 0.$$
La razón por la que el sumatorio desaparece es porque $i \neq j \implies u_i · u_j$. Luego hemos visto que $\{u_1, \dots, u_{k-1}, u_k\}$ es ortogonal ([[Conjunto F-ortogonal]]). 

Notemos que $\{u_1, \dots, u_{k-1}\}$ es linealmente independiente, ya que $\dim \langle u_1, \dots, u_{k-1} \rangle = \dim \langle v_1, \dots, v_{k-1} \rangle = k-1$. Luego $u_j \neq 0, \forall j = 1, \dots, k-1$. Además, $u_k \neq 0$. Efectivamente, encontramos la siguiente contradicción:
$$u_k = 0 \implies v_k = \sum_{i = 1}^{k-1} \frac{v_k · u_i}{||u_i||^2} u_1 \in \langle u_1, \dots, u_{k-1} \rangle = \langle v_1, \dots, v_{k-1} \rangle,$$
lo cual es una contradicción porque $B$ es base. Por el [[Lema vectores ortogonales son linealmente independientes]], deducimos que $\{u_1, \dots, u_{k-1}, u_k\}$ es linealmente independiente. Además, por construcción, $\langle u_1, \dots, u_k \rangle \subseteq \langle v_1, \dots, v_k \rangle \implies$ $\langle u_1, \dots, u_k \rangle = \langle v_1, \dots, v_k \rangle$, dado que sus dimensiones son iguales ([[Prop 5. EV]]).

Después de un número finito de pasos, obtenemos una base ortogonal $\{u_1, \dots, u_n\}$ de $V$ tal que $\langle u_1, \dots, u_k \rangle = \langle v_1, \dots, v_k \rangle$, $\forall k = 1, \dots, n$.

Finalmente, si definimos $e_j = \frac{u_j}{||u_j||}, \forall j = 1, \dots, n$, entonces $B' = \{e_1, \dots, e_n\}$ es base ortonormal de $V$ y $\langle e_1, \dots, e_k \rangle = \langle v_1, \dots, v_k \rangle, \forall k = 1, \dots, n$.
Tags: demostración ÁlgebraI
<!--ID: 1712235233611-->
END

