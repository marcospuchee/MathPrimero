	
---
mathLink:
---
### Contenido Principal

**Fecha:** 2024-05-16, 09:43

```ad-lemma
Sea $(E, V, +)$ [[espacio afín euclídeo]] y sean $P \in E$ y $W_Q \subseteq E$ [[variedad afín]]. Entonces $\exists ! T \in E$ tal que satisface
1. $T \in W_Q$.
2. $\vec{PT} \in W^\perp$.
```


```ad-proof
Sea $Q \in W_Q$,  consideramos $\vec{PQ} \in V$. Recordemos que $V = W \bigoplus W^\perp$ (porque $V$ es [[espacio vectorial euclídeo]]). Entonces $\vec{PQ} = w + w'$ donde $w \in W, w' \in W^\perp$ (únicos). 

Consideramos $T = P + w'$. Tenemos $\vec{PT} = w' \in W'$. Por otro lado:
$$Q = Q + \vec{PQ} = P + (w+w') = (P+w')+w = T+w \implies T = Q-w \in W_Q.$$

Veamos ahora la unicidad del punto $T$. Sea $T' \in E$ tal que $T' \in W_Q$ y $\vec{PT} \in W^\perp$. Tenemos: $\vec{PQ} = \vec{PT'} + \vec{T'Q}$, con $\vec{PT'} \in W^\perp$ y $\vec{T'Q} \in W$, luego $\vec{PQ} = w' + w$. Como $V = W \bigoplus W^\perp$, tenemos que $\vec{PT'} = w'$ y $\vec{T'Q} = w$. Por tanto, $T' = Q-w = T$. 
```

**Tema:** [[Espacios afines euclídeos]]
**Corolarios:**

---
### Anki

START
Básico
Anverso: Lema existencia y unicidad proyección ortogonal de un punto sobre una variedad afín
Reverso: Sea $(E, V, +)$ [[Espacio afín euclídeo]] y sean $P \in E$ y $W_Q \subseteq E$ [[Variedad afín]]. Entonces $\exists ! T \in E$ tal que satisface
1. $T \in W_Q$.
2. $\vec{PT} \in W^\perp$.
Tags: proposición/teorema ÁlgebraI
<!--ID: 1715864620208-->
END

START
Básico
Anverso: Lema existencia y unicidad proyección ortogonal de un punto sobre una variedad afín
Reverso: Sea $Q \in W_Q$,  consideramos $\vec{PQ} \in V$. Recordemos que $V = W \bigoplus W^\perp$ (porque $V$ es [[Espacio vectorial euclídeo]]). Entonces $\vec{PQ} = w + w'$ donde $w \in W, w' \in W^\perp$ (únicos). 

Consideramos $T = P + w'$. Tenemos $\vec{PT} = w' \in W'$. Por otro lado:
$$Q = Q + \vec{PQ} = P + (w+w') = (P+w')+w = T+w \implies T = Q-w \in W_Q.$$

Veamos ahora la unicidad del punto $T$. Sea $T' \in E$ tal que $T' \in W_Q$ y $\vec{PT} \in W^\perp$. Tenemos: $\vec{PQ} = \vec{PT'} + \vec{T'Q}$, con $\vec{PT'} \in W^\perp$ y $\vec{T'Q} \in W$, luego $\vec{PQ} = w' + w$. Como $V = W \bigoplus W^\perp$, tenemos que $\vec{PT'} = w'$ y $\vec{T'Q} = w$. Por tanto, $T' = Q-w = T$. 
Tags: demostración ÁlgebraI
<!--ID: 1716477603208-->
END