### Contenido principal

```ad-Formal
En $\mathbb R^2$, $$d_c(x,y) := \left \{ \begin{array}{l l} 0 & x = y, \\
d_2(x,(0,0))+d_2((0,0),y) & x \neq y. \end{array} \right .$$
```

```ad-note
**Resumen del estudio de $(\mathbb R^2, \mathcal T_{d_c})$.**
- **Bolas:** $B_{d_c}(x; \varepsilon) = \{x\} \cup B_{d_2}((0,0); \varepsilon - ||x||_2)$. Si $x \neq (0,0)$ y $\varepsilon < ||x||_2$, entonces $B_{d_c}(x; \varepsilon) = \{x\}$.
- **Abiertos:** $A$ abierto $\iff$ $(0,0) \notin A$ $\lor$ $\exists \varepsilon > 0$ tal que $B_{d_2}(x; \varepsilon) \subseteq A$.
- **Base de entornos:** Dado $x \in \mathbb R^2 \textrm{\\} \{(0,0)\}$, $\mathcal B(x) = \{\{x\}\}$. $\mathcal B((0,0)) = \{B_{d_2}((0,0), \varepsilon) : \varepsilon > 0 \}$.
- **1AN:** sí.
- **Hausdorff:** sí.
- **Base de abiertos:** $\{B_{d_c}(x; \varepsilon) : x \in \mathbb R^2, \, \varepsilon > 0 \}$.
- **2AN:** no.
- **Separable:** no.
- **Conexo:** no.
- **Conexo por arcos:** no.

```


