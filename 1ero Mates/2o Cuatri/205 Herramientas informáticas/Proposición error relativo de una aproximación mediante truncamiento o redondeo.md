
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-10, 15:04

```ad-proposition
Si $x \in \mathbb R$ y $fl^T(x)$ y $fl^R(x)$ son las representaciones de punto flotante (normalizadas) con $t$ dígitos y base $\beta$ entonces:
$$\begin{array}{l}E_r(fl^T(x)) \le \beta^{1-t}, \\
E_r(fl^R(x)) \le \frac{1}{2} \beta^{1-t}
\end{array}$$
```


```ad-proof
Sea $x = (.d_1 d_2 \dots d_t d_{t+1} d_{t+1} \dots)_\beta \cdot \beta^e$ la representación de punto flotante normalizada de $x$, entonces $fl^T(x) = (.d_1d_2 \dots d_t)_\beta \cdot \beta^e$. Por tanto,
$$E_r(fl^T(x)) = \frac{|x-fl^T(x)|}{|x|} = \frac{(.d_{t+1} d_{t+2} \dots)_\beta \cdot \beta^{e-t}}{(.d_1 d_2 \dots)_\beta \cdot \beta^e}.$$
Como $(.d_{t+1} d_{t+2} \dots)_\beta \le 1$ y $(.d_1 d_2 \dots)_\beta \ge \beta^{-1}$ (ya que $d_1 \ge 1)$, tenemos
$$E_r(fl^T(x)) \le \frac{\beta^{e-t}}{\beta^{-1} \cdot \beta^e} = \beta^{1-t}.$$

Veamos ahora el caso del redondeo. Si $0 \le (.d_{t+1} d_{t+2} \dots)_\beta < 1/2$, tenemos
$$|x-fl^R(x)| = (.d_{t+1} d_{t+2} \dots)_\beta \cdot \beta^{e-t} < \frac{1}{2} \cdot \beta^{e-t},$$
por tanto,
$$E_r(fl^R(x)) = \frac{|x-fl^R(x)|}{|x|} \le \frac{1/2 \beta^{e-t}}{\beta^{-1} \cdot \beta^e} = \frac{1}{2} \cdot \beta^{1-t}.$$
En cambio, si $1/2 \le (.d_{t+1}d_{t+2} \dots)_\beta \le 1$,
$$fl^R(x) = (d_1 \beta^{-1} + \dots + (d_t + 1)\beta^{-t}) \cdot \beta^e,$$
y, por tanto,
$$\begin{eqnarray}
|x-fl^R(x)| &=& \left | \sum_{k=1}^{+\infty} d_k \beta^{-k} - \left ( \sum_{k=1}^{t-1} d_k \beta^{-k} + (d_t + 1)\beta^{-t} \right ) \right | \cdot \beta^e \\
&=& \left | - \beta^{-t} + \sum_{k = t+1}^{+\infty} d_k \beta^{-k} \right | \cdot \beta^e \\
&=& |1-(.d_{t+1} d_{t+2} \dots)_\beta| \cdot \beta^{e-t} \le \frac{1}{2} \cdot \beta^{e-t},
\end{eqnarray}$$
de donde se deduce de nuevo
$$E_r(fl^R(x)) \le \frac{1/2 \beta^{e-t}}{\beta^{-1} \cdot \beta^e} = \frac{1}{2} \cdot \beta^{1-t}.$$ 
```

**Tema:** [[Sistemas numéricos y fuentes de error#3. Aritmética de punto flotante.]]
**Corolarios:**

---
### Anki
