### Contenido Principal

```ad-theorem
Sean $\Omega \subseteq \mathbb R^n$ abierto, $f,g_1, \dots, g_m: \Omega \longrightarrow \mathbb R^m$ de clase $C^1$, donde $1 \le m < n$. Supongamos que $M = \{x \in \Omega : g_1(x) = 0, \dots, g_m(x) = 0 \}$ es una variedad diferenciable de dimensión $n-m$. Si $a$ es un extremo local de $f$ condicionado a $M$, entonces $\exists \lambda_1, \dots, \lambda_m \in \mathbb R$ tales que $$\nabla f(a) = \lambda_1 \nabla g_1(a) + \dots + \lambda_m \nabla g_m(a).$$
```

```ad-proof
Sea $a \in M$, supongamos que $f$ tiene un máximo local condicionado a $M$ en $a$, entonces $\exists W$ entorno abierto de $a$ tal que $f(x) \le f(a)$, $\forall x \in W \cap M$. Recordemos que $g = (g_1, \dots, g_m)$ es de clase $C^1$. Como $M$ variedad, entonces $g'(a)$ tiene rango máximo $m$. Supongamos que son las últimas columnas de $g'(x)$ las que son linealmente independientes. Definimos $k = n-m$, y sabemos que $$\det \left ( \frac{\partial g_i}{\partial x_{k+j}} \right )_{1 \le i,j \le m} \neq 0.$$
Aplicamos el teorema de la función implícita, entonces $\exists U$ entorno abierto de $a$ y $V$ entorno abierto de $\tilde a = (a_1, \dots, a_k)$ y $\phi: V \longrightarrow \mathbb R^m$ $C^1$ tal que $\phi(a_1, \dots, a_n) = (a_{k+1}, \dots, a_m)$ y $$U \cap M = \{x \in U : g(x) = 0 \} = \{(x_1, \dots, x_k, \phi(x_1, \dots, x_k)) : (x_1, \dots, x_k) \in V \}.$$ Notemos que como $U \cap M \subseteq W \cap M$, entonces $$f(x_1, \dots, x_k, \phi(x_1, \dots, x_k)) \le f(a) = f(a_1, \dots, a_k, \phi(a_1, \dots, a_k)),$$ $\forall (x_1, \dots, x_k) \in V$.

Consideramos la función $$\begin{array}{c r c l}
h: & V & \longrightarrow & \mathbb R \\
& (x_1, \dots, x_k) & \longmapsto & f(x_1, \dots, x_k, \phi(x_1, \dots, x_k)), \end{array}$$ que es de clase $C^1$. $h$ tiene un máximo relativo en $\tilde a = (a_1, \dots, a_k)$, luego $\nabla h(\tilde a) = 0$. Aplicando la regla de la cadena, tenemos que
$$\nabla h(\tilde a) = \nabla f(a) \cdot 
\begin{pmatrix}  1  & 0 & \dots & 0 \\ 0 & 1 & \dots & 0 \\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & 1 \\  \frac{\partial \phi_1}{\partial x_1}(\tilde a) & \frac{\partial \phi_1}{\partial x_2}(\tilde a) & \dots & \frac{\phi_1}{\partial x_k}(\tilde a) \\ \vdots & \vdots & & \vdots \\ \frac{\partial \phi_m}{\partial x_1}(\tilde a) & \frac{\partial \phi_m}{\partial x_2}(\tilde a) & \dots & \frac{\partial \phi_m}{\partial x_k}(\tilde a) \end{pmatrix},$$ 
donde podemos llamar a cada columna $u_i$, $\forall i =1, \dots, k$. Por tanto, $\nabla f(a)$ es ortogonal al subespacio $H$ generado por los vectores $u_1, \dots, u_k$, que son linealmente independientes. Así, $H$ es de dimensión $k$. Además, $g(x_1, \dots, x_k, \phi(x_1, \dots, x_k)) = 0$, $\forall (x_1, \dots, x_k) \in V$, $\forall i = 1, \dots, m$, luego $\nabla g_1(a), \dots, \nabla g_m(a)$ son ortogonales a $H$, y la dimensión del ortogonal de $H$ es $n-k = m$, lo que implica que $\{\nabla g_1(a), \dots, \nabla g_m(a) \}$ forman una base del ortogonal de $H$.

Como $\nabla f(a)$ está en el ortogonal de $H$, $\exists \lambda_1, \dots, \lambda_n \in \mathbb R$ tales que $$\nabla f(a) = \lambda_1 \nabla g_1(a) + \dots + \lambda_m \nabla g_m(a).$$
```

**Tema:** [[Extremos condicionados y multiplicadores de Lagrange]]

**Definiciones referenciadas:** [$C^1$](Función de clase C1), [[Variedad diferenciable]], [[Extremo condicionado]], [[Vector gradiente]], [[Entorno]], [Subespacio ortogonal](Subespacio ortogonal a un subespacio)
**Resultados referenciados:** [[Teorema de la función implícita]], [Regla de la cadena](Regla de la cadena (Rn))

---
### Anki

