### Contenido principal

```ad-Formal
Sean $\Omega \subset \mathbb R^n$ abierto, decimos que $f: \Omega \to \mathbb R^n$ es un cambio de variable si
- $f \in C^1(\Omega)$.
- $f$ inyectiva.
- $J_f(x) \neq 0$, $\forall x \in \Omega$.
```

```ad-note
- $f$ cambio de variable $\implies$ $B = f(\Omega)$ abierto  y la inversa $f^{-1}: B \to \Omega$ es de clase $C^1$.
- La composición de cambios de variable es un cambio de variable.
```


**Tema:** [[Los teoremas de la función inversa y de la función implícita#2. Cambios de variable.]]

**Definiciones referenciadas:**  [$C^1$](Función de clase C1), [$J_f(x)$](Determinante jacobiano)

---
### Ejemplos

```ad-Ejemplo
**Coordenadas polares.**
$f: ]0, + \infty[ \times \mathbb R \to \mathbb R^2$, $f(\rho, \theta) = (\rho \cos \theta, \rho \sin \theta)$. Notemos que
$$J_f(\rho, \theta) = \det \begin{pmatrix} \cos \theta & - \rho \sin \theta \\
\sin \theta & \rho \cos \theta \end{pmatrix} = \rho \neq 0.$$
Por tanto, $f$ es localmente inyectiva, pero no globalmente inyectiva: $f(\rho, \theta + 2\pi k) = f(\rho, \theta)$. Para ello, restringimos $f$ a $B = ]0, +\infty[ \times [0, 2\pi[$, y tenemos que $f$ es inyectiva en $B$. Pero $f(B) = \mathbb R^2 \textrm{\\} \{(0,0)\}$. Tomando $U = ]0, + \infty[ \times ]0, 2\pi[$, $f: U \to \mathbb R^2$ es un cambio de variable y $f(U) = \mathbb R^2 \textrm{\\} \{(x,0) : x \ge 0 \}$ es abierto.
```

```ad-Ejemplo
**Coordenadas cilíndricas.**
$f: ]0, +\infty[ \times \mathbb R^2 \to \mathbb R^2$, $f(\rho, \theta, z) = (\rho \cos \theta, \rho \sin \theta, z)$. Notemos que $J_f(\rho, \theta, z) = p > 0$.

Tenemos que $f$ es localmente inyectiva pero no globalmente inyectiva y,
$$f(]0, +\infty[ \times \mathbb R^2) = \mathbb R^3 \textrm{\\} \{(0,0,z) : z \in \mathbb R \}.$$
Sin embargo, $f: ]0, +\infty[ \times ]0, 2\pi[ \times \mathbb R \to \mathbb R^3$ es un cambio de variable y su imagen es:
$$f(]0, +\infty[ \times ]0, 2\pi[ \times \mathbb R) = \mathbb R^3 \textrm{\\} \{(z,0,z) : x \ge 0, z \in \mathbb R \}.$$
```

```ad-Ejemplo
$f: ]0,+\infty[ \times ]0, 2\pi[ \times ]0, \pi[ \to \mathbb R^3$ con $f(\rho, \theta, \varphi) = (\rho \cos \theta \sin \varphi, \rho \sin \theta \sin \varphi, \rho \cos \varphi)$. Notemos que $J_f(\rho, \theta, \varphi) = \rho^2 \sin \varphi > 0$ ya que $\varphi \in ]0, \pi[$. 

Luego $f$ es un cambio de variable, y  su imagen es
$$f(]0, + \infty[ \times ]0, 2\pi[ \times ]0, \pi[) = \mathbb R^3 \textrm{\\} \{(x,0,z) : x \ge 0, z \in \mathbb R \},$$
que es abierto.
```


---
### Anki
