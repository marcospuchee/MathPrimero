2024-01-23, 16:27
### Contenido principal

Primero debemos encontrar el mínimo global de la función, es decir, el punto con el menor valor y posible de la función. La opción de calcular derivadas no es posible dado que con funciones con muchas variables se complica mucho.

El descenso del gradiente contempla la analogía de lanzar una esfera por la función (como si fuera un valle), y llegará un punto en el que la esfera haya rodado hasta el punto más bajo de la función.

Cuando movemos la esfera una cantidad $\Delta v_1$ hacia la posición $v_1$, y una cantidad $\Delta v_2$ hacia la posición $v_2$, podemos representar que la función $C (v_1, v_2)$ cambia de la siguiente forma:
$$\Delta C \approx \frac{\partial C}{\partial v_1} \Delta v_1 + \frac{\partial C}{\partial v_2} \Delta v_2$$
Sin embargo, como nos interesa que la esfera ruede hacia abajo, tenemos que encontrar $\Delta v_1, \Delta v_2$ de tal manera que $\Delta C$ sea negativo. Para ello, definimos $\Delta v = (\Delta v_1, \Delta v_2)^T$. Definimos el vector gradiente como 
$$\nabla C = (\frac{\partial C}{\partial v_2}, \frac{\partial C}{\partial v_2})^T$$
De esta manera,
$$\Delta C \approx \nabla C · \Delta v$$
Esta ecuación nos permite conocer cómo elegir $\Delta v$ para hacer $\Delta C$ negativa, supongamos que elegimos
$$\Delta v = - \eta \nabla C$$
donde $\eta$ es un parámetro positivo muy pequeño conocido como el ratio de aprendizaje. Entonces, la ecuación anterior nos lleva a que $\Delta C \approx - \eta \nabla C · \nabla C = - \eta || \nabla C ||^ 2$. De tal manera, podemos definir la "ley de movimiento" de la esfera como $\Delta v = -\eta \nabla C$.

Entonces, el uso que le daremos a esta "ley de movimiento" es: calcular un valor para $\Delta v$, mover la posición de la esfera $v$ la cantidad computada: $v \rightarrow v' = v - \eta \nabla C$, y repetir estos pasos hasta llegar a el mínimo global.

El valor que se le da a $\eta$ debe ser lo suficientemente pequeño como para que $\Delta C > 0$ siempre, pero no demasiado pequeño como para hacer que el descenso del gradiente sea muy lento. Además, la aproximación: $\Delta \approx \nabla C · \Delta v$ se debe mantener como válida.

--- 
### Referencias

[[Neural Networks and Deep Learning#Descenso del gradiente.]]

---
### Anki
