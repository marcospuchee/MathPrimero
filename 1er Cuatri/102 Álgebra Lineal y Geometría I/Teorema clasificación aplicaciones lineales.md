### Enunciado Teorema 

Sea $f: K^n \rightarrow K^m$ una aplicación. Entonces $f$ es lineal $\iff \forall (x_1, \dots, x_n) \in K^n$, $f(x_1, \dots, x_n) =$ $(a_{1,1} x_1 + \dots + a_{1,n} x_n, \dots, a_{m,1} x_1 + \dots + a_{m,n} x_n)$ para algunos $a_{i,j} \in K$.

Como todo $k$-[[Espacio vectorial finitamente generado]] es isomorfo ([[Isomorfismo]]) a algún $K^n$, este teorema esencialmente clasifica todas las aplicaciones lineales.

---
### Demostración

$\leftarrow$.
Sea $\lambda, \mu \in K$, $(x_1, \dots, x_n), (y_1, \dots, y_n) \in K^n$, queremos ver cuánto es $f(\lambda(x_1, \dots, x_n) + \mu(y_1, \dots, y_n))= f(\lambda x_1 + \mu y_1, \dots, \lambda x_n + \mu y_n)$. Vamos a aplicar la definición de $f$ que tenemos de hipótesis:

$(a_{1,1}(\lambda x_1 + \mu y_1) + \dots + a_{1,n}(\lambda x_n + \mu y_n), \dots, a_{m,1}(\lambda x_1  + \mu y_1) + \dots + a_{m,n} (\lambda x_n + \mu y_n))$.

Vamos a separar $x_i$ e $y_i$:
$\lambda (a_{1,1} x_1 + \dots + a_{1,n} x_n, \dots, a_{m,1} x_1+ \dots + a_{m,n} x_n) +\mu(a_{1,1} y_1 + \dots + a_{1,n} y_n, \dots, a_{m,1} y_1 + \dots + a_{m,n} y_n)$
Vamos a sustituir por la hipótesis: $\lambda f(x_1, \dots, x_n) + \mu f(y_1, \dots, y_n)$. Por tanto, acabamos de ver que $f$ es lineal.

$\rightarrow$.
Sea $f: K^n \rightarrow K^m$ lineal, queremos ver que $f$ sea una aplicación de las que describe el teorema. Consideremos la base canónica de $K^n$, sea $B_c = \{e_1, \dots, e_n\}$ la base canónica de $K^n$, entonces $f(e_1) = (a_{1,1}, \dots a_{m,1}), \dots, f(e_n) = (a_{1,n}, \dots, a_{m,n})$ para algunos $a_{i,j} \in K$. Por el [[Teorema de existencia y unicidad de aplicaciones lineales]], $\exists ! f: K^n \rightarrow K^m$ que cumpla estas condiciones.
Sea $(x_1, \dots, x_n) \in K^n$, entonces $(x_1, \dots, x_n) = x_1 e_1 + \dots + x_n e_n$. Así, $f(x_1, \dots, x_n) = f(x_1 e_1 + \dots + x_n e_n) = x_1 f(e_1) + \dots + x_n f(e_n)$. Sustituyendo por la definición de $f$ que hemos dado antes, esto es: $x_1 (a_{1,1}, \dots, a_{m,1}) + \dots + x_n (a_{1,n}, \dots, a_{m,n})$. 
Hacemos la suma: $(a_{1,1} x_1 + \dots + a_{1,n} x_n, \dots, a_{m,1} x_1 + \dots a_{m,n} x_n)$. 

---
### Referencias

[[Aplicación lineal]]
