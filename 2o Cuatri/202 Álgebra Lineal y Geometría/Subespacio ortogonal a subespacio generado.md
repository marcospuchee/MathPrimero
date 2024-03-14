
---
mathLink: $U = \langle u_1, u_2, \dots, u_m \rangle \implies U^\perp = \{u_1, \dots, u_m\}^\perp$
---
### Contenido Principal

**Fecha:** 2024-02-23, 16:58

Sea $F$ [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ ([[Subespacio vectorial]]). Entonces,

```ad-proposition
$$U = \langle u_1, u_2, \dots, u_m \rangle \implies U^\perp = \{u_1, \dots, u_m\}^\perp$$
```

```ad-proof
Queremos ver que $U^\perp = \{u_1, \dots, u_m\}^\perp$.
$\subseteq$.
Dado que $\{u_1, \dots, u_m \} \subseteq U$, por la nota en [[Subespacio ortogonal a un subespacio]], $U^\perp \subseteq \{u_1, \dots, u_m \}^\perp$.

$\supseteq$.
Sea $x \in \{u_1, \dots, u_m \}^\perp$. Tenemos $F(x,v_i) = 0, \forall i = 1, \dots, m$. Sea $u \in U$ cualquiera, $\exists \alpha_1, \dots, \alpha_m \in \mathbb K$ tal que $u = \alpha_1 u_1 + \dots + \alpha_m u_m$.
Ahora, 
$$F(x,u) = F(x, \alpha_1 v_1 + \dots + \alpha_m u_m) = \alpha_1 F(x, u_1) + \dots + \alpha_m F(x, u_m) = 0$$
Por tanto, $x \in U^\perp$. Deducimos que $\{u_1, \dots, u_m \}^\perp \subseteq U^\perp$.
```

**Tema:** [[Formas bilineales]]
**Corolarios:** [[Teorema dimensión subespacio ortogonal]]

---
### Anki

START
Respuesta anidada
Sea $F$ [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ ([[Subespacio vectorial]]). Entonces,
$${{c1::U = \langle u_1, u_2, \dots, u_m \rangle}} \implies {{c2::U^\perp = \{u_1, \dots, u_m\}^\perp}}$$
Tags: proposición/teorema ÁlgebraI
<!--ID: 1708973800389-->
END

START
Básico
Anverso: Demostración de que sea $F$ [[Forma bilineal simétrica]] sobre $V$, y sea $U \le V$ ([[Subespacio vectorial]]). Entonces,
$$U = \langle u_1, u_2, \dots, u_m \rangle \implies U^\perp = \{u_1, \dots, u_m\}^\perp$$
Reverso: Queremos ver que $U^\perp = \{u_1, \dots, u_m\}^\perp$.
$\subseteq$.
Dado que $\{u_1, \dots, u_m \} \subseteq U$, por la nota en [[Subespacio ortogonal a un subespacio]], $U^\perp \subseteq \{u_1, \dots, u_m \}^\perp$.

$\supseteq$.
Sea $x \in \{u_1, \dots, u_m \}^\perp$. Tenemos $F(x,v_i) = 0, \forall i = 1, \dots, m$. Sea $u \in U$ cualquiera, $\exists \alpha_1, \dots, \alpha_m \in \mathbb K$ tal que $u = \alpha_1 u_1 + \dots + \alpha_m u_m$.
Ahora, 
$$F(x,u) = F(x, \alpha_1 v_1 + \dots + \alpha_m u_m) = \alpha_1 F(x, u_1) + \dots + \alpha_m F(x, u_m) = 0$$
Por tanto, $x \in U^\perp$. Deducimos que $\{u_1, \dots, u_m \}^\perp \subseteq U^\perp$.
Tags: demostración ÁlgebraI
<!--ID: 1708973800393-->
END
