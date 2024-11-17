### Enunciado Teorema

Sea $A \in M_{m \times n} (K)$. Entonces $\exists P \in GL_m (K), Q \in GL_n (K)$ ([[Endomorfismo biyectivo]], [[Matriz invertible]]) tal que: $$ PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} \textrm{ para algún } r\in \mathbb N \cup \set{0} $$
En particular, $rg_f(A) = rg_c(A)$.

$PAQ$ es una matriz por bloques donde el primer bloque es la matriz identidad, y el resto son submatrices con todo $0$. Cabe destacar que $PAQ \in M_{m \times n} (K)$, al igual que $A$. 

---
### Demostración

Empezamos justificando el *"En particular"* (ósea que suponemos que $\exists P,Q$ tales que cumplen las condiciones). Por [[Proposición el rango de una matriz no cambia al multiplicarla por matrices invertibles]], $rg_f(A) = rg_f(PAQ) = rg_f \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} = r = rg_c\begin{pmatrix} I_r && 0 \\ 0 && 0\end{pmatrix} =$ $rg_c(PAQ) = rg_c(A)$. Así, $rg_f(A) = rg_c(A)$.

Ahora vamos a demostrar la existencia de $P$ y $Q$. Sea $f : K^n \to K^m$ la [[Aplicación lineal]] tal que $M_{B_c, B_c'} (f) =A$ ([[Matriz coordenada]]): 
![[Pasted image 20231209140831.png]]
Nos gustaría encontrar unas [[Base]] $B, B'$ tal que $M_{B,B'} (f) = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$. Si conseguimos esto, tendremos que, siendo $P = M_{B_c', B'} (Id_{K^m}) = B_c' \to^P B'$ ([[Matriz cambio de base]]) y $Q = M_{B, B_c} (Id_{K^n}) = B \to^Q B_c$, $PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0\end{pmatrix}$. Por ser matrices de cambio de base, $P$ y $Q$ son [[Matriz invertible]], y la demostración estaría completada.

Vamos a conseguir $B, B'$. Sea $\{v_{r+1}, \dots, v_n\}$ [[Base]] de $Kerf$ ([[Núcleo]]), la prolongamos a $B =\{v_1, \dots, v_r, v_{r+1}, \dots, v_n\}$ base de $V$. Esto nos garantiza que $M_{B,B'} (f) = \begin{pmatrix} \textrm{algo} && 0 \end{pmatrix}, \forall B'$ base de $K^m$, donde "algo" tiene $r$ columnas. Ahora hay q pensar como escoger $B'$ tal que las $r$ primeras columnas sean $I_r$. 
Sea $B' = \{v_1', \dots, v_m'\}$, vamos a ver cómo necesitamos que sean los $v_i'$. Veamos $f(v_1)_{B'}$ ([[Coordenadas]]), que es la primera columna de $M_{B,B'} (f)$, y necesitamos que sea $I_r$ por lo tanto, la primera columna va a ser $(1, 0, \dots, 0)^T$ lo que necesariamente implica que $v_1' = f(v_1)$. Haciendo lo mismo con el resto de columnas, $v_r' = f(v_r)$ (desde $r$ hasta $m$ pueden ser cualquier cosa porque al ser $\{v_{r+1}, \dots, v_n\}$ base de $Kerf$ entonces su imagen es $0$) . Ahora para que $\{f(v_1), \dots, f(v_r)\}$ sea base, necesitamos que es linealmente independiente ([[Independencia lineal]]):
Supongamos $\lambda_1 f(v_1) + \dots + \lambda_r f(v_r) = 0$ con $\lambda_i \in K$. Queremos ver que $\lambda_1 = \dots = \lambda_r = 0$. Tenemos que $0 = \lambda_1 f(v_1) + \dots + \lambda_r f(v_r) = f(\lambda_1 v_1 + \dots + \lambda_r v_r) = 0 \implies \lambda_1 v_1 + \dots + \lambda_r v_r \in Kerf = \langle v_{r+1}, \dots, v_n \rangle$. Por tanto, $\lambda_1 v_1 + \dots + \lambda_r v_r = \lambda_{r+1} v_{r+1} + \dots + \lambda_n v_n$ para algunos $\lambda_{r+1}, \dots, \lambda_n \in K$. Lo pasamos todo a un lado: $\lambda_1 v_1 + \dots + \lambda_r v_r - \lambda_{r+1} v_{r+1} - \dots - \lambda_n v_n = 0$ que es combinación lineal de vectores de $B$, así $\lambda_1 = \dots = \lambda_r = 0$ (también lo son los demás pero no importan).
Prolongamos $\{f(v_1), \dots, f(v_r)\}$ a una base $B' = \{f(v_1), \dots, f(v_r), v_{r+1}', \dots, v_m'\}$ base de $K^m$. Se tiene que $M_{B,B'} (f) = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$, con esto la demostración está completada y observamos que $n-r = dim(Kerf)$, luego $dimK^n = dim(Kerf) + dim(Imf)$, $dim(Imf) = r = rg(f) = rg(A)$.

---
### Referencias

