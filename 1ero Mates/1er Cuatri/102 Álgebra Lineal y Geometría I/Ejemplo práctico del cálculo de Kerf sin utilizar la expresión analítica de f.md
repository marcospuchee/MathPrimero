2023-12-17, 14:07
### Contenido principal

Sea $A = \begin{pmatrix} 1 && -1 && 0 && 1 \\ 0 && 1 && 1 && 1 \\ 2 && -1 && 1 && 3 \end{pmatrix} \in M_{3 \times 4} (\mathbb R)$, encuentra $P$ y $Q$ invertibles tales que $PAQ = \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix}$. Según el procedimiento en [[Teorema producto por matrices invertibles matriz sencilla]], necesitamos encontrar $Kerf$ si queremos resolver este problema. Esta es la manera corta de conseguir $Kerf$ sin utilizar la expresión de $f$:

Sabemos que $Kerf = \{(x, y, z, t) \in \mathbb R ^4 | f(x,y,z,t) = 0\} = \{(x,y,z,t) \in \mathbb R^4 | f(x,y,z,t)_{B_c'} = 0_{B_c'} \} =$ $\{(x,y,z,t) \in \mathbb R^4 | A \begin{pmatrix} x \\ y \\ z \\ t \end{pmatrix} = \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix} \}$, según [[Cálculo de las coordenadas una imagen dada la matriz asociada]]. Si realizamos el producto de $A$ por las [[Coordenadas]] de $(x,y,z,t)$ en la base canónica de $\mathbb R^4$, nos da el [[Sistemas de ecuaciones lineales]] con [[Forma matricial de un sistema de ecuaciones]]:
$$ \begin{pmatrix}1 && -1 && 0 && 1 && 0 \\ 0 && 1 && 1 &&1&&0\\2&&-1&&1&&3&&0 \end{pmatrix} $$

--- 
### Referencias

[[Equivalencia de matrices#1. Rango]]

Ejemplo sacado de: https://youtu.be/XoN24A1doVk?si=_nAosiNezg79P_cs