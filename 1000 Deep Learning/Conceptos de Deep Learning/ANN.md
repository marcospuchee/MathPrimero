2023-12-23, 20:44
### Contenido principal

ANN son las iniciales de _'Artificial Neural Network'_, es decir, [Red Neuronal Artificial](https://es.wikipedia.org/wiki/Red_neuronal_artificial). Una red neuronal artificial se encarga de pasar de un input a un output. Por ejemplo, tu historial de búsqueda con la probabilidad de que hagas click en un anuncio.

La forma en que se pasa del input ($x_i$) al output ($\hat y$) es: 
$$\hat{y} = \sigma(\sum_{i = 0}^n x_i w_i)$$
donde $\hat y$ es la predicción, $x_i$ es el valor de la $i$-ésima variable $X$ y $w_i$ es el _'weight'_, que especifica cómo de importante es cada input para la predicción. Las $w_i$ las aprende la máquina a través de lo que se conoce como [[Backpropagation]]. Dado que el sumatorio daría lugar a una ecuación linear, en [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) se pueden resolver también problemas no-lineales, así se añade la función $\sigma$ que es no lineal.

Luego, una Red Neuronal Artificial es un conjunto muy grande de
$$\sigma(\sum_{i = 0}^n x_i w_i)$$
que dan lugar a un $\hat y$.

--- 
### Referencias

[[Conceptos de Deep Learning#ANN]]

---
### Anki

START
KaTeX and Markdown Basic
Front: Qué quiere decir ANN?
Back: ANN son las iniciales de _'Artificial Neural Network'_, es decir, [Red Neuronal Artificial](https://es.wikipedia.org/wiki/Red_neuronal_artificial). Una red neuronal artificial se encarga de pasar de un input a un output. Por ejemplo, tu historial de búsqueda con la probabilidad de que hagas click en un anuncio.
Tags: definición
<!--ID: 1703419705077-->
END

START
KaTeX and Markdown Basic
Front: Cómo funciona un ANN?
Back: La forma en que se pasa del input ($x_i$) al output ($\hat y$) es: 
$$\hat{y} = \sigma(\sum_{i = 0}^n x_i w_i)$$
donde $\hat y$ es la predicción, $x_i$ es el valor de la $i$-ésima variable $X$ y $w_i$ es el _'weight'_, que especifica cómo de importante es cada input para la predicción. Las $w_i$ las aprende la máquina a través de lo que se conoce como [Backpropagation](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s). Dado que el sumatorio daría lugar a una ecuación linear, en [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) se pueden resolver también problemas no-lineales, así se añade la función $\sigma$ que es no lineal.

Luego, una Red Neuronal Artificial es un conjunto muy grande de
$$\sigma(\sum_{i = 0}^n x_i w_i)$$
que dan lugar a un $\hat y$.
Tags: definición
<!--ID: 1703419651642-->
END


