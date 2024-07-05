### Contenido principal

Fecha: 2024-05-02, 17:42

```ad-note
title: Ejemplo
Sea $(A, V, +)$ [[espacio afín]], y sea $v \in V$. Definimos $T_v: A \to A$ con $P \to P+v$. Veamos que $T_v$ es una [[aplicación afín]] asociada a la aplicación lineal $Id_V: V \to V$.

$\forall P, Q \in A$, tenemos:
$$\begin{array}{l}
\overrightarrow{PT_v(Q)} = \vec{PQ} + \overrightarrow{QT_v(Q)} = \vec{PQ} + \overrightarrow{Q(Q+v)} = \vec{PQ} + v,  \\
\overrightarrow{PT_v(Q)} = \overrightarrow{PT_v(P)} + \overrightarrow{T_v(P) T_v(Q)} = \overrightarrow{P(P+v)} + \overrightarrow{T_v(P)T_v(Q)} = v + \overrightarrow{T_v(P)T_v(Q)}.
\end{array}$$
Por tanto, $\vec{PQ} + v = \overrightarrow{T_v(P)T_v(Q)} + v$. Luego, $\overrightarrow{T_v(P)T_v(Q)} = \vec{PQ} = id_V(\vec{PQ})$, $\forall P, Q \in A$.

Así, la aplicación $T_v$ es la traslación del vector $v$. En particular, hemos visto que $T_v$ es un isomorfismo afín (porque $id_V$ es biyectiva y [[inyectividad, sobreyectividad y biyectividad de apliaciones afines respecto sus subyacentes]]).
```

**Tema:** [[Aplicaciones afines]]
**Referencias:**

---
### Anki

START
Básico
Anverso: Cuál es la aplicación afín que define la translación de un vector, cuál es su aplicación lineal subyacente?
Reverso: Sea $(A, V, +)$ [[Espacio afín]], y sea $v \in V$. Definimos $T_v: A \to A$ con $P \to P+v$. Veamos que $T_v$ es una [[Aplicación afín]] asociada a la aplicación lineal $Id_V: V \to V$.

$\forall P, Q \in A$, tenemos:
$$\begin{array}{l}
\overrightarrow{PT_v(Q)} = \vec{PQ} + \overrightarrow{QT_v(Q)} = \vec{PQ} + \overrightarrow{Q(Q+v)} = \vec{PQ} + v,  \\
\overrightarrow{PT_v(Q)} = \overrightarrow{PT_v(P)} + \overrightarrow{T_v(P) T_v(Q)} = \overrightarrow{P(P+v)} + \overrightarrow{T_v(P)T_v(Q)} = v + \overrightarrow{T_v(P)T_v(Q)}.
\end{array}$$
Por tanto, $\vec{PQ} + v = \overrightarrow{T_v(P)T_v(Q)} + v$. Luego, $\overrightarrow{T_v(P)T_v(Q)} = \vec{PQ} = id_V(\vec{PQ})$, $\forall P, Q \in A$.

Así, la aplicación $T_v$ es la traslación del vector $v$. En particular, hemos visto que $T_v$ es un isomorfismo afín (porque $id_V$ es biyectiva y [[inyectividad, sobreyectividad y biyectividad de apliaciones afines respecto sus subyacentes]]).
Tags: demostración ÁlgebraI
<!--ID: 1714669443514-->
END
