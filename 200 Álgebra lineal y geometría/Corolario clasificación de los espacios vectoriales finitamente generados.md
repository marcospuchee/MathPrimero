### Corolario

Sea $V$ un $k$-[[Espacio vectorial finitamente generado]], $dimV = n \iff V \cong K^n$ ([[Isomorfismo]]).

---
### Demostración

$\rightarrow$.
Sean $B = \{v_1, \dots, v_n\}$ [[Base]] de $V$ y $B_c = \{e_1 \dots, e_n\}$ la base canónica de $K^n$, entonces por el [[Teorema de existencia y unicidad de aplicaciones lineales]], $\exists ! f : V \to K^n$ lineal tal que $f(v_i) = e_i \forall i$. Como $f$ envía una base de $V$ a una base de $K^n$, entonces por (iii) de [[Proposición sg, sl y base con aplicaciones lineales]], $f$ es biyectiva. Como es lineal y biyectiva, entonces se sigue que $f$ es un isomorfismo.

$\leftarrow$. 
Esto se puede extrapolar a cualquier $V \cong V'$: $V \cong V' \implies dimV = dim{V'}$. En efecto, como $V \cong V', \exists f: V \to V'$ lineal y biyectiva. Por tanto, si $B$ es base de $V$, entonces $f(B)$ es base de $V'$ por (iii) [[Proposición sg, sl y base con aplicaciones lineales]]. Como $f$ es biyectiva, $dimV = |B| = |f(B)| = dim(V')$ 

---
### Referencias

[[Aplicación lineal]]