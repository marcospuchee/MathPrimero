### Contenido Principal


```ad-theorem
Sea $\tilde x := (\overline x^T, \tilde x_a^T)^T \in \mathbb R^{n+m}$, con $\tilde x_a = 0_m$, la SBP óptima de $(\tilde P_a)$ obtenida en la fase I ([[(ejercicio) solución óptima de la Fase I]]), y sea $B_a$ la base (de $[A \quad I_m]$) a la que está asociada:
1. Si todas las variables artificiales son no básicas, entonces $B:= B_a$ es una base de $(P)$ y $\overline x$ es una [[solución básica posible]] asociada a $B$.
2. Si $\exists x_k$ artificial en la base, $k \in \mathcal J_{B_a}$, entonces $\exists x_s$ original no básica ($s \in \mathcal J_{N_a}$) tal que $\alpha_{ks} \neq 0$ y
$$B_a' = (B_a \textrm{\\} \{a_k\}) \cup \{a_s \}.$$
también es base de $(\tilde P_a)$ con la misma SBP asociada.
```

```ad-proof
1. Consideremos la descomposición $\tilde x = (\tilde x^T_{B_a}, \tilde x^T_{N_a})^T \in \mathbb R^{m+(m+n-m)}$, con $\tilde x_{N_a} = 0_n$ y
$$\tilde x_{B_a} = B_a^{-1}b \ge 0_m.$$
Como todas las variables artificiales están en $\tilde x_{N_a}$, podemos descomponer $\overline x = (\tilde x_{B_a}^T, 0_n^T) \in \mathbb R^{m+(n-m)}$, que es SBP asociada a $B_a$ por [[punto con términos independientes en las variables artificiales es SBP del problema ampliado]].

2. Razonemos por inducción al absurdo y supongamos que $\alpha_{kj} = 0$ para toda variable original no básica ($j \in \mathcal J_{N_a}$). La $k$-ésima ecuación del sistema
$$x_{B_a} + B_a^{-1}N_a x_{N_a} = B_a^{-1}b$$
resulta
$$(*) \quad x_k + \sum_{j \in \mathcal J_{N_a}} \alpha_{kj} x_j = 0.$$
Si volvemos al conjunto factible original de $(P)$ (eliminando las variables artificiales), en vista de nuestra hipótesis, la ecuación $(*)$ se reduce a $0 = 0$. Esto quiere decir que la $k$-ésima ecuación del sistema origianl $Ax = b$ es redundante (combinación lineal de las demás), lo cual es imposible puesto que $\textrm{rg}A = m$.
Para demostrar que $B_a'$ es base, solo hace falta probar que sus columnas son linealmente independientes. Como $\alpha_{ks} \neq 0$, la demostración es como en el [[criterio de factibilidad]], por lo que la omitiremos. Consideremos la descomposición de $\tilde x = (\tilde x_{B_a'}^T, \tilde x_{N_a'}^T)^T$. Como $\mathcal J_{N_a'} = (\mathcal J_{N_a} \textrm{\\} \{s\}) \cup \{k\}$ y, por hipótesis, $\tilde x_k = 0$, tenemos que $\tilde x_{N_a'} = 0_n$. Ahora de la ecuación clásica de factibilidad
$$B_a' \tilde x_{B_a'} + N_a' \tilde x_{N_a'} = b,$$
se deduce que $\tilde x_{B_a'} = (B_a')^{-1}b$; es decir, $\tilde x$ es una SBP asociada a $B_a'$.
```

