## Tema 1. Espacios métricos.
**Referencia:** [[Espacios métricos]]

- [[Métrica]]
- [[Espacio métrico]]
- [[Subespacio métrico]]
- [[Distancia punto-conjunto]]
- [[Bola abierta]]
- [[Bola cerrada]]
- [[Espacio métrico acotado]]
- [[Espacio métrico acotado sii es bola abierta]]
- [[Conjunto acotado]]
- [[Conjunto acotado si existe bola que lo contenga]]
- [[Diámetro]]
- [[Conjunto abierto]]
- [[Intersección finita de abiertos es abierta]]
- [[Unión arbitraria de abiertos es abierta]]
- [[Entorno]]
- [[Conjunto abierto sii es entorno de todos sus puntos]]
- [[Conjunto cerrado]]
- [[(por demostrar) Conjunto es cerrado si para todo punto en su complementario existe bola que no intersecta con el conjunto]]
---
## Tema 2. Espacios topológicos.
**Referencia:** [[Espacios topológicos]]
### 1. Definición.
- [[Topología]]
- [[Espacio topológico]]
- [[Conjunto abierto]] (espacios topológicos)
- [[Conjunto cerrado]] (espacios topológicos)
- [[Analogía propiedades conjunto abierto y conjunto cerrado]]
### 2. Entornos.
- [[Entorno]] (espacios topológicos)
- [[Conjunto que contiene a entorno de un punto es entorno del punto]]
- [[Intersección de entornos de un punto es entorno del punto]]
- [[Conjunto abierto sii es entorno de todos sus puntos]]
- [[Base de entornos]]
- [[Espacio topológico 1 AN]]
- [[Espacio topológico Hausdorff]]
### 3. Bases de abiertos.
- [[Base de abiertos]]
- [[Caracterización de base de abiertos]]
- [[(ejercicio) Propiedades de las bases de abiertos]]
- [[Teorema topología a partir de base de abiertos]]
- [[Espacio topológico 2 AN]]
- [[Base de entornos a partir de base de abiertos]]
- [[2 AN sii cualquier base de abiertos posee una subbase de abiertos numerable]]
### 4. Métricas equivalentes.
- [[Métricas equivalentes]]
- [[Métricas equivalentes sii la bola de una se puede contener en la otra y viceversa]]
- [[Métricas equivalentes si existen constantes tales que una envuelve a la otra]]
---
## Tema 3: Puntos especiales.
**Referencia:** [[Puntos especiales]]
### 1. Puntos de adherencia.
- [[Adherencia]]
- [[Caracterización de punto de adherencia (base de entornos)]]
- [[Caracterización punto de adherencia en espacios métricos (distancia punto-conjunto)]]
- [[Propiedades de las adherencias]]
- [[Relación conjunto cerrado con adherencia]]
- [[Conjunto denso]]
- [[Caracterización de conjunto denso (intersección abiertos)]]
- [[Espacio topológico separable]]
- [[Todo 2AN es separable]]
- [[Todo espacio métrico separable es 2AN]]
- [[Punto de acumulación]]
- [[Punto aislado]]
### 2. Puntos frontera.
- [[Frontera topológica]].
Como la frontera topológica es un subconjunto de la adherencia, cumple las proposiciones de la adherencia.
### 3. Puntos interiores. 
- [[Punto interior]]
- [[Caracterización de interior (definición alternativa)]]
- [[Caracterización de frontera (definición alternativa)]]
- [[(ejercicio) Caracterización de punto interior (base de entornos)]]
- [[Caracterización de punto interior en espacios métricos (distancia punto-conjunto)]]
- [[Propiedades interior]]
- [[Propiedades conjuntos abiertos (respecto a su interior y frontera)]]
### 4. Caracterización de adherencia por sucesiones
- [[Convergencia sucesión (topología)]]
- [[Caracterización de convergencia (base de entornos)]]
- [$\{x_n\} \to x \iff \forall \varepsilon > 0, \, \exists n_0 : \forall n > n_0 \quad d(x_n, x) < \varepsilon$](Caracterización de convergencia en espacios métricos (distancia))
- [[(ejercicio) Caracterización de convergencia en espacios métricos (sucesión de distancias)]]
- [[La convergencia en Hausdorff es única]]
- [[Caracterización de punto de adherencia en espacios métricos (convergencia)]]
- [[Caracterización de conjunto denso en espacios métricos (convergencia)]]
- [[Caracterización de punto frontera en espacios métricos (convergencia)]]
---
## Tema 4: Continuidad
**Referencia:** [[Continuidad]]
### 1. Continuidad.
- [[Función continua]]
- [[Caracterización de continuidad (bases de entornos)]]
- [[Caracterización de continuidad en espacios métricos (sucesiones)]]
- [[Composición de continuas es continua]]
- [[Relación de adherencia se mantiene con funciones continuas]]
### 2. Continuidad global.
- [[Caracterización de continuidad global (antiimagen de abiertos)]]
- [[Caracterización de continuidad global (antiimagen de cerrados)]]
- [[Composición de continuas globales es continua global]]
### 3. Homeomorfismos.
- [[Homeomorfismo]]
- [[Caracterización de homeomorfismo (imagen abiertos y cerrados)]]
- [[2AN es propiedad topológica]]
- [[1AN es propiedad topológica]]
- [[Hausdorff es propiedad topológica]]
- [[Separable es propiedad topológica]]
- [[Metrizable es propiedad topológica]]
### 4. Continuidad uniforme e isometrias.
- [[Función uniformemente continua]]
- [Uniformemente continua $\implies$ continua](Uniformemente continua implica continua)
- [[Isometria]]
- [Isometría $\implies ($ inyectiva $\land$ uniformemente continua $)$](Isometría implica inyectiva y uniformemente continua)
---
## Tema 5: Subespacios topológicos.
**Referencia:** [[Subespacios topológicos]]
### 1. Definición.
- [$\mathcal T_H$](Topología inducida), [$\mathcal T_H$ es topología](Topología inducida) 
- [$C$ cerrado en $\mathcal T_H$ $\iff \exists C'$ cerrado en $\mathcal T : C = C' \cap H$](Caracterización cerrado en topología inducida (cerrado))
- [$U \in \mathcal E_H(x) \iff \exists U' \in \mathcal E(x) : U = U' \cap H$](Caracterización entorno en topología inducida (entorno topología padre))
- [$\mathcal B_H(x) = \{B \cap H : B \in \mathcal B(x) \}$ es base de entornos en $\mathcal T_H$](Base de entornos relativa a partir de base de entornos total)
- [La propiedad $1\textrm{AN}$ es hereditaria](Base de entornos de topología inducida a partir de base de entornos de topología padre)
- [$\mathcal B_H = \{B \cap H : B \in \mathcal B \}$ es base de abiertos en $\mathcal T_H$](Base de abiertos relativa a partir de base de abiertos total)
- [La propiedad $2 \textrm{AN}$ es hereditaria](Base de abiertos relativa a partir de base de abiertos total)
- [[La propiedad de ser metrizable es hereditaria]]
### 2. Adherencia, interior y frontera relativa.
- [$\textrm{ad}_ H(S) = \textrm{ad}(S) \cap H$](Caracterización de adherencia en subespacio (intersección))
- [$\textrm{int}(S) \cap H \subseteq \textrm{int}_ H(S)$](Intersección interior con subconjunto está contenida en el interior del subespacio)
- [$\textrm{fr}_ H(S) \subseteq \textrm{fr}(S) \cap H$](Intersección interior con subconjunto está contenida en el interior del subespacio)
### 3. Continuidad y subespacios.
- [[Aplicación inclusión es continua]]
- [$f$ continua en $x_0$ $\iff$ $f: (X, \mathcal T) \to (H, \mathcal T_H')$ continua en $x_0$](Caracterización continuidad en un punto (restricción del codominio))
- [$f$ continua $\implies$ $f \restriction_H: (H, \mathcal T_H) \to (Y, \mathcal T')$ continua](Restricción de una función continua es continua)
- [$f$ continua en $x_0$ $\iff \exists U \in \mathcal E(x_0) : f \restriction_U$ continua en $x_0$](Caracterización continuidad en un punto (restricción del dominio a entorno))
- [$\{A_i\}_ {i \in I}$ familia de abiertos $: X = \bigcup_{i \in I} A_i$ y $f \restriction_{A_i}$ continua $\forall i$ $\implies$ $f$ continua](Función restringida a familia de abiertos continua implica función total continua)
- [$\{C_i \}_ {i = 1}^n$ familia finita de cerrados $: X = \bigcup_{i = 1}^n C_i$ y $f_ {\restriction_{C_i}}$ continua $\forall i$ $\implies$ $f$ continua](Función restringida a familia finita de cerrados continua implica función total continua)
---
## Tema 6: Conexión.
**Referencia:** [[Conexión]]
### 1. Definición.
- [Espacio topológico conexo](Espacio topológico disconexo)
- [[Espacio topológico disconexo]]
- [$\exists$ partición de abiertos $\iff$ $\exists$ partición de cerrados](Espacio topológico disconexo)
- [$(X, \mathcal T)$ conexo $\iff$ $X, \emptyset$ son los únicos abiertos y cerrados a la vez](Caracterización de espacio topológico conexo (total y vacío unicos abiertos y cerrados a la vez))
- [$(X, \mathcal T)$ conexo $\iff$ $\forall f: (X, \mathcal T) \to (\{0,1\}, \mathcal T_D)$ continua es constante](Caracterización espacio topológico conexo (función topología discreta de un conjunto con dos elementos))
- [$(X, \mathcal T)$ conexo $\iff \forall f:(X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua cumple que $\forall x,y \in X$ $:$ $(\exists c \in \mathbb R$ $:$ $f(x) < c < f(y))$ $\implies$ $\exists z \in X$ $:$ $f(z) = z$](Caracterización de espacio topológico conexo (función a los reales con la topología usual))
- [$f:(X, \mathcal T) \to (Y, \mathcal T')$ continua, $(X, \mathcal T)$ conexo $\implies$ $f(X)$ es subespacio conexo de $(Y, \mathcal T')$](La imagen de un conexo por una aplicación continua es conexa)
- [La conexión es propiedad topológica](La imagen de un conexo por una aplicación continua es conexa)
### 2. Subespacios conexos de $(\mathbb R, \mathcal T_u)$.
- [[Intervalo]]
- [Un subespacio de $(\mathbb R, \mathcal T_u)$ es conexo $\iff$ es un intervalo](Un subespacio de (R, T_u) es conexo sii es un intervalo)
- [$(\mathbb R, \mathcal T_u)$ es conexo](Un subespacio de (R, T_u) es conexo sii es un intervalo)
- [$f:(X, \mathcal T) \to (\mathbb R, \mathcal T_u)$ continua $\land$ $(X, \mathcal T)$ conexo $\implies$ $f(X)$ intervalo](Un subespacio de (R, T_u) es conexo sii es un intervalo)
