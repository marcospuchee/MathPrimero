### Proposición
Toda sucesión de una sucesión convergente, converge al límite de la sucesión.

---
### Demostración

Sea $(a_n)^\infty_{n=1}$ una sucesión convergente a $l$. Sea $(a_{n_k})^\infty_{k=1}$ una subsucesión suya. Veamos que $\exists \lim_{x \to \infty} a_{n_k} = l$. Como $lim_{n \to \infty} a_n = l$, dado $\epsilon > 0$, $\exists k_o \in \mathbb{N} : |a_n - l| < \epsilon, \forall n \ge k_o$. 

Si $k \ge k_o, n_k \ge n_{k_0} \ge k_o$. Por tanto, $|a_{n_k} - l |< \epsilon \implies lim_{k \to \infty} a_{n_k} = l$.

---
### Referencias
[[Sucesión]]