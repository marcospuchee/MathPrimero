### Contenido Principal

```ad-theorem
Sea $G$ un $p$-grupo y $G \curvearrowright \Omega$. Entonces
$$|\Omega| \equiv |\Omega \\_ \textrm{fix}| \pmod p.$$
```

^daaf34

```ad-proof
Por el corolario anterior, $\exists \alpha_{t+1}, \dots, \alpha_n \in \Omega$ tales que:
$$|\Omega| = |\Omega_\textrm{fix}|+ \sum_{i = t+1}^n |\textrm{Orb}_{\alpha_i}| = |\Omega_\textrm{fix}| + \sum_{i = t+1} |G: \textrm{Stab}_{\alpha_i}|.$$
Ahora notamos que: $\forall t+1 \le i \le n$, como $\textrm{Stab}_{\alpha_i} \le G$, entonces $|G:\textrm{Stab}_{\alpha_i}| \mid |G| = p^n$. En particular, $|G:\textrm{Stab}_{\alpha_i}| \equiv 0 \pmod p$. Así:
$$|\Omega| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |G: \textrm{Stab}_{\alpha_i}| \equiv |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n 0 \equiv |\Omega_{\textrm{fix}}| \pmod p.$$
```

**Tema:** [[Acciones de grupos#2. Teorema Órbita-Estabilizador.]]
**Corolario:**

**Definiciones referenciadas:** [$p$-grupo](p-grupo), [$\Omega \\_ \textrm{fix}$](Órbita).
**Resultados referenciados:** [$|\Omega| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb} \\_ {\alpha \\_ i}|$](Corolario 2 teorema órbita-estabilizador)

---
### Anki

START
Respuesta anidada
Sea $G$ un {{c1::$p$-grupo}} y {{c1::$G \curvearrowright \Omega$}}. Entonces
$${{c2::|\Omega|}} \equiv {{c3::|\Omega \\_ \textrm{fix}|}} \pmod p.$$
Tags: est
<!--ID: 1731931804928-->
END