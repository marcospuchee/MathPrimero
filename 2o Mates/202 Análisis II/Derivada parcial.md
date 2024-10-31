### Contenido principal

```ad-Formal
Sean $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^m$, $a \in \Omega$, $u \in \mathbb R^n \textrm{\\} \{0\}$. Consideramos la [[derivada direccional]]
$$\lim_{t \to 0} \frac{f(a+tu) - f(a)}{t} = D_u f(a) \in \mathbb R^m.$$

Cuando $u$ es un vector de la base canónica de $\mathbb R^n$, a dichas derivadas las llamamos derivadas parciales. Las denotamos por
$$D_i f(a) = \frac{\partial f}{\partial x_i} = D_{e_i}f(a), \quad \forall i = 1, \dots, n.$$
```

^84fd05

```ad-note
Notemos que si $a = (a_1, \dots, a_n)$,
$$D_i f(a) = \lim_{t \to 0} \frac{f(a_1, \dots, a_i + t, \dots, a_n) - f(a_1, \dots, a_n)}{t}.$$
```

```ad-note
Notemos además que si $f = (f_1, \dots, f_m) : \Omega \subseteq \mathbb R^n \to \mathbb R^m$, entonces
$$\exists D_u f(A) \iff \exists D_u f_j(a), \quad \forall j = 1, \dots, m.$$
Luego $D_u f(a) = (D_uf_1(a), \dots, D_uf_m(a))$.
```


**Tema:** [[Diferenciabilidad de funciones de varias variables#1. Derivadas direccionales y diferencial.]]

---
### Anki

START
Básico
Anverso: Definición de derivada parcial
Reverso: Sean $\Omega \subseteq \mathbb R^n$ abierto, $f: \Omega \to \mathbb R^m$, $a \in \Omega$, $u \in \mathbb R^n \textrm{\\} \{0\}$. Consideramos la [[derivada direccional]]
$$\lim_{t \to 0} \frac{f(a+tu) - f(a)}{t} = D_u f(a) \in \mathbb R^m.$$

Cuando $u$ es un vector de la base canónica de $\mathbb R^n$, a dichas derivadas las llamamos derivadas parciales. Las denotamos por
$$D_i f(a) = \frac{\partial f}{\partial x_i} = D_{e_i}f(a), \quad \forall i = 1, \dots, n.$$
Tags: anII
<!--ID: 1728549801895-->
END