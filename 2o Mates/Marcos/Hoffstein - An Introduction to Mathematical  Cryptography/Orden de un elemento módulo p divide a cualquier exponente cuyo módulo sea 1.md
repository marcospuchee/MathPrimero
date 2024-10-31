### Contenido Principal

```ad-proposition
Sea $p$ un [[número primo]] y $a \in \mathbb Z$ tal que $p \nmid a$. Supongamos que $a^n \equiv 1 \pmod p$. Entonces, el orden de $a$ módulo $p$ ([[orden de un elemento módulo p]]) divide a $n$.
```

```ad-proof
Sea $k$ el orden de $a$ módulo $p$. Utilizamos el [[teorema de la división euclídea]]:
$$n = kq + r, \quad 0 \le r < k.$$
Entonces,
$$1 \equiv a^n \equiv a^{kq+r} \equiv (a^k)^q \cdot a^r \equiv 1^q \cdot a^r \equiv a^r \pmod p.$$
Como $<k$, y $k$ es la menor, entonces $r = 0$. Por tanto, $n = kq$, y $k | n$.
```

**Tema:** [[An Introduction to Cryptography#4. Potencias, raíces primitivas y cuerpos finitos.]]

---
### Anki
