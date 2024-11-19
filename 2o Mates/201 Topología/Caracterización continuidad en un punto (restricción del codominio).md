### Contenido Principal

```ad-proposition
Sean $f: (X, \mathcal T) \to (Y, \mathcal T')$ aplicación, $x_0 \in X$, $f(X) \subseteq H \subseteq Y$. Entonces, $f$ continua en $x_0$ $\iff$ $f: (X, \mathcal T) \to (H, \mathcal T_H')$ continua en $x_0$.
```

```ad-proof
$\Rightarrow$. 
Sabemos que $\forall U \in \mathcal E_{\mathcal T'_H}(f(x_0))$, $\exists U' \in \mathcal E_{\mathcal T'}(f(x_0))$ tal que $U = U' \cap H$. Por definición de ser $f$ continua, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq U'$, pero
$$f(V) = f(V) \cap H \subseteq  U' \cap H = U,$$
lo que implica que $f:(X, \mathcal T) \to (H, \mathcal T_H')$ es continua en $x_0$.

$\Leftarrow$.
Sabiendo que la aplicación inclusión, $i$, es continua y que la composición de continuas es continua,  podemos tomar $f \circ i$, que es es continua en $x_0$ (abuso de notación).
```

**Tema:** [[Subespacios topológicos#3. Continuidad y subespacios.]]

**Definiciones referenciadas:** [$\mathcal T_H$](Topología inducida), [[Función continua]], [[Entorno]]
**Resultados referenciados:** [$U \in \mathcal E_H(x) \iff \exists U' \in \mathcal E(x) : U = U' \cap H$](Caracterización entorno en topología inducida (entorno topología padre)), [[Composición de continuas es continua]], [[Aplicación inclusión es continua]]

---
### Anki

START
Básico
Anverso: Caracterización continuidad en un punto (restricción del codominio)
Reverso: Sean $f: (X, \mathcal T) \to (Y, \mathcal T')$ aplicación, $x_0 \in X$, $f(X) \subseteq H \subseteq Y$. Entonces, $f$ continua en $x_0$ $\iff$ $f: (X, \mathcal T) \to (H, \mathcal T_H')$ continua en $x_0$.
Tags: top
<!--ID: 1731931805320-->
END

START
Básico
Anverso: Demostración de que sean $f: (X, \mathcal T) \to (Y, \mathcal T')$ aplicación, $x_0 \in X$, $f(X) \subseteq H \subseteq Y$. Entonces, $f$ continua en $x_0$ $\iff$ $f: (X, \mathcal T) \to (H, \mathcal T_H')$ continua en $x_0$.
Reverso: $\Rightarrow$. 
Sabemos que $\forall U \in \mathcal E_{\mathcal T'_H}(f(x_0))$, $\exists U' \in \mathcal E_{\mathcal T'}(f(x_0))$ tal que $U = U' \cap H$. Por definición de ser $f$ continua, $\exists V \in \mathcal E(x_0)$ tal que $f(V) \subseteq U'$, pero
$$f(V) = f(V) \cap H \subseteq  U' \cap H = U,$$
lo que implica que $f:(X, \mathcal T) \to (H, \mathcal T_H')$ es continua en $x_0$.

$\Leftarrow$.
Sabiendo que la aplicación inclusión, $i$, es continua y que la composición de continuas es continua,  podemos tomar $f \circ i$, que es es continua en $x_0$ (abuso de notación).
Tags: dem top
<!--ID: 1731931805329-->
END

