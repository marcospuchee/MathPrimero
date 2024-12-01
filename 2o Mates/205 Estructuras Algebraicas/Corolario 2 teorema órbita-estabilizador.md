### Contenido Principal

```ad-cor
Sea $G \curvearrowright \Omega$. Si $\Omega$ es finito y las órbitas de longitud mayor que $1$ ($\alpha \notin \Omega_{\textrm{fix}}$) están representadas por elementos $\alpha_{t+1}$, $\alpha_{t+2}$, $\dots$, $\alpha_n$, entonces
$$|\Omega| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb} \\_ {\alpha \\_ i}|$$
```

^83344a

```ad-proof
Dado que $|\Omega| = \sum^n_ {i = 1} |\textrm{Orb}_ {\alpha_ i}|$, ordenamos $\alpha_1, \alpha_2, \dots, \alpha_n$ de forma que los primeros elementos sean puntos fijos, esto es, tales que $\textrm{Orb}_{\alpha_i} = \{\alpha_i\}$. Digamos que son $t$.

Entonces, notamos que $\Omega_\textrm{fix} = \{\alpha_1, \dots, \alpha_t \}$.
$\supseteq$. Evidentemente, $\forall 1 \le i \le t$, como $\textrm{Orb}_{\alpha_i} = \{\alpha_i\}$, entonces $\alpha_i \in \Omega_\textrm{fix}$.
$\subseteq$. Sea $\gamma \in \Omega_{\textrm{fix}}$. Como $\{\textrm{Orb}_\alpha : \alpha \in \Omega \}$ forma una partición de $\Omega$, $\gamma$ pertenece a una, y solo una órbita, $\gamma \in \textrm{Orb}_\gamma = \{\gamma \}$. Por tanto, $\gamma \in \{\alpha_1, \dots, \alpha_t \}$.

Por tanto,
$$|\Omega| = \sum_{i = 1}^n |\textrm{Orb}_{\alpha_i}| = \sum_{i = 1}^t |\textrm{Orb}_{\alpha_i}| + \sum_{i = t+1}^n |\textrm{Orb}_{\alpha_i}| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb}_{\alpha_i}|.$$
```

**Tema:** [[Acciones de grupos#2. Teorema Órbita-Estabilizador.]]

**Definiciones referenciadas:** [$G \curvearrowright \Omega$](Acción de grupo), [$\Omega \\_ \textrm{fix}$](Órbita), [$\textrm{Orb} \\_ \alpha$](Órbita).
**Resultados referenciados:** [$|\Omega| = \sum^n_ {i = 1} |\textrm{Orb}_ {\alpha_ i}|$](Corolario teorema órbita-estabilizador)

---
### Anki

START
Respuesta anidada
Sea $G \curvearrowright \Omega$. Si $\Omega$ es {{c1::finito}} y las órbitas de longitud mayor que $1$ ($\alpha \notin \Omega_{\textrm{fix}}$) {{c1::están representadas por elementos $\alpha_{t+1}$, $\alpha_{t+2}$, $\dots$, $\alpha_n$}}, entonces
$${{c2::|\Omega|}} = {{c3::|\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb} \\_ {\alpha \\_ i}|}}$$
Tags: est
<!--ID: 1731931805054-->
END

START
Básico
Anverso: Demostración de que sea $G \curvearrowright \Omega$. Si $\Omega$ es finito y las órbitas de longitud mayor que $1$ ($\alpha \notin \Omega_{\textrm{fix}}$) están representadas por elementos $\alpha_{t+1}$, $\alpha_{t+2}$, $\dots$, $\alpha_n$, entonces
$$|\Omega| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb} \\_ {\alpha \\_ i}|$$
Reverso: Dado que $|\Omega| = \sum^n_ {i = 1} |\textrm{Orb}_ {\alpha_ i}|$, ordenamos $\alpha_1, \alpha_2, \dots, \alpha_n$ de forma que los primeros elementos sean puntos fijos, esto es, tales que $\textrm{Orb}_{\alpha_i} = \{\alpha_i\}$. Digamos que son $t$.

Entonces, notamos que $\Omega_\textrm{fix} = \{\alpha_1, \dots, \alpha_t \}$.
$\supseteq$. Evidentemente, $\forall 1 \le i \le t$, como $\textrm{Orb}_{\alpha_i} = \{\alpha_i\}$, entonces $\alpha_i \in \Omega_\textrm{fix}$.
$\subseteq$. Sea $\gamma \in \Omega_{\textrm{fix}}$. Como $\{\textrm{Orb}_\alpha : \alpha \in \Omega \}$ forma una partición de $\Omega$, $\gamma$ pertenece a una, y solo una órbita, $\gamma \in \textrm{Orb}_\gamma = \{\gamma \}$. Por tanto, $\gamma \in \{\alpha_1, \dots, \alpha_t \}$.

Por tanto,
$$|\Omega| = \sum_{i = 1}^n |\textrm{Orb}_{\alpha_i}| = \sum_{i = 1}^t |\textrm{Orb}_{\alpha_i}| + \sum_{i = t+1}^n |\textrm{Orb}_{\alpha_i}| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb}_{\alpha_i}|.$$
Tags: dem est
<!--ID: 1731931805058-->
END