START
Básico
Anverso: Teorema de los multiplicadores de Lagrange
Reverso: Sean $\Omega \subseteq \mathbb R^m$ abierto, $f,g_1, \dots, g_m: \Omega \longrightarrow \mathbb R$ de clase $C^1$, donde $1 \le m < n$. Supongamos que $M = \{x \in \Omega : g_1(x) = 0, \dots, g_m(x) = 0 \}$ es una variedad diferenciable de dimensión $n-m$. Si $a$ es un extremo local de $f$ condicionado a $M$, entonces $\exists \lambda_1, \dots, \lambda_m \in \mathbb R$ tales que $$\nabla f(a) = \lambda_1 \nabla g_1(a) + \dots + \lambda_m \nabla g_m(a).$$
Tags: anII
<!--ID: 1734607182718-->
END

START
Básico
Anverso: Sean $\Omega \subseteq \mathbb R^m$ abierto, $f,g_1, \dots, g_m: \Omega \longrightarrow \mathbb R$ de clase $C^1$, donde $1 \le m < n$. Supongamos que $M = \{x \in \Omega : g_1(x) = 0, \dots, g_m(x) = 0 \}$ es una variedad diferenciable de dimensión $n-m$. Si $a$ es un extremo local de $f$ condicionado a $M$, entonces $\exists \lambda_1, \dots, \lambda_m \in \mathbb R$ tales que $$\nabla f(a) = \lambda_1 \nabla g_1(a) + \dots + \lambda_m \nabla g_m(a).$$
Reverso: Sea $a \in M$, supongamos que $f$ tiene un máximo local condicionado a $M$ en $a$, entonces $\exists W$ entorno abierto de $a$ tal que $f(x) \le f(a)$, $\forall x \in W \cap M$. Recordemos que $g = (g_1, \dots, g_m)$ es de clase $C^1$. Como $M$ variedad, entonces $g'(a)$ tiene rango máximo $m$. Supongamos que son las últimas columnas de $g'(x)$ las que son linealmente independientes. Definimos $k = n-m$, y sabemos que $$\det \left ( \frac{\partial g_i}{\partial x_{k+j}} \right )_{1 \le i,j \le m} \neq 0.$$
Aplicamos el teorema de la función implícita, entonces $\exists U$ entorno abierto de $a$ y $V$ entorno abierto de $\tilde a = (a_1, \dots, a_k)$ y $\phi: V \longrightarrow \mathbb R^m$ $C^1$ tal que $\phi(a_1, \dots, a_n) = (a_{k+1}, \dots, a_m)$ y $$U \cap M = \{x \in U : g(x) = 0 \} = \{(x_1, \dots, x_k, \phi(x_1, \dots, x_k)) : (x_1, \dots, x_k) \in V \}.$$ Notemos que como $U \cap M \subseteq W \cap M$, entonces $$f(x_1, \dots, x_k, \phi(x_1, \dots, x_k)) \le f(a) = f(a_1, \dots, a_k, \phi(a_1, \dots, a_k)),$$ $\forall (x_1, \dots, x_k) \in V$.

Consideramos la función $$\begin{array}{c r c l}
h: & V & \longrightarrow & \mathbb R \\
& (x_1, \dots, x_k) & \longmapsto & f(x_1, \dots, x_k, \phi(x_1, \dots, x_k)), \end{array}$$ que es de clase $C^1$. $h$ tiene un máximo relativo en $\tilde a = (a_1, \dots, a_k)$, luego $\nabla h(\tilde a) = 0$. Aplicando la regla de la cadena, tenemos que
$$\nabla h(\tilde a) = \nabla f(a) \cdot 
\begin{pmatrix}  1  & 0 & \dots & 0 \\ 0 & 1 & \dots & 0 \\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & 1 \\  \frac{\partial \phi_1}{\partial x_1}(\tilde a) & \frac{\partial \phi_1}{\partial x_2}(\tilde a) & \dots & \frac{\phi_1}{\partial x_k}(\tilde a) \\ \vdots & \vdots & & \vdots \\ \frac{\partial \phi_m}{\partial x_1}(\tilde a) & \frac{\partial \phi_m}{\partial x_2}(\tilde a) & \dots & \frac{\partial \phi_m}{\partial x_k}(\tilde a) \end{pmatrix},$$ 
donde podemos llamar a cada columna $u_i$, $\forall i =1, \dots, k$. Por tanto, $\nabla f(a)$ es ortogonal al subespacio $H$ generado por los vectores $u_1, \dots, u_k$, que son linealmente independientes. Así, $H$ es de dimensión $k$. Además, $g(x_1, \dots, x_k, \phi(x_1, \dots, x_k)) = 0$, $\forall (x_1, \dots, x_k) \in V$, $\forall i = 1, \dots, m$, luego $\nabla g_1(a), \dots, \nabla g_m(a)$ son ortogonales a $H$, y la dimensión del ortogonal de $H$ es $n-k = m$, lo que implica que $\{\nabla g_1(a), \dots, \nabla g_m(a) \}$ forman una base del ortogonal de $H$.

Como $\nabla f(a)$ está en el ortogonal de $H$, $\exists \lambda_1, \dots, \lambda_n \in \mathbb R$ tales que $$\nabla f(a) = \lambda_1 \nabla g_1(a) + \dots + \lambda_m \nabla g_m(a).$$
Tags: anII dem
<!--ID: 1734607182720-->
END
