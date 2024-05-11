
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-20, 17:28

```ad-cor
Si $p$ es un [[número primo]] positivo, $p \nmid a$ y $n \equiv m \pmod{p-1}$ entonces
$$a^n \equiv a^m \pmod p.$$
```

```ad-proof
Supongamos que $n > m$. Como $n-m$ es múltiplo de $p-1$, se tiene que
$$n = m+(p-1)u$$
para algún $u \in \mathbb Z$. Por el [[primer teorema de Fermat]], $a^{p-1} \equiv 1 \pmod p$, y haciendo la potencia $u$-ésima, $a^{u(p-1)} \equiv 1 \pmod p$. Si ahora multiplicamos por $a^m$ se obtiene $a^{m+u(p-1)} \equiv a^m \pmod p$, es decir, $a^n \equiv a^m \pmod p$.
```

**Tema:** [[Aritmética modular#5. Primer teorema de Fermat - Teorema de Euler]]
**Corolarios:**

---
### Anki
