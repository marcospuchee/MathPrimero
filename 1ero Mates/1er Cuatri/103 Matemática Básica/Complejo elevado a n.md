### Proposición

Sea $z = |z| (cos \theta + i sin \theta)$ y sea $n \in \mathbb N$. Entonces:
1. $z^n = |z|^n (cos(n\theta) + isin(n \theta))$.
2. $z^{-n} = \frac{1}{|z|^n}(cos(-n\theta) + isin(-n\theta))$.

---
### Demostración

1. Procedemos por inducción. El caso $n = 1$ está claro. Supongamos que es cierto para $n$ y veámoslo para $n+1$:
$$z^{n+1} = z^nz = (|z|^n(cos(n\theta) + i sin (n \theta)))(|z|(cos(\theta) + isin(\theta))) = |z|^{n+1} (cos((n+1)\theta) + isin((n+1)\theta))  $$
2. Veamos ahora el caso de $z^{-n}$.
$$z^{-n} = (z^n)^{-1} = (|z|^n (cos(n\theta) + isin(n \theta)))^{-1} = \frac{1}{|z|^n} ( cos (-n \theta) + isin(-n \theta))$$
gracias a [[Corolario inverso de complejo]]

---
### Referencias

[[Número complejo]]

---
### Anki

START
Básico
Anverso: Sea $z \in \mathbb C$, cuánto es $z ^n$?
Reverso: Sea $z = |z| (cos \theta + i sin \theta)$ y sea $n \in \mathbb N$. Entonces:
1. $z^n = |z|^n (cos(n\theta) + isin(n \theta))$.
Tags: proposición/teorema
<!--ID: 1705822944791-->
END

START
Básico
Anverso: Sea $z \in \mathbb C$, cuánto es $z^{-n}$?
Reverso: Sea $z = |z| (cos \theta + i sin \theta)$ y sea $n \in \mathbb N$. Entonces:
1. $z^{-n} = \frac{1}{|z|^n}(cos(-n\theta) + isin(-n\theta))$. 
Tags: proposición/teorema
<!--ID: 1705822944796-->
END

START
Básico
Anverso: Demuestra que sea $z = |z| (cos \theta + i sin \theta)$ y sea $n \in \mathbb N$. Entonces:
1. $z^n = |z|^n (cos(n\theta) + isin(n \theta))$.
Reverso: Procedemos por inducción. El caso $n = 1$ está claro. Supongamos que es cierto para $n$ y veámoslo para $n+1$:
$$z^{n+1} = z^nz = (|z|^n(cos(n\theta) + i sin (n \theta)))(|z|(cos(\theta) + isin(\theta))) = |z|^{n+1} (cos((n+1)\theta) + isin((n+1)\theta))  $$
Tags: demostración
<!--ID: 1705822944799-->
END

START
Básico
Anverso: Demuestra que sea $z = |z| (cos \theta + i sin \theta)$ y sea $n \in \mathbb N$. Entonces:
1. $z^{-n} = \frac{1}{|z|^n}(cos(-n\theta) + isin(-n\theta))$.
Reverso: Veamos ahora el caso de $z^{-n}$.
$$z^{-n} = (z^n)^{-1} = (|z|^n (cos(n\theta) + isin(n \theta)))^{-1} = \frac{1}{|z|^n} ( cos (-n \theta) + isin(-n \theta))$$
gracias a [[Corolario inverso de complejo]]
Tags: demostración
<!--ID: 1705822944801-->
END