**Tema:** [[201 Topología#Topologías estudiadas.]]

---
### Estudio.
##### Métrica
- **Definida positiva**. Sean $x \neq y \in \mathbb R^2$. Por definición, $$d_c(x,y) = d_2(x,(0,0)) + d_2((0,0),y),$$ pero $d_2(x,(0,0)) \ge 0$ y $d_2((0,0),y) \ge 0$, luego $d_c(x,y) \ge 0$. Sin embargo, $d_2(x,(0,0)) = 0 \iff x = (0,0)$, lo que implicaría que $d_2(y,(0,0)) > 0$, dado que $y \neq x = (0,0)$, luego si $x \neq y$, entonces $d_c(x,y) > 0$.
- **Simétrica**. Dados $x,y \in \mathbb R^2$, $$d_c(x,y) = d_2(x,(0,0)) + d_2((0,0),y) = d_2(y,(0,0)) + d_2((0,0),x) = d_c(y,x).$$
- **Desigualdad triangular**. Dados $x,y,z \in \mathbb R^2$, entonces  $$\begin{eqnarray}
d_c(x,z) &=& d_2(x,(0,0)) + d_2(z,(0,0)) \\ &\le& d_2(x,(0,0)) + d_2(y,(0,0)) + d_2(y,(0,0)) + d_2(z,(0,0)) \\ &=& d_2(x,y) + d_2(y,z).
\end{eqnarray}$$

##### Bolas
Dados $x \in \mathbb R^2$, $\varepsilon > 0$, por definición, $$\begin{eqnarray}
B_{d_c}(x; \varepsilon) &=& \{y \in \mathbb R^2 : d_c(x,y) < \varepsilon \} \\
&=& \{x\} \cup \{y \in \mathbb R^2 : d_2(x,(0,0)) + d_2(y,(0,0)) < \varepsilon \} \\
&=& \{x\} \cup \{y \in \mathbb R^2 :  ||y||_2 < \varepsilon - ||x||_2 \} \\
&=& \{x\} \cup B_{d_2}((0,0); \varepsilon - ||x||_2)
\end{eqnarray}$$
Notemos que si $x \neq (0,0)$ y $\varepsilon < d_2(x, (0,0))$, entonces $$B_{d_c}(x; \varepsilon) = \{x \}.$$

##### Abiertos
Por definición, un conjunto $A$ es abierto $\iff \forall x \in A , \, \exists \varepsilon > 0 : B_{d_c}(x; \varepsilon) \subseteq A$. 
- Notemos que si $(0,0) \notin A$, entonces, $\forall x \in A$, podemos tomar $\varepsilon < d_2(x, (0,0))$, por lo que $B_{d_c}(x; \varepsilon) = \{x\} \subseteq A$, luego $A$ es abierto.
- Supongamos que $(0,0) \in A$, entonces $A$ abierto $\iff$ $\exists \varepsilon > 0$ tal que $$B_{d_c}((0,0); \varepsilon) = \{(0,0)\} \cup \{ y \in \mathbb R^2 : d_2(y, (0,0)) < \varepsilon \} = B_{d_2}((0,0); \varepsilon) \subseteq A.$$

##### Base de entornos
Dado $x \in \mathbb R^2 \textrm{\\} \{(0,0)\}$, entonces $\mathcal B(x) = \{\{x\}\}$ es una base de entornos. Vamos a demostrarlo:
1. Está claro que $\{x\} \in \mathcal B(x)$ dado que $\{x\} \in \mathcal T_{d_c}$ y $x \in \{x\} \subseteq \{x\}$, luego $\{x\} \in \mathcal E(x)$.
2. Dado $B \in \mathcal E(x)$, entonces $x \in B$. Luego, $x \in \{x\} \subseteq B$.

Para $(0,0)$, hemos visto que los abiertos son los mismos que en la topología usual, luego podemos tomar la base de entornos definida en la topología usual: $\mathcal B((0,0)) = \{ B_{d_2}((0,0), \varepsilon) : \varepsilon > 0  \}$.

##### 1AN
Será suficiente encontrar $\mathcal B((0,0))$ numerable. Veamos si $\mathcal B((0,0)) = \{B_{d_c}((0,0); \frac{1}{n}) : n \in \mathbb N \}$ es base de entornos.
- Está claro que dado $B_{d_c}((0,0); \frac{1}{n})$ con $n \in \mathbb N$ es entorno, dado que es abierto y está contenido en sí mismo además de contener al $(0,0)$.
- Dado un entorno $U \in \mathcal E((0,0))$, entonces $\exists A \in \mathcal T_{d_c}$ tal que $(0,0) \in A \subseteq U$. Dado que $A$ es abierto, $\exists \varepsilon > 0$ tal que $B_{d_c}((0,0); \varepsilon) \subseteq A$, pero tomando $n > \frac{1}{\varepsilon}$, entonces $$B_{d_c}((0,0); \frac{1}{n}) \subseteq B_{d_c}((0,0); \varepsilon) \subseteq A \subseteq U.$$

Por tanto, $(\mathbb R^2, \mathcal T_{d_c})$ es 1AN.

##### Hausdorff
Sean $x,y \in \mathbb R^2 \textrm{\\} \{(0,0) \}$. Tomamos $\{x\} \in \mathcal E(x), \{y\} \in \mathcal E(y)$. Está claro que $\{x\} \cap \{y\} = \emptyset$, luego $(\mathbb R^2, \mathcal T_{d_c})$ es Hausdorff.
##### Base de abiertos
Dado que es un espacio métrico, $\mathcal B = \{B_{d_c}(x; \varepsilon) : x \in \mathbb R^2, \, \varepsilon > 0 \}$ forman una base de abiertos.

##### 2AN
Dado que hay una cantidad infinita no numerable de abiertos de la forma $\{x\}$, todos estos abiertos deberán estar en cualquier base de abiertos $\mathcal B$, luego no puede existir una base de abiertos numerable. Así, $(\mathbb R^2, \mathcal T_{d_c})$ no es 2AN.

##### Separable
Sabemos que todo espacio métrico separable es 2AN, sin embargo, $T_{d_c}$ no es 2AN, luego tampoco puede ser separable.

##### Conexo 
La métrica del cartero es disconexa. Podemos tomar $A = B_{d_2}((0,0); 1)$, notemos que el complementario es abierto dado que $(0,0) \notin A^c$, luego tenemos una partición por abiertos.
##### Conexo por arcos
Dado que no es conexo y conexo por arcos $\implies$ conexo, entonces no es conexo por arcos.
