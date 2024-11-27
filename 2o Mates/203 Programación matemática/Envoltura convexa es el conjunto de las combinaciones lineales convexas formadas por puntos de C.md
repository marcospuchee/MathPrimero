### Contenido Principal

```ad-proposition
Para cualquier $C \subseteq \mathbb R^n$:
$$\textrm{conv}C = \left \{ \sum_{i = 1}^k \lambda_i x_i \, | \, k \in \mathbb N, x_1, \dots, x_k \in C, \lambda_1, \dots, \lambda_k \ge 0, \sum_{i =1 }^k \lambda_i = 1 \right \}.$$
```

```ad-proof
Denotemos por $\Delta$ al conjunto del lado derecho de la igualdad. Primero demostraremos que $\Delta$ es convexo. Para ello, sean
$$x = \sum_{i = 1}^k \alpha_i x_i, \, y = \sum_{j = 1}^l \beta_j y_j \in \Delta$$
dos combinaciones lineales convexas. Sea $\lambda \in [0,1]$, definamos $\forall i = 1, \dots, k+l$,
$$\hat x_i := \left \{ \begin{matrix*}[l l] x_i & \textrm{si } i \in \{1, \dots, k\} \\ y_{i-k}, & \textrm{si } i \in \{k+1, \dots, k+l\}, \end{matrix*} \right . \quad \hat \lambda_i := \left \{ \begin{matrix*}[r l] (1-\lambda)\alpha_i & \textrm{si } i \in \{1, \dots, k\} \\ \lambda \beta_{i-k}, & \textrm{si } i \in \{k+1, \dots, k+l\}, \end{matrix*} \right .$$
Se tiene por tanto que
$$(1-\lambda)x + \lambda y = (1-\lambda)\sum_{i = 1}^k \alpha_i x_i + \lambda \sum_{j  =1}^l \beta_j y_j = \sum_{i = 1}^{k+l} \hat \lambda_i \hat x_i,$$
con $\hat x_1, \dots, \hat x_{l+k} \in C$, $\hat \lambda_i \ge 0$, para todo $i = 1, \dots, k+l$, y $\sum_{i = 1}^{l+k} \hat \lambda_i = 1$. Esto es, $(1-\lambda)x + \lambda y$ se puede escribir como [[combinación lineal convexa]] de $k+l$ puntos de $C$, por lo que $(1-\lambda)x + \lambda y \in \Delta$. Luego $\Delta$ es convexo. Como $C \subseteq \Delta$, en vista de [[(por demostrar) Envoltura convexa de un conjunto es el conjunto convexo mínimo que lo contiene]], se debe cumplir que $\textrm{conv}C \subseteq \Delta$.

Para la otra inclusión, tomemos $x \in \Delta$:
$$x = \sum_{i = 1}^k \lambda_i x_i; \quad x_1, \dots, x_k \in C; \quad \alpha_1, \dots, \alpha_k \ge 0; \quad \sum_{i = 1}^k \alpha_i = 1.$$
Sea $D \subseteq \mathbb R^n$ un [[conjunto convexo]] cualquiera tal que $C \subseteq D$. Entonces $x_1, \dots, x_k \in D$, y en vista de [[conjunto convexo sii contiene combinaciones lineales convexas de cualquier subconjunto finito]], se tiene que $x \in D$. Concluimos que $x \in \textrm{conv}C$ ([[envoltura convexa]]).
```

**Tema:** [[Modelo de programación lineal]]

---
### Anki

START
Básico
Anverso: Proposición definición general de envoltura convexa
Reverso: Para cualquier $C \subseteq \mathbb R^n$:
$$\textrm{conv}C = \left \{ \sum_{i = 1}^k \lambda_i x_i \, | \, k \in \mathbb N, x_1, \dots, x_k \in C, \lambda_1, \dots, \lambda_k \ge 0, \sum_{i =1 }^k \lambda_i = 1 \right \}.$$
Tags:
<!--ID: 1727083427994-->
END

START
Básico
Anverso: Demostración de que para cualquier $C \subseteq \mathbb R^n$:
$$\textrm{conv}C = \left \{ \sum_{i = 1}^k \lambda_i x_i \, | \, k \in \mathbb N, x_1, \dots, x_k \in C, \lambda_1, \dots, \lambda_k \ge 0, \sum_{i =1 }^k \lambda_i = 1 \right \}.$$
Reverso: Denotemos por $\Delta$ al conjunto del lado derecho de la igualdad. Primero demostraremos que $\Delta$ es convexo. Para ello, sean
$$x = \sum_{i = 1}^k \alpha_i x_i, \, y = \sum_{j = 1}^l \beta_j y_j \in \Delta$$
dos combinaciones lineales convexas. Sea $\lambda \in [0,1]$, definamos $\forall i = 1, \dots, k+l$,
$$\hat x_i := \left \{ \begin{matrix*}[l l] x_i & \textrm{si } i \in \{1, \dots, k\} \\ y_{i-k}, & \textrm{si } i \in \{k+1, \dots, k+l\}, \end{matrix*} \right . \quad \hat \lambda_i := \left \{ \begin{matrix*}[r l] (1-\lambda)\alpha_i & \textrm{si } i \in \{1, \dots, k\} \\ \lambda \beta_{i-k}, & \textrm{si } i \in \{k+1, \dots, k+l\}, \end{matrix*} \right .$$
Se tiene por tanto que
$$(1-\lambda)x + \lambda y = (1-\lambda)\sum_{i = 1}^k \alpha_i x_i + \lambda \sum_{j  =1}^l \beta_j y_j = \sum_{i = 1}^{k+l} \hat \lambda_i \hat x_i,$$
con $\hat x_1, \dots, \hat x_{l+k} \in C$, $\hat \lambda_i \ge 0$, para todo $i = 1, \dots, k+l$, y $\sum_{i = 1}^{l+k} \hat \lambda_i = 1$. Esto es, $(1-\lambda)x + \lambda y$ se puede escribir como [[combinación lineal convexa]] de $k+l$ puntos de $C$, por lo que $(1-\lambda)x + \lambda y \in \Delta$. Luego $\Delta$ es convexo. Como $C \subseteq \Delta$, en vista de [[Envoltura convexa de un conjunto es el conjunto convexo mínimo que lo contiene]], se debe cumplir que $\textrm{conv}C \subseteq \Delta$.

Para la otra inclusión, tomemos $x \in \Delta$:
$$x = \sum_{i = 1}^k \lambda_i x_i; \quad x_1, \dots, x_k \in C; \quad \alpha_1, \dots, \alpha_k \ge 0; \quad \sum_{i = 1}^k \alpha_i = 1.$$
Sea $D \subseteq \mathbb R^n$ un [[conjunto convexo]] cualquiera tal que $C \subseteq D$. Entonces $x_1, \dots, x_k \in D$, y en vista de [[conjunto convexo sii contiene combinaciones lineales convexas de cualquier subconjunto finito]], se tiene que $x \in D$. Concluimos que $x \in \textrm{conv}C$ ([[envoltura convexa]]).
Tags: dem prm
<!--ID: 1727083427996-->
END
