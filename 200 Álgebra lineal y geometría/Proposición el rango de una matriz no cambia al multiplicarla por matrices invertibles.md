### Proposición

Sean $A \in M_{m \times n} (K), P \in GL_m (K)$ ([[Endomorfismo biyectivo]], [[Matriz invertible]]), $Q \in GL_n (K)$, entonces:
1) $rg_c (A) = rg_c (PAQ)$
2) $rg_f (A) = rg_f (PAQ)$

Dado que la matriz identidad $I_n$ también es invertible, esta proposición también cumple el caso $rg_c (A) = rg_c(PA) = rg_c(AQ)$, y viceversa con filas. 

---
### Demostración

1) Sea $f : K^n \rightarrow K^m$ la [[Aplicación lineal]] tal que $M_{B_c, B_c'} (f) = A$ ([[Matriz asociada a una aplicación lineal]])(ejercicio: por qué existe y es única esta f? ([[Teorema de existencia y unicidad de aplicaciones lineales]]). Veamos el siguiente diagrama:![[Pasted image 20231208205647.png]]Los cuadros azules son cosas que no tenemos. Nos gustaría encontrar $B$ [[Base]] de $K^n$ y $B'$ base de $K^m$ tales que $M_{B,B'} (f) = PAQ$. Una vez conseguido esto, tendremos que (por [[Coincidencia rango de una aplicación lineal con el rango de columnas de cualquier matriz asociada]]), $rg_c (PAQ) = rg(f) = rg_c(A)$. La forma de encontrar $B, B'$ es a través de la [[Proposición toda matriz invertible es de cambio de base]]: como $P$ es invertible, $\exists B'$ base de $K^m$ tal que $B_c' \rightarrow^P B'$, es decir, $P = M_{B_c', B_c} (id_{K^m})$. Como $Q$ es invertible, $\exists B$ base de $K^n$ tal que $B \rightarrow^Q B_c$, es decir, $Q = M_{B,B_c} (id_{K^n})$. Falta ver que $M_{B,B'} (f) = PAQ$, lo cual queda justificado por [[Proposición matriz asociada a la composición de aplicaciones lineales]]:![[Pasted image 20231209133548.png]]
2) Para esto hace falta saber lo que es la [[Matriz traspuesta]] y algunas de sus propiedades ([[Propiedades de la matriz traspuesta]]). $rg_f(A) = rg_c(A^t)$. Como $A \in M_{m \times n} (K) \implies A^t \in M_{n \times m} (K)$, esto es importante para ver por qué matrices invertibles deberíamos multiplicar $A^t$. Por ejemplo, $rg_c(A^t) = rg_c(QA^tP)$, pero como queremos llegar a que $rg_f(A) = rg_f(PAQ)$, entonces conociendo cómo es la traspuesta de un producto de matrices, nos quedamos con que $rg_c(A^t) = rg_c(Q^tA^tP^t)$, y así, como $Q^tA^tP^t = (PAQ)^t$, nos queda que $rg_c((PAQ)^t) = rg_f(((PAQ)^t)^t) = rg_f(PAQ)$. 

---
### Referencias

[[Equivalencia de matrices#1. Rango]]