### Contenido Principal

```ad-theorem
Sea el [[poliedro]]
$$\mathcal F := \{x \in \mathbb R^n \, | \, Ax = b, x \ge 0_n \},$$
donde $A \in \mathbb R^{m \times n}$, con $\textrm{rg}A = m$, $b \in \mathbb R^m$ y $c \in \mathbb R^n$. Entonces $\overline x$ es punto extremo de $\mathcal F$ $\iff$ $A$ se puede descomponer (reordenando sus columnas) como $A = [B \quad N]$, con $B \in \mathbb R^{m \times m}$ invertible  y $N \in \mathbb R^{m \times (n-m)}$, de forma que
$$\overline x = \begin{pmatrix} B^{-1}b \\ 0_{n-m} \end{pmatrix}, \quad \textrm{con } B^{-1}b \ge 0_m.$$
```

```ad-proof
$\Leftarrow$. 
Sea $\overline x = ((B^{-1}b)^T, 0_{n-m}^T)^T \in \mathbb R^n$ con $B^{-1}b \ge 0_m$. Se tiene que $\overline x \in \mathcal F$ ya que $x \ge 0_n$ y
$$A \overline x = [B \quad N] \begin{pmatrix} B^{-1}b \\ 0_{n-m} \end{pmatrix} = BB^{-1}b + N0_{n-m} = b.$$
Supongamos que $\exists y,z \in \mathcal F$ y $\lambda \in ]0,1[$ tales que $\overline x = (1-\lambda)y + \lambda z$. Descomponiendo $(y_B^T, y_N^T)^T$ y $z = (z_B^T, z_N^T)^T$ con $y_B, z_B \in \mathbb R^m$, $y_N, z_N \in \mathbb R^{n-m}$ tenemos que
$$\begin{matrix}
B^{-1}b = (1-\lambda)y_B + \lambda z_B, \\
0_{n-m} = (1-\lambda)y_N + \lambda z_N.
\end{matrix}$$
De la última igualdad, junto con $0<\lambda < 1$ y $y_N, z_N \ge 0_{n-m}$, deducimos que $y_N = z_N = 0_{n-m}$. Además, como $y \in \mathcal F$, se cumple que $Ay = b$, lo que se traduce en
$$[B \quad N] \begin{pmatrix} y_B \\ 0_{n-m} \end{pmatrix} = b \iff By_B = b \iff y_B = B^{-1}b.$$
Un razonamiento análogo prueba que $z_B = B^{-1}b$. Por lo tanto, $\overline x = y = z$ y entonces $\overline x$ es un punto extremo de $\mathcal F$.

$\Rightarrow$. 
Sea $\overline x$ un punto extremo de $\mathcal F$ y sea $k \in \{0, 1, \dots, n\}$ el número de componentes no nulas de $\overline x$. Podemos reordenar las columnas del sistema de manera que
$$(**) \quad \overline x = (\overline x_1, \dots, \overline x_k, 0, \dots, 0)^T, \quad \textrm{con } \overline x_j > 0, \, \forall j = 1, \dots, k.$$
Como $\overline x \in \mathcal F$, se cumple que $A \overline x = b$. Denotemos $A := [a_1 \, \dots \, a_n]$ con $a_j \in \mathbb R^m$ para $j = 1, \dots, n$. Demostraremos que $a_1, \dots, a_k$ son linealmente independientes. Para ello, supongamos que $\exists \lambda_1, \dots, \lambda_k \in \mathbb R$ tal que
$$(*) \quad \sum_{j = 1}^k \lambda_j a_j = 0_m.$$
Definamos $w := (\lambda_1, \dots, \lambda_k, 0, \dots, 0)^T \in \mathbb R^n$ y, para $\alpha > 0$, construyamos los vectores
$$\begin{matrix} y = \overline x + \alpha w, \\ z = \overline x - \alpha w \end{matrix}.$$
Por una parte, $(*)$ implica que $Aw = 0_m$ y, por tanto, $Ay = Az = b$. Por otra parte, para $\alpha$ suficientemente pequeño podemos garantizar que $y,z \ge 0_n$. Tenemos entonces que $y,z \in \mathcal F$. Como $\overline x = \frac{1}{2}y + \frac{1}{2}z$, llegamos a que $\overline x = y = z$ y por tanto $w = 0_n$. Así, las columnas $a_1, \dots, a_k \in \mathbb R^m$ son linealmente independientes. En particular hemos probado que $k \le m$. Si $k<m$ añadimos columnas $a_{k+1}, \dots, a_m$ (reordenando si es necesario) hasta completar una base de $\mathbb R^m$ y construimos $B := [a_1 \, \dots \, a_m] \in \mathbb R^{m}$ invertible. Denotando por $N$ al resto de columnas de $A$, tenemos la descomposición buscada. De la misma forma descomponemos
$$\overline x = \begin{pmatrix} \overline x_B \\ \overline x_N \end{pmatrix}, \quad \textrm{con } \overline x_B \in \mathbb R^m, \, \overline x_N \in \mathbb R^{n-m}.$$
En vista de $(**)$, necesariamente $\overline x_N = 0_{n-m}$. Finalmente, como $A \overline x = b$, entonces $B \overline x_B = b$ con $\overline x_B \ge 0_m$ (por ser $\overline x \in \mathcal F$), lo que concluye la prueba.
```

