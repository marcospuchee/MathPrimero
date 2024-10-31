### Contenido Principal


```ad-theorem
Si $G$ y $H$ son grupos cíclicos ([[grupo cíclico]]) con $|G| = |H|$, entonces $G \cong H$. Específicamente:
1. Si $\langle x \rangle$ es un grupo cíclico infinito, entonces la aplicación
$$\begin{matrix}
\textrm{exp} : & (\mathbb Z, +) & \to & (\langle x \rangle, \cdot) \\
& n & \to & x^n
\end{matrix}$$
es un isomorfismo. Por tanto, $\langle x \rangle \cong \mathbb Z$.

2. Si $\langle x \rangle$ y $\langle y \rangle$ son grupos cíclicos de orden $n \in \mathbb Z^+$, entonces la aplicación
$$\begin{matrix}
\overline{\textrm{exp}}: & (\langle x \rangle, \cdot) & \to & (\langle y \rangle, \cdot) \\
& x^n & \to & y^n
\end{matrix}$$
es un isomorfimos. En particular, $\langle x \rangle \cong \mathbb Z_n$.
```

^6b08f1

```ad-proof
1. Sabemos que la función $\textrm{exp}$ es homomorfismo. Falta ver que es biyectiva. Sin embargo, por [[propiedades orden grupos cíclicos]], sabemos que es inyectiva, y es evidente que es sobreyectiva.
2. Tenemos que
$$\overline{\textrm{exp}}(x^p \cdot x^q) = \overline{\textrm{exp}}(x^{p+q}) = y^{p+q} = y^p \cdot y^q \implies \overline{\textrm{exp}}(x^p) = \overline{\textrm{exp}}(x^q),$$
luego es homomorfismo. Además,
$$\textrm{Ker}(\overline{\textrm{exp}}) = \{x^m : \overline{\textrm{exp}}(x^m) = 1_G \} = \{x^m : y^m = 1_G \} = \{1_G\},$$
donde la última igualdad se deriva de [[propiedades orden grupos cíclicos]]. Que sea sobreyectiva es evidente.
```

**Tema:** [[Teoría de grupos#9. Homomorfismos.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Cuál es el teorema de unicidad de grupos cíclicos
Reverso: Si $G$ y $H$ son grupos cíclicos ([[grupo cíclico]]) con $|G| = |H|$, entonces $G \cong H$. Específicamente:
1. Si $\langle x \rangle$ es un grupo cíclico infinito, entonces la aplicación
$$\begin{matrix}
\textrm{exp} : & (\mathbb Z, +) & \to & (\langle x \rangle, \cdot) \\
& n & \to & x^n
\end{matrix}$$
es un isomorfismo. Por tanto, $\langle x \rangle \cong \mathbb Z$.

2. Si $\langle x \rangle$ y $\langle y \rangle$ son grupos cíclicos de orden $n \in \mathbb Z^+$, entonces la aplicación
$$\begin{matrix}
\overline{\textrm{exp}}: & (\langle x \rangle, \cdot) & \to & (\langle y \rangle, \cdot) \\
& x^n & \to & y^n
\end{matrix}$$
es un isomorfimos. En particular, $\langle x \rangle \cong \mathbb Z_n$.
Tags: est
<!--ID: 1728549801126-->
END

START
Básico
Anverso: Demostración de que si $G$ y $H$ son grupos cíclicos ([[grupo cíclico]]) con $|G| = |H|$, entonces $G \cong H$. Específicamente:
1. Si $\langle x \rangle$ es un grupo cíclico infinito, entonces la aplicación
$$\begin{matrix}
\textrm{exp} : & (\mathbb Z, +) & \to & (\langle x \rangle, \cdot) \\
& n & \to & x^n
\end{matrix}$$
es un isomorfismo. Por tanto, $\langle x \rangle \cong \mathbb Z$.

2. Si $\langle x \rangle$ y $\langle y \rangle$ son grupos cíclicos de orden $n \in \mathbb Z^+$, entonces la aplicación
$$\begin{matrix}
\overline{\textrm{exp}}: & (\langle x \rangle, \cdot) & \to & (\langle y \rangle, \cdot) \\
& x^n & \to & y^n
\end{matrix}$$
es un isomorfimos. En particular, $\langle x \rangle \cong \mathbb Z_n$.
Reverso: 
1. Sabemos que la función $\textrm{exp}$ es homomorfismo. Falta ver que es biyectiva. Sin embargo, por [[propiedades orden grupos cíclicos]], sabemos que es inyectiva, y es evidente que es sobreyectiva.
2. Tenemos que
$$\overline{\textrm{exp}}(x^p \cdot x^q) = \overline{\textrm{exp}}(x^{p+q}) = y^{p+q} = y^p \cdot y^q \implies \overline{\textrm{exp}}(x^p) = \overline{\textrm{exp}}(x^q),$$
luego es homomorfismo. Además,
$$\textrm{Ker}(\overline{\textrm{exp}}) = \{x^m : \overline{\textrm{exp}}(x^m) = 1_G \} = \{x^m : y^m = 1_G \} = \{1_G\},$$
donde la última igualdad se deriva de [[propiedades orden grupos cíclicos]]. Que sea sobreyectiva es evidente.
Tags: dem est
<!--ID: 1728549801184-->
END