**Tema:** [[El método Simplex#4. Obtención de una base inicial.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de la fase II
Reverso: Sea $\tilde x := (\overline x^T, \tilde x_a^T)^T \in \mathbb R^{n+m}$, con $\tilde x_a = 0_m$, la SBP óptima de $(\tilde P_a)$ obtenida en la fase I ([[Solución óptima de la Fase I]]), y sea $B_a$ la base (de $[A \quad I_m]$) a la que está asociada:
1. Si todas las variables artificiales son no básicas, entonces $B:= B_a$ es una base de $(P)$ y $\overline x$ es una [[solución básica posible]] asociada a $B$.
2. Si $\exists x_k$ artificial en la base, $k \in \mathcal J_{B_a}$, entonces $\exists x_s$ original no básica ($s \in \mathcal J_{N_a}$) tal que $\alpha_{ks} \neq 0$ y
$$B_a' = (B_a \textrm{\\} \{a_k\}) \cup \{a_s \}.$$
también es base de $(\tilde P_a)$ con la misma SBP asociada.
Tags: prm
<!--ID: 1730103598874-->
END

START
Básico
Anverso: Demostración de que sea $\tilde x := (\overline x^T, \tilde x_a^T)^T \in \mathbb R^{n+m}$, con $\tilde x_a = 0_m$, la SBP óptima de $(\tilde P_a)$ obtenida en la fase I ([[Solución óptima de la Fase I]]), y sea $B_a$ la base (de $[A \quad I_m]$) a la que está asociada:
1. Si todas las variables artificiales son no básicas, entonces $B:= B_a$ es una base de $(P)$ y $\overline x$ es una [[solución básica posible]] asociada a $B$.
2. Si $\exists x_k$ artificial en la base, $k \in \mathcal J_{B_a}$, entonces $\exists x_s$ original no básica ($s \in \mathcal J_{N_a}$) tal que $\alpha_{ks} \neq 0$ y
$$B_a' = (B_a \textrm{\\} \{a_k\}) \cup \{a_s \}.$$
también es base de $(\tilde P_a)$ con la misma SBP asociada.
Reverso: 1. Consideremos la descomposición $\tilde x = (\tilde x^T_{B_a}, \tilde x^T_{N_a})^T \in \mathbb R^{m+(m+n-m)}$, con $\tilde x_{N_a} = 0_n$ y
$$\tilde x_{B_a} = B_a^{-1}b \ge 0_m.$$
Como todas las variables artificiales están en $\tilde x_{N_a}$, podemos descomponer $\overline x = (\tilde x_{B_a}^T, 0_n^T) \in \mathbb R^{m+(n-m)}$, que es SBP asociada a $B_a$ por [[punto con términos independientes en las variables artificiales es SBP del problema ampliado]].

2. Razonemos por inducción al absurdo y supongamos que $\alpha_{kj} = 0$ para toda variable original no básica ($j \in \mathcal J_{N_a}$). La $k$-ésima ecuación del sistema
$$x_{B_a} + B_a^{-1}N_a x_{N_a} = B_a^{-1}b$$
resulta
$$(*) \quad x_k + \sum_{j \in \mathcal J_{N_a}} \alpha_{kj} x_j = 0.$$
Si volvemos al conjunto factible original de $(P)$ (eliminando las variables artificiales), en vista de nuestra hipótesis, la ecuación $(*)$ se reduce a $0 = 0$. Esto quiere decir que la $k$-ésima ecuación del sistema origianl $Ax = b$ es redundante (combinación lineal de las demás), lo cual es imposible puesto que $\textrm{rg}A = m$.
Para demostrar que $B_a'$ es base, solo hace falta probar que sus columnas son linealmente independientes. Como $\alpha_{ks} \neq 0$, la demostración es como en el [[criterio de factibilidad]], por lo que la omitiremos. Consideremos la descomposición de $\tilde x = (\tilde x_{B_a'}^T, \tilde x_{N_a'}^T)^T$. Como $\mathcal J_{N_a'} = (\mathcal J_{N_a} \textrm{\\} \{s\}) \cup \{k\}$ y, por hipótesis, $\tilde x_k = 0$, tenemos que $\tilde x_{N_a'} = 0_n$. Ahora de la ecuación clásica de factibilidad
$$B_a' \tilde x_{B_a'} + N_a' \tilde x_{N_a'} = b,$$
se deduce que $\tilde x_{B_a'} = (B_a')^{-1}b$; es decir, $\tilde x$ es una SBP asociada a $B_a'$.
Tags: prm dem
<!--ID: 1730103598879-->
END