**Tema:** [[Modelo de programación lineal#3. Identificación analítica de soluciones.]]

**Definiciones referenciadas:** [[Punto extremo]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema de caracterización de puntos extremos?
Reverso: Sea el [[poliedro]]
$$\mathcal F := \{x \in \mathbb R^n \, | \, Ax = b, x \ge 0_n \},$$
donde $A \in \mathbb R^{m \times n}$, con $\textrm{rg}A = m$, $b \in \mathbb R^m$ y $c \in \mathbb R^n$. Entonces $\overline x$ es [[punto extremo]] de $\mathcal F$ $\iff$ $A$ se puede descomponer (reordenando sus columnas) como $A = [B \quad N]$, con $B \in \mathbb R^{m \times m}$ invertible  y $N \in \mathbb R^{m \times (n-m)}$, de forma que
$$\overline x = \begin{pmatrix} B^{-1}b \\ 0_{n-m} \end{pmatrix}, \quad \textrm{con } B^{-1}b \ge 0_m.$$
Tags:
<!--ID: 1727083427962-->
END

START
Básico
Anverso: Demostración de que sea el [[poliedro]]
$$\mathcal F := \{x \in \mathbb R^n \, | \, Ax = b, x \ge 0_n \},$$
donde $A \in \mathbb R^{m \times n}$, con $\textrm{rg}A = m$, $b \in \mathbb R^m$ y $c \in \mathbb R^n$. Entonces $\overline x$ es [[punto extremo]] de $\mathcal F$ $\iff$ $A$ se puede descomponer (reordenando sus columnas) como $A = [B \quad N]$, con $B \in \mathbb R^{m \times m}$ invertible  y $N \in \mathbb R^{m \times (n-m)}$, de forma que
$$\overline x = \begin{pmatrix} B^{-1}b \\ 0_{n-m} \end{pmatrix}, \quad \textrm{con } B^{-1}b \ge 0_m.$$
Reverso: $\leftarrow$. Sea $\overline x = ((B^{-1}b)^T, 0_{n-m}^T)^T \in \mathbb R^n$ con $B^{-1}b \ge 0_m$. Se tiene que $\overline x \in \mathcal F$ ya que $x \ge 0_n$ y
$$A \overline x = [B \quad N] \begin{pmatrix} B^{-1}b \\ 0_{n-m} \end{pmatrix} = BB^{-1}b + N0_{n-m} = b.$$
Supongamos que $\exists y,z \in \mathcal F$ y $\lambda \in ]0,1[$ tales que $\overline x = (1-\lambda)y + \lambda z$. Descomponiendo $(y_B^T, y_N^T)^T$ y $z = (z_B^T, z_N^T)^T$ con $y_B, z_B \in \mathbb R^m$, $y_N, z_N \in \mathbb R^{n-m}$ tenemos que
$$\begin{matrix}
B^{-1}b = (1-\lambda)y_B + \lambda z_B, \\
0_{n-m} = (1-\lambda)y_N + \lambda z_N.
\end{matrix}$$
De la última igualdad, junto con $0<\lambda < 1$ y $y_N, z_N \ge 0_{n-m}$, deducimos que $y_N = z_N = 0_{n-m}$. Además, como $y \in \mathcal F$, se cumple que $Ay = b$, lo que se traduce en
$$[B \quad N] \begin{pmatrix} y_B \\ 0_{n-m} \end{pmatrix} = b \iff By_B = b \iff y_B = B^{-1}b.$$
Un razonamiento análogo prueba que $z_B = B^{-1}b$. Por lo tanto, $\overline x = y = z$ y entonces $\overline x$ es un [[punto extremo]] de $\mathcal F$.

$\rightarrow$. Sea $\overline x$ un punto extremo de $\mathcal F$ y sea $k \in \{0, 1, \dots, n\}$ el número de componentes no nulas de $\overline x$. POdemos reordenar las columnas del sistema de manera que
$$(**) \, \overline x = (\overline x_1, \dots, \overline x_k, 0, \dots, 0)^T, \quad \textrm{con } \overline x_j > 0, \, \forall j = 1, \dots, k.$$
Como $\overline x \in \mathcal F$, se cumple que $A \overline x = b$. Denotemos $A := [a_1 \, \dots \, a_n]$ con $a_j \in \mathbb R^m$ para $j = 1, \dots, n$. Demostraremos que $a_1, \dots, a_k$ son linealmente independientes. Para ello, supongamos que $\exists \lambda_1, \dots, \lambda_k \in \mathbb R$ tal que
$$(*) \sum_{j = 1}^k \lambda_j a_j = 0_m.$$
Definamos $w := (\lambda_1, \dots, \lambda_k, 0, \dots, 0)^T \in \mathbb R^n$ y, para $\alpha > 0$, construyamos los vectores
$$\begin{matrix} y = \overline x + \alpha w, \\ z = \overline x - \alpha w \end{matrix}.$$
Por una parte, $(*)$ implica que $Aw = 0_m$ y, por tanto, $Ay = Az = b$. Por otra parte, para $\alpha$ suficientemente pequeño podemos garantizar que $y,z \ge 0_n$. Tenemos entonces que $y,z \in \mathcal F$. Como $\overline x = \frac{1}{2}y + \frac{1}{2}z$, llegamos a que $\overline x = y = z$ y por tanto $w = 0_n$. Así, las columnas $a_1, \dots, a_k \in \mathbb R^m$ son linealmente independientes. En particular hemos probado que $k \le m$. Si $k<m$ añadimos columnas $a_{k+1}, \dots, a_m$ (reordenando si es necesario) hasta completar una base de $\mathbb R^m$ y construimos $B := [a_1 \, \dots \, a_m] \in \mathbb R^{m}$ invertible. Denotando por $N$ al resto de columnas de $A$, tenemos la descomposición buscada. De la misma forma descomponemos
$$\overline x = \begin{pmatrix} \overline x_B \\ \overline x_N \end{pmatrix}, \quad \textrm{con } \overline x_B \in \mathbb R^m, \, \overline x_N \in \mathbb R^{n-m}.$$
En vista de $(**)$, necesariamente $\overline x_N = 0_{n-m}$. Finalmente, como $A \overline x = b$, entonces $B \overline x_B = b$ con $\overline x_B \ge 0_m$ (por ser $\overline x \in \mathcal F$), lo que concluye la prueba.
Tags: prm dem
<!--ID: 1727083427965-->
END