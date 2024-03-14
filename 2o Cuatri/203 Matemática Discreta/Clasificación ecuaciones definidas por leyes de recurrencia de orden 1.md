
---
mathLink: $a_{n+1} = \lambda a_n \iff a_n = a_0 \lambda^n$
---
### Contenido Principal

**Fecha:** 2024-02-22, 17:28

Sea $(a_n)_{n=1}^\infty$ una [[Sucesión]] definida por una [[Ley de recurrencia]].

```ad-proposition
$$a_{n+1} = \lambda a_n \iff a_n = a_0 \lambda^n$$
```


```ad-proof
Tomamos como ejemplo la sucesión definida por la ley de recurrencia de primer orden:
$$a_{n+1} = 2 a_n, \quad a_0 = 1$$
La sucesión no es otra que la [[Sucesión geométrica]] de razón 2, de término general
$$a_n = 2^n$$
Cualquier otra sucesión definida por la misma ley de recurrencia tiene como término general
$$a_n = a_0 2^n$$
Análogamente, es fácil comprobar que las sucesiones definidas por una ley de recurrencia
$$a_{n+1} = \lambda a_n$$
son todas sucesiones geométricas de razón $\lambda$ y de término general $a_n = a_0 \lambda^n$$.
```



**Tema:** [[Ecuaciones de recurrencia#2. Solución de las leyes de recurrencia lineales y homogéneas]]
**Corolarios:**

---
### Anki

START
Respuesta anidada
Sea $(a_n)_{n=1}^\infty$ una [[Sucesión]] definida por una [[Ley de recurrencia]].
$${{c1::a_{n+1} = \lambda a_n}} \iff {{c2::a_n = a_0 \lambda^n}}$$
Tags: MatDiscreta proposición/teorema
<!--ID: 1708973800649-->
END

START
Básico
Anverso: Demuestra que sea $(a_n)_{n=1}^\infty$ una [[Sucesión]] definida por una [[Ley de recurrencia]].
$$a_{n+1} = \lambda a_n \iff a_n = a_0 \lambda^n$$
Reverso: Tomamos como ejemplo la sucesión definida por la ley de recurrencia de primer orden:
$$a_{n+1} = 2 a_n, \quad a_0 = 1$$
La sucesión no es otra que la [[Sucesión geométrica]] de razón 2, de término general
$$a_n = 2^n$$
Cualquier otra sucesión definida por la misma ley de recurrencia tiene como término general
$$a_n = a_0 2^n$$
Análogamente, es fácil comprobar que las sucesiones definidas por una ley de recurrencia
$$a_{n+1} = \lambda a_n$$
son todas sucesiones geométricas de razón $\lambda$ y de término general $a_n = a_0 \lambda^n$$.
Tags: demostración MatDiscreta
<!--ID: 1708973800654-->
END