[[Equivalencia de matrices#1. Rango]]

[[Teorema producto por matrices invertibles matriz sencilla (demostración 2)]]

---
### Anki

START
Básico
Anverso: Cuál es el teorema que afirma que el producto de matrices invertibles puede dar lugar a una matriz sencilla?
Reverso: Sea $A \in M_{m \times n} (K)$. Entonces $\exists P \in GL_m (K), Q \in GL_n (K)$ ([[Endomorfismo biyectivo]], [[Matriz invertible]]) tal que: $$ PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} \textrm{ para algún } r\in \mathbb N \cup \set{0} $$
En particular, $rg_f(A) = rg_c(A)$.

$PAQ$ es una matriz por bloques donde el primer bloque es la matriz identidad, y el resto son submatrices con todo $0$. Cabe destacar que $PAQ \in M_{m \times n} (K)$, al igual que $A$. 
Tags: proposición/teorema
<!--ID: 1704822883687-->
END

START
Básico
Anverso: Demostración de que sea $A \in M_{m \times n} (K)$. Entonces $\exists P \in GL_m (K), Q \in GL_n (K)$ ([[Endomorfismo biyectivo]], [[Matriz invertible]]) tal que: $$ PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} \textrm{ para algún } r\in \mathbb N \cup \set{0} $$
En particular, $rg_f(A) = rg_c(A)$.
Reverso: Empezamos justificando el *"En particular"* (ósea que suponemos que $\exists P,Q$ tales que cumplen las condiciones). Por [[Proposición el rango de una matriz no cambia al multiplicarla por matrices invertibles]], $rg_f(A) = rg_f(PAQ) = rg_f \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} = r = rg_c\begin{pmatrix} I_r && 0 \\ 0 && 0\end{pmatrix} =$ $rg_c(PAQ) = rg_c(A)$. Así, $rg_f(A) = rg_c(A)$.

Ahora vamos a demostrar la existencia de $P$ y $Q$. Sea $f : K^n \to K^m$ la [[Aplicación lineal]] tal que $M_{B_c, B_c'} (f) =A$ ([[Matriz coordenada]]): 
![[Pasted image 20231209140831.png]]
Nos gustaría encontrar unas [[Base]] $B, B'$ tal que $M_{B,B'} (f) = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$. Si conseguimos esto, tendremos que, siendo $P = M_{B_c', B'} (Id_{K^m}) = B_c' \to^P B'$ ([[Matriz cambio de base]]) y $Q = M_{B, B_c} (Id_{K^n}) = B \to^Q B_c$, $PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0\end{pmatrix}$. Por ser matrices de cambio de base, $P$ y $Q$ son [[Matriz invertible]], y la demostración estaría completada.

Vamos a conseguir $B, B'$. Sea $\{v_{r+1}, \dots, v_n\}$ [[Base]] de $Kerf$ ([[Núcleo]]), la prolongamos a $B =\{v_1, \dots, v_r, v_{r+1}, \dots, v_n\}$ base de $V$. Esto nos garantiza que $M_{B,B'} (f) = \begin{pmatrix} \textrm{algo} && 0 \end{pmatrix}, \forall B'$ base de $K^m$, donde "algo" tiene $r$ columnas. Ahora hay q pensar como escoger $B'$ tal que las $r$ primeras columnas sean $I_r$. 
Sea $B' = \{v_1', \dots, v_m'\}$, vamos a ver cómo necesitamos que sean los $v_i'$. Veamos $f(v_1)_{B'}$ ([[Coordenadas]]), que es la primera columna de $M_{B,B'} (f)$, y necesitamos que sea $I_r$ por lo tanto, la primera columna va a ser $(1, 0, \dots, 0)^T$ lo que necesariamente implica que $v_1' = f(v_1)$. Haciendo lo mismo con el resto de columnas, $v_r' = f(v_r)$ (desde $r$ hasta $m$ pueden ser cualquier cosa porque al ser $\{v_{r+1}, \dots, v_n\}$ base de $Kerf$ entonces su imagen es $0$) . Ahora para que $\{f(v_1), \dots, f(v_r)\}$ sea base, necesitamos que es linealmente independiente ([[Independencia lineal]]):
Supongamos $\lambda_1 f(v_1) + \dots + \lambda_r f(v_r) = 0$ con $\lambda_i \in K$. Queremos ver que $\lambda_1 = \dots = \lambda_r = 0$. Tenemos que $0 = \lambda_1 f(v_1) + \dots + \lambda_r f(v_r) = f(\lambda_1 v_1 + \dots + \lambda_r v_r) = 0 \implies \lambda_1 v_1 + \dots + \lambda_r v_r \in Kerf = \langle v_{r+1}, \dots, v_n \rangle$. Por tanto, $\lambda_1 v_1 + \dots + \lambda_r v_r = \lambda_{r+1} v_{r+1} + \dots + \lambda_n v_n$ para algunos $\lambda_{r+1}, \dots, \lambda_n \in K$. Lo pasamos todo a un lado: $\lambda_1 v_1 + \dots + \lambda_r v_r - \lambda_{r+1} v_{r+1} - \dots - \lambda_n v_n = 0$ que es combinación lineal de vectores de $B$, así $\lambda_1 = \dots = \lambda_r = 0$ (también lo son los demás pero no importan).
Prolongamos $\{f(v_1), \dots, f(v_r)\}$ a una base $B' = \{f(v_1), \dots, f(v_r), v_{r+1}', \dots, v_m'\}$ base de $K^m$. Se tiene que $M_{B,B'} (f) = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$, con esto la demostración está completada y observamos que $n-r = dim(Kerf)$, luego $dimK^n = dim(Kerf) + dim(Imf)$, $dim(Imf) = r = rg(f) = rg(A)$.
Tags: demostración
<!--ID: 1704822883695-->
END