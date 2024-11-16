### Contenido Principal

```ad-proposition
Los semiespacios cerrados ([[semiespacio cerrado]]) son conjuntos cerrados ([[conjunto cerrado]]) y convexos ([[conjunto convexo]]).
```

```ad-proof
Probaremos la convexidad de $H^-$. Sean $x_1, x_2 \in H^-$ y sea $\lambda \in [0,1]$. Se tiene que
$$a^T ((1-\lambda)x_1 + \lambda x_2) = (1-\lambda)a^T x_1 + \lambda a^T x_2 \le (1-\lambda)b + \lambda b = b,$$
lo que prueba que $(1-\lambda)x_1 + \lambda x_2 \in H^-$ y, por tanto, $H^-$ es convexo.

Para probar que $H^-$ es cerrado, veamos que su complementario $(H^-)^c = \{x \in \mathbb R^n \, | \, a^T x > b\}$ es un [[conjunto abierto]]. Sea $x \in (H^-)^c$, $a^Tx>b$ luego $a^Tx -b > 0$. Tomamos $\varepsilon = \frac{a^T x - b}{||a^T||} > 0$ y veamos que $B(x; \varepsilon) \subseteq (H^-)^c$. Dado $y \in B(x, \varepsilon)$, se dan las siguientes desigualdades:
$$|a^T y - a^T x| = |a^T(y-x)| \le ||a|| \, ||y-x|| < ||a|| \varepsilon = ||a|| \frac{a^Tx - b}{||a^T||} = a^Tx - b.$$
La primera desigualdad es por el [[teorema de Cauchy-Schwartz]], y la segunda es cierta ya que $y \in B(x, \varepsilon)$. Entonces,
$$-a^Tx + b < a^Ty - a^Tx < a^Tx -b.$$
Luego $a^Ty > b$, por lo que $y \in (H^-)^c$ y hemos demostrado que $(H^-)^c$ es un conjunto abierto y, por tanto, que $H^-$ es cerrado.

La prueba para $H^+$ es completamente análoga.
```

**Tema:** [[Modelo de programación lineal#3. Poliedros.]]

---
### Anki

START
Básico
Anverso: Demostración de que los semiespacios cerrados ([[semiespacio cerrado]]) son conjuntos cerrados ([[Conjunto cerrado]]) y convexos ([[conjunto convexo]]).
Reverso: Probaremos la convexidad de $H^-$. Sean $x_1, x_2 \in H^-$ y sea $\lambda \in [0,1]$. Se tiene que
$$a^T ((1-\lambda)x_1 + \lambda x_2) = (1-\lambda)a^T x_1 + \lambda a^T x_2 \le (1-\lambda)b + \lambda b = b,$$
lo que prueba que $(1-\lambda)x_1 + \lambda x_2 \in H^-$ y, por tanto, $H^-$ es convexo.

Para probar que $H^-$ es cerrado, veamos que su complementario $(H^-)^c = \{x \in \mathbb R^n \, | \, a^T x > b\}$ es un [[Conjunto abierto]]. Sea $x \in (H^-)^c$, $a^Tx>b$ luego $a^Tx -b > 0$. Tomamos $\varepsilon = \frac{a^T x - b}{||a^T||} > 0$ y veamos que $B(x; \varepsilon) \subseteq (H^-)^c$. Dado $y \in B(x, \varepsilon)$, se dan las siguientes desigualdades:
$$|a^T y - a^T x| = |a^T(y-x)| \le ||a|| \, ||y-x|| < ||a|| \varepsilon = ||a|| \frac{a^Tx - b}{||a^T||} = a^Tx - b.$$
La primera desigualdad es por el [[teorema de Cauchy-Schwartz]], y la segunda es cierta ya que $y \in B(x, \varepsilon)$. Entonces,
$$-a^Tx + b < a^Ty - a^Tx < a^Tx -b.$$
Luego $a^Ty > b$, por lo que $y \in (H^-)^c$ y hemos demostrado que $(H^-)^c$ es un conjunto abierto y, por tanto, que $H^-$ es cerrado.

La prueba para $H^+$ es completamente análoga.
Tags: dem prm
<!--ID: 1727083427971-->
END

START
Respuesta anidada
Los semiespacios cerrados ([[semiespacio cerrado]]) son {{c1::conjuntos cerrados ([[Conjunto cerrado]]) y convexos ([[conjunto convexo]]).}}
Tags:
<!--ID: 1727083427973-->
END
