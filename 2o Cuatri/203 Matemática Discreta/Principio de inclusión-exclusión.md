
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-02-05, 21:53

Sea $X$ un conjunto y sean $A_1, A_2, \dots A_n$ subconjuntos. Entonces, 

```ad-theorem
$$\bigg | \bigcup_{i = 1}^n A_i \bigg | = \sum_{I \in \mathcal P(\{1,2, \dots, n\}) - \{\emptyset\}} (-1)^{|I| - 1} \bigg | \bigcap_{i \in I} A \bigg | $$
```


```ad-proof
Procederemos por inducción sobre $n$.

**$n=1$**. Queremos que $|\bigcup_{i = 1}^n A_i| = |A_1|$. Aplicando la fórmula, tenemos que $\sum_{I \in \mathcal P(\{1\}) - \{\emptyset\}} (-1)^{|I| - 1} | \bigcap_{i \in I} A_i| = (-1)^{1-1} |\bigcap_{i \in \{1\}} A_i| = |A_1|$. Por tanto, la fórmula queda probada para $n = 1$.

Es necesario probarla para **$n=2**. Según el teorema,
$$|A_1 \cup A_2| = |A_1| + |A_2| - |A_1 \cap A_2|$$
La unión $A_1 \cup A_2$ se puede poner como la unión disjunta
$$A_1 \cup A_2 = (A_1 \text{\\} A_2) \cup (A_2 \text{\\} A_1) \cup (A_1 \cap A_2)$$
donde $|A_1 \text{\\} A_2| = |A_1| - |A_1 \cap A_2|$ y $|A_2 \text{\\} A_1| = |A_2| - |A_1 \cap A_2|$. Usando el [[Principio de la suma]], se obtiene la expresión del enunciado.

Supongamos ahora que la ecuación es cierta para $n = k$, es decir,
$$\bigg | \bigcup_{i = 1}^k A_i \bigg | = \sum_{I \in \mathcal P(\{1,2, \dots, k\}) - \{\emptyset\}} (-1)^{|I| - 1} \bigg | \bigcap_{i \in I} A \bigg |$$
Falta probarlo para $n = k+1$:
$$| \bigcup_{i = 1}^{k+1} A_i | = | (\bigcup_{i = 1}^k A_i) \cup A_{k+1}| = |\bigcup_{i = 1}^k A_i | + |A_{k+1}| - |(\bigcup_{i = 1}^k A_i) \cap A_{k+1}|$$
donde se ha usado la hipótesis para el caso $n = 2$. Vamos a buscar que esta expresión coincida con:
$$\sum_{I \in \mathcal P(\{1,2, \dots, k+1\}) - \{\emptyset\} } (-1)^{|I| - 1} |\bigcap_{i \in I} A_i|$$

Descompongamos ahora el conjunto $\mathcal P(\{1, 2, \dots, k, k+1\})$ en tres subconjuntos distintos:
- $S_1 = \mathcal P(\{1, 2, \dots, k\})$
- $S_2 = \{\{k+1\} \}$
- $S_3 = \{X \cup \{k+1\} : X \in \mathcal P(\{1, 2, \dots, k\}) - \{\emptyset\} \}$.

Si separamos los índices $I$ según estén en $S_1, S_2$ o $S_3$, obtenemos los sumadnos que buscamos:
$$
\begin{gather*}
\sum_{I \in \mathcal P(\{1,2, \dots, k+1\}) - \{\emptyset\} } (-1)^{|I| - 1} |\bigcap_{i \in I} A_i| = \\
\sum_{i \in S_1 - \{\emptyset\} } (-1)^{|I|-1} |\bigcap_{i \in I} A_i| + \sum_{I \in S_2 - \{\emptyset\}}  (-1)^{|I| - 1} |\bigcap_{i \in I} A_i| + \sum_{I \in S_3 - \{\emptyset\}}  (-1)^{|I| - 1} |\bigcap_{i \in I} A_i|
\end{gather*}
$$
La primera suma es, por la hipótesis de inducción, $|\bigcup_{i = 1}^k A_i|$, la segunda suma es simplemente $|A_{k+1}|$. Si $I \in S_3$ entonces $I = \{j_1, j_2, \dots, j_s, k+1 \}$ con $\{j_1, j_2, \dots, j_s \} \subset \{1, 2, \dots, k\}$ y no vacío. Luego
$$
\begin{align}
(-1)^{|I| -1} |\bigcap_{i \in I} A_i| &= (-1)^{s+1-1} |A_{j1} \cap A_{j2} \cap \dots \cap A_{js} \cap A_{k+1}| \\
&= (-1)^s |(A_{j1} \cap A_{k+1}) \cap (A_{j2} \cap A_{k+1}) \cap \dots \cap (A_{js} \cap A_{k+1})|
\end{align}
$$
Cuando $I$ varia sobre $S_3$, tendremos que evaluar todas las posibilidades de conjuntos $\{j_1, j_2, \dots, j_s\} \subset \{1, \dots, k\}$ no vacíos. Esto nos permite escribir la tercera suma así:
$$
\begin{align}
\sum_{I \in S_3} (-1)^{|I| - 1} |\bigcap_{i \in I} A_i| &= \sum_{I \in \mathcal P(\{1,2, \dots, k\}) - \{\emptyset\} } (-1)^{|I|} |\bigcap_{i \in I} (A_i \cap A_{k+1})| \\
&= - \sum_{I \in \mathcal P(\{1,2, \dots, k\}) - \{\emptyset\} } (-1)^{|I| - 1} |\bigcap_{i \in I} (A_i \cap A_{k+1})| \\
&= -|\bigcup_{i = 1}^{n-1} (A_i \cap A_{k+1})|
\end{align}
$$
En el último paso hemos hecho valer la hipótesis de inducción.
```

