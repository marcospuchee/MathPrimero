
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-04-18, 16:06

```ad-lemma
Sea $(A, V, +)$ un [[espacio afín]], se satisface:
1. $\forall P, Q, R \in A, \quad \vec{PR} = \vec{PQ} + \vec{QR}$ (relación Chasles).
2. $\forall P, Q \in A, \quad \vec{PQ} = 0 \iff P = Q$.
3. $\forall P, Q \in A, \quad \vec{PQ} = - \vec{QP}$.
4. $\forall P, Q,R,S \in A, \quad \vec{PQ} = \vec{RS} \iff \vec{PR} = \vec{QS}$ (ley del paralelogramo).
```

```ad-proof
**$(i)$**
$$P + (\vec{PQ} + \vec{QR}) = (P + \vec{PQ}) + \vec{QR} = Q + \vec{QR} = R,$$
y deducimos que $\vec{PR} = \vec{PQ} + \vec{PR}.$

**$(ii)$.**
Sea $P, Q \in A$, Si $P = Q$, por $(i)$ tenemos:
$$\vec{PR} = \vec{PP} + \vec{PR} \implies \vec{PP} = 0,$$
ya que sumando $- \vec{PR}$ a ambas partes, se queda $\vec{PP} = 0$. Por tanto, $\vec{PQ} = 0$ si $P = Q$. Veamos hacia la otra dirección. Supongamos que $\vec{PQ} = 0$. Entonces, como sabemos por la primera parte de esta demostración que $\vec{PP} = 0$, tenemos:
$$Q = P + \vec{PQ} = P + (\vec{PP} + \vec{PQ}) = P + \vec{PP} =  P.$$

**$(iii)$.**
Sean $P, Q \in A$ caulesquiera, por $(i)$ y $(ii)$, tenemos:
$$0 = \vec{PP} = \vec{PQ} + \vec{QP} \implies \vec{QP} = -\vec{PQ}.$$

**$(iv)$.**
Por $(i)$, tenemos que $\vec{PS} = \vec{PQ} + \vec{QS} \land \vec{PS} = \vec{PR} + \vec{RS}$, luego deducimos que $\vec{PQ} = \vec{RS} \iff \vec{QS} = \vec{PR}$.
```

**Tema:** [[Espacios afines]]
**Corolarios:** [[Ecuación cambio de sistema de referencia]], [[Resultados para variedades afines]]

---
### Anki

START
Básico
Anverso: Qué propiedades cumple todo espacio afín?
Reverso: Sea $(A, V, +)$ un [[espacio afín]], se satisface:
1. $\forall P, Q, R \in A, \quad \vec{PR} = \vec{PQ} + \vec{QR}$ (relación Chasles).
2. $\forall P, Q \in A, \quad \vec{PQ} = 0 \iff P = Q$.
3. $\forall P, Q \in A, \quad \vec{PQ} = - \vec{QP}$.
4. $\forall P, Q,R,S \in A, \quad \vec{PQ} = \vec{RS} \iff \vec{PR} = \vec{QS}$ (ley del paralelogramo).
Tags: proposición/teorema ÁlgebraI
<!--ID: 1714060760890-->
END

START
Básico
Anverso: Demostración de que sea $(A, V, +)$ un [[espacio afín]], se satisface:
1. $\forall P, Q, R \in A, \quad \vec{PR} = \vec{PQ} + \vec{QR}$ (relación Chasles).
2. $\forall P, Q \in A, \quad \vec{PQ} = 0 \iff P = Q$.
3. $\forall P, Q \in A, \quad \vec{PQ} = - \vec{QP}$.
4. $\forall P, Q,R,S \in A, \quad \vec{PQ} = \vec{RS} \iff \vec{PR} = \vec{QS}$ (ley del paralelogramo).
Reverso: **$(i)$**
$$P + (\vec{PQ} + \vec{QR}) = (P + \vec{PQ}) + \vec{QR} = Q + \vec{QR} = R,$$
y deducimos que $\vec{PR} = \vec{PQ} + \vec{PR}.$

**$(ii)$.**
Sea $P, Q \in A$, Si $P = Q$, por $(i)$ tenemos:
$$\vec{PR} = \vec{PP} + \vec{PR} \implies \vec{PP} = 0,$$
ya que sumando $- \vec{PR}$ a ambas partes, se queda $\vec{PP} = 0$. Por tanto, $\vec{PQ} = 0$ si $P = Q$. Veamos hacia la otra dirección. Supongamos que $\vec{PQ} = 0$. Entonces, como sabemos por la primera parte de esta demostración que $\vec{PP} = 0$, tenemos:
$$Q = P + \vec{PQ} = P + (\vec{PP} + \vec{PQ}) = P + \vec{PP} =  P.$$

**$(iii)$.**
Sean $P, Q \in A$ caulesquiera, por $(i)$ y $(ii)$, tenemos:
$$0 = \vec{PP} = \vec{PQ} + \vec{QP} \implies \vec{QP} = -\vec{PQ}.$$

**$(iv)$.**
Por $(i)$, tenemos que $\vec{PS} = \vec{PQ} + \vec{QS} \land \vec{PS} = \vec{PR} + \vec{RS}$, luego deducimos que $\vec{PQ} = \vec{RS} \iff \vec{QS} = \vec{PR}$.
Tags: demostración ÁlgebraI
<!--ID: 1714060760911-->
END