2024-01-21, 10:02
### Contenido principal

Los perceptrones son un tipo de neurona artificial. Hoy en día se utilizan más las neuronas sigmoid ([[Neurona sigmoid]]), pero para conocer qué son las neuronas sigmoid, es necesario primero conocer los perceptrones. 

Los perceptrones toman distintas entradas binarias y producen una salida binaria:
![[Pasted image 20240121100449.png]]
En este ejemplo tiene tres entradas ($x_1, x_2, x_3$), pero podría tener más o menos.

La manera en que esta neurona produce la salida es a través de los pesos $w_1, w_2, w_3$ que simbolizan cómo de importante son las variables $x_1, x_2, x_3$ respectivamente. En esta neurona en específico, la salida es o $0$ o $1$, dependiendo del valor de $\sum_j w_j x_j$, que si pasa cierto umbral devuelve $1$, y sino, devuelve $0$. El umbral se pasa como parámetro de la neurona:
$$
\textrm{salida}= \left\{ \begin{array}{lcc} 0 & si & w ·x+b \le 0 \\  1 & si & w·x+b > 0 \end{array} \right.$$
donde hemos simplificado $\sum_j w_j x_j \sim w · x$ y $b = -$ umbral $=$ bias (sesgo).


--- 
### Referencias

[[Neural Networks and Deep Learning#Perceptrones]]

---
### Anki

START
Básico
Anverso: Arquitectura de un perceptrón
Reverso: Los perceptrones son un tipo de neurona artificial. Hoy en día se utilizan más las neuronas sigmoid ([[Neurona sigmoid]]), pero para conocer qué son las neuronas sigmoid, es necesario primero conocer los perceptrones. 

Los perceptrones toman distintas entradas binarias y producen una salida binaria:
![[Pasted image 20240121100449.png]]
En este ejemplo tiene tres entradas ($x_1, x_2, x_3$), pero podría tener más o menos.
Tags: definición
<!--ID: 1705919553324-->
END

START
Básico
Anverso: Cómo se produce la salida en los perceptrones?
Reverso: La manera en que esta neurona produce la salida es a través de los pesos $w_1, w_2, w_3$ que simbolizan cómo de importante son las variables $x_1, x_2, x_3$ respectivamente. En esta neurona en específico, la salida es o $0$ o $1$, dependiendo del valor de $\sum_j w_j x_j$, que si pasa cierto umbral devuelve $1$, y sino, devuelve $0$. El umbral se pasa como parámetro de la neurona:
$$
\textrm{salida}= \left\{ \begin{array}{lcc} 0 & si & w ·x+b \le 0 \\  1 & si & w·x+b > 0 \end{array} \right.$$
donde hemos simplificado $\sum_j w_j x_j \sim w · x$ y $b = -$ umbral $=$ bias (sesgo).
Tags: definición
<!--ID: 1705919553327-->
END