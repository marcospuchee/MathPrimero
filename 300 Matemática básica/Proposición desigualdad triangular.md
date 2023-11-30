### Proposición

Sean $z,w \in \mathbb C$, entonces:
$$ |z+w| \le |z| + |w| $$

---
### Demostración

Es suficiente probar que $|z+w|^2 \le (|z| + |w|)^2$.

$|z+w|^2 = (z+w)(\overline{z+w}) = (z+w)(\overline z + \overline w) = |z|^2 + z\overline w + \overline z w + |w|^2$ ([[Proposición números complejos]]) 
También tenemos que $(|z| + |w|)^2 = |z|^2 + 2|z||w| + |w|^2$. Veamos que $z\overline w + \overline z w \le 2 |z| |w|$.

$z \overline w + \overline z w = z \overline w + \overline{z \overline w}$, pero sabemos que $z \overline w = a+bi$ y $\overline{z + \overline w} = a-bi$.
Entonces $z \overline w + \overline{z + \overline w} = 2Re(z \overline w) \le 2 |z \overline w| = 2 |z||\overline w| = 2 |z||w|$.

---
### Referencias

[[Números complejos y polinomios]]