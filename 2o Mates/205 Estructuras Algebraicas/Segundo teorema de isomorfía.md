### Contenido Principal

```ad-theorem
Sea $G$ un grupo, $N \unlhd G$ y $H \le G$. Entonces $(HN)/N \cong H/(H \cap N)$.
```

^9dd2b9

```ad-proof
Consideramos
$$\begin{array}{c c c c} f: & H & \to & (HN)/N \\ & h & \mapsto & hN. \end{array}$$

**Homomorfismo:** sean $h_1, h_2 \in H$,
$$f(h_1 h_2) = (h_1 h_2)N = (h_1 N)(h_2 N) = f(h_1) f(h_2).$$

**Sobreyectiva:** sea $xN \in HN/N$, entonces $x = hn$ para algunos $h \in H$, $n \in N$. Tenemos que
$$xN = (hn)N = h(nN) = h(N) = f(h).$$

**Veamos $\textrm{Ker}(f) = H \cap N$:**
$\supseteq$. Sea $x \in H \cap N$. En particular, $x \in N$. Por tanto,
$$f(x) = xN = N = 1_{(HN)/H} \implies x \in \textrm{Ker}(f).$$

$\subseteq$.
Sea $x \in \textrm{Ker}(f)$. Veamos que $x \in H \cap N$.
- $x \in H$ ($x \in \textrm{Ker}(f) \subseteq H$).
- $f(x) = xN$, pero $f(x) = 1_{(HN)/N} = N$, luego $x \in N$.


Por el [[primer teorema de isomorfía]], $H/\textrm{Ker}(f) \cong \textrm{Im}(f)$, y $H / H \cap N \cong HN/N$.
```

**Tema:** [[Teoría de grupos#15. Teoremas de isomorfía.]]
**Corolario:**

---
### Anki

START
Básico
Anverso: Segundo teorema de isomorfía
Reverso: Sea $G$ un grupo, $N \unlhd G$ y $H \le G$. Entonces $(HN)/N \cong H/(H \cap N)$.
Tags: est
<!--ID: 1730228001536-->
END

START
Básico
Anverso: Demostración de que sea $G$ un grupo, $N \unlhd G$ y $H \le G$. Entonces $(HN)/N \cong H/(H \cap N)$.
Reverso: Consideramos
$$\begin{array}{c c c c} f: & H & \to & (HN)/N \\ & h & \mapsto & hN. \end{array}$$

**Homomorfismo:** sean $h_1, h_2 \in H$,
$$f(h_1 h_2) = (h_1 h_2)N = (h_1 N)(h_2 N) = f(h_1) f(h_2).$$

**Sobreyectiva:** sea $xN \in HN/N$, entonces $x = hn$ para algunos $h \in H$, $n \in N$. Tenemos que
$$xN = (hn)N = h(nN) = h(N) = f(h).$$

**Veamos $\textrm{Ker}(f) = H \cap N$:**
$\supseteq$. Sea $x \in H \cap N$. En particular, $x \in N$. Por tanto,
$$f(x) = xN = N = 1_{(HN)/H} \implies x \in \textrm{Ker}(f).$$

$\subseteq$.
Sea $x \in \textrm{Ker}(f)$. Veamos que $x \in H \cap N$.
- $x \in H$ ($x \in \textrm{Ker}(f) \subseteq H$).
- $f(x) = xN$, pero $f(x) = 1_{(HN)/N} = N$, luego $x \in N$.


Por el [[primer teorema de isomorfía]], $H/\textrm{Ker}(f) \cong \textrm{Im}(f)$, y $H / H \cap N \cong HN/N$.
Tags: dem est
<!--ID: 1730228001539-->
END

