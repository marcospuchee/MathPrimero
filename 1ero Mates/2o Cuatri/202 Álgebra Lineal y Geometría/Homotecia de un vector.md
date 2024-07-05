### Contenido principal

Fecha: 2024-05-02, 17:50

```ad-note
title: Ejemplo
Sea $(A, V, +)$ [[espacio afín]] (donde $V$ es un $\mathbb K$-espacio vectorial). Sean $C \in A$ y $\alpha \in \mathbb K$. La homotecia de centro $C$ y razón $\alpha$ es la aplicación $h_{C, \alpha}: A \to A$ con $P \to C + \alpha \vec{CP}$.

Veamos que $h_{C, \alpha}$ es una aplicación afín cuya aplicación lineal subyacente es $\alpha Id_V: V \to V$ con $v \to \alpha v$.

Notemos que $\overrightarrow{Ch(P)} = \overrightarrow{C(C+ \alpha \vec{CP})} = \alpha \vec{CP}$ y $\overrightarrow{Ch(P)} = \vec{CP} + \overrightarrow{Ph(P)}$. Luego $\overrightarrow{Ph(P)} = \alpha \vec{CP} - \vec{CP} = (\alpha-1) \vec{CP}$.

Ahora,
$$\begin{array}{l}
\overrightarrow{Ph(Q)} = \overrightarrow{Ph(P)} + \overrightarrow{h(P)h(Q)}, \\
\overrightarrow{Ph(Q)} = \vec{PQ} + \overrightarrow{Qh(Q)}
\end{array}$$
Luego,
$$\begin{eqnarray}
\overrightarrow{h(P)h(Q)} &=& \vec{PQ} + \overrightarrow{Qh(Q)} - \overrightarrow{Ph(P)} = \vec{PQ} + (\alpha-1)\vec{CQ} - (\alpha -1)\vec{CP} = \\
&=& \vec{PQ} + (1-\alpha)(\vec{QC} + \vec{CP}) = \vec{PQ} + (1-\alpha)(\vec{QP}) = (1-1+\alpha)\vec{PQ} = \alpha \vec{PQ} = \alpha Id_V (\vec{PQ})
\end{eqnarray}$$
```

**Tema:** [[Aplicaciones afines]]
**Referencias:**

---
### Anki

START
Básico
Anverso: Cuál es la aplicación afín que define la homotecia de un vector, cuál es su aplicación lineal subyacente?
Reverso: Sea $(A, V, +)$ [[Espacio afín]] (donde $V$ es un $\mathbb K$-espacio vectorial). Sean $C \in A$ y $\alpha \in \mathbb K$. La homotecia de centro $C$ y razón $\alpha$ es la aplicación $h_{C, \alpha}: A \to A$ con $P \to C + \alpha \vec{CP}$.

Veamos que $h_{C, \alpha}$ es una aplicación afín cuya aplicación lineal subyacente es $\alpha Id_V: V \to V$ con $v \to \alpha v$.

Notemos que $\overrightarrow{Ch(P)} = \overrightarrow{C(C+ \alpha \vec{CP})} = \alpha \vec{CP}$ y $\overrightarrow{Ch(P)} = \vec{CP} + \overrightarrow{Ph(P)}$. Luego $\overrightarrow{Ph(P)} = \alpha \vec{CP} - \vec{CP} = (\alpha-1) \vec{CP}$.

Ahora,
$$\begin{array}{l}
\overrightarrow{Ph(Q)} = \overrightarrow{Ph(P)} + \overrightarrow{h(P)h(Q)}, \\
\overrightarrow{Ph(Q)} = \vec{PQ} + \overrightarrow{Qh(Q)}
\end{array}$$
Luego,
$$\begin{eqnarray}
\overrightarrow{h(P)h(Q)} &=& \vec{PQ} + \overrightarrow{Qh(Q)} - \overrightarrow{Ph(P)} = \vec{PQ} + (\alpha-1)\vec{CQ} - (\alpha -1)\vec{CP} = \\
&=& \vec{PQ} + (1-\alpha)(\vec{QC} + \vec{CP}) = \vec{PQ} + (1-\alpha)(\vec{QP}) = (1-1+\alpha)\vec{PQ} = \alpha \vec{PQ} = \alpha Id_V (\vec{PQ})
\end{eqnarray}$$
Tags: demostración ÁlgebraI
<!--ID: 1714669443509-->
END