### Enunciado Teorema

La [[Ley de buena ordenación]] es equivalente al [[Principio de inducción débil]].

---
### Demostración

Veamos que $LBO \implies PID$. Sea $P$ una propiedad sobre los  naturales que verifica que:
1. $P(1)$ cierto.
2. $P(n)$ cierto $\implies P(n+1)$ cierto.

Denominamos $A=\{n \in \mathbb{N} : P(n)$ falso $\}$. Si demostramos que $A=\emptyset$, habremos demostrado que $P(n)$ es cierta $\forall n \in \mathbb{N}$. Supongamos que $A \not = \emptyset$. Por la ley de buena ordenación sabemos que existe $m \in A$ tal que $m \le a, \forall a \in A$. Por estar $m \in A$, sabemos que $P(m)$ no es cierta. Como $P(1)$ cierta, sabemos que $m > 1$. Por ser $m$ mínimo de $A$ sabemos que $m-1 \not \in A$, con lo que $P(m-1)$ cierta. Pero entonces, por (2) sabemos que $P(m)$ es cierta, y llegamos la contradicción. Por tanto, $A = \emptyset$.

---
### Referencias
[[Divisibilidad]]