### Contenido principal

Fecha: 2024-02-06, 18:59

Al aplicar el [[Principio de inclusión-exclusión]], podemos o bien contar los elementos de un conjunto que verifica todas las propiedades de una lista de propiedades, o bien contar los elementos de un conjunto que no verifica ninguna propiedad de una lista de propiedades. Sin embargo, en ocasiones estaremos interesados en diferentes alternativas:
- Los elementos de un conjunto que verifican una, y sólo una, de las propiedades de la lista. En el caso de trabajar con tres subconjuntos $C_1, C_2, C_3$, el cardinal del subconjunto de los elementos que está en uno, y sólo uno, de los tres subconjuntos es igual a:
$$|C_1| + |C_2| + |C_3| - 2|C_1 \cap C_2| - 2|C_1 \cap C_3| - 2|C_2 \cap C_3| + 3|C_1 \cap C_2 \cap C_3|$$
- El cardinal del subconjunto de los elementos que verifican dos, y sólo dos, de las propiedades de la lista. La fórmula sería ahora la siguiente:
$$|C_1 \cap C_2| + |C_1 \cap C_3| + |C_2 \cap C_3| - 3|C_1 \cap C_2 \cap C_3|$$
- El cardinal del subconjunto de los elementos que verifican como mucho dos de los tres subconjuntos. La fórmula sería la siguiente:
$$|C_1| + |C_2| + |C_3| - |C_1 \cap C_2| - |C_1 \cap C_3| - |C_2 \cap C_3|$$

**Tema:** [[Métodos de enumeración y combinatoria#4. Principio de inclusión-exclusión]]
**Referencias:** [[Principio de inclusión-exclusión]]

---
### Anki
