2024-01-17, 19:08
### Contenido principal

Esta nota hace referencia a la entropía de Shannon, no a la de física.

La entropía de Shannon es una cantidad que describe la cantidad de incertidumbre que posee una determinada variable. Es decir, describe la distribución de una probabilidad. La entropía alcanza su punto máximo en $p(x) = 0.5$.

Esta es la fórmula de la entropía:
$$ H = -\sum_{i = 1}^n p(x_i) \log_2(p(x_i))$$
donde $x_i$ son los valores que tenemos, y $p(x_i)$ la probabilidad de que ocurra. La base del logaritmo puede ser cualquiera. En este caso, como la base es 2, la unidad de medida es _'bits'_. En cambio, si el logaritmo es natural, la unidad de medida es _'nats'_.

Un conjunto con alta entropía tiene alta varianza ([[Medidas de dispersión]]). La principal diferencia entre entropía y varianza es que la entropía es no linear y no hace falta asumir ninguna distribución. En cambio, la varianza se asocia con la [[Distribución normal]].

--- 
### Referencias

[[Conceptos de Deep Learning#Matemáticas, NumPY, PyTorch]]

---
### Anki

START
Básico
Anverso: Qué es la [[entropía]] de Shannon?
Reverso: La entropía de Shannon es una cantidad que describe la cantidad de incertidumbre que posee una determinada variable. Es decir, describe la distribución de una probabilidad. La entropía alcanza su punto máximo en $p(x) = 0.5$.
Tags: definición
<!--ID: 1705771401019-->
END

START
Básico
Anverso: Cuál es la fórmula de la [[entropía]] de Shannon?
Reverso: Esta es la fórmula de la entropía:
$$ H = -\sum_{i = 1}^n p(x_i) \log_2(p(x_i))$$
donde $x_i$ son los valores que tenemos, y $p(x_i)$ la probabilidad de que ocurra. La base del logaritmo puede ser cualquiera. En este caso, como la base es 2, la unidad de medida es _'bits'_. En cambio, si el logaritmo es natural, la unidad de medida es _'nats'_.
Tags: definición
<!--ID: 1705771401022-->
END

START
Básico
Anverso: Qué relación guarda la [[entropía]] con la varianza?
Reverso: Un conjunto con alta entropía tiene alta varianza ([[Medidas de dispersión]]). La principal diferencia entre entropía y varianza es que la entropía es no linear y no hace falta asumir ninguna distribución. En cambio, la varianza se asocia con la distribución normal.
Tags: definición
<!--ID: 1705771401025-->
END