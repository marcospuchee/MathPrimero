### Contenido Principal

```ad-proposition
$f:(X, \mathcal T) \to (Y, \mathcal T')$ continua y $x \in X$. Entonces, $f(C_x) \subseteq C_{f(x)}$.
```

```ad-proof
Como $C_x$ es conexo y $f$ es continua, $f(C_x)$ es conexo y $f(x) \in f(C_x)$, luego $f(C_x) \subseteq C_{f(x)}$, dado que $f(C_x) \cap C_{f(x)} \neq \emptyset$.
```

**Tema:** [[Conexión#3. Componentes conexos.]]

**Definiciones referenciadas:** [[Función continua]], [[Componente conexo]], [$C_x$](Componente conexo)
**Resultados referenciados:** [$f:(X, \mathcal T) \to (Y, \mathcal T')$ continua, $(X, \mathcal T)$ conexo $\implies$ $f(X)$ es subespacio conexo de $(Y, \mathcal T')$](La imagen de un conexo por una aplicación continua es conexa), [$C$ conexo, $C_x$ componente conexo $: C \cap C_x \neq \emptyset \implies C \subseteq C_x$](Conexo que intersecta con componente conexo está contenido en componente conexo)

---
### Corolarios.

```ad-cor
title: Corollarium
$f:(X, \mathcal T) \to (Y, \mathcal T')$ homeomorfismo, entonces $f$ lleva componentes conexos a componentes conexos.
```

```ad-proof
Sabemos que $f(C_x) \subseteq C_{f(x)}$. Como $f^{-1}$ es continua, se cumple lo mismo, pero al revés: $f^{-1}(C_{f(x)}) \subseteq C_{f^{-1}(f(x))} = C_x$. Por lo tanto, $C_{f(x)} \subseteq f(C_x)$, y tenemos la igualdad: $f(C_x) = C_{f(x)}$.
```


```ad-cor
title: Corollarium
El número de componentes conexos es invariante topológico
```

---
### Anki
