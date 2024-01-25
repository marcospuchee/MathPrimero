2024-01-21, 10:28
### Contenido principal

Las neuronas sigmoid, al igual que los perceptrones ([[Perceptrón]]), toman distintas entradas y devuelven salidas, pero a diferencia de estos, ni las entradas ni las salidas son binarias:
![[Pasted image 20240121100449.png]]
En este ejemplo, tiene tres entradas $(x_1, x_2, x_3)$, pero podría tener más o menos.

Por tanto, los valores ya no son binarios, sino que $x_i \in [0, 1], \forall i$. Para cada entrada $x_i, \exists w_i$ que es el peso de cada entrada, y además, $\exists b$ que es el sesgo (bias). Así, la manera en que se produce una salida no es un $1$ o un $0$, sino que la salida es:
$$\sigma (z) = \frac{1}{1+e^{-z}}$$
donde $z = \sum_j( w_j x_j) -b$.

$\sigma(z)$ es la [[Función sigmoid]].

--- 
### Referencias

[[Neural Networks and Deep Learning#Neuronas sigmoid.]]

---
### Anki

START
Básico
Anverso: Arquitectura de una neurona sigmoid
Reverso: Las neuronas sigmoid, al igual que los perceptrones ([[Perceptrón]]), toman distintas entradas y devuelven salidas, pero a diferencia de estos, ni las entradas ni las salidas son binarias:
![[Pasted image 20240121100449.png]]
En este ejemplo, tiene tres entradas $(x_1, x_2, x_3)$, pero podría tener más o menos.

Por tanto, los valores ya no son binarios, sino que $x_i \in [0, 1], \forall i$. Para cada entrada $x_i, \exists w_i$ que es el peso de cada entrada, y además, $\exists b$ que es el sesgo (bias).
Tags: definición
<!--ID: 1705919553313-->
END

DELETE

START
Básico
Anverso: Cómo se produce la salida en las neuronas sigmoid?
Reverso: Así, la manera en que se produce una salida no es un $1$ o un $0$, sino que la salida es:
$$\sigma (z) = \frac{1}{1+e^{-z}}$$
donde $z = \sum_j( w_j x_j) -b$ 
Tags: definición
END
