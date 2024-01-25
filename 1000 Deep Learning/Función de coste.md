2024-01-23, 09:19
### Contenido principal

En este ejemplo, cada entrada es un vector de $784$ dimensiones ($28 \times 28$ píxeles). Y a la salida deseada (la respuesta correcta) se la denomina $y(x)$, donde en el caso de que $y = 6$, es decir, que el número escrito a mano sea un $6$, $y(x) = (0,0,0,0,0,0,1,0,0,0)^T$.

La función de coste es aquello que nos permite encontrar los pesos ($w_i$) y los sesgos ($b_i$) tales que la salida que nos proporciona la red neuronal se aproxima a la salida deseada $y(x)$. Para cuantificar cómo de bien funcionan unos pesos y unos sesgos determinados, utilizamos la función de coste:
$$C(w,b) = \frac{1}{2n} \sum_x ||y(x) - a||^2$$
donde $w$ contiene todos los pesos, $b$ todos los sesgos y $n$ es el número total de entradas (de entrenamiento). $a$ es el vector de salidas de la red cuando $x$ es la entrada, es decir, depende de $x, w, b$. Denotamos $||v||$ la longitud del vector $v$.

Cuanto más se aproxima al $0$, $y(x)$ es aproximadamente $a$. La manera de conseguir que se aproxime al $0$ es a través del 'gradient descent' o [[Analogía del descenso del gradiente]]. 

A la función de coste también se la llama [[Error cuadrático medio]].

--- 
### Referencias

[[Neural Networks and Deep Learning#Ejemplo 1. Red neuronal para clasificar dígitos escritos a mano.]]

---
### Anki
