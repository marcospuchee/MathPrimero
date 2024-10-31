### Contenido Principal

```ad-cor
Sea $f: \Omega \subseteq \mathbb R^n \to \mathbb R$, donde $\Omega$ es abierto en $\mathbb R^n$, $a \in \Omega$, $f$ diferenciable en $a$. Supongamos que $\nabla f(a) \neq 0$. Entonces, la [[derivada direccional]] de $f$ en $a$ es máxima en la dirección del [[vector gradiente]].

Es decir, $v = \frac{\nabla f(a)}{|| \nabla f(a)||}$ cumple que
$$\max \{D_u f(a) : u \in \mathbb R^n, \, u \neq 0 \} = D_v f(a) = || \nabla f(a) ||.$$
```

^129915

```ad-proof
Por [[caracterización de función diferenciable]], sabemos que
$$D_v f(a) = \langle \nabla f(a), v \rangle = \langle \nabla f(a), \frac{\nabla f(a)}{|| \nabla f(a)||} \rangle = || \nabla f(a)||.$$

Sea $u \in \mathbb R^n$ con $||u|| = 1$, se cumple que
$$D_u f(a) = \langle \nabla f(a), u \rangle \le || \nabla f(a)|| \cdot || u || = || \nabla f(a)||.$$
```

**Tema:** [[Diferenciabilidad de funciones de varias variables#2. Matrices jacobianas y vector gradiente.]]

---
### Anki

START
Básico
Anverso: Cuál es la interpretación del vector gradiente?
Reverso: Sean $f: \Omega \subseteq \mathbb R^n \to \mathbb R$, donde $\Omega$ es abierto en $\mathbb R^n$, $a \in \Omega$, $f$ diferenciable en $a$. Supongamos que $\nabla f(a) \neq 0$. Entonces, la [[derivada direccional]] de $f$ en $a$ es máxima en la dirección del [[vector gradiente]].

Es decir, $v = \frac{\nabla f(a)}{|| \nabla f(a)||}$ cumple que
$$\max \{D_u f(a) : u \in \mathbb R^n, \, u \neq 0 \} = D_v f(a) = || \nabla f(a) ||.$$
Tags: anII
<!--ID: 1728820185224-->
END

START
Básico
Anverso: Demostración de que sean $f: \Omega \subseteq \mathbb R^n \to \mathbb R$, donde $\Omega$ es abierto en $\mathbb R^n$, $a \in \Omega$, $f$ diferenciable en $a$. Supongamos que $\nabla f(a) \neq 0$. Entonces, la [[derivada direccional]] de $f$ en $a$ es máxima en la dirección del [[vector gradiente]].

Es decir, $v = \frac{\nabla f(a)}{|| \nabla f(a)||}$ cumple que
$$\max \{D_u f(a) : u \in \mathbb R^n, \, u \neq 0 \} = D_v f(a) = || \nabla f(a) ||.$$
Reverso: Por [[caracterización de función diferenciable]], sabemos que
$$D_v f(a) = \langle \nabla f(a), v \rangle = \langle \nabla f(a), \frac{\nabla f(a)}{|| \nabla f(a)||} \rangle = || \nabla f(a)||.$$

Sea $u \in \mathbb R^n$ con $||u|| = 1$, se cumple que
$$D_u f(a) = \langle \nabla f(a), u \rangle \le || \nabla f(a)|| \cdot || u || = || \nabla f(a)||.$$
Tags: dem anII
<!--ID: 1728820185227-->
END