**Tema:** [[Métodos de enumeración y combinatoria#4. Principio de inclusión-exclusión]]
**Demostrado por:** 
**Consecuencias:** [[Teorema cálculo función de Euler]]

---
### Anki

START
Básico
Anverso: Qué dice el principio de inclusión-exclusión?
Reverso: Sea $X$ un conjunto y sean $A_1, A_2, \dots A_n$ subconjuntos. Entonces,
$$\bigg | \bigcup_{i = 1}^n A_i \bigg | = \sum_{I \in \mathcal P(\{1,2, \dots, n\}) - \{\emptyset\}} (-1)^{|I| - 1} \bigg | \bigcap_{i \in I} A \bigg | $$
Tags: proposición/teorema
<!--ID: 1707170512628-->
END

START
Básico
Anverso: Demostración del paso inductivo del principio de inclusión-exclusión
Reverso: Supongamos ahora que la ecuación es cierta para $n = k$, es decir,
$$\bigg | \bigcup_{i = 1}^k A_i \bigg | = \sum_{I \in \mathcal P(\{1,2, \dots, k\}) - \{\emptyset\}} (-1)^{|I| - 1} \bigg | \bigcap_{i \in I} A \bigg |$$
Falta probarlo para $n = k+1$:
$$| \bigcup_{i = 1}^{k+1} A_i | = | (\bigcup_{i = 1}^k A_i) \cup A_{k+1}| = |\bigcup_{i = 1}^k A_i | + |A_{k+1}| - |(\bigcup_{i = 1}^k A_i) \cap A_{k+1}|$$
donde se ha usado la hipótesis para el caso $n = 2$. Vamos a buscar que esta expresión coincida con:
$$\sum_{I \in \mathcal P(\{1,2, \dots, k+1\}) - \{\emptyset\} } (-1)^{|I| - 1} |\bigcap_{i \in I} A_i|$$

Descompongamos ahora el conjunto $\mathcal P(\{1, 2, \dots, k, k+1\})$ en tres subconjuntos distintos:
- $S_1 = \mathcal P(\{1, 2, \dots, k\})$
- $S_2 = \{\{k+1\} \}$
- $S_3 = \{X \cup \{k+1\} : X \in \mathcal P(\{1, 2, \dots, k\}) - \{\emptyset\} \}$.

Si separamos los índices $I$ según estén en $S_1, S_2$ o $S_3$, obtenemos los sumadnos que buscamos:
$$
\begin{gather*}
\sum_{I \in \mathcal P(\{1,2, \dots, k+1\}) - \{\emptyset\} } (-1)^{|I| - 1} |\bigcap_{i \in I} A_i| = \\
\sum_{i \in S_1 - \{\emptyset\} } (-1)^{|I|-1} |\bigcap_{i \in I} A_i| + \sum_{I \in S_2 - \{\emptyset\}}  (-1)^{|I| - 1} |\bigcap_{i \in I} A_i| + \sum_{I \in S_3 - \{\emptyset\}}  (-1)^{|I| - 1} |\bigcap_{i \in I} A_i|
\end{gather*}
$$
La primera suma es, por la hipótesis de inducción, $|\bigcup_{i = 1}^k A_i|$, la segunda suma es simplemente $|A_{k+1}|$. Si $I \in S_3$ entonces $I = \{j_1, j_2, \dots, j_s, k+1 \}$ con $\{j_1, j_2, \dots, j_s \} \subset \{1, 2, \dots, k\}$ y no vacío. Luego
$$
\begin{align}
(-1)^{|I| -1} |\bigcap_{i \in I} A_i| &= (-1)^{s+1-1} |A_{j1} \cap A_{j2} \cap \dots \cap A_{js} \cap A_{k+1}| \\
&= (-1)^s |(A_{j1} \cap A_{k+1}) \cap (A_{j2} \cap A_{k+1}) \cap \dots \cap (A_{js} \cap A_{k+1})|
\end{align}
$$
Cuando $I$ varia sobre $S_3$, tendremos que evaluar todas las posibilidades de conjuntos $\{j_1, j_2, \dots, j_s\} \subset \{1, \dots, k\}$ no vacíos. Esto nos permite escribir la tercera suma así:
$$
\begin{align}
\sum_{I \in S_3} (-1)^{|I| - 1} |\bigcap_{i \in I} A_i| &= \sum_{I \in \mathcal P(\{1,2, \dots, k\}) - \{\emptyset\} } (-1)^{|I|} |\bigcap_{i \in I} (A_i \cap A_{k+1})| \\
&= - \sum_{I \in \mathcal P(\{1,2, \dots, k\}) - \{\emptyset\} } (-1)^{|I| - 1} |\bigcap_{i \in I} (A_i \cap A_{k+1})| \\
&= -|\bigcup_{i = 1}^{n-1} (A_i \cap A_{k+1})|
\end{align}
$$
En el último paso hemos hecho valer la hipótesis de inducción.
Tags: demostración
<!--ID: 1707170512634-->
END

START
Básico
Anverso: Demostración del caso base en el principio de inclusión-exclusión
Reverso: **$n=1$**. Queremos que $|\bigcup_{i = 1}^n A_i| = |A_1|$. Aplicando la fórmula, tenemos que $\sum_{I \in \mathcal P(\{1\}) - \{\emptyset\}} (-1)^{|I| - 1} | \bigcap_{i \in I} A_i| = (-1)^{1-1} |\bigcap_{i \in \{1\}} A_i| = |A_1|$. Por tanto, la fórmula queda probada para $n = 1$.

Es necesario probarla para **$n=2$**. Según el teorema,
$$|A_1 \cup A_2| = |A_1| + |A_2| - |A_1 \cap A_2|$$
La unión $A_1 \cup A_2$ se puede poner como la unión disjunta
$$A_1 \cup A_2 = (A_1 \text{\\} A_2) \cup (A_2 \text{\\} A_1) \cup (A_1 \cap A_2)$$
donde $|A_1 \text{\\} A_2| = |A_1| - |A_1 \cap A_2|$ y $|A_2 \text{\\} A_1| = |A_2| - |A_1 \cap A_2|$. Usando el [[Principio de la suma]], se obtiene la expresión del enunciado.
Tags: demostración
<!--ID: 1707170512638-->
END