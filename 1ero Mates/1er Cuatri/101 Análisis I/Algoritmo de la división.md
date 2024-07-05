### Contenido principal

Dados $n, m \in \mathbb{N}$, $n \le m$ y $n \not = 0$, $\exists q,r \in \mathbb{N}$, donde $r < n$, tales que $m = nq +r$.

En efecto:
- Si $n = m \implies q=1, r=0$
- Si $n<m$, $\exists p1 \in \mathbb{N}$ tal que $m = n+p1$ ($0 < p1 < m$):
	1. Caso 1. $p1 < n$ entonces $q = 1, r = p1$.
	2. Caso 2. $p1  = n$; $m = n + n = 2n$ entonces $q=2, r = 0$
	3. Caso 3. $p1 > n$; $\exists p2$ tal que $p1 = n + p2$ ($0 < p2  < p1$). $m = n + n + p2 = 2n + p2$.
		1. $p2 < n$. Lo mismo que antes.
		2. $p2 = n$. Lo mismo que antes.
		3. $p2 > n$. Lo mismo que antes.


--- 
### Referencias

[[Teorema de la división euclídea]]