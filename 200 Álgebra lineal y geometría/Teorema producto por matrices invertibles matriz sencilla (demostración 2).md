### Enunciado Teorema

Sea $A \in M_{m \times n} (K)$. Entonces $\exists P,Q$ [[Matriz invertible]] tales que $PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$, con $r = rg(A)$.

---
### Demostración

Por el [[Método Gauss-Jordan]], podemos hacer una serie de transformaciones elementales de filas ([[Transformación elemental de filas]]) para convertir $A$ en su forma normal ([[Forma normal de una matriz]]) $H$. Es decir, $A \sim_f A' \sim_f A'' \sim_f \dots \sim_f H$. Por lo que hemos visto en [[Matriz elemental de tipo I]], [[Matriz elemental de tipo II]], [[Matriz elemental de tipo III]], $\exists E_1$ elemental tal que $E_1 A = A'$, $\exists E_2$ elemental tal que $E_2 A' = A''$ y así sucesivamente hasta llegar a $H$.
Sea $k$ el número de transformaciones elementales que realizamos, nos damos cuenta de que $H = E_k A^{(k-1)} = E_k E_{k-1} A^{(k-2)} = \dots = E_k \dots E_1 A = H$. Llamemos $E_k \dots E_1 = P$, sabemos que $E_i$ es invertible $\forall i$ y que además $P$ es invertible (porque el producto de matrices invertibles es invertible). Ahora, haciendo transformaciones elementales de columnas, podemos convertir $H$ en una matriz de la forma $\begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$: $H \sim_c H' \sim_c H'' \sim_c \dots \sim_c \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$. Por tanto, $\exists E_1'$ tal que $HE_1' = H'$, $\exists E_2'$ tal que $H'E_2' = H''$. Análogamente a como lo hemos hecho con las filas, llegamos a que $\begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} = HE_1' \dots E_l'$, vamos a llamar $Q = E_1' \dots E_l'$. Así, $PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$. Además, está claro que $r = rg(A)$ por la [[Proposición el rango de una matriz no cambia al multiplicarla por matrices invertibles]].

Además, hemos visto que $\exists E_1, \dots, E_k, E_1', \dots, E_l'$ tales que $(E_1 \dots E_k) A (E_1' \dots E_l') = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$.

---
### Referencias

[[Equivalencia de matrices#2. Matrices elementales]]

[[Teorema producto por matrices invertibles matriz sencilla]]
