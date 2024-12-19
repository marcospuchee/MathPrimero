### Contenido Principal

```ad-theorem
Consideremos un problema de PLE en formato canónico con región factible
$$\mathcal F = \{x \in \mathbb Z^n: Ax \le b, \, \, x \ge 0_n \},$$
con $A \in \mathbb R^{m \times n}$ y $b \in \mathbb R^m$. Entonces, la desigualdad
$$\sum_{j = 1} \lfloor u^T a_j \rfloor x_j \le \lfloor u^T b \rfloor,$$
es válida para $\mathcal F$, $\forall u \in \mathbb R^m_+$.
```

```ad-proof
Sea $x = (x_1, \dots, x_n)^T \in \mathcal F$ y sea $u \in \mathbb R^m$. Como las componentes de $u$ son no negativas, podemos premultiplicar la desigualdad $Ax \le b$ por $u^T$ y obtenemos que
$$u^T Ax \le u^Tb \iff \sum_{j = 1}^n (u^T a_j)x_j \le u^Tb.$$
Ahora, $\forall j = 1, \dots, n$, se tiene que $\lfloor u^T a_j \rfloor \le u^T a_j$. Podemos multiplicar cada una de estas desigualdades por $x_j$ (mantiene el signo al ser no negativa) y, combinando con la desigualdad anterior, llegamos a
$$\sum_{j = 1}^n \lfloor u^T a_j \rfloor x_j \le \sum_{j = 1}^n (u^T a_j) x_j \le u^T b.$$
Por último, al ser las variables enteras, se tiene que el lado izquierdo de la primera desigualdad es un número entero, y por definición de parte entera de $\lfloor u^T b \rfloor$ se llega a lo que estabamos demostrando.
```

**Tema:** [[Programación lineal entera#2. Combinatoria poliédrica.]]

**Definiciones referenciadas:** [[Desigualdad válida]]
**Resultados referenciados:** -.

---
### Anki

START
Básico
Anverso: Procedimiento de Chvátal-Gomory para PLE puros
Reverso: Consideremos un problema de PLE en formato canónico con región factible
$$\mathcal F = \{x \in \mathbb Z^n: Ax \le b, \, \, x \ge 0_n \},$$
con $A \in \mathbb R^{m \times n}$ y $b \in \mathbb R^m$. Entonces, la desigualdad
$$\sum_{j = 1} \lfloor u^T a_j \rfloor x_j \le \lfloor u^T b \rfloor,$$
es válida para $\mathcal F$, $\forall u \in \mathbb R^m$.
Tags: prm
<!--ID: 1733328768626-->
END

START
Básico
Anverso: Demostración de que consideremos un problema de PLE en formato canónico con región factible
$$\mathcal F = \{x \in \mathbb Z^n: Ax \le b, \, \, x \ge 0_n \},$$
con $A \in \mathbb R^{m \times n}$ y $b \in \mathbb R^m$. Entonces, la desigualdad
$$\sum_{j = 1} \lfloor u^T a_j \rfloor x_j \le \lfloor u^T b \rfloor,$$
es válida para $\mathcal F$, $\forall u \in \mathbb R^m$.
Reverso: Sea $x = (x_1, \dots, x_n)^T \in \mathcal F$ y sea $u \in \mathbb R^m$. Como las componentes de $u$ son no negativas, podemos premultiplicar la desigualdad $Ax \le b$ por $u^T$ y obtenemos que
$$u^T Ax \le u^Tb \iff \sum_{j = 1}^n (u^T a_j)x_j \le u^Tb.$$
Ahora, $\forall j = 1, \dots, n$, se tiene que $\lfloor u^T a_j \rfloor \le u^T a_j$. Podemos multiplicar cada una de estas desigualdades por $x_j$ (mantiene el signo al ser no negativa) y, combinando con la desigualdad anterior, llegamos a
$$\sum_{j = 1}^n \lfloor u^T a_j \rfloor x_j \le \sum_{j = 1}^n (u^T a_j) x_j \le u^T b.$$
Por último, al ser las variables enteras, se tiene que el lado izquierdo de la primera desigualdad es un número entero, y por definición de parte entera de $\lfloor u^T b \rfloor$ se llega a lo que estabamos demostrando.
Tags: dem prm
<!--ID: 1733328768628-->
END
