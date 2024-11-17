### Enunciado Teorema

Sean $A, C \in M_{m \times n} (K)$. Son equivalentes:
1) $A \sim C$ ([[Matrices equivalentes]])
2) $rg(A) = rg(C)$.
3) $A$ y $C$ representan la misma [[Aplicación lineal]] en dos pares de [[Base]], esto es, si $f : V \rightarrow V'$ con $B$ base de $V$ y $B'$ base de $V'$ y $M_{B, B'} (f) = A$ ([[Matriz coordenada]]) , entonces $\exists \widetilde{B}$ base de $V$ y $\widetilde B'$ base de $V'$ tal que $M_{\widetilde{B}, \widetilde{B'}} (f) = C$.

---
### Demostración

#### 1 $\implies$ 2
$\exists P, Q$ [[Matriz invertible]] tales que $PAQ = C$ (). Utilizando: [[Proposición el rango de una matriz no cambia al multiplicarla por matrices invertibles]], sabemos que $rg(A) = rg(PAQ) = rg(C)$.
#### 2 $\implies$ 1
$rg(A) = rg(C) = r$. Sabemos por ([[Teorema producto por matrices invertibles matriz sencilla]]) que $A \sim \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} \sim C$. Así, como $\sim$ es una [[Relación de equivalencia]], por la propiedad transitiva, $A \sim C$.
#### 1 $\implies$ 3
$\exists P, Q$ invertibles tales que $PAQ = C$. También tenemos que $f : V \rightarrow V'$ con $B$ base de $V$ y $B'$ base de $V'$ tal que $M_{B, B'} (f) = A$. Componemos a izquierda y derecha con las identidades tal que: ![[Pasted image 20240110200137.png]]
y buscamos $\widetilde B, \widetilde{B}'$ y $C$. Como sabemos que $PAQ = C$, nos gustaría que $M_{B', \widetilde{B'}} (id_{V'}) = P$ y que $M_{\widetilde B, B} (id_V) = Q$. Porque por la [[Proposición matriz asociada a la composición de aplicaciones lineales]], $PAQ = M_{\widetilde B, \widetilde{B'}} (f) = C$ luego tendríamos lo que buscamos. Como $P$ es [[Matriz invertible]], $\exists \widetilde{B'}$ [[Base]] de $V'$ tal que $B' \rightarrow^P \widetilde{B'}$ ([[Matriz cambio de base]]) por la [[Proposición toda matriz invertible es de cambio de base]]. Análogamente, $\exists \widetilde B$ base de $V$ tal que $\widetilde B \rightarrow^Q B$. Es decir, $P = M_{B', \widetilde{B'}} (id_{V'})$ y $Q = M_{\widetilde B, B} (id_V)$. Así, $M_{\widetilde B, \widetilde{B'}} (f) = PAQ = C$.
#### 3 $\implies$ 1
Tenemos:
![[Pasted image 20240115115102.png]]
¿$\exists P,Q$ [[Matriz invertible]] tales que $PAQ = C$?
Sea $P = M_{B', \widetilde{B'}} (id_{V'})$ y $Q = M_{\widetilde B, B} (id_V)$. Como son matrices asociadas a la identidad, son matrices de cambio de base ([[Matriz cambio de base]]), luego $P$ y $Q$ son invertibles ([[Proposición toda matriz invertible es de cambio de base]]). Por la fórmula [[Proposición matriz asociada a la composición de aplicaciones lineales]], $C = M_{\widetilde B, \widetilde{B'}} (f) = PAQ$. Luego $A \sim C$.

---
### Referencias

[[Equivalencia de matrices#3. Matrices equivalentes]]

---
### Anki

START
Básico
Anverso: Demuestra que sean $A, C \in M_{m \times n} (K)$. Son equivalentes:
1) $A \sim C$ ([[Matrices equivalentes]])
2) $rg(A) = rg(C)$. 
Reverso:
#### 1 $\implies$ 2
$\exists P, Q$ [[Matriz invertible]] tales que $PAQ = C$ (). Utilizando: [[Proposición el rango de una matriz no cambia al multiplicarla por matrices invertibles]], sabemos que $rg(A) = rg(PAQ) = rg(C)$.
#### 2 $\implies$ 1
$rg(A) = rg(C) = r$. Sabemos por ([[Teorema producto por matrices invertibles matriz sencilla]]) que $A \sim \begin{pmatrix} I_r && 0 \\ 0 && 0 \end{pmatrix} \sim C$. Así, como $\sim$ es una [[Relación de equivalencia]], por la propiedad transitiva, $A \sim C$.

Tags: demostración
<!--ID: 1705316321417-->
END

START
Básico
Anverso: Demuestra que sean $A, C \in M_{m \times n} (K)$. Son equivalentes:
1) $A \sim C$ ([[Matrices equivalentes]])
2) $A$ y $C$ representan la misma [[Aplicación lineal]] en dos pares de [[Base]], esto es, si $f : V \rightarrow V'$ con $B$ base de $V$ y $B'$ base de $V'$ y $M_{B, B'} (f) = A$ ([[Matriz coordenada]]) , entonces $\exists \widetilde{B}$ base de $V$ y $\widetilde B'$ base de $V'$ tal que $M_{\widetilde{B}, \widetilde{B'}} (f) = C$.
Reverso:
#### 1 $\implies$ 2
$\exists P, Q$ invertibles tales que $PAQ = C$. También tenemos que $f : V \rightarrow V'$ con $B$ base de $V$ y $B'$ base de $V'$ tal que $M_{B, B'} (f) = A$. Componemos a izquierda y derecha con las identidades tal que: ![[Pasted image 20240110200137.png]]
y buscamos $\widetilde B, \widetilde{B}'$ y $C$. Como sabemos que $PAQ = C$, nos gustaría que $M_{B', \widetilde{B'}} (id_{V'}) = P$ y que $M_{\widetilde B, B} (id_V) = Q$. Porque por la [[Proposición matriz asociada a la composición de aplicaciones lineales]], $PAQ = M_{\widetilde B, \widetilde{B'}} (f) = C$ luego tendríamos lo que buscamos. Como $P$ es [[Matriz invertible]], $\exists \widetilde{B'}$ [[Base]] de $V'$ tal que $B' \rightarrow^P \widetilde{B'}$ ([[Matriz cambio de base]]) por la [[Proposición toda matriz invertible es de cambio de base]]. Análogamente, $\exists \widetilde B$ base de $V$ tal que $\widetilde B \rightarrow^Q B$. Es decir, $P = M_{B', \widetilde{B'}} (id_{V'})$ y $Q = M_{\widetilde B, B} (id_V)$. Así, $M_{\widetilde B, \widetilde{B'}} (f) = PAQ = C$.
#### 2 $\implies$ 1
Tenemos:
![[Pasted image 20240115115102.png]]
¿$\exists P,Q$ [[Matriz invertible]] tales que $PAQ = C$?
Sea $P = M_{B', \widetilde{B'}} (id_{V'})$ y $Q = M_{\widetilde B, B} (id_V)$. Como son matrices asociadas a la identidad, son matrices de cambio de base ([[Matriz cambio de base]]), luego $P$ y $Q$ son invertibles ([[Proposición toda matriz invertible es de cambio de base]]). Por la fórmula [[Proposición matriz asociada a la composición de aplicaciones lineales]], $C = M_{\widetilde B, \widetilde{B'}} (f) = PAQ$. Luego $A \sim C$.

Tags: demostración
<!--ID: 1705316321421-->
END
