
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-10, 15:29

```ad-cor
Si $x \in \mathbb R$ y $fl(x)$ es una representación de punto flotante (normalizada) con $t$ dígitos y base $\beta$, entonces
$$fl(x) = x(1+\delta) \quad \textrm{con } |\delta| \le u,$$
donde $u$ se llama unidad de redonde, o también precisión máquina. Si $u_T$ y $u_R$ son las unidades de redondeo correspondientes a las representaciones de punto flotante por corte y redondeo respectivamente, tenemos que
$$u_T = \beta^{1-t} \quad u_R = \frac{1}{2} \cdot \beta^{1-t}.$$
```

```ad-proof
Si $x \neq 0$, tenemos
$$fl(x) = fl(x) - x + x = \frac{fl(x)-x}{x} x + x = x(1+\delta),$$
donde $\delta = (fl(x) - x)/x$ ([[proposición error relativo de una aproximación mediante truncamiento o redondeo]]). Si $x = 0$, $fl(x) = 0$ y no hay que probar nada.
```

**Tema:** [[Sistemas numéricos y fuentes de error#3. Aritmética de punto flotante.]]
**Corolarios:**

---
### Anki
