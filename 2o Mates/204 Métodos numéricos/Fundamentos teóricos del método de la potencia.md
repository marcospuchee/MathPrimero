### Contenido Principal

```ad-theorem
Consideramos $A \in \mathbb R^{n \times n}$ diagonalizable, con valores propios tales que
$$|\lambda_1| > |\lambda_2| \ge |\lambda_3| \ge \dots \ge |\lambda_n|.$$
El método de la Potencia calcula $\lambda_1$ con $|\lambda_1| = \rho(A)$.
```

```ad-proof
Si $A$ es diagonalizable, entonces existe una base de $\mathbb R^n$ de vectores propios (caracterización de diagonalizable):
$$\{v_1, v_2, \dots, v_n \}, \quad Av_i = \lambda_i v_i.$$
Si $x \in \mathbb R^n$, entonces $\exists \alpha_1, \dots, \alpha_n \in \mathbb R$ tales que
$$x = \sum_{i = 1}^n \alpha_i v_i \implies A^kx = \sum_{i = 1}^n \alpha_i A^k v_i = \sum_{i = 1}^n \alpha_i \lambda_i^k v_i = \alpha_1 \lambda_1^k v_1 + \sum_{i = 2}^n \alpha_i \lambda_i^k v_i,$$
que, si sacamos factor común de $\lambda_1$, nos queda:
$$y^{(k)}:=A^k x = \lambda_1^k \left ( \alpha_1 v_1 + \sum_{i = 2}^n \alpha_i \left ( \frac{\lambda_i}{\lambda_1} \right )^k v_i \right ),$$
pero notemos que si $k \to +\infty$, entonces $r^{(k)} := \alpha_1v_1 + \sum_{i = 2}^n \alpha_i \left ( \frac{\lambda_i}{\lambda_1} \right )^k v_i \to \alpha_1 v_1$, dado que $|\lambda_1| > |\lambda_i|$, $\forall 2 \le i \le n$. Luego para $k$ grande, $y^{(k)} \approx \lambda_1^k \alpha_1 v_1$. Es decir, $y^{(k)}$ es esencialmente un vector propio de $A$.

De hecho, si definimos $q_k$ como la sucesión de cocientes de Rayleigh de $y^{(k)}$, tenemos que
$$q_k := \frac{(y^{(k)})^T A y^{(k)}}{(y^{(k)})^T y^{(k)}} = \frac{(y^{(k)})^T y^{(k+1)}}{(y^{(k)})^T y^{(k)}} = \frac{(\lambda_1^k r^{(k)})^T (\lambda_1^{k+1} r^{(k+1)})}{(\lambda_1^k r^{(k)})^T(\lambda_1^k r^{(k)})} = \lambda_1 \frac{(r^{(k)})^T r^{(k+1)}}{(r^{(k)})^T r^{(k)}},$$
pero notemos que
$$\lim_{k \to \infty} q_k = \lambda_1 \lim_{k \to \infty} \frac{(r^{(k)})^T r^{(k+1)}}{(r^{(k)})^T r^{(k)}} = \lambda_1 \frac{\alpha_1^2 v_1^T v_1}{\alpha_1^2 v_1^T v_1} = \lambda_1.$$
```

**Tema:** [[Métodos para valores y vectores propios#3. Método de la potencia.]]

**Definiciones referenciadas:** [[Matriz diagonalizable]], [[Valor propio de una matriz]], [$\rho(A)$](Radio espectral)
**Resultados referenciados:**

---
### Anki

START
Básico
Anverso: Demostración de la convergencia del método de la potencia
Reverso: Si $A$ es diagonalizable, entonces existe una base de $\mathbb R^n$ de vectores propios (caracterización de diagonalizable):
$$\{v_1, v_2, \dots, v_n \}, \quad Av_i = \lambda_i v_i.$$
Si $x \in \mathbb R^n$, entonces $\exists \alpha_1, \dots, \alpha_n \in \mathbb R$ tales que
$$x = \sum_{i = 1}^n \alpha_i v_i \implies A^kx = \sum_{i = 1}^n \alpha_i A^k v_i = \sum_{i = 1}^n \alpha_i \lambda_i^k v_i = \alpha_1 \lambda_1^k v_1 + \sum_{i = 2}^n \alpha_i \lambda_i^k v_i,$$
que, si sacamos factor común de $\lambda_1$, nos queda:
$$y^{(k)}:=A^k x = \lambda_1^k \left ( \alpha_1 v_1 + \sum_{i = 2}^n \alpha_i \left ( \frac{\lambda_i}{\lambda_1} \right )^k v_i \right ),$$
pero notemos que si $k \to +\infty$, entonces $r^{(k)} := \alpha_1v_1 + \sum_{i = 2}^n \alpha_i \left ( \frac{\lambda_i}{\lambda_1} \right )^k v_i \to 0$, dado que $|\lambda_1| > |\lambda_i|$, $\forall 2 \le i \le n$. Luego para $k$ grande, $y^{(k)} \approx \lambda_1^k \alpha_1 v_1$. Es decir, $y^{(k)}$ es esencialmente un vector propio de $A$.

De hecho, si definimos $q_k$ como la sucesión de cocientes de Rayleigh de $y^{(k)}$, tenemos que
$$q_k := \frac{(y^{(k)})^T A y^{(k)}}{(y^{(k)})^T y^{(k)}} = \frac{(y^{(k)})^T y^{(k+1)}}{(y^{(k)})^T y^{(k)}} = \frac{(\lambda_1^k r^{(k)})^T (\lambda_1^{k+1} r^{(k+1)})}{(\lambda_1^k r^{(k)})^T(\lambda_1^k r^{(k)})} = \lambda_1 \frac{(r^{(k)})^T r^{(k+1)}}{(r^{(k)})^T r^{(k)}},$$
pero notemos que
$$\lim_{k \to \infty} q_k = \lambda_1 \lim_{k \to \infty} \frac{(r^{(k)})^T r^{(k+1)}}{(r^{(k)})^T r^{(k)}} = \lambda_1 \frac{\alpha_1^2 v_1^T v_1}{\alpha_1^2 v_1^T v_1} = \lambda_1.$$
Tags: dem met
<!--ID: 1735044171446-->
END
