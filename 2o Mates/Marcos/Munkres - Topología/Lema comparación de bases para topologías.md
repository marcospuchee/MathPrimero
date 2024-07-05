
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-06-17, 20:47

```ad-lemma
Sean $\mathcal B$ y $\mathcal B'$ bases para las topologías $\mathcal T$ y $\mathcal T'$ ([[base para una topología]]), respectivamente, sobre $X$. Entonces son equivalentes:
1. $\mathcal T'$ es más fina ([[topologías comparables]]) que $\mathcal T$.
2. $\forall x \in X$ y $B \in \mathcal B$ tal que $x \in B$, $\exists B' \in \mathcal B'$ tal que $x \in B' \subset B$.
```

```ad-proof
$(ii) \implies (i)$.
Dado un elemento $U$ de $\mathcal T$, queremos probar que $U \in \mathcal T'$. Sea $x \in U$. Sea $x \in U$. Puesto que $\mathcal B$ genera a $\mathcal T$, $\exists B \in \mathcal B$ tal que $x \in B \subset U$. Por hipótesis, $\exists B' \in \mathcal B'$ tal que $x \in B' \subset B$. Entonces $x \in B' \subset U$, por lo que $U \in \mathcal T'$, por definición.

$(i) \implies (ii)$.
Tenemos $x \in B$ y $B \in \mathcal B$, con $x \in B$. Ahora bien, $B \in \mathcal T$ por definición, y $\mathcal T \subset \mathcal T'$ por hipótesis, luego $B \in \mathcal T'$. Puesto que $\mathcal T'$ está generada por $\mathcal B'$, $\exists B' \in \mathcal B'$ tal que $x \in B' \subset B$.
```

**Tema:** [[Espacios topológicos y funciones continuas#2. Base de una topología]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sean $\mathcal B$ y $\mathcal B'$ bases para las topologías $\mathcal T$ y $\mathcal T'$ ([[base para una topología]]), respectivamente, sobre $X$. Entonces son equivalentes:
1. {{c1::$\mathcal T'$ es más fina ([[topologías comparables]]) que $\mathcal T$.}}
2. {{c2::$\forall x \in X$ y $B \in \mathcal B$ tal que $x \in B$, $\exists B' \in \mathcal B'$ tal que $x \in B' \subset B$.}}
Tags: proposición/teorema top
<!--ID: 1718723531795-->
END

START
Básico
Anverso: Demostración de que sean $\mathcal B$ y $\mathcal B'$ bases para las topologías $\mathcal T$ y $\mathcal T'$ ([[base para una topología]]), respectivamente, sobre $X$. Entonces son equivalentes:
1. $\mathcal T'$ es más fina ([[topologías comparables]]) que $\mathcal T$.
2. $\forall x \in X$ y $B \in \mathcal B$ tal que $x \in B$, $\exists B' \in \mathcal B'$ tal que $x \in B' \subset B$.
Reverso: $(ii) \implies (i)$.
Dado un elemento $U$ de $\mathcal T$, queremos probar que $U \in \mathcal T'$. Sea $x \in U$. Sea $x \in U$. Puesto que $\mathcal B$ genera a $\mathcal T$, $\exists B \in \mathcal B$ tal que $x \in B \subset U$. Por hipótesis, $\exists B' \in B'$ tal que $x \in B' \subset B$. Entonces $x \in B' \subset U$, por lo que $U \in \mathcal T'$, por definición.

$(i) \implies (ii)$.
Tenemos $x \in B$ y $B \in \mathcal B$, con $x \in B$. Ahora bien, $B \in \mathcal T$ por definición, y $\mathcal T \subset \mathcal T'$ por hipótesis, luego $B \in \mathcal T'$. Puesto que $\mathcal T'$ está generada por $\mathcal B'$, $\exists B' \in \mathcal B'$ tal que $x \in B' \subset B$.
Tags: demostración top
<!--ID: 1718723531807-->
END
