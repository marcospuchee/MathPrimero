### Contenido Principal

```ad-proposition
Si $||Q|| < 1$ para alguna norma matricial subordinada a una norma vectorial, entonces el método iterativo asociado es convergente.
```

```ad-proof
Veamos que $\lim \limits_{k \to \infty} ||e^k|| = 0$ para la norma vectorial asociada a la norma matricial en la que $||Q|| < 1$: $$0 \le ||e^k|| = ||Q^k e^0|| \le ||Q^k|| \, ||e^0|| \le ||Q||^k ||e^0|| \overset{k \to \infty}{\longrightarrow} 0.$$ El criterio del emparedado, permite concluir que $\lim \limits_{k \to \infty} Q^k e^0 = 0$ independientemente de $e^0$.
```

**Tema:** [[Métodos iterativos para resolver sistemas de ecuaciones lineales#2. Estudio de la convergencia.]]

**Definiciones referenciadas:** [$Q := -M^{-1}N$](Matriz de iteración), [[Norma matricial subordinada a una norma vectorial]], [[Método iterativo convergente]], [$e^k := x^k - x$](Error.md), 
**Resultados referenciados:** [[Criterio del emparedado]]

---
### Anki

START
Básico
Anverso: Relación norma matriz de iteración con método convergente
Reverso: Si $||Q|| < 1$ para alguna norma matricial subordinada a una norma vectorial, entonces el método iterativo asociado es convergente.
Tags: met
<!--ID: 1735044171384-->
END

START
Básico
Anverso: Demostración de que si $||Q|| < 1$ para alguna norma matricial subordinada a una norma vectorial, entonces el método iterativo asociado es convergente.
Reverso: Veamos que $\lim \limits_{k \to \infty} ||e^k|| = 0$ para la norma vectorial asociada a la norma matricial en la que $||Q|| < 1$: $$0 \le ||e^k|| = ||Q^k e^0|| \le ||Q^k|| \, ||e^0|| \le ||Q||^k ||e^0|| \overset{k \to \infty}{\longrightarrow} 0.$$ El criterio del emparedado, permite concluir que $\lim \limits_{k \to \infty} Q^k e^0 = 0$ independientemente de $e^0$.
Tags: met dem
<!--ID: 1735044171387-->
END

