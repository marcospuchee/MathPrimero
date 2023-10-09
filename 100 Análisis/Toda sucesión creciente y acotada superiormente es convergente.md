### Proposición

Toda sucesión creciente y acotada superiormente es convergente

---
### Demostración

Sea $(a_n)^\infty_{n=1}$ una sucesión creciente y acotada superiormente, $\exists s = sup(a_n)$. Sea $\epsilon > 0, s - \epsilon$ no es cota superior, por tanto, $\exists n_o \in \mathbb{N}$ tal que $a_{n_0} > s - \epsilon$. Como $(a_n)^\infty_{n=1}$ es creciente, si $n \ge n_o$, $a_n \ge a_{n_o}.$ Luego, $a_n > s- \epsilon$. $s - a_n < \epsilon \implies |a_n - s| < \epsilon$, por lo tanto, $\exists \lim_{n \to \infty} a_n = s$. 

---
### Referencias
[[Sucesión]]
[[Límite de una sucesión]]
