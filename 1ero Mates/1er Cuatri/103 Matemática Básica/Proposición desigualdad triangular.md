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

[[Número complejo]]

START
Básico
Anverso: Qué dice la propiedad de la desigualdad triangular?
Reverso: Sean $z,w \in \mathbb C$, entonces:
$$ |z+w| \le |z| + |w| $$
Tags: proposición/teorema
<!--ID: 1705822944846-->
END

START
Básico
Anverso: Demostración de la desigualdad triangular en números complejos
Reverso: Es suficiente probar que $|z+w|^2 \le (|z| + |w|)^2$.

$|z+w|^2 = (z+w)(\overline{z+w}) = (z+w)(\overline z + \overline w) = |z|^2 + z\overline w + \overline z w + |w|^2$ ([[Proposición números complejos]]) 
También tenemos que $(|z| + |w|)^2 = |z|^2 + 2|z||w| + |w|^2$. Veamos que $z\overline w + \overline z w \le 2 |z| |w|$.

$z \overline w + \overline z w = z \overline w + \overline{z \overline w}$, pero sabemos que $z \overline w = a+bi$ y $\overline{z + \overline w} = a-bi$.
Entonces $z \overline w + \overline{z + \overline w} = 2Re(z \overline w) \le 2 |z \overline w| = 2 |z||\overline w| = 2 |z||w|$.
Tags: demostración
<!--ID: 1705822944849-->
END