### Enunciado Teorema

Si $\{I_n\}_{n \in \mathbb{N}}$ es un sistema de intervalos ([[Familia de intervalos encajados]]) CERRADOS encajados, entonces $\cap_{n \in \mathbb{{N}}} I_n \not = \phi$ (la intersección de los intervalos $\not = \phi$).

Además, si se cumple para cada $\epsilon > 0, \exists n \in \mathbb{N}$ tal que $diamI_n < \epsilon$, (épsilon es la longitud del intervalo) entonces $\cap_{n \in \mathbb{N}} I_n$ se reduce a un único punto.

Si $I_n = [a_n, b_n], diamI_n = b_n - a_n$.
 
---
### Demostración

Sea $I_n = [a_n, b_n], a_n < b_n$, llamamos $A = \{a_n: n \in \mathbb{N}\}$ y $B = \{b_n : n \in \mathbb{N}\}$.
Como $[a_{n+1}, b_{n+1} ] \subset [a_n, b_n] \forall n \in \mathbb{N}$, se puede afirmar que $a_1 \le \dots \le a_n \le a_{n+1} \le b_{n+1} \le b_n \le \dots \le b_1.$

Luego $A$ está acotado superiormente y $B$ está acotado inferiormente, luego existen el $supA = a$ y existe el $infB = b$. Además $a \le b$.
Veamos que $[a, b] = \cap_{n\in\mathbb{N}} I_n$: en efecto, $x \in [a,b] \iff a \le x \le b$. (??? [[Teorema de la densidad de Q en R]]).
Como $a = supA$ y $b = infB$, $a_n \le x \le b_n \forall n \in \mathbb{N}$, por lo que $x \in [a_n, b_n]$ y $x \in \cap_{n \in \mathbb{N}} [a_n, b_n]$.ç
En conclusión $[a,b] \subset \cap I_n$.

##### Demostración de que se reduce a un único punto (si se cumplen las condiciones necesarias)

Supongamos ahora que para cada $\epsilon > 0$, existe $n \in \mathbb{N}$ tal que $b_n - a_n < \epsilon$. $\epsilon$ es la distancia del intervalo. Veamos que $a = b$:

Como $[a, b] \subset [a_n, b_n]$, $0 \le b-a \le b_n - a_n < \epsilon$. Como $\epsilon > 0$ es arbitrario, concluimos que $b - a = 0$, por lo que el intervalo es un punto.



---
### Referencias
