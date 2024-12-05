### Contenido Principal

```ad-proposition
Sea $(X, \mathcal T)$ un espacio topológico. $(X, \mathcal T)$ conexo por arcos $\implies$ $(X, \mathcal T)$ conexo.
```

```ad-proof
Procederemos por reducción al absurdo. Sea $(X, \mathcal T)$ conexo por arcos, supongamos que es disconexo. Entonces, $\exists \emptyset \neq A, \emptyset \neq B \in \mathcal T$ partición por abiertos.

Sean $x \in A$, $y \in B$ y $\sigma: [0,1] \longrightarrow X$ continua tal que $\sigma(0) = x$ y $\sigma(1) = y$. Entonces, $$\begin{array}{c}
\emptyset \neq A \cap \sigma([0,1]) \in \mathcal T_{\sigma([0,1])} \\
\emptyset \neq B \cap \sigma([0,1]) \in \mathcal T_{\sigma([0,1])}
\end{array}$$ es una partición por abiertos, lo que implica que $\sigma([0,1])$ es disconexo. Pero $[0,1]$ es conexo y $\sigma$ es continua, luego $\sigma([0,1])$ es conexo.
```

**Tema:** [[Conexión#4. Conexión por arcos.]]

**Definiciones referenciadas:** [[Espacio topológico conexo por arcos]], [[Arco]], [Espacio topológico conexo](Espacio topológico disconexo), [[Función continua]]
**Resultados referenciados:** [$f:(X, \mathcal T) \to (Y, \mathcal T')$ continua, $(X, \mathcal T)$ conexo $\implies$ $f(X)$ es subespacio conexo de $(Y, \mathcal T')$](La imagen de un conexo por una aplicación continua es conexa)

---
### Anki
