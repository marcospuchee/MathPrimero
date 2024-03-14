
---
mathLink: El polinomio característico de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ tiene $k$ raíces simples $\implies x_0^n, \dots, x_{k-1}^n$ es base de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$
---
### Contenido Principal

**Fecha:** 2024-02-22, 17:38

Sea $p(x)$ el [[Polinomio característico asociado al espacio vectorial de las sucesiones definidas por una misma ley de recurrencia]].

```ad-proposition
Si el polinomio característico de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ tiene $k$ raíces simples (reales o complejas), entonces las sucesiones $x_0^n, x_1^n, \dots, x_{k-1}^n$ forman una [[base]] de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$
```


```ad-proof
Sea $x$ una raíz de $p(x)$, veamos que $a_n = x^n$ cumple:
$a_{n+k} = x^{n+k} = x^n · x^k$ (como es raíz de $p(x)$, cumple $x^k - \lambda_{k-1} x^{k-1} - \lambda_{k-2} x^{k-2} - \dots - \lambda_0 x^0 = 0$, luego) $= x^n · (\lambda_{k-1} x^{k-1} + \lambda_{k-2} x^{k-1} + \dots + \dots + \lambda_0 x^0)$ $= \lambda_{k-1} x^{n+k-1} + \lambda_{k-2}x^{n+k-2} + \dots + \lambda_0 x^n$. Como $a_n = x^n, a_{n+k-1} = x^{n+k-1}$ luego todo lo anterior es igual a:
$$\lambda_{k-1} a_{n+k-1} + \lambda_{k-2} a_{n+k-2} + \dots + \lambda_1 a_{n+1} + \lambda_0 x^n,$$
luego las raíces cumplen la [[Ley de recurrencia lineal y homogénea]] y $x_0^n, x_1^n, \dots, x_{k-1}^n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$.

Si ahora vemos que $\dim S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} = k$ y $\{x_0^n, x_1^n, \dots, x_{k-1}^n\}$ es linealmente independiente, entonces veremos que es base.

Tomamos $\phi: S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} \to \mathbb R^k$ con $\phi(a_n) \to (a_0, a_1, \dots, a_{k-1})$ (el [[Isomorfismo]] de [[El conjunto de todas las sucesiones definidas por una misma ley de recurrencia es espacio vectorial]]). Luego $\phi (x_0^n) = (x_0^0, x_0^1, \dots, x_0^{n-1})$. Tenemos $k$ vectores con $k$ coordenadas, formamos el determinante correspondiente:
$$
\begin{vmatrix}
1 & x_0^1 & x_0^2 & x_0^3 & \dots & x_0^{k-1} \\
1 & x_1^1 & x_1^2 & x_1^3 & \dots & x_1^{k-1} \\
\vdots \\
1 & x_{k-1}^1 & x_{k-1}^2 & x_{k-1}^3 & \dots & x_{k-1}^{k-1}
\end{vmatrix},
$$
que es el determinante que devuelve:
$$
\begin{eqnarray}
&=& (x_0-x_1)(x_0-x_2) \dots (x_0-x_{k-1})(x_1-x_2)(x_1-x_3) \dots (x_{k-1}-x_{k-1}) \\
&=& \prod_{0 \le i,j \le k-1} (x_i - x_j) \neq 0 \textrm{ porque } x_0 \neq x_1 \neq \dots \neq x_{k-1}
\end{eqnarray}
$$
luego es linealmente independiente, y es base.
```



**Tema:** [[Ecuaciones de recurrencia#2. Solución de las leyes de recurrencia lineales y homogéneas]]
**Corolarios:** [[Teorema solución ley de recurrencia]]

---
### Anki

START
Básico
Anverso: Demuestra que sea $p(x)$ el [[Polinomio característico asociado al espacio vectorial de las sucesiones definidas por una misma ley de recurrencia]]. Si el polinomio característico de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$ tiene $k$ raíces simples (reales o complejas), entonces las sucesiones $x_0^n, x_1^n, \dots, x_{k-1}^n$ forman una [[base]] de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$
Reverso: Sea $x$ una raíz de $p(x)$, veamos que $a_n = x^n$ cumple:
$a_{n+k} = x^{n+k} = x^n · x^k$ (como es raíz de $p(x)$, cumple $x^k - \lambda_{k-1} x^{k-1} - \lambda_{k-2} x^{k-2} - \dots - \lambda_0 x^0 = 0$, luego) $= x^n · (\lambda_{k-1} x^{k-1} + \lambda_{k-2} x^{k-1} + \dots + \dots + \lambda_0 x^0)$ $= \lambda_{k-1} x^{n+k-1} + \lambda_{k-2}x^{n+k-2} + \dots + \lambda_0 x^n$. Como $a_n = x^n, a_{n+k-1} = x^{n+k-1}$ luego todo lo anterior es igual a:
$$\lambda_{k-1} a_{n+k-1} + \lambda_{k-2} a_{n+k-2} + \dots + \lambda_1 a_{n+1} + \lambda_0 x^n,$$
luego las raíces cumplen la [[Ley de recurrencia lineal y homogénea]] y $x_0^n, x_1^n, \dots, x_{k-1}^n \in S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$.

Si ahora vemos que $\dim S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} = k$ y $\{x_0^n, x_1^n, \dots, x_{k-1}^n\}$ es linealmente independiente, entonces veremos que es base.

Tomamos $\phi: S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}} \to \mathbb R^k$ con $\phi(a_n) \to (a_0, a_1, \dots, a_{k-1})$ (el [[Isomorfismo]] de [[El conjunto de todas las sucesiones definidas por una misma ley de recurrencia es espacio vectorial]]). Luego $\phi (x_0^n) = (x_0^0, x_0^1, \dots, x_0^{n-1})$. Tenemos $k$ vectores con $k$ coordenadas, formamos el determinante correspondiente:
$$
\begin{vmatrix}
1 & x_0^1 & x_0^2 & x_0^3 & \dots & x_0^{k-1} \\
1 & x_1^1 & x_1^2 & x_1^3 & \dots & x_1^{k-1} \\
\vdots \\
1 & x_{k-1}^1 & x_{k-1}^2 & x_{k-1}^3 & \dots & x_{k-1}^{k-1}
\end{vmatrix},
$$
que es el determinante que devuelve:
$$
\begin{eqnarray}
&=& (x_0-x_1)(x_0-x_2) \dots (x_0-x_{k-1})(x_1-x_2)(x_1-x_3) \dots (x_{k-1}-x_{k-1}) \\
&=& \prod_{0 \le i,j \le k-1} (x_i - x_j) \neq 0 \textrm{ porque } x_0 \neq x_1 \neq \dots \neq x_{k-1}
\end{eqnarray}
$$
luego es linealmente independiente, y es base.
Tags: demostración  MatDiscreta
<!--ID: 1708973800635-->
END

START
Respuesta anidada
Sea $p(x)$ el [[Polinomio característico asociado al espacio vectorial de las sucesiones definidas por una misma ley de recurrencia]]. 

{{c1::$p(x)$ tiene $k$ raíces simples}} $\implies$ {{c2$::x_0^n, \dots, x_{k-1}^n$ es base de $S_{\lambda_0, \lambda_1, \dots, \lambda_{k-1}}$}}
Tags: proposición/teorema MatDiscreta
<!--ID: 1708973800643-->
END
