
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-09, 19:39

```ad-theorem
Sea $f: G \to H$ un [[homomorfismo]] entre [[grupo]]s. Entonces, $f$ es un [[isomorfismo]] si y sólo si $\exists f^{-1}: H \to G$ [[homomorfismo]] tal que $f \circ f^{-1} = 1_H$ y $f^{-1} \circ f = 1_G$; donde $1_A$ denota la identidad del conjunto $A$.
```


```ad-proof
$\rightarrow$.
Como $f$ es un isomorfismo, por definición, $\forall b \in H, \, \exists ! a \in G$ tal que $f(a) = b$. Sea $f^{-1}: H \to G$ la aplicación definida por $f^{-1}(b) = a$. Tenemos entonces:
$$\begin{array}{l}
f \circ f^{-1}(b) = f(f^{-1}(b)) = f(a) = b \implies f \circ f^{-1} = 1_H \\
f^{-1} \circ f(a) = f^{-1}(f(a)) = f^{-1}(b) = a \implies f^{-1} \circ f = 1_G
\end{array}.$$
Comprobar que $f^{-1}$ es un homomorfismo es trivial.

$\leftarrow$.
- $f$ inyectiva. Sean $a,b \in G$ tales que $f(a) = f(b)$. Entonces, $f^{-1} \circ f(a) = f^{-1} \circ f(b) \implies a = b$. Luego $f$ es inyectiva.
- $f$ sobreyectiva: sea $b \in H$, queremos ver que $\exists a \in G$ tal que $f(a) = b$. Tomamos $a = f^{-1}(b)$. Así, $f(a) = f(f^{-1}(b)) = b$. Luego $f$ es sobreyectiva.
```


**Tema:** [[Grupos#2. Homomorfismos y subgrupos.]]
**Demostrado por:**
**Consecuencias:**

---
### Anki

START
Respuesta anidada
Sea $f: G \to H$ un [[homomorfismo]] entre [[grupo]]s. Entonces, {{c1::$f$ es un [[isomorfismo]]}} si y sólo si {{c2::$\exists f^{-1}: H \to G$ [[homomorfismo]] tal que $f \circ f^{-1} = 1_H$ y $f^{-1} \circ f = 1_G$; donde $1_A$ denota la identidad del conjunto $A$.}}
Tags: proposición/teorema hungerford
<!--ID: 1721211802884-->
END