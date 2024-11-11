
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-07-09, 14:50

```ad-theorem
Si $G$ es un [[grupo]] (resp. [[semigrupo]], [[monoide]]) y $a \in G$, entonces $\forall m,n \in \mathbb Z$ (resp. $\mathbb N^*, \mathbb N$):
1. $a^ma^n = a^{m+n}$.
2. $(a^m)^n = a^{mn}$.
```

^9fd486


```ad-proof
Primero vamos a verificar un resultado que nos será útil para la demostración: $(a^{-1})^n = (a^n)^{-1}$. Tenemos:
$$(a^n)^{-1} = (\prod_{i = 1}^n a)^{-1} = (a \dots a)^{-1}.$$
Sin embargo, por $(v)$ de [[propiedades de los grupos]], esto es igual a:
$$(a^{-1} \dots a^{-1}) = \prod_{i = 1}^n a^{-1} = (a^{-1})^n,$$
luego queda demostrado.

$(i)$.
- 1er caso: $m,n > 0$.
$$a^m a^n = \left (\prod_{i = 1}^n a \right ) \left (\prod_{i = 1}^m a \right) = \prod^{n+m}_{i = 1} a,$$
por ser ambos [[n-producto estándar]].
- 2o caso: $m,n < 0$. Sabemos entonces que $a^m a^n = a^{-m} a^{-n}$ con $n,m \in \mathbb N^*$. Luego como hemos visto:
$$a^{-n} a^{-m} = (a^{-1})^n (a^{-1})^m = \left ( \prod_{i = 1}^n a^{-1} \right ) \left ( \prod_{i = 1}^m a^{-1} \right ) = \prod^{m+n}_{a = 1} a^{-1} = (a^{-1})^{m+n} = a^{-m-n},$$
que deshaciendo el cambio anterior, queda $a^{m+n}$ con $m,n < 0$.
- 3er caso: $m < 0$ y $n > 0$, o viceversa. Podemos suponer sin pérdida de generalidad que $m<0$. Vamos a aplicar el [[principio de inducción débil]] sobre $n$. Para $n=1$, tenemos $a^ma$ con $m<0$ o $a^{-m}a$ con $m \in \mathbb N^*$. Sin embargo,
$$a^{-m}a = (a^{-1})^m a = \prod_{i = 1}^m (a^{-1})a = \left ( \prod_{i = 1}^{m-1} a^{-1} \right )(a^{-1}a) = \prod_{i = 1}^{m-1} a^{-1} = (a^{-1})^{m-1} = a^{-m+1} = a^{m+1}$$
con $m < 0$. Para el paso inductivo, suponemos uque $a^m a^{n-1} = a^{n+m-1}$. Veamos que $a^n a^m = a^{n+m}$. Tenemos que
$$a^n a^m = a(a^{n-1}a^m) = a(a^{n+m-1}) = a^{n+m}.$$

$(ii)$.
- 1er caso: $m>0, n \in \mathbb Z$. Vamos a proceder por inducción débil sobre $m$. $m = 1 \implies (a^1)^n = a^n = a^{nm}$. El paso inductivo nos lleva a suponer que $(a^{m-1})^n = a^{n(m-1)}$, veamos que se cumple para $n$: $(a^m)^n = (a^{m-1}a)^n = a^n a^{(m-1)n} = a^{nm}$.
- 2o caso: $m<0, n \in \mathbb Z$. Tenemos que $(a^m)^n = (a^{-m})^n$ con $m \in \mathbb N^*$. Sin embargo,
$$(a^{-m})^n = ((a^{-1})^m)^n = (a^{-1})nm = a^{-nm},$$
que, deshaciendo la transformación, queda $a^{nm}$ con $m<0$.
```


**Tema:** [[Grupos#1. Semigrupos, monoides y grupos]]
**Demostrado por:** [[Principio de inducción débil]], [[propiedades de los grupos]]
**Consecuencias:**

---
### Anki
