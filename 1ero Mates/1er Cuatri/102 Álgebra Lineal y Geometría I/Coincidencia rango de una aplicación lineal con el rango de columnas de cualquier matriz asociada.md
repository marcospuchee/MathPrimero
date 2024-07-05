### Proposición

Sea $f: V \rightarrow V'$ una [[Aplicación lineal]], $B$ [[Base]] de $V$ y $B'$ base de $V'$. Entonces
$$rg(f) = rg_c(M_{B, B'} (f))$$

---
### Demostración

Para demostrar esto, debemos conocer la siguiente observación: sean $B$ [[Base]] de $V$,  $g: V \rightarrow M_{m\times 1} (K)$ (por tanto $dimV = m$) con $v \rightarrow v_B$. Se tiene que $g$ es un [[Isomorfismo]] (ejercicio). En particular, si $U = \langle v_1, \dots, v_n \rangle \le V$, entonces $\left.g\right|_U : U \rightarrow g(U)$ también es un [[Isomorfismo]]. Se sigue que $dim \langle v_1, \dots, v_n \rangle = dim \langle g(U) \rangle =$ (por iv) de [[Proposiciones aplicación lineal espacios vectoriales]]) $dim \langle g(v_1), \dots, g(v_n) \rangle = dim \langle (v_1)_B, \dots, (v_n)_B \rangle$.

Sea $B = \{v_1 \dots, v_n\}$. Entonces $V = \langle v_1, \dots, v_n \rangle$. Así, $rg(f) = dim f(V) =$ (por iv) de [[Proposiciones aplicación lineal espacios vectoriales]]) $dim \langle f(v_1), \dots, f(v_n) \rangle = dim\langle f(v_1)_{B'}, \dots f(v_n)_{B'} \rangle$ por la observación. Sin embargo, $f(v_1)_{B'}, \dots, f(v_n)_{B'}$ forman las columnas de $M_{B,B'} (f)$. Así, por definición de [[Rango de columnas de una matriz]], $dim \langle (v_1)_B, \dots, (v_n)_B \rangle = rg_c(M_{B,B'}(f))$

---
### Referencias

[[Equivalencia de matrices#1. Rango]]

---
### Anki

START
Básico
Anverso: A qué rango de columnas es igual el rango de filas de una aplicación lineal?
Reverso: Sea $f: V \rightarrow V'$ una [[Aplicación lineal]], $B$ [[Base]] de $V$ y $B'$ base de $V'$. Entonces
$$rg(f) = rg_c(M_{B, B'} (f))$$
Tags: proposición/teorema
<!--ID: 1704822883793-->
END

START
Básico
Anverso: Demostración de que sea $f: V \rightarrow V'$ una [[Aplicación lineal]], $B$ [[Base]] de $V$ y $B'$ base de $V'$. Entonces
$$rg(f) = rg_c(M_{B, B'} (f))$$
Reverso: Para demostrar esto, debemos conocer la siguiente observación: sean $B$ [[Base]] de $V$,  $g: V \rightarrow M_{m\times 1} (K)$ (por tanto $dimV = m$) con $v \rightarrow v_B$. Se tiene que $g$ es un [[Isomorfismo]] (ejercicio). En particular, si $U = \langle v_1, \dots, v_n \rangle \le V$, entonces $\left.g\right|_U : U \rightarrow g(U)$ también es un [[Isomorfismo]]. Se sigue que $dim \langle v_1, \dots, v_n \rangle = dim \langle g(U) \rangle =$ (por iv) de [[Proposiciones aplicación lineal espacios vectoriales]]) $dim \langle g(v_1), \dots, g(v_n) \rangle = dim \langle (v_1)_B, \dots, (v_n)_B \rangle$.

Sea $B = \{v_1 \dots, v_n\}$. Entonces $V = \langle v_1, \dots, v_n \rangle$. Así, $rg(f) = dim f(V) =$ (por iv) de [[Proposiciones aplicación lineal espacios vectoriales]]) $dim \langle f(v_1), \dots, f(v_n) \rangle = dim\langle f(v_1)_{B'}, \dots f(v_n)_{B'} \rangle$ por la observación. Sin embargo, $f(v_1)_{B'}, \dots, f(v_n)_{B'}$ forman las columnas de $M_{B,B'} (f)$. Así, por definición de [[Rango de columnas de una matriz]], $dim \langle (v_1)_B, \dots, (v_n)_B \rangle = rg_c(M_{B,B'}(f))$
Tags: demostración
<!--ID: 1704822883798-->
END