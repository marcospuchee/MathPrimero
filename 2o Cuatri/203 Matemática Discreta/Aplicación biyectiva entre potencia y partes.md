
---
mathLink: $\exists f : \mathcal P(\mathcal X) \to \{0,1\}^{\mathcal X}$ biyectiva
---
### Contenido Principal

**Fecha:** 2024-02-04, 10:55

Dado un conjunto $\mathcal X$,

```ad-proposition
Existe una aplicación biyectiva entre $\mathcal P(\mathcal X)$ ([[Conjunto de partes]]) y $\{0,1\}^{\mathcal X}$ ([[Conjunto potencia]]).
```


```ad-proof
Sea la aplicación $\psi: \mathcal P(\mathcal X) \to \{0, 1\}^{\mathcal X}$ tal que $\phi(A) = \varphi_A$ ([[Función característica de un conjunto]]).
- Si $\psi (A) = \psi (B):$ si $x \in A$, $\varphi_A(x) =1$; como $\psi(A)(x) = \psi (B)(x)$, $\varphi_B (x) =1$, luego $x \in B$. Si $x \notin A, \varphi_A (x) = 0$; por tanto, $\varphi_B (x) = 0$, luego $x \notin B$. Esto prueba que $\psi(A) = \psi(B) \implies A = B$, luego $\psi$ es inyectiva.ç
- Dada una aplicación $f : \mathcal X \to \{0,1\}$, tomando $A = f^{-1}(\{1\})$, se cumple que $\psi(A) = f$, por lo que $\psi$ es sobreyectiva. En efecto, como $A = \{x \in \mathcal X$ tal que $f(x) = 1\}$ por lo tanto
	- Si $x \in A$, entonces $f(x)=1$.
	- Si $x \notin A$, entonces $f(x) = 0$, porque no hay otra posibilidad.
Observamos que $f$ da las mismas imágenes que $\varphi_A$ luego $f = \varphi_A = \psi(A)$.
```



**Tema:** [[Métodos de enumeración y combinatoria#2. El número de subconjuntos de un conjunto]]
**Corolarios:**

---
### Anki
