### Contenido principal

Fecha: 2024-05-15, 20:04

Dadas las condiciones iniciales $(\vec{r}_0, \vec{v}_0)$ podemos calcular la
solución siguiendo los siguientes pasos:

1. Cálculo del [[potencial]] $U(r) = -\int F(r) dr$ y de la [[energía mecánica total]] $E = \frac{1}{2}mv_0^2 + U(r_0)$.
2. Cálculo del momento angular ([[momento angular de una partícula]]) $\vec{l} = m\vec{r}_0 \wedge \vec{v}_0$. Si $\vec{l} = 0$ ([[momento angular nulo]]) pasamos al algoritmo del caso unidimensional. Si $\vec{l} \neq 0$ ([[momento angular no nulo]]) pasamos al siguiente paso.
3. Cálculo del módulo del momento angular, $l = |\vec{l}|$, y del plano del movimiento, $\vec{r} \cdot \vec{l} = 0$. Consideramos coordenadas polares $(r, \theta)$ en ese plano.
4. Determinemos el potencial efectivo y la función que da la velocidad radial:
$$
V(r) \equiv U(r) + \frac{l^2}{2mr^2}, \quad v_r(r) = \sqrt{\frac{2}{m}[E - V(r)]}
$$
5. Calculamos la coordenada radial $r = r(t)$ como la inversa de
$$
t(r) = t_0 + \int_{r_0}^{r} \frac{dr}{v_r(r)}
$$
6. Calculamos la coordenada angular
$$    
\theta = \theta(t) = \theta_0 + \int_{t_0}^{t} \frac{l dt}{mr^2(t)}
$$

**Referencias:** [[Fuerzas conservativas. Campo central.#c) Integración de las ecuaciones del movimiento y estudio cualitativo.]]

---
### Anki